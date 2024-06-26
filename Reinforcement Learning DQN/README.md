# Reinforcement Learning DQN

## Overview
Like many other areas of machine learning research, reinforcement learning (RL) is evolving at breakneck speed. Just as they have done in other research areas, researchers are leveraging deep learning to achieve state-of-the-art results.

In particular, reinforcement learning has significantly outperformed prior ML techniques in game playing, reaching human-level and even world-best performance on Atari, beating the human Go champion, and is showing promising results in more difficult games like Starcraft II.

In this lab, you will learn to train an RL model to play the cart pole game with near 100% accuracy.

# Objectives
In this lab, you will:

Create an intermediary GCS bucket, clone the sample repository, and configure environment variables.
Create a training job with AI Platform.
Learn the basic principles of reinforcement learning (RL).
Learn about the cart pole game and how RL can be applied to it.
Generate videos of increasingly better performing models on cart pole.
Bonus: play a game of cart pole in the GCP Console with your trained model.
Once you're ready, scroll down and follow the steps below to get your lab environment set up.

## Task 1. Enable AI Platform
Before you clone the code for this lab, make sure the AI Platform service is enabled.

1. On the left-hand side navigation menu of the GCP console, select APIs & Services > Library.

2. Type in AI Platform Training Prediction API in the search console and select the following option:

3. If the API is not already enabled, select the option to enable it. It takes a few minutes to enable the API. Don't proceed until the API is enabled.

## Task 2. Create a storage bucket
1. In the Google Cloud Console, on the Navigation menu (Navigation menu icon), click Cloud Storage.

2. Click + Create.

3. Type a unique name for your bucket, such as your project ID.

4. Click Create.

5. Confirm Enforce public access prevention on this bucket on "Public access will be prevented" pop-up.

## Task 3. Launch AI Platform Notebooks
To launch AI Platform Notebooks:

1. Click on the Navigation Menu (Navigation menu icon). Navigate to AI Platform, then to Workbench.

2. On the Notebook instances page, click NEW NOTEBOOK. Select TensorFlow Enterprise and choose the latest version of TensorFlow Enterprise 2.3 (with LTS) > Without GPUs.

In the pop-up, confirm the name of the deep learning VM, move to the bottom of the window and click Create.

The new VM will take 2-3 minutes to start.

3. Click Open JupyterLab. A JupyterLab window will open in a new tab.

## Task 4. Clone code
To clone the relevant notebook into your JupyterLab instance:

1. In JupyterLab, click the Terminal icon to open a new terminal.

2. At the command-line prompt, type in the following command and press Enter:

```sh
git clone https://github.com/GoogleCloudPlatform/training-data-analyst.git
```

3. Confirm that you have cloned the repository by double clicking on the training-data-analyst directory and ensuring you can see its contents.

## Task 5. Run through the notebook
1. From the left-hand menu, select training-data-analyst > quests > rl > dqn > dqns_on_gcp.ipynb. This will open a new tab.

2. Ensure you're using the Python 3 kernel by selecting Python 3 from the upper right corner of the notebook.
