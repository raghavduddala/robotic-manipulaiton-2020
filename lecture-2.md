Robotic manipualtors can be picked up/selected based on many factors, but the type of control also plays a huge factor.
1. Position control 
2. Torque Control

**Position Control**
UR- 5 and UR-10
ABB - BI manual robot

**Torque Control**
KUKA
FRANKA PANDA
Kinova--- (Very small base and easy to fix on wheel chairs)



**MOTORS/ACTUATORS**
* One end of the Spectrum - motors have high RPM. Electric motors are heavy and are highly effeicient when they roatat eat high RPM. So for the robots the transmission is coupled with a high gear ratios (i.e High RPM from motor to a Low RPM Shaft motion). Higher gear ratio transmission models are difficult to simulate and model and hence can use some **encoder/potentiometer/sensors** to measure the torque or the **joint angles** and use a **P/PD/PID Feedback Control**.
  
* The other end of the Spectrum, we have Direct Drive motors (so that we have a direct relation between the Current(i) to the motor and the torque (Tau) output in the shaft. Torque Controlled motors generally. If the gear ratios is around 1-2, we can called them Strict direct drive motors(Srictly Torque Control) Gear ratio 10-20(Quasi-Static Torque Control) and any gear ratio higher than that is not Torque Control.

  * **Discussion**
  * If a robot is using a position control, then it is difficult for the humans to get near the robot. Because the robot will tend to achieve the desired position/pose irrespective of anything present there including a human. So for controlling the **joint torques** essentially uses a Torque Sensor(Spring/Strain Guage)( (BAXTER) usess Series Elastic Actuators). So motors with high gear ratios can also use this. More discussion in **FORCE CONTROL**  lectures.
  
  
