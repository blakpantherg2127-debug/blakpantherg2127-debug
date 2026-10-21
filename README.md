## Dagmawi Guangul

I'm an M.S. student in Artificial Intelligence at Minnesota State University, Mankato, in the combined BS/MS program. I build machine learning systems and measure whether they actually work: per-class and per-range failure analysis, honest baselines, and confidence intervals on the numbers I report. My work spans perception for autonomous driving, ranking models, 3D vision, data pipelines and product experimentation.

I'm looking for Summer 2027 internships in machine learning, perception and data science.

Feel free to contact me at **guanguldagmawi@gmail.com** (preferred) or dagmawiguangul@gmail.com.

[LinkedIn](https://www.linkedin.com/in/dagmawi-guangul/) · [Older personal GitHub](https://github.com/Dagmawi-Guangul)

### Perception and 3D vision

**[kitti-perception-failure-analysis](https://github.com/blakpantherg2127-debug/kitti-perception-failure-analysis)**  
0.825 mAP@50 hid a 0.543 pedestrian recall. Class- and size-level failure analysis of a YOLO26-nano detector on KITTI: recall by object size with bootstrap confidence intervals, a breakdown of why each missed box was missed, threshold trade-offs and per-class calibration.

**[nuscenes-lidar-camera-fusion-eval](https://github.com/blakpantherg2127-debug/nuscenes-lidar-camera-fusion-eval)**  
Over half of annotated nuScenes objects have fewer than 5 LiDAR points. Range and camera-visibility analysis of 18,538 annotations, with a LiDAR-to-camera transform chain tested against the official devkit.

**photo-head** (private)  
3D head reconstruction from one front and one side photo, with camera registration, silhouette fitting, texture projection and a scan-comparison viewer.

### Ranking and applied ML

**CTR prediction pipeline** (private)  
Criteo ad-click pipeline with feature hashing and log transforms. Logistic-regression baseline at 0.774 test AUC on 4.59M held-out impressions; DeepFM and DCNv2 ranking models built and tested on synthetic data, full Criteo runs in progress.

**MinneMUDAC 2025**  
Mentor-mentee match prediction for Big Brothers Big Sisters, combining an LSTM with few-shot LLM prompting; 6.7 RMSE.

### Data systems

**[environmental-monitoring-system](https://github.com/Dagmawi-Guangul/environmental-monitoring-system)**  
Java and JavaScript system for ingesting and displaying multi-source environmental sensor data (in progress).

**chouse** (private)  
Entity matching across four open datasets, with distance, address and name evidence combined into confidence-tiered matches; 42 test files.

**nateco** (private)  
Data pipeline whose results must beat random, no-change and density baselines before they count.

Private repositories are available on request.

### Background

- Data science extern at Hulugram, a messaging app: designed A/B tests for in-app features with the product team and used causal inference to estimate their effect on session duration. Built a reusable experiment-design framework that standardized effect sizes and statistical power thresholds and added sequential testing.
- Led a five-person technical research team at the Green Legacy Initiative in Addis Ababa, Ethiopia, building data pipelines and reporting tools.
- Event coordinator for the MNSU chapter of the National Society of Black Engineers; member of ColorStack and CodePath.

### Tools

Python, PyTorch, scikit-learn, NumPy, pandas, Ultralytics YOLO, nuScenes devkit, pytest, ruff, Docker. Also R, Java, JavaScript and SQL.
