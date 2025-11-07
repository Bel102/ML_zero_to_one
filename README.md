🧠 MNIST 手写数字识别 (My First Machine Learning Project)








这是我跟着 AI 一步步完成的第一个机器学习项目，使用 Python + Jupyter Notebook 构建了一个简单的神经网络来识别手写数字（MNIST 数据集）。
虽然我还是零基础，但这个项目让我初步了解了机器学习的工作流程 🚀

🧩 项目简介

本项目训练了一个全连接神经网络模型 (Fully Connected Neural Network)，用于识别 0~9 的手写数字。
数据集来自经典的 MNIST，模型包括：

输入层：28×28 的灰度图像

隐藏层：128 个神经元 + ReLU 激活

输出层：10 分类 + Softmax 激活

🧰 使用技术

Python 3.8+

TensorFlow / Keras

Matplotlib

Jupyter Notebook

⚙️ 运行方法

克隆项目：

git clone https://github.com/你的用户名/你的仓库名.git
cd 你的仓库名


安装依赖：

pip install tensorflow matplotlib


打开 Notebook：

jupyter notebook


运行 first_whole_project.ipynb，查看训练过程与结果。

📊 模型表现

训练完成后，模型在测试集上通常能达到约 97% 的准确率。
你可以通过修改模型层数或学习率来尝试进一步提升性能。

💡 学习收获

通过这个项目，我学会了：

如何加载与预处理数据；

如何构建与训练神经网络；

如何评估模型的性能；

如何在 Jupyter Notebook 中记录实验。
