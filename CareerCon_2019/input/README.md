# Data Description

#### `X[train/test].csv` - the input data, covering 10 sensor channels and 128 measurements per time series plus three ID columns:
- `row_id`: The ID for this row.
- `series_id`: ID number for the measurement series. Foreign key to y_train/sample_submission.
- `measurement_number`: Measurement number within the series.

The orientation channels encode the current angles how the robot is oriented as a quaternion (see Wikipedia). Angular velocity describes the angle and speed of motion, and linear acceleration components describe how the speed is changing at different times. The 10 sensor channels are:
- orientation_X
- orientation_Y
- orientation_Z
- orientation_W
- angular_velocity_X
- angular_velocity_Y
- angular_velocity_Z
- linear_acceleration_X
- linear_acceleration_Y
- linear_acceleration_Z

#### y_train.csv - the surfaces for training set:
-series_id: ID number for the measurement series.
-group_id: ID number for all of the measurements taken in a recording session. Provided for the training set only, to enable more cross validation strategies.
-surface: the target for this competition.

#### sample_submission.csv - a sample submission file in the correct format.
