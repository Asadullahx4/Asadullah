# 👋 Hey there, I'm **Asadullah**!  

### **Learning to build cool things with code** 🌱  
_**Tech enthusiast | Software Developer | Cloud Explorer | AI Advocate**_

---

### I'm a final-year Computer Systems student at **Riga Technical University** (RTU), passionate about building cool things with code and learning new tech every day. 🌱

---

### 🚀 **Current Focus**
- **Software Development** (Python, Cloud, AI)
- Diving deep into **Cloud Computing** and **Artificial Intelligence**.

---

### 💻 **Skills & Technologies**  
- **Languages**: `Python`, `SQL`, `JavaScript`
- **Cloud**: `Oracle Cloud`, `AWS`
- **Tools**: `Git`, `Linux`, `Docker`
- **Interests**: **AI**, **Machine Learning**, **Full-stack Development**

---

### 📂 **Current Projects**  
- Building **cloud-based solutions** that scale.
- Exploring real-time data processing with **AI**.

---

### 🌱 **What I’m Learning**  
- **Cloud** technologies and **Machine Learning**.
- Advanced **Software Engineering** principles.

---

### 📬 **Let’s Connect!**  
- [LinkedIn](https://www.linkedin.com/in/asad-ullah-9b687b263/)

---

### 🏅 Fun Fact
- Sports lover and always up for a tech challenge! ⚽🏀 

---

### 📱 **Contact Me**  
[![Email](https://img.shields.io/badge/Gmail-Email-red?logo=gmail&logoColor=white)](mailto:iasadullah04@gmail.com)  
[![Phone](https://img.shields.io/badge/Phone-%2B37126219910-green?logo=phone&logoColor=white)](tel:+37126219910)

---

_"Code is like humor. When you have to explain it, it’s bad."_ - Cory House



---

## 🎮 Fun Game: Guess the Number!

Try to guess the number I’m thinking of between 1 and 10! Here's a simple game in Python:

```python
import random

def guess_the_number():
    number = random.randint(1, 10)
    guess = None
    attempts = 0

    print("Welcome to Guess the Number!")
    print("I’m thinking of a number between 1 and 10.")

    while guess != number:
        guess = int(input("Enter your guess: "))
        attempts += 1
        if guess < number:
            print("Too low! Try again.")
        elif guess > number:
            print("Too high! Try again.")
        else:
            print(f"Congratulations! You've guessed the right number {number} in {attempts} attempts.")

guess_the_number()
