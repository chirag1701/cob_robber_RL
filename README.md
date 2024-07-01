# Cops and Robbers Reinforcement Learning

This project demonstrates a reinforcement learning environment for a Cops and Robbers game using Python. The environment simulates a simple grid world where a cop tries to catch a robber.

## Table of Contents
- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Results](#results)
- [Author](#author)

## Introduction

The Cops and Robbers project simulates a grid world environment where agents (cops and robbers) interact. The cop's goal is to catch the robber, while the robber aims to evade capture. The project utilizes reinforcement learning techniques to train agents in this environment.

## Environment Setup

### Prerequisites
- Python 3.11
- Required Python libraries are listed in `requirements.txt`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/chirag1701/cops_and_robbers_rl.git
   cd cops_and_robbers_rl
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the environment test, execute the following command:

```bash
python cop_robbers_RL.ipynb
```

The script will initialize the environment, run a test episode, and print the results to the console.

### Example Output

```
Step 1
=======================
| . . . . . . . . . . |
| . . . . . . . . . . |
| . . . . . . . . . . |
| . . . . . . . . . . |
| C . . . . . . . . . |
| . . . . . . . . . . |
| . . . . . . . . . . |
| . . . . . . . . . . |
| . . . . . . . . . R |
| . . . . . . . . . . |
=======================
Actions: {'cop': 2, 'robber': 3}, Rewards: {'cop': -1, 'robber': 1}
...
```

## Results

The training results are logged and displayed during the simulation, showing various metrics such as episode length mean, reward mean, and loss values. The environment visualization updates at each step, showing the positions of the cop and robber.

## Author

Chirag Sindhwani  
Dept of Electrical Engineering  
IIT BHU , Varanasi, India
