# 🧠 Flappy Bird AI

A self-learning Flappy Bird AI built using **Artificial Neural Networks (ANN)** and **Neuroevolution** concepts like **speciation**, **fitness calculation**, **sorting by fitness**, and **child generation**. The AI plays the game, evolves over generations, and gets better at surviving.

## Preview:
![Screenshot1](/images/ss.png)
![screenshot2](/images/sss.png)


## 🚀 Features
- ✅ Neural network-based AI birds
- 🧬 Genetic Algorithm: evolve smarter generations
- 📊 Fitness calculation based on survival time and pipe navigation
- 🧠 Speciation to preserve innovation and avoid premature convergence
- 📈 Real-time training and visual feedback

## 🧬 How It Works

### 1. **Neural Network (ANN)**
Each bird has a simple neural network:
- **Inputs**: vertical distance from pipe, horizontal distance to pipe, bird's velocity, etc.
- **Output**: whether to flap or not

### 2. **Fitness Function**
Fitness is calculated by:
- +1 for every pipe passed

### 3. **Selection & Speciation**
- Birds are grouped into **species** based on genome similarity
- Within each species, only the top performers are allowed to reproduce
- 
### 4.  **Evolution Loop**

#To Run This Locally :
- Download the Repo.
- Use following command:
```bash
pip install pygame
python main.py  

```

