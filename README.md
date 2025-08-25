
# 🎂 Birthday Greeting App

A simple Android application that allows users to enter a name and generate a personalized **Birthday Greeting** message.

---

## 📌 Features

* 🎨 **UI designed with XML (ConstraintLayout)**
* 📝 **EditText** for entering the birthday person’s name
* 🔘 **Button** to send the name to the next activity
* 🖼️ **ImageView** with a birthday cake image
* 📤 **Intent-based navigation** between activities
* 🎉 Displays a **custom birthday greeting message**

---

## 📷 Screenshots

| Main Screen | Greeting Screen |
| ----------- | --------------- |
| <img src="https://github.com/user-attachments/assets/a61e48af-7acd-44d5-842a-93bcca47ff2b" width="250"/> | <img src="https://github.com/user-attachments/assets/77c26730-670a-4101-b3c2-cbde7d7b6b13" width="250"/> |



---

## 🛠️ Tech Stack

* **Language:** Java
* **UI Design:** XML
* **Framework:** Android SDK
* **IDE:** Android Studio

---

## 🚀 How It Works

1. User enters a **name** in `EditText`.
2. Clicks on the **Send Greeting** button.
3. Name is passed to another activity using an **Intent**.
4. Second activity displays **“Happy Birthday <Name>!”** with an image.

---

## 📂 Project Structure

```
BirthdayGreetingApp/
│── app/src/main/java/com/example/birthdaygreet/
│   ├── MainActivity.java        # First screen (input name)
│   ├── GreetingActivity.java    # Second screen (show greeting)
│
│── app/src/main/res/layout/
│   ├── activity_main.xml        # Layout for MainActivity
│   ├── activity_greeting.xml    # Layout for GreetingActivity
│
│── app/src/main/res/drawable/
│   ├── birthday_cake.png        # Birthday image
```

---

## 🖥️ Installation & Run

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/BirthdayGreetingApp.git
   ```
2. Open in **Android Studio**.
3. Run on Emulator or Physical Device.
