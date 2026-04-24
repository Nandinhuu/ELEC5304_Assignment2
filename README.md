# ELEC5304_Assignment2
1. Project 2: CIFAR-10 Classification Network

2. Import Libraries and Set Runtime
   说明使用 PyTorch、torchvision、T4 GPU。

3. Data Preparation
   下载 CIFAR-10。
   用 80%:20% split 得到 training set 和 testing set。
   使用 transforms，包括 RandomCrop、RandomHorizontalFlip、Normalize。

4. Baseline CNN Model
   设计一个合理 CNN。
   解释为什么 CNN 适合图像分类。

5. Training and Evaluation Functions
   写 train_one_epoch、evaluate、accuracy 计算函数。

6. Main Training for >80% Test Accuracy
   使用较完整训练，例如 20 到 40 epochs。
   输出 test accuracy。
   保存结果截图或打印结果。

7. Fast Training Model for 1-Minute T4 Target
   设计更轻量或更高效的网络。
   训练时间限制 1 分钟。
   输出 training time 和 test accuracy。
   目标至少 70%。

8. Design Justification
   解释网络结构、optimizer、learning rate、data augmentation、batch size。

9. Task 2 Question Answer
   回答 limited training time 下什么 architecture 更适合，以及原因。

10. Final Summary
   列出两个目标是否达成。
