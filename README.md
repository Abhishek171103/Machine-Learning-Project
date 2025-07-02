# Machine-Learning-Project
# Mini assessment task


# 📝 Mini Report: ML Classification & Generative AI

---

## 🧠 Task 1: ML Classification using PyTorch (Iris Dataset)

We built a simple two-layer neural network from scratch using PyTorch to classify the famous Iris dataset into three flower species: Setosa, Versicolor, and Virginica.

### 🔧 Model Architecture

- **Input Layer**: 4 neurons (features)
- **Hidden Layer**: 10 neurons, ReLU activation
- **Output Layer**: 3 neurons (classes)

### ⚙️ Training Details

- **Optimizer**: Stochastic Gradient Descent (SGD)
- **Loss Function**: CrossEntropyLoss
- **Epochs**: 50
- **Train/Test Split**: 80/20
- **Feature Scaling**: Standardized using `StandardScaler`

### 📈 Results

- **Final Train Accuracy**: ~100%
- **Final Test Accuracy**: ~96% (varies slightly by run)
- The model achieved high accuracy on both train and test data, indicating good generalization.

### 📊 Accuracy vs Epoch Plot

Train and test accuracy steadily increased and stabilized by epoch 30–40, showing successful learning without overfitting.

---

## 🤖 Task 2: Generative AI using GPT-2

We used Hugging Face's GPT-2 (small) model to explore the effect of temperature on text creativity. The prompt used was:

> `"Once upon a time"`

### 🛠 Generation Parameters

- **Model**: GPT-2 (117M)
- **Top-k**: 50
- **Max Tokens**: 50
- **Temperatures**: 0.7 and 1.0

### 📄 Output Comparison

#### 🔹 Temperature = 0.7

> Once upon a time, the sun was shining behind the clouds, rising and falling like a stream of water, and the sun was descending...

- Output is more **coherent**, logical, and grammatically correct.

#### 🔹 Temperature = 1.0

> Once upon a time this game was about something bigger than itself. The player has to take a game to the next level...

- Output is more **creative**, with abstract or surprising sentences.

### 🎯 Key Insight

- **Lower temperature (0.7)** results in focused, sensible text.
- **Higher temperature (1.0)** increases creativity but may reduce coherence.

---

## 🧠 Key Learnings

During this project, I learned many useful things about Machine Learning and Generative AI.

### 🔹 What was challenging:
- I had to write the full training loop myself and understand how data is passed, how loss is calculated, and how the model learns.
- It was also tricky to set the right training settings like learning rate and number of neurons. But after trying a few times, I got good accuracy.

### 🔹 What was interesting:
- The most interesting part was generating text using GPT-2. I liked how changing the **temperature** made the text either more focused or more creative.
- Using Hugging Face was also fun because it made working with a powerful AI model very easy with just a few lines of code.

I really enjoyed seeing how AI can learn from data and also create something new like human-like text.

## ✅ Conclusion

This assessment successfully covered both supervised ML using PyTorch and generative text using transformers. It provided hands-on experience with foundational AI concepts and helped us appreciate both predictive accuracy and creative diversity in modern models.
