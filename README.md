<h1 align="center">Hi, I'm Anuj Pai Raikar 👋</h1>

<p align="center">
  <b>Robotics &amp; ML engineer</b>: perception, autonomy and on-device AI for robots that work outside the lab.
</p>

<p align="center">
  <a href="mailto:anujpairaikar98@gmail.com"><img src="https://img.shields.io/badge/Email-anujpairaikar98%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/anuj-pai-raikar/"><img src="https://img.shields.io/badge/LinkedIn-anuj--pai--raikar-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/22by7-raikar/22by7-raikar.github.io/blob/main/data/Anuj_Pai_Raikar.pdf"><img src="https://img.shields.io/badge/CV-PDF-555555?style=flat&logo=readthedocs&logoColor=white" alt="CV"></a>
</p>

---

### About me

- 🤖 **MS Robotics Engineering, WPI**: research in the [Manipulation and Environmental Robotics Lab](https://wp.wpi.edu/merlab/) under Prof. Berk Calli.
- 🧠 **AI/ML Engineer at [Vizzhy](https://www.vizzhy.com/)**: LLM-driven app over multi-modal data (audio, text, images) for personalized health analytics.
- 🚜 **Previously**: precise AMR docking at **JLG Industries (Oshkosh)**, the perception/ML stack for a security robot at **DEKA**, ML at **Cybic Tech**, and consulting at **Oracle**.
- 🔭 **Right now**: on-device voice interfaces for robots, and steering vision-language-action policies around obstacles they never saw in training.

### Featured projects

| Project | What it does | Highlights |
|---|---|---|
| 🎙️ [**On-Device Voice Interface**](https://github.com/22by7-raikar/On-Device-Voice-Interface) | A robot that hears someone across a noisy room, turns toward them, acts on free-form requests through validated LLM tool calls, and stops the instant it's told to. Fully on-device. | C++17 · whisper.cpp · beamforming/DOA · barge-in |
| 🔊 [**edge_audio**](https://github.com/22by7-raikar/cpp-edge-audio) | Decides whether audio is worth transcribing *before* spending ASR compute on it, plus a streaming voice-command loop. | F1 **0.920** vs 0.807 rule gate · **~33%** fewer Whisper calls · ~1 µs per decision |
| 🦾 [**Predictive guidance for VLAs on SO-101**](https://github.com/22by7-raikar/SO_101_semantic_manipulation) | Fine-tuned SmolVLA steered at inference time with depth-based cost gradients inside its flow-matching sampler, backed by a CBF-QP safety filter. | SmolVLA · RealSense · LeRobot · CBF-QP |
| 🎯 [**Marine PTZ Tracker**](https://github.com/22by7-raikar/marine-ptz-tracker) | Pan/tilt rig that detects and follows a small marine target; an Arduino owns the final safety boundary. | YOLO11n + BoT-SORT · p95 capture-to-command **~58 ms** · 97% frames detected |
| 🚗 [**System ID + MPC Path Tracking**](https://github.com/22by7-raikar/gem_ws) | Neural network learns vehicle dynamics from simulation; MPC uses it to track an 835 m, 3,822-waypoint path on the POLARIS GEM e2. | ROS · Gazebo · PyTorch · CVXPY |
| 🚁 [**Sliding Mode Control for Crazyflie**](https://github.com/22by7-raikar/SMC_Quadrotor) | Boundary-layer SMC with quintic trajectories and custom-trajectory support. | C++ · ROS · **2.48 mm** mean tracking error |

<details>
<summary><b>More work: perception, sensor fusion, planning, RL</b></summary>
<br>

- **LiDAR & sensor fusion:** [Classical 3D LiDAR detection](https://github.com/22by7-raikar/Classical-3D_LiDAR_Detection) (custom RANSAC, KD-tree, clustering and tracking in C++) · [LiDAR–camera 3D object tracking](https://github.com/22by7-raikar/LiDAR_Camera_3D_Object_Tracking) · [UKF LiDAR–RADAR fusion](https://github.com/22by7-raikar/UKF_3D_LiDAR-RADAR_Fusion_Tracking) · [2D feature tracking for collision detection](https://github.com/22by7-raikar/2D-Feature-Tracking-Collision-Detection)
- **Autonomy & planning:** [PlanTF autonomous-driving stack extension](https://github.com/22by7-raikar/PlanTF_Autonomous_Driving_Stack_Extension) · [Motion planning in dynamic environments](https://github.com/22by7-raikar/Motion-Planning-in-Dynamic-Enviroment) · [Motion planning](https://github.com/22by7-raikar/Motion-Planning) · [State estimation & localization for self-driving cars](https://github.com/22by7-raikar/Coursera-State-Estimation-Localization-Self-Driving-Cars)
- **Aerial robotics:** [Hands-on autonomous aerial robotics](https://github.com/22by7-raikar/RBE595-Hands-On-Autonomous-Aerial-Robotics) (Madgwick/UKF attitude estimation, window perception, planning through trees)
- **Learning & vision:** [Reinforcement learning](https://github.com/22by7-raikar/RBE-595-Reinforcement-Learning) · [Panoptic segmentation](https://github.com/22by7-raikar/Panoptic_Segmentation) · [Synthesizing 2D ultrasound from 3D CT](https://github.com/22by7-raikar/Synthesizing-2D-Ultrasound-Images-from-3D-CT-Volume)

</details>

### Toolbox

- **Languages:** C++ (14/17) · Python · MATLAB
- **Robotics:** ROS · Gazebo · LeRobot · PCL · Eigen
- **ML & perception:** PyTorch · OpenCV · YOLO · whisper.cpp · scikit-learn
- **Control & estimation:** MPC · sliding mode control · CBF-QP · Kalman/UKF filtering
- **Engineering:** CMake · GitHub Actions CI · Docker · Doxygen · Arduino

---

<p align="center"><i>Always happy to talk robots, perception, or on-device AI. Reach out!</i></p>
