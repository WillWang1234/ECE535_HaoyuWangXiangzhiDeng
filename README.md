# ECE535_HaoyuWangXiangzhiDeng
**Project Introduction:**

This project, titled "Deep-Learning based Tracking for Mobile Systems," was jointly created by Haoyu Wang and Xiangzhi Deng for the completion of the ECE535 course at Umass Amherst.

**Background:**

Tracking is a fundamental service in mobile embedded systems. For instance, mixed reality headsets require tracking for pose estimation, map generation, and rendering virtual content. Recent advances in deep learning have enabled end-to-end learning methods, mapping raw sensor data to the desired output (pose and map) using neural networks. These networks process images, detect features, estimate depth, and perform related tasks. The first preprocessing step prepares raw data from various sensors to be input into the model. The preprocessed data is fed to the sensor-specific feature encoders that transform the data into high-level representations called feature vectors. The combined feature vectors are fed into a pose regressor, a network trained to predict the pose. The combined feature vectors can also generate a map of the environment.

**Project Goals:**

The goal of this project is to develop a deep learning tracking algorithm for two mobile systems.

**Deliverables:**

- Implement and understand an end-to-end learning approach for tracking – TartanVO.
- Benchmark TartanVO's performance on two datasets to evaluate its effectiveness (data & code provided).
- Analyze performance differences across datasets and provide reasoning for the observed variations.

**Required Software and Hardware:**

- Software: Python
- Hardware: Laptop with CUDA-enabled GPU

**References:**

- Paper: [TartanVO: A Generalizable Learning-based VO](https://arxiv.org/pdf/2011.00359.pdf)
- Code Repository: [GitHub Repository](https://github.com/castacks/tartanvo)
- Datasets:
  1. [EuRoC Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)
  2. [KITTI Dataset](https://www.cvlibs.net/datasets/kitti/eval_odometry.php)
  3. [HoloSet Dataset](https://tinyurl.com/holoset-dataset)

This project is a collaborative effort by Haoyu Wang and Xiangzhi Deng to explore deep learning-based tracking in the context of mobile systems.
