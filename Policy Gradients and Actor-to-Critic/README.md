# Policy Gradients and Actor-to-Critic

## Overview
Like many other areas of machine learning research, reinforcement learning (RL) is evolving at breakneck speed. Just as they have done in other research areas, researchers are leveraging deep learning to achieve state-of-the-art results.

In particular, reinforcement learning has significantly outperformed prior ML techniques in game playing, reaching human-level and even world-best performance on Atari, beating the human Go champion, and is showing promising results in more difficult games like Starcraft II.

In this lab, you will learn to train an RL model to play the cart pole game using policy gradients and actor-to-critic.

## Objectives
In this lab, you will:

**Explore policy gradients in RL**
**Explore the actor-to-critic model**
Once you're ready, scroll down and follow the steps below to get your lab environment set up.

## Create a storage bucket
1. In the Google Cloud Console, on the Navigation menu (Navigation menu icon), click Cloud Storage.

2. Click + Create.

3. Type a unique name for your bucket, such as your project ID.

4. Click Create.

5. Confirm Enforce public access prevention on this bucket on "Public access will be prevented" pop-up.

## Task 1. Enable AI Platform
Before you clone the code for this lab, make sure the AI Platform service is enabled.

1. In the left-hand side navigation menu of the GCP console, select APIs & Services > Library.

2. Type in AI Platform Training & Prediction API in the search console and select the following option:

3. If the API is not already enabled, select the option to enable it. It takes a few minutes to enable the API. Don't proceed until the API is enabled.

## Task 2. Launch AI Platform Notebooks
To launch AI Platform Notebooks:

1. Click on the Navigation Menu. Navigate to AI Platform, then to Notebooks.

2. On the Notebook instances page, click New Notebook.

3. Select TensorFlow Enterprise and choose the latest version of TensorFlow Enterprise 2.6 (with LTS) > Without GPUs.

4. In the pop-up, confirm the name of the deep learning VM, and then move to the bottom of the window and click Create.

The new VM will take 2-3 minutes to start.

5. Click Open JupyterLab. A JupyterLab window opens in a new tab.

## Task 3. Clone course repo within your AI Platform Notebooks instance
To clone the training-data-analyst notebook in your JupyterLab instance:

1. In JupyterLab, to open a new terminal, click the Terminal icon.

2. At the command-line prompt, run the following command:

```sh
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
```
3. To confirm that you have cloned the repository, double-click on the training-data-analyst directory and ensure that you can see its contents.
The files for all the Jupyter notebook-based labs throughout this course are available in this directory.

## Task 4. Run through the Notebook
1. From the left-hand menu, select training-data-analyst > quests > rl > a2c > a2c_on_gcp.ipynb. This will open a new tab.

2. Ensure you're using the Python 3 kernel by selecting Python 3 from the upper right corner of the notebook.

3. In the notebook interface, click on Edit > Clear All Outputs (click on Edit, then in the drop-down menu, select Clear All Outputs).
