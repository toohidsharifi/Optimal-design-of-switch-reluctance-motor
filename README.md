# Optimal-design-of-switch-reluctance-motor
![Optimal Motor](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/494e3e56-1411-480b-a66d-7e1c8723dcef)

Electric motors with promising features such as high torque capability, low cost, fault tolerance, reasonable power factor, modularity, etc. can be easily
integrated into the structure of electric vehicles. Various electric motors can provide such criteria for vehicle manufacturers. One of them is the switch
reluctance motor about which many recent research studies talked. Although the switch reluctance motor (SRM) is a reputable candidate for transportation 
applications, one should be careful about the annoying torque ripple in these motors. In the context of machine design, various methods have been implemented
to palliate the cogging torque and torque ripple of SRMs. These strategies usually consider either drive or machine design to tackle the torque ripple problem.
The drive tackling is very straightforward and the basic is to inject the required harmonic to face the torque ripple-producing forces. Therefore, it's 
applicable after the machine design has finished and the machine is ready for test in the laboratory. Without an appropriate drive, the designer would not be
able to improve the performance. On the other hand, the machine design strategy, also utilized in this project, is implemented in the machine design procedure.
The user would be able to drive the motor without any further consideration. Therefore, the cost of implementation of this method is much less than the first one.

![images](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/e31763b4-70ca-4fe9-ba40-373ec0a90a51)
![images](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/c8ba7681-1525-4bff-9313-baaa1bacdd5f)

Torque Ripple Minimization for a Switch Reluctance Motor Using the Ant Lion Optimization Algorithm
High torque density is a significant criterion for electric vehicle applications. In the context of torque performance, firstly, the average torque of the motor
should be improved, and, secondly, the torque ripple of the machine must be at a satisfactory level. Switch reluctance motors (SRMs), as an alternative, pass the
e first criterion. However, the torque ripple of the SRMs can be problematic for the users. Various methods have been used for torque ripple minimization, and
most of them are related to structural techniques. However, these methods cannot be considered as the optimal ones. In this project, a 3-phase switch reluctance
motor with 18 stator poles and 12 rotor poles (18/12) has been introduced, designed to be used in electric vehicles. The torque ripple of the motor is optimized
using the Ant Lion Optimization (ALO) algorithm, which is a metaheuristic approach, and the result of the optimization problem is compared with the initial machine. 

![Untitled](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/6845a8b9-24fe-433c-a1bd-2608d11b3ddc)

For the SRM proposed in the previous section, we want to optimize (minimize) the torque ripple of the motor. Here, it is essential to save the torque capability
(average torque) of the motor. We assign five decision variables to the optimization problem. The first and second are the outer and inner widths of the rotor
tooth. We assign the third and fourth ones to the stator tooth width. In addition to the torque ripple minimization, we want to find a relation between the 
number of turns and torque ripple.

![Untitled 2](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/91618fdd-a8b3-49b8-97e0-712a2142e3d5)

For this reason, the number of turns is the fifth decision variable of this problem. Actually, in the motor design problem, the number of turns is a constant 
value. However, here we want to analyze the relationship between that and the torque ripple of the motor.
So, for decision variables,
  
4<x_1<10 ⇒ "Outer width of rotor tooth "("deg")

5<x_2<13 ⇒ "Inner width of rotor tooth "("deg")

3<x_3<5 ⇒ "Inner width of stator tooth "("deg")

3<x_4<5.5 ⇒ "Outer width of stator tooth "("deg")

40<x_5<60 ⇒ "Number of turns" 

![decision variables of optimization](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/d4cc9459-ebf0-4d6e-81cb-d281d4a43b5d)
