# JetsonCopter
PID Controller for quadcopter, powered by Nvidia Jetson Nano

# To start program.
1. Execute ``` make ``` in root of this repo.
2. Navigate to output and execute ```./Hermies```

# Controlling Hermies
1. Gains
   - The user can controll all 3 main PID controller gains during flight (PITCH, ROLL, YAW)
   - *However, PITCH and ROLL use the same gain values.*
   
### Base Speed Control
| Key | Description |
| --- | --- |
| UP-ARROW | ++ speed of all motors by 1 point. |
| DOWN-ARROW | -- speed of all motors by 1 point. |

### Pitch and Roll Control
| Key | Description | * | Key | Description |
| --- | --- | --- | --- | --- |
| q | ++ 'P' gain by 1.0 point. | * | a | -- 'P' gain by 1.0 point. |
| w | ++ 'I' gain by 0.1 point. | * | s | -- 'I' gain by 0.1 point. |
| e | ++ 'D' gain by 5.0 point. | * | d | -- 'D' gain by 5.0 point. |

### Yaw Control
| Key | Description | * | Key | Description |
| --- | --- | --- | --- | --- |
| z | ++ 'P' gain by 1.0 point. | * | c | -- 'P' gain by 1.0 point. |
| x | ++ 'I' gain by 0.1 point. | * | v | -- 'I' gain by 0.1 point. |
