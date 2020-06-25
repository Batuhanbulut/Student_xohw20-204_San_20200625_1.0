#Student_xohw20_204_San_06-25-2020_1.0
Open Hardware 2020 Design Contest Student Category Project 
Project Name: SonicReader: Accelerator on Temperature Reading from Multiple Sensors
Team Number: xohw20_204 
Supervisor Name: İsmail San
Team Members: Batuhan Bulut, Işıl Höcek
IP BLOCKS includes our self designed IP cores for hardware part of the projects, which are converter block, controller block and slavetoaxi block. Controller blocks takes the inputs from sensors, has an special FSM structure inside it. Converter blocks takes the actual temperature bits from the coming data, converts them and sens them to the slavetoaxi block. Slavetoaxi block takes the stream data saves them in registers for reading from the PS.
HARDWARE PART is divided into 2 files. HardwarePart1 includes .cache , .hw , .ip_user_files,.runs and hardwarepart2 includes the rest of the files that reqired for execution of the project. For an execution you need to merge the HardwarePart1 and HardwarePart2 at underline spiplproje file. This file together includes our Hardware solution for sensor reading.
SOFTWARE PART includes our software reading files for project. It mainly focuses on SDK part. It basically reads sensors from ARM based processing system.
