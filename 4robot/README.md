---
sort: 4
---
# 机器人学


工业机器人起源，第一步工业机器人，1961年，现在这个机器人还活着，在工作。

所以机械臂并不是一个新东西。



- introduction
- Spatial Representation and Transformation 
- Kinumatics and Inverse Kinumatics
- Differential Relationship
- Motion Planning
- Dynamics
- Robot Control and Compliance

机器人的空间关系，多轴机器人，要知道每个轴的运动和以及最后到达位置的关系，因此每个轴都要放一个坐标系统。每个轴开始动，这些坐标系统在动的过程中就有变换的关系，transformation。这个解决后，针对机器人做运动学分析，到达目标位置各轴要摆出多少角度，或者说各轴给了各角度，末端会到什么位置。这些都是静态。

后面讨论微分，位置微分为速度，运动关系。一个机器人系统，比如车，四个轮子的速度和车的速度，这就是个运动关系，jaccobi关系，很重要，运动上的关系。对于运动的描述，同样也有正反两种。

有了这个之后，就可以规划一个路径了，有了路劲就有了空间里每个要到的点，以及每个轴要到的点的坐标，每个点在轴坐标的速度。

前面没有谈机器人的重量和质量，这里要加入动力学。让一个东西看起来像真的一样，比如说仿真如何看起来像真的一样，主要就在动力学仿真上。动力学很难描述，这也是仿真困难的地方

到这里机器人所有的东西都有了，就要做控制了，真正进入电控的部分。有了规划的路径，分析了每个轴的运动，速度和位置，电机推动，有质量，动作有没有到位，就靠控制器补偿，反馈控制。控制不仅仅有位置控制，要让机器人进入和环境交互的领域，就需要处理位置和力的关系，这样就可以夹取东西了。

工业机器人大概就是这么个样子。

