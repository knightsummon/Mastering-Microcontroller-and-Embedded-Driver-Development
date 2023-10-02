# 13 Creating Hello-World Project



## The Discovery Board

![02](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/02.jpg)

Open the `STM32CUBEIDE` IDE

Select on the new project search box and try to find the `STM32F4DISCOVERY` , in 2023, this board name has been changed to `STM32F407G-DISC1`

![01](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/01.jpg)

![03](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/03.jpg)

The STM32Cube is function for peripheral configuration using STM32CubeMX code

`Src` folder includes a `main.c` entry file.

![05](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/05.jpg)

## Compile a Project

![06](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/06.jpg)

### Meet a Warning

![07](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/07.jpg)

FPU is stand for `Floating Point Unit `, which are not used in this project. So in order to solve this warning, we choose to disable it.

![08](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/08.jpg)

## Download Project onto the Target

This option downloads the code onto the target and also it puts the board into debug mode

![09](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/09.jpg)

#### Create debug Configuration

![10](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/10.jpg)

#### Debug and Switch Perspective to the Board Debugger

Now the Discovery Board is going to debug mode.  
Change The perspective IDE into the debug perspective.   

![11](https://github.com/knightsummon/Mastering-Microcontroller-and-Embedded-Driver-Development/blob/main/Creating%20a%20project%20using%20STM32CUBEIDE/13%20Creating%20Hello-World%20Project.assets/11.jpg)

Then the STM Discovery Board will run your command lines.
