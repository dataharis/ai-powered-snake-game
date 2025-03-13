# 🐍 AI Snake Game using Deep Q-Learning 🚀

## 📌 Project Documentation  

### 📍 Objectives  

#### 🎯 Problem Statement  
- Traditional Snake game is controlled by humans.  
- The aim is to develop an AI agent that learns how to play efficiently using Deep Q-Learning.  
- **Why Deep Q-Learning?**  
  - Traditional rule-based approaches lack adaptability.  
  - Deep Q-Learning allows AI to learn optimal strategies dynamically by generalizing from past experiences.  

#### 🎯 Goals  
- Implement an AI agent using Deep Q-Learning to play the Snake game autonomously.  
- Train the AI to maximize its score while avoiding obstacles.  
- Visualize training performance and analyze AI improvement over time.  

---

## 🛠️ Coding Process  

### 📌 Step-by-Step Breakdown  

1️⃣ **Planning**  
   - Define game rules and AI training methodology.  
   - Choose frameworks and libraries (Pygame, PyTorch, NumPy).  

2️⃣ **Design**  
   - Define state representation (snake position, food, obstacles).  
   - Design the reward system for AI training.  

3️⃣ **Implementation**  
   - **`game.py`** → Implements the Snake game environment.  
   - **`agent.py`** → AI agent that learns through Deep Q-Learning.  
   - **`model.py`** → Defines the neural network for AI learning.  
   - **`plot.py`** → Visualizes training progress.  

4️⃣ **Testing**  
   - Debug AI behavior and fine-tune hyperparameters.  
   - Ensure smooth gameplay and reward optimization.  

---

## 🚧 Key Challenges & Solutions  

### ⚠️ Challenges Encountered  
- Training instability due to high variance in AI actions.  
- Optimizing the reward function for better learning.  

### ✅ Solutions & Problem-Solving  
- Implemented **experience replay** to stabilize training.  
- Tuned learning rate and discount factor for optimal training results.  

---

## ✨ Features & Design  

✅ **Deep Q-Learning for AI Training**  
✅ **Automated Gameplay with AI Agent**  
✅ **Training Visualization with Graphs**  
✅ **Modular Code Structure for Flexibility**  

---

## ⚙️ How It Works  
### 1️⃣ **State Representation** 🧩  
   - AI **observes** the game (snake position, food position, obstacles).  
   - Converts the game environment into **numerical data** for processing.  

### 2️⃣ **Action Selection** 🎯  
   - The AI **chooses the best move** (Up, Down, Left, Right) using predicted **Q-values**.  

### 3️⃣ **Reward System** 💰  
   - ✅ **+10** for eating food 🍏  
   - ❌ **-10** for hitting a wall or itself 💀  
   - ⏳ **Small penalty** for each step to encourage efficient food collection.  

### 4️⃣ **Training with Deep Q-Learning** 📈  
   - The AI **trains over thousands of games**, learning from rewards & penalties.  
   - Uses **experience replay** for efficient learning.  

## 📊 Training Process  
- AI starts with **random moves** 🤪 and gradually **improves its decisions** using the **epsilon-greedy strategy**.  
- **Training Graphs** 📉 visualize how AI **improves over time**:  
  - 🔵 **Blue Line**: Scores per game.  
  - 🟠 **Orange Line**: Moving average of scores.  

## 🏆 Results & Performance  
- 🎯 **Initial AI Score (Random Moves)**: ~5  
- 🚀 **AI Score After Training**: **50+**  
- 🧑‍🤝‍🧑 **Human Average Score**: ~30  
- ✅ The AI **outperforms most human players** after sufficient training.  

## 🚀 Future Improvements  
🔹 Implement **Double DQN** for better decision-making.  
🔹 Use **CNN-based models** 🧠 for advanced state representation.  
🔹 Optimize the **reward system** for **faster AI training**. 

---
## 📂 Project Structure  
```
┣ 📜 agent.py         # AI agent (Deep Q-Learning)  
┣ 📜 game.py          # Snake game environment (Pygame)  
┣ 📜 model.py         # Neural Network model  
┣ 📜 helper.py          # Training performance visualization  
┣ 📜 README.md        # Project documentation  
┗ 📜 requirements.txt  # Dependencies  
```

---

## 🛠 Installation & Setup  

### 1️⃣ Clone the repository ⬇️  
```bash
git clone https://github.com/dataharis/ai-powered-snake-game.git
cd ai-powered-snake-game  
```

### 2️⃣ Install dependencies 📦  
```bash
pip install -r requirements.txt  
```

### 3️⃣ Run the game with AI 🤖  
```bash
python game.py   
python agent.py  # Train AI to play Snake  
```

---

## 👨‍💻 Contributors  
**Harish Saifi** ([LinkedIn](http://www.linkedin.com/in/dataharis) | [GitHub](https://github.com/dataharis)) 🚀  

🔥 Happy Coding! 🔥  
