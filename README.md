
# 🌱 ReLeaf — Smart Environmental Action Platform

ReLeaf is an environmental awareness and green-action application developed during **InnoHack 4.0 at KIET Deemed to be University**. The project aims to encourage people to take meaningful environmental actions through technology.

The project combines an Android mobile application with a Django backend to connect the user interface with backend APIs and support the application's functionality.

## ✨ Key Features

- 📱 **Android Application:** A mobile interface designed to make environmental engagement accessible.
- 🌿 **Environmental Awareness:** Encourages users to participate in green initiatives and sustainable activities.
- 🔗 **API Integration:** Connects the Android application with the Django backend.
- ⚙️ **Backend Services:** Uses Python and Django to manage server-side functionality.
- 🌍 **Green Action:** Focuses on encouraging positive environmental behaviour.

*Note: Features may vary depending on the current implementation of the application.*

## 🛠️ Tech Stack

### Android Application
- Java
- XML
- Android SDK
- Gradle

### Backend
- Python
- Django
- REST API integration

### Tools
- Android Studio
- Visual Studio Code
- Git and GitHub

## 📂 Project Structure

```text
ReLeaf/
├── android/          # Android application source code
├── backend/          # Django backend source code
├── .gitignore        # Git ignore rules
└── README.md         # Project documentation
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/divyanshdahikar/ReLeaf.git
cd ReLeaf
```

### 2. Set Up the Android Application

1. Install [Android Studio](https://developer.android.com/studio).
2. Open Android Studio.
3. Select **Open** and choose the `android` folder.
4. Allow Gradle to sync and install any required dependencies.
5. Run the application on an emulator or a compatible Android device.

If an APK is available in the repository, you can also use it to install the application on a compatible Android device.

### 3. Set Up the Django Backend

Make sure Python is installed on your system.

Open a terminal in the backend directory:

```bash
cd backend
```

Create and activate a virtual environment.

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Configure the environment variables using the provided `.env.example` file. Create a local `.env` file and fill in the required values according to the project's configuration.

Run database migrations:

```bash
python manage.py migrate
```

Start the development server:

```bash
python manage.py runserver
```

The backend will usually be available at:

```text
http://127.0.0.1:8000/
```

**Important:** When connecting the Android emulator to a backend running on your computer, `127.0.0.1` inside the emulator refers to the emulator itself. Use `10.0.2.2` to access your computer's localhost from the standard Android emulator, and configure the API base URL accordingly.

## 👥 Team & Hackathon

ReLeaf was developed as part of **InnoHack 4.0**, hosted at **KIET Deemed to be University**.

- **Team:** [Add team name]
- **Team Members:** [Tag or add teammate names]
- **Hackathon Organizer:** InnoGeeks
- **Institution:** KIET Deemed to be University

Thank you to the organizers, mentors, and fellow participants for providing an opportunity to learn, collaborate, and build solutions with real-world impact.

## 🔮 Future Improvements

- Expand environmental awareness and green-action features.
- Improve user experience and application performance.
- Add more environmental data integrations.
- Enhance backend reliability and API functionality.
- Introduce additional features that encourage sustainable habits.

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome.

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch to your fork.
5. Open a Pull Request.

## 📄 License

No license has been specified yet. Please contact the repository owner before reusing or distributing this project's code.

## 🔗 Repository

GitHub: [divyanshdahikar/ReLeaf](https://github.com/divyanshdahikar/ReLeaf)

---

**Built with 🌱 to encourage environmental awareness and positive change.**
