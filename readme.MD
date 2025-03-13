# 🐍 AI Snake Game using Deep Q-Learning 🎮🧠

## 📌 Overview  
This project implements an **AI-powered Snake Game** 🎮 using **Deep Q-Learning (DQN)**. The AI agent learns how to play Snake by interacting with the environment and optimizing its moves using reinforcement learning.

## 🧐 Problem Statement  
🔹 Traditional Snake games require **human control**.  
🔹 The goal is to develop an **AI agent** 🤖 that **learns to play** efficiently.  
🔹 **Why Deep Q-Learning?**  
   - 🚫 Rule-based approaches **lack adaptability**.  
   - ✅ **DQN enables AI** to generalize from past experiences and improve its decision-making.  

## 🛠 Technology Stack  
- **🖥 Programming Language**: Python 🐍  
- **📚 Libraries Used**:  
  - PyTorch / TensorFlow 🤖 *(Neural Network Training)*  
  - OpenAI Gym 🏋️‍♂️ *(Environment Simulation)*  
  - NumPy & Matplotlib 📊 *(Data Processing & Visualization)*  
  - Pygame 🎮 *(Game Engine)*  

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

## 📂 Project Structure  

# 📦 AI-Snake-Game-DQN  

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


