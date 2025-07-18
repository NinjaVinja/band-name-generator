# 🎸 Band Name Generator 🎤

Welcome to the **Band Name Generator** – a fun and beginner-friendly Python project that suggests a band name based on your personal input. Just enter your city and your pet's name, and get a cool band name idea instantly!

---

## 🚀 Features

- Simple interactive command-line interface
- Great for practicing Python `input()` and `print()` functions
- No external libraries required
- Beginner-level project to get started with Python

---

## 🧠 How It Works

1. The program greets the user.
2. It asks for:
   - The name of the city you grew up in
   - The name of your pet
3. It then combines them to generate a potential **band name**.

---

## 💻 Code Example

```python
print("🎸 Welcome to the Band Name Generator 🎤")
city_name = input("What's the name of the city you grew up in? \n")
pets_name = input("What's your pet's name? \n")
print("Your band name could be: " + city_name + " " + pets_name)
