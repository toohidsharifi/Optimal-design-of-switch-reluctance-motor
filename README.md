# Optimal-design-of-switch-reluctance-motor
Torque Ripple Minimization for a Switch Reluctance Motor Using the Ant Lion Optimization Algorithm
High torque density is a significant criterion for electric vehicle applications. In the context of torque performance, firstly, the average torque of the motor
should be improved, and, secondly, the torque ripple of the machine must be at a satisfactory level. Switch reluctance motors (SRMs), as an alternative, pass the
e first criterion. However, the torque ripple of the SRMs can be problematic for the users. Various methods have been used for torque ripple minimization, and
most of them are related to structural techniques. However, these methods cannot be considered as the optimal ones. In this project, a 3-phase switch reluctance
motor with 18 stator poles and 12 rotor poles (18/12) has been introduced, designed to be used in electric vehicles. The torque ripple of the motor is optimized
using the Ant Lion Optimization (ALO) algorithm, which is a metaheuristic approach, and the result of the optimization problem is compared with the initial machine. 

For the SRM proposed in the previous section, we want to optimize (minimize) the torque ripple of the motor. Here, it is essential to save the torque capability
(average torque) of the motor. We assign five decision variables to the optimization problem. The first and second are the outer and inner widths of the rotor
tooth. We assign the third and fourth ones to the stator tooth width. In addition to the torque ripple minimization, we want to find a relation between the 
number of turns and torque ripple.

For this reason, the number of turns is the fifth decision variable of this problem. Actually, in the motor design problem, the number of turns is a constant 
value. However, here we want to analyze the relationship between that and the torque ripple of the motor.
So, for decision variables,
  
![image](https://github.com/toohidsharifi/Optimal-design-of-switch-reluctance-motor/assets/126771405/a8927955-2d3e-4c5b-aaf4-3e5b99bc9315)

