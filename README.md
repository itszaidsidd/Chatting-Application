# 💬 Real-Time Chatting Application

A desktop-based real-time peer-to-peer chat application built using **Java**, **Java Swing**, and **TCP/IP Sockets**, featuring separate **Server** and **Client** modules for live bi-directional communication.

---

## 🚀 Features

* **Real-Time Communication:** Instant message transmission between the Server and Client using Java Sockets (`ServerSocket` and `Socket`).
* **Custom Desktop GUI:** Built entirely with Java Swing and AWT, featuring a modern messenger-style interface.
* **Timestamp Integration:** Automatically appends live time stamps to sent and received messages.
* **Dynamic Layout Rendering:** Panel re-rendering and validation for smooth real-time chat history updates.

---

## 🛠️ Tech Stack

* **Language:** Java
* **UI Framework:** Java Swing, AWT
* **Networking:** `java.net.*`, `java.io.*` (DataInputStream, DataOutputStream)
* **Utilities:** SimpleDateFormat, Calendar, Borders, Listeners

---

## 📁 Project Structure

```text
Chatting-Application/
│
├── chatting/
│   └── aplication/
│       ├── Server.java     # Server-side UI & Socket Listener (Port 6001)
│       └── Client.java     # Client-side UI & Socket Connection
│
└── icons/                  # Application assets (Profile pictures, back buttons, media icons)

```


## ⚙️ Setup and Installation Instructions

### Prerequisites

* **Java Development Kit (JDK)** installed on your machine.
* Any Java-supported IDE (e.g., **IntelliJ IDEA**, **Eclipse**, or **NetBeans**).

### How to Run the Application:

1. **Clone the Repository:**

git clone [https://github.com/itszaidsidd/Chatting-Application.git](https://github.com/itszaidsidd/Chatting-Application.git)


2. **Open in IDE:**
* Import the project folder into your preferred IDE. Ensure the `chatting.aplication` package and `icons` folder are correctly configured in the classpath.


3. **Run the Server First:**
* Open **`Server.java`** and run the `main` method.
* The server will initialize a window and start listening on port `6001`.


4. **Run the Client Next:**
* Open **`Client.java`** and run its `main` method.
* The client will connect to the local server (`127.0.0.1` on port `6001`).


5. **Start Chatting:**
* Type your message in the text field and click **Send** on either the Server or Client window to see live peer-to-peer messaging in action!



---

## 👨‍💻 Author

**Mohd Zaid**

* Full Stack Developer & Educator
* GitHub: [@itszaidsidd](https://github.com/itszaidsidd)

```

```
