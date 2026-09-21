# Task 1 — Requirements
| Req_ID | Description                                                                                       | Priority |
| ------ | ------------------------------------------------------------------------------------------------- | -------- |
| R1     | The robot shall remain in the IDLE state when switched on without a delivery request.             | High     |
| R2     | The robot shall move from IDLE to NAVIGATING when a delivery request is received.                 | High     |
| R3     | The robot shall navigate toward the requested destination while in the NAVIGATING state.          | High     |
| R4     | The robot shall enter AVOIDING_OBSTACLE when an obstacle is detected during navigation.           | High     |
| R5     | The robot shall return to NAVIGATING after successfully avoiding the obstacle.                    | High     |
| R6     | The robot shall enter DELIVERING when it reaches the requested destination.                       | High     |
| R7     | The robot shall enter RETURNING after successfully delivering the package.                        | High     |
| R8     | The robot shall enter RETURNING when its battery becomes critically low during navigation.        | High     |
| R9     | The robot shall return to IDLE when it reaches the warehouse.                                     | High     |
| R10    | The robot shall not transition directly from IDLE  to DELIVERING.                                 | High     |
