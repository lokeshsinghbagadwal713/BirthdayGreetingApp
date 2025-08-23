
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

| Main Screen                                                                 | Greeting Screen                                                                     |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| ![MainActivity](https://via.placeholder.com/200x400.png?text=Main+Activity) | ![GreetingActivity](https://via.placeholder.com/200x400.png?text=Greeting+Activity) |


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

👉 Once you add screenshots and upload to GitHub, it’ll look professional.

Do you want me to also **make your GitHub repository folder structure (with starter files like README.md, LICENSE, .gitignore, and sample code)** so you can just push it?
