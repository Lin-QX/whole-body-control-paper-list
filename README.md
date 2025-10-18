# whole-body-control-paper-list
- [Human2Humanoid](#human2humanoid)
- [RL](#rl)
- [Animation](#animation)

## Acknowledgements
This paper list was heavily inspired by the following wonderful repositories. Sincere thanks to their authors:
- [awesome-humanoid-robot-learning](https://github.com/YanjieZe/awesome-humanoid-robot-learning) by [Yanjie Ze](https://github.com/YanjieZe)
- [bipedal-robot-learning-collection](https://github.com/zita-ch/bipedal-robot-learning-collection) by [Zhang Chong](https://github.com/zita-ch)

## Human2Humanoid
utilize motion data
- [2025.10](https://arxiv.org/abs/2510.14952), From Language to Locomotion: Retargeting-free Humanoid Control via Motion Latent Guidance, [website](https://gentlefress.github.io/roboghost-proj/)
- [2025.10](https://arxiv.org/abs/2510.14454), AdaMimic: Towards Adaptable Humanoid Control via Adaptive Motion Tracking, [website](https://taohuang13.github.io/adamimic.github.io/)
- [2025.10](https://arxiv.org/abs/2510.14293), Learning Human-Humanoid Coordination for Collaborative Object Carrying, [website](https://yushi-du.github.io/COLA/)
- [2025.10](https://arxiv.org/abs/2510.11072), PhysHSI: Towards a Real-World Generalizable and Natural Humanoid-Scene Interaction System, [website](https://why618188.github.io/physhsi/)
- [2025.10](https://arxiv.org/abs/2510.05070), ResMimic: From General Motion Tracking to Humanoid Whole-body Loco-Manipulation via Residual Learning, [website](https://resmimic.github.io/)
- [2025.10](https://arxiv.org/abs/2510.02252), Retargeting Matters: General Motion Retargeting for Humanoid Motion Tracking, [code](https://github.com/YanjieZe/GMR)
- [2025.09](https://arxiv.org/abs/2509.26633), OmniRetarget: Interaction-Preserving Data Generation for Humanoid Whole-Body Loco-Manipulation and Scene Interaction, [website](https://omniretarget.github.io/)
- [2025.09](https://arxiv.org/abs/2509.20717), RobotDancing: Residual-Action Reinforcement Learning Enables Robust Long-Horizon Humanoid Motion Tracking
- [2025.09](https://arxiv.org/abs/2509.20322), VisualMimic: Visual Humanoid Loco-Manipulation via Motion Tracking and Generation, [website](https://visualmimic.github.io/)
- [2025.09](https://arxiv.org/abs/2509.16757), HDMI: Learning Interactive Humanoid Whole-Body Control from Human Videos, [website](https://hdmi-humanoid.github.io/)
- [2025.09](https://arxiv.org/abs/2509.16638), KungfuBot2: Learning Versatile Motion Skills for Humanoid Whole-Body Control, [website](https://kungfubot2-humanoid.github.io/)
- [2025.09](https://arxiv.org/abs/2509.15443), Implicit Kinodynamic Motion Retargeting for Human-to-humanoid Imitation Learning
- [2025.09](https://arxiv.org/abs/2509.14353), DreamControl: Human-Inspired Whole-Body Humanoid Control for Scene Interaction via Guided Diffusion, [website](https://genrobo.github.io/DreamControl/)
- [2025.09](https://arxiv.org/abs/2509.13833), Track Any Motions under Any Disturbances, [website](https://zzk273.github.io/Any2Track/)
- [2025.09](https://arxiv.org/abs/2509.13780), Behavior Foundation Model for Humanoid Robots, [website](https://bfm4humanoid.github.io/)
- [2025.09](https://arxiv.org/abs/2509.13534), Embracing Bulky Objects with Humanoid Robots: Whole-Body Manipulation with Reinforcement Learning
- [2025.09](https://arxiv.org/abs/2509.13200), StageACT: Stage-Conditioned Imitation for Robust Humanoid Door Opening, [website](https://icradooropen.github.io/icradooropen/)
- [2025.08](https://arxiv.org/abs/2508.21043), HITTER: A HumanoId Table TEnnis Robot via Hierarchical Planning and Learning, [website](https://humanoid-table-tennis.github.io/)
- [2025.08](https://arxiv.org/abs/2508.08241), BeyondMimic: From Motion Tracking to Versatile Humanoid Control via Guided Diffusion, [website](https://beyondmimic.github.io/)
- [2025.07](https://arxiv.org/abs/2507.15649), EMP: Executable Motion Prior for Humanoid Robot Standing Upper-body Motion Imitation
- [2025.07](https://arxiv.org/abs/2507.09371), Constrained Style Learning from Imperfect Demonstrations under Task Optimality
- [2025.07](https://arxiv.org/abs/2507.07356), UniTracker: Learning Universal Whole-Body Motion Tracker for Humanoid Robots, [website](https://yinkangning0124.github.io/Humanoid-UniTracker/)
- [2025.06](https://arxiv.org/abs/2506.14770), GMT: General Motion Tracking for Humanoid Whole-Body Control, [website](https://gmt-humanoid.github.io/)
- [2025.06](https://arxiv.org/abs/2506.13751), LeVERB: Humanoid Whole-Body Control with Latent Vision-Language Instruction, [website](https://ember-lab-berkeley.github.io/LeVERB-Website/)
- [2025.06](https://arxiv.org/abs/2506.12779), From Experts to a Generalist: Toward General Whole-Body Control for Humanoid Robots, [website](https://beingbeyond.github.io/BumbleBee/)
- [2025.06](https://arxiv.org/abs/2506.12769), RL from Physical Feedback: Aligning Large Motion Models with Humanoid Control, [website](https://beingbeyond.github.io/RLPF/)
- [2025.06](https://arxiv.org/abs/2506.08931), CLONE: Holistic Closed-Loop Whole-Body Teleoperation for Long-Horizon Humanoid Control, [website](https://humanoidclone.github.io/CLONE.github.io/)
- [2025.06](https://arxiv.org/abs/2505.17627), H2-COMPACT: Human-Humanoid Co-Manipulation via Adaptive Contact Trajectory Policies, [website](https://h2compact.github.io/h2compact/)
- [2025.05](https://arxiv.org/abs/2505.07294), HuB: Learning Extreme Humanoid Balance, [website](https://hub-robot.github.io/)
- [2025.05](https://arxiv.org/abs/2505.06776), FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation, [website](https://lecar-lab.github.io/falcon-humanoid/)
- [2025.05](https://arxiv.org/abs/2505.06584), JAEGER: Dual-Level Humanoid Whole-Body Controller, [website](https://beingbeyond.github.io/Jaeger/)
- [2025.05](https://arxiv.org/abs/2505.03738), AMO: Adaptive Motion Optimization for Hyper-Dexterous Humanoid Whole-Body Control, [website](https://amo-humanoid.github.io/)
- [2025.05](https://arxiv.org/abs/2505.03729), VideoMimic: Visual imitation enables contextual humanoid control, [website](https://www.videomimic.net/)
- [2025.05](https://arxiv.org/abs/2505.02833), TWIST: Teleoperated Whole-Body Imitation System, [website](https://yanjieze.com/TWIST/)
- [2025.04](https://arxiv.org/abs/2504.21738), LangWBC: Language-directed Humanoid Whole-Body Control via End-to-end Learning, [website](https://langwbc.github.io/)
- [2025.04](https://arxiv.org/abs/2504.16843), Physically Consistent Humanoid Loco-Manipulation using Latent Diffusion Models
- [2025.04](https://arxiv.org/abs/2504.14305), Adversarial Locomotion and Motion Imitation for Humanoid Policy Learning, [website](https://almi-humanoid.github.io/)
- [2025.02](https://arxiv.org/abs/2502.01465), Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions, [website](https://project-instinct.github.io/)
- [2025.02](https://arxiv.org/abs/2502.01143), ASAP: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills, [website](https://agile.human2humanoid.com/)
- [2024.12](https://arxiv.org/abs/2412.07773), Mobile-TeleVision: Predictive Motion Priors for Humanoid Whole-Body Control, [website](https://mobile-tv.github.io/)
- [2024.10](https://arxiv.org/abs/2410.21229), HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots, [website](https://hover-versatile-humanoid.github.io/)
- [2024.06](https://arxiv.org/abs/2406.10454), HumanPlus: Humanoid Shadowing and Imitation from Humans, [website](https://humanoid-ai.github.io/)
- [2024.06](https://arxiv.org/abs/2406.08858), OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning, [website](https://omni.human2humanoid.com/)
- [2024.03](https://arxiv.org/abs/2403.04436), Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation, [website](https://human2humanoid.com/)
- [2024.02](https://arxiv.org/abs/2402.16796), Expressive Whole-Body Control for Humanoid Robots, [website](https://expressive-humanoid.github.io/)

## RL
env and reward engineering and ...
- [2025.10](https://arxiv.org/abs/2510.11682), Ego-Vision World Model for Humanoid Contact Planning, [website](https://ego-vcp.github.io/)
- [2025.09](https://arxiv.org/abs/2509.21690), Towards Versatile Humanoid Table Tennis: Unified Reinforcement Learning with Prediction Augmentation
- [2025.09](https://arxiv.org/abs/2509.21231), SEEC: Stable End-Effector Control with Model-Enhanced Residual Learning for Humanoid Loco-Manipulation
- [2025.07](https://arxiv.org/abs/2507.08656), Multi-critic Learning for Whole-body End-effector Twist Tracking
- [2025.07](https://arxiv.org/abs/2507.08303), Learning Robust Motion Skills via Critical Adversarial Attacks for Humanoid Robots
- [2025.07](https://arxiv.org/abs/2507.07980), UniTac: Whole-Robot Touch Sensing Without Tactile Sensors, [website](https://ivl.cs.brown.edu/research/unitac)
- [2025.07](https://arxiv.org/abs/2507.06905), ULC: A Unified and Fine-Grained Controller for Humanoid Loco-Manipulation, [website](https://ulc-humanoid.github.io/)
- [2025.06](https://arxiv.org/abs/2506.16986), Learning Accurate Whole-body Throwing with High-frequency Residual Policy and Pullback Tube Acceleration
- [2025.06](https://arxiv.org/abs/2506.09366), SkillBlender: Towards Versatile Humanoid Whole-Body Loco-Manipulation via Skill Blending, [website](https://usc-gvl.github.io/SkillBlender-web/)
- [2025.06](https://arxiv.org/abs/2506.07876), Versatile Loco-Manipulation through Flexible Interlimb Coordination, [website](https://relic-locoman.rai-inst.com/)
- [2025.05](https://arxiv.org/abs/2505.24198), Hold My Beer: Learning Gentle Humanoid Locomotion and End-Effector Stabilization Control, [website](https://lecar-lab.github.io/SoFTA/)
- [2025.05](https://arxiv.org/abs/2505.22974), Learning coordinated badminton skills for legged manipulators
- [2025.05](https://arxiv.org/abs/2505.20829), Learning a Unified Policy for Position and Force Control in Legged Loco-Manipulation, [website](https://unified-force.github.io/)
- [2025.05](https://arxiv.org/abs/2505.10918), Unleashing Humanoid Reaching Potential via Real-world-Ready Skill Space, [website](https://zzk273.github.io/R2S2/)
- [2025.05](https://arxiv.org/abs/2505.06883), FACET: Force-Adaptive Control via Impedance Reference Tracking for Legged Robots, [website](https://facet.pages.dev/)
- [2025.04](https://arxiv.org/abs/2504.06662), RAMBO: RL-Augmented Model-Based Whole-Body Control for Loco-Manipulation, [website](https://jin-cheng.me/rambo.github.io/)
- [2025.02](https://arxiv.org/abs/2502.20061), HiFAR: Multi-Stage Curriculum Learning for High-Dynamics Humanoid Fall Recovery
- [2025.02](https://arxiv.org/abs/2502.13013), HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit, [website](https://homietele.github.io/)
- [2025.02](https://arxiv.org/abs/2502.12152), Learning Getting-Up Policies for Real-World Humanoid Robots, [website](https://humanoid-getup.github.io/)
- [2025.02](https://arxiv.org/abs/2502.08378), Learning Humanoid Standing-up Control across Diverse Postures, [website](https://taohuang13.github.io/humanoid-standingup.github.io/)
- [2025.02](https://arxiv.org/abs/2502.03206), HugWBC: A Unified and General Humanoid Whole-Body Controller for Fine-Grained Locomotion, [website](https://hugwbc.github.io/)
- [2024.10](https://arxiv.org/abs/2410.05681), Whole-Body Dynamic Throwing with Legged Manipulators
- [2024.09](https://arxiv.org/abs/2409.17731), Robust Ladder Climbing with a Quadrupedal Robot
- [2024.09](https://arxiv.org/abs/2409.16048), Whole-body End-Effector Pose Tracking
- [2024.09](https://arxiv.org/abs/2409.04882), Learning to Open and Traverse Doors with a Legged Manipulator
- [2024.06](https://arxiv.org/abs/2406.06005), WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts, [website](https://lecar-lab.github.io/wococo/)
- [2024.03](https://arxiv.org/abs/2403.10506), HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation, [website](https://humanoid-bench.github.io/)
- [2023.10](https://arxiv.org/abs/2310.03191), Sim-to-Real Learning for Humanoid Box Loco-Manipulation

## Animation 
physics-based
- [2025.10](https://arxiv.org/abs/2510.06203), Reference Grounded Skill Discovery
- [2025.09](https://arxiv.org/abs/2509.22442), Learning to Ball: Composing Policies for Long-Horizon Basketball Moves, [website](https://pei-xu.github.io/Basketball)
- [2025.07](https://arxiv.org/abs/2507.05906), Feature-Based vs. GAN-Based Learning from Demonstrations: When and Why
- [2025.05](https://arxiv.org/abs/2505.23708), AMOR: Adaptive Character Control through Multi-Objective Reinforcement Learning
- [2025.05](https://arxiv.org/abs/2505.19086), MaskedManipulator: Versatile Whole-Body Control for Loco-Manipulation
- [2025.05](https://arxiv.org/abs/2505.12619), HIL: Hybrid Imitation Learning of Diverse Parkour Skills from Videos
- [2025.05](https://arxiv.org/abs/2505.12278), Emergent Active Perception and Dexterity of Simulated Humanoids from Visual Reinforcement Learning, [website](https://www.zhengyiluo.com/PDC-Site/)
- [2025.05](https://arxiv.org/abs/2505.04961), ADD: Physics-Based Motion Imitation with Adversarial Differential Discriminators
- [2025.05](https://arxiv.org/abs/2505.04002), PARC: Physics-based Augmentation with Reinforcement Learning for Character Controllers, [code](https://github.com/mshoe/PARC)
- [2025.05](https://arxiv.org/abs/2505.02094), SkillMimic-V2: Learning Robust and Generalizable Interaction Skills from Sparse and Noisy Demonstrations, [website](https://ingrid789.github.io/SkillMimicV2/)
- [2025.04](https://arxiv.org/abs/2504.11054), Zero-Shot Whole-Body Humanoid Control via Behavioral Foundation Models, [website](https://metamotivo.metademolab.com/)
- [2025.03](https://arxiv.org/abs/2503.19901), TokenHSI: Unified Synthesis of Physical Human-Scene Interactions through Task Tokenization, [website](https://liangpan99.github.io/TokenHSI/)
- [2025.02](https://arxiv.org/abs/2502.20390), InterMimic: Towards Universal Whole-Body Control for Physics-Based Human-Object Interactions, [website](https://sirui-xu.github.io/InterMimic/)
- [2024.10](https://arxiv.org/abs/2410.03441), CLoSD: Closing the Loop between Simulation and Diffusion for multi-task character control, [website](https://guytevet.github.io/CLoSD-page/)
- [2024.09](https://arxiv.org/abs/2409.14393), MaskedMimic: Unified Physics-Based Character Control Through Masked Motion Inpainting, [website](https://research.nvidia.com/labs/par/maskedmimic/)
- [2024.08](https://arxiv.org/abs/2408.15270), SkillMimic: Learning Basketball Interaction Skills from Demonstrations, [website](https://ingrid789.github.io/SkillMimic/)
- [2024.06](https://arxiv.org/abs/2406.14558), CooHOI: Learning Cooperative Human-Object Interaction with Manipulated Object Dynamics, [website](https://gao-jiawei.com/Research/CooHOI/)
- [2023.05](https://arxiv.org/abs/2305.06456), Perpetual Humanoid Control for Real-time Simulated Avatars, [code](https://github.com/ZhengyiLuo/PHC)
- [2022.08](https://arxiv.org/abs/2205.01906), ASE: Large-Scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters
- [2021.08](https://arxiv.org/abs/2104.02180), AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control
- [2018.08](https://arxiv.org/abs/1804.02717), DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills
