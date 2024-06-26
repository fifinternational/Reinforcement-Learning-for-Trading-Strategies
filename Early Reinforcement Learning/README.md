# Early Reinforcement Learning

## Overview
Like many other areas of machine learning research, reinforcement learning (RL) is evolving at breakneck speed. Just as they have done in other research areas, researchers are leveraging deep learning to achieve state-of-the-art results.

In particular, reinforcement learning has significantly outperformed prior ML techniques in game playing, reaching human-level and even world-best performance on Atari, beating the human Go champion, and is showing promising results in more difficult games like Starcraft II.

In this lab, you will learn the basics of reinforcement learning by building a simple game, which has been modeled off of a sample provided by OpenAI Gym.

## Objectives
In this lab, you will:

+ **Create a Vertex Notebook.**
+ **Clone the sample repository from the training data analyst repo found on Github.**
+ **Read, understand, and run the steps found in the notebook.**
  
Once you're ready, scroll down and follow the steps below to get your lab environment set up.

## Task 1. Launch Vertex AI Notebooks
1. In the Google Cloud Console, on the Navigation Menu, click Vertex AI > Workbench. Select User-Managed Notebooks.

2. On the Notebook instances page, click New Notebook > TensorFlow Enterprise > TensorFlow Enterprise 2.6 (with LTS) > Without GPUs.

3. In the New notebook instance dialog, confirm the name of the deep learning VM, if you don’t want to change the region and zone, leave all settings as they are and then click Create. The new VM will take 2-3 minutes to start.

Click Open JupyterLab.
A JupyterLab window will open in a new tab.

You will see “Build recommended” pop up, click Build. If you see the build failed, ignore it.

## Task 2. Clone course repo within your Vertex AI Notebooks instance
To clone the training-data-analyst notebook in your JupyterLab instance:

1. In JupyterLab, to open a new terminal, click the Terminal icon.

2. At the command-line prompt, run the following command:

```sh
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
```

3. To confirm that you have cloned the repository, double-click on the training-data-analyst directory and ensure that you can see its contents.
The files for all the Jupyter notebook-based labs throughout this course are available in this directory.

## Task 3. Run through the Notebook
1. From the left-hand menu, select training-data-analyst > quests > rl > early_rl > early_rl.ipynb. This will open a new tab.

2. Ensure you're using the Python 3 kernel by selecting Python 3 from the upper right corner of the notebook.
