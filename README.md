# UR10e-Human-Motion-Replication

This project explores how **robotic systems can accurately replicate human movement**, bridging the gap between **biomechanics and robotics**. The goal was to program a **UR10e robotic arm** to mimic **human motion patterns** with **smooth, repeatable, and precise movements**.  

Instead of using motion sensors, we **recorded human movement using a high-speed camera**, extracting **position, velocity, and acceleration** data using **motion tracking software**. This data was then used to generate **robotic motion trajectories**, which were later compared to the arm's actual movements to verify replication accuracy.  

This work has potential applications in **biomechanics research, automation, and AI-driven motion learning**.  



## 🔬 **Key Objectives**
- ✅ **Capture and analyze human motion data** using **high-speed camera tracking**.  
- ✅ **Develop inverse kinematics and trajectory planning algorithms** in **MATLAB and URScript**.  
- ✅ **Implement real-time motion control** on the **UR10e robotic arm**.  
- ✅ **Compare human vs. robotic movement** to validate accuracy.  


## 🛠 **Tools & Technologies Used**
### **Software**
- **MATLAB** – Motion analysis, inverse kinematics, and trajectory planning.  
- **URScript** – Programming real-time robotic motion sequences.  
- **High-Speed Camera Software** – Extracting **position, velocity, and acceleration data** from recorded human motion.  

### **Hardware**
- **UR10e Robotic Arm** – 6-axis robotic manipulator for motion execution.  
- **High-Speed Camera** – Recording human movement for data extraction and motion validation.  

### **Techniques**
- **Motion Replication** – Converting real human movement into robotic trajectories.  
- **Kinematics & Trajectory Planning** – Computing optimal movement paths.  
- **Real-Time Control** – Fine-tuning motion execution with **feedback loops**.  


## 🔬 **Methodology**
### **1️⃣ Capturing Human Motion Data**
- **Recording with a High-Speed Camera:**  
  - Filmed **human running and jumping movements** at different speeds.  
  - Used **motion tracking software** to extract **position, velocity, and acceleration**.  
- **Data Processing in MATLAB:**  
  - Smoothed extracted movement data to remove noise.  
  - Converted motion paths into **programmable robotic trajectories**.  

### **2️⃣ Programming & Control Implementation**
- **URScript Programming for UR10e:**  
  - Developed control programs to execute **smooth, repeatable movements**.  
  - Implemented **inverse kinematics solutions** for real-time trajectory adjustments.  
- **Fine-Tuning Movement Constraints:**  
  - Adjusted **speed, acceleration, and velocity constraints** to match human motion.  

### **3️⃣ Motion Replication & Testing**
- **Executing Robotic Motion on UR10e:**  
  - Programmed the robotic arm to perform **linear, circular, and oscillatory movements**.  
  - Ran **step-by-step motion trials** to refine execution accuracy.  
- **Motion Comparison with High-Speed Camera:**  
  - Recorded robotic movement using **high-speed imaging**.  
  - Compared robotic trajectories to original human movements to **verify replication accuracy**.  


## 📊 **Key Findings & Takeaways**
- ✅ Successfully **replicated human movement on a robotic arm** without motion sensors.  
- ✅ Achieved **high repeatability and precision** in robotic motion.  
- ✅ Used **high-speed camera tracking** to extract and compare movement data.  
- ✅ Laid the groundwork for **real-time adaptive control and AI-driven motion learning**.  


## 🚀 **Future Improvements**
- **Improve real-time motion correction** using **adaptive control algorithms**.  
- **Optimize trajectory planning** for **higher-speed dynamic applications**.  
- **Integrate force feedback** for **human-like joint flexibility and responsiveness**.  

