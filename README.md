# HW8_JusongCai

In HW8, the target is to replicate HW1 and rebuild HW7-communication between PIC32 and IMU via I2C under Harmony framework. Following instructions in ME433 schedule repo, I created harmony project and completed configuration settings. A few files then generated. Next step was to copy HW7 main code into "app.c" to build communication among IMU, PIC32 and LCD. In this case, "main.c" is just the main function that controls "app.c" so don't have to edit that. Also, other source files and library should be introduced in: "ST7735.c/h", "imc.h", "imu.c", and "i2c_master_noint.c/h". Build the job and generate hex files that can be programmed into the board.

Since the directory of the hex files in production folders is too deep, so they cannot be uploaded into Git somehow. I don't know why. But it does not matter since since the source code is complete, so you can refer to that and build program by yourself without any errors.
