# Deep Q-Learning Project

This project implements Deep Q-Learning with Experience Replay for the Lunar Lander environment.

## Description

The repository includes the implementation of the Deep Q-Learning algorithm using the following components:
- Experience replay for stabilizing training.
- A target Q-Network for more stable Q-value updates.
- An epsilon-greedy policy for action selection.

## Files

- `C3_W3_A1_Assignment.ipynb`: Jupyter notebook containing the implementation and training process.
- `deep_q_algorithm.png`: Diagram of the Deep Q-Learning algorithm.
- `lunar_lander.gif`: GIF showing the Lunar Lander environment.
- `public_tests.py`: Python script containing public tests for the implementation.
- `rl_formalism.png`: Diagram explaining the reinforcement learning formalism.
- `utils.py`: Utility functions used in the project.

## Getting Started

### Prerequisites

To run this project, you need the following dependencies:
- Python 3.x
- Jupyter Notebook
- NumPy
- TensorFlow or PyTorch
- Gym

### Installation

1. Clone the repository:

   git clone https://github.com/regmibhuwan/deep_q_learning_project.git
   cd deep_q_learning_project

2. Install the required dependencies:

pip install -r requirements.txt

3. Open the Jupyter notebook and run the cells:

jupyter notebook C3_W3_A1_Assignment.ipynb

## Usage
Run the Jupyter notebook to train the Deep Q-Learning agent on the Lunar Lander environment and observe the learning process.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
