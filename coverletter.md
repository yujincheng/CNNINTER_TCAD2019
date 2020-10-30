Dear editors/reviewers,
Here is the manuscript for the TRANSACTIONS ON COMPUTER-AIDED DESIGN OF INTEGRATED CIRCUITS AND SYSTEMS (TCAD), entitled "INCAME : interruptible CNN Accelerator for Multi-robot Exploration".

In this manuscript, we extend our previous work "INCA: INterruptible CNN Accelerator for Multi-tasking in Embedded Robots" which is accepted by the Design Automation Conference (DAC2020), with the following novel contributions:

1. Besides the hardware conflicts when using CNN accelerator to a real-world robot system, some other operations are also time-costing and make it difficult for CNN-based algorithms in the real-time embedded system. We design hardware architectures for these operations, and propose a method to combine the CNN backbone and these operations to make robotics developers easier to deploy algorithms onto embedded hardware.

2. We deploy and evaluate the INCAME framework in a practical robot task, Multi-robot Exploration, which is a basic problem in robotics. In this manuscript, we detail the system framework, algorithm components, and the data flow, as well as the related work. With the help of this case example, readers can better understand our motivation, methods, and evaluation.

3. As the Robot Operating System (ROS) is widely used in robotics. In this manuscript, we introduce the programming paradigm of ROS in detail, and design the corresponding interface for ROS. So that the robot developers can better use the software and hardware system in INCAME.

4. We add more experimental results in this manuscript, including the extra cost of fetching modified instruction sequences, hardware resources evaluation, and the quantitative results in some experimental cases.