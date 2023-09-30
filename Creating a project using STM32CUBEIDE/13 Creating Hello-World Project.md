# 13 Creating Hello-World Project



## The Discovery Board

![02](13 Creating Hello-World Project.assets/02.jpg)

Open the `STM32CUBEIDE` IDE

Select on the new project search box and try to find the `STM32F4DISCOVERY` , in 2023, this board name has been changed to `STM32F407G-DISC1`

![01](13 Creating Hello-World Project.assets/01.jpg)

![03](13 Creating Hello-World Project.assets/03.jpg)

The STM32Cube is function for peripheral configuration using STM32CubeMX code

`Src` folder includes a `main.c` entry file.

![05](13 Creating Hello-World Project.assets/05.jpg)

## Compile a Project

![06](13 Creating Hello-World Project.assets/06.jpg)

### Meet a Warning

![07](13 Creating Hello-World Project.assets/07.jpg)

FPU is stand for `Floating Point Unit `, which are not used in this project. So in order to solve this warning, we choose to disable it.

![08](13 Creating Hello-World Project.assets/08.jpg)

## Download Project onto the Target

This option downloads the code onto the target and also it puts the board into debug mode

![09](13 Creating Hello-World Project.assets/09.jpg)

#### Create debug Configuration

![10](13 Creating Hello-World Project.assets/10.jpg)

#### Debug and Switch Perspective to the Board Debugger

Now the Discovery Board is going to debug mode.  
Change The perspective IDE into the debug perspective.   

![11](13 Creating Hello-World Project.assets/11.jpg)

Then the STM Discovery Board will run your command lines.