# 📱 Android Visiting Card App (Java)

A simple Android application that displays a personal visiting card using **Java** and **XML** in Android Studio.

---

## 📋 Requirements

- Android Studio
- Java
- Android SDK

---

## 📁 Project Structure

```
app/
└── src/
    └── main/
        ├── java/
        │   └── com/example/visitingcard/
        │       └── MainActivity.java
        │
        ├── res/
        │   ├── layout/
        │   │   └── activity_main.xml
        │   │
        │   └── drawable/
        │       └── profile.png
        │
        └── AndroidManifest.xml
```

---

## 🚀 How to Use

### Step 1: Create a New Project

1. Open **Android Studio**
2. Click **New Project**
3. Select **Empty Views Activity**
4. Choose **Java** as the language.
5. Click **Finish**.

---

### Step 2: Add the Java Code

Open:

```
app > java > MainActivity.java
```

Replace the existing code with the provided **MainActivity.java** code.

---

### Step 3: Add the XML Layout

Open:

```
app > res > layout > activity_main.xml
```

Replace the existing code with the provided **activity_main.xml** code.

---

### Step 4: Update the Manifest

Open:

```
app > manifests > AndroidManifest.xml
```

Replace or update it with the provided **AndroidManifest.xml** code.

---

### Step 5: Add Your Profile Picture

Copy your image into:

```
app
└── src
    └── main
        └── res
            └── drawable
                └── profile.png
```

Then change the ImageView source:

```xml
android:src="@drawable/profile"
```

---

### Step 6: Edit Your Details

Open **activity_main.xml** and change the following values:

- Name
- Job Title
- Company
- Phone Number
- Email
- Website
- Address

Example:

```xml
android:text="John Smith"
```

Replace it with:

```xml
android:text="Your Name"
```

---

### Step 7: Run the App

1. Connect an Android device or start an emulator.
2. Click the **Run ▶** button.
3. The visiting card will appear on the screen.

---

## 📱 Features

- Profile Image
- Name
- Job Title
- Company Name
- Phone Number
- Email Address
- Website
- Address
- Scrollable Layout

---

## 📂 Files Used

| File | Purpose |
|------|---------|
| `MainActivity.java` | Loads the main layout |
| `activity_main.xml` | Designs the visiting card |
| `AndroidManifest.xml` | App configuration |
| `profile.png` | Profile image |

---

## 🛠 Technologies Used

- Java
- XML
- Android Studio
- Android SDK

---

## ▶ Expected Output

The application displays a simple digital visiting card containing:

- 👤 Profile Photo
- 🧑 Name
- 💼 Designation
- 🏢 Company
- 📞 Phone Number
- 📧 Email
- 🌐 Website
- 📍 Address

---

## 📄 License

This project is for educational and learning purposes.
