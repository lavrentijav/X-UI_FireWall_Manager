[RU-ru](README_RU.md)
---
# **X-UI FireWall Manager**

**X-UI FireWall Manager** is a powerful firewall management tool with a user-friendly web interface. It allows users to efficiently configure, monitor, and manage network security rules via an intuitive interface, and also offers extendable functionality via plugins.

## 🚀 **Key Features:**
- **Web Interface**: An easy-to-use application for managing the firewall.
- **Plugin Support**: Easily extendable architecture with the ability to add new plugins for handling various protocols.
- **Queue and Multitasking Support**: Processes rules and events asynchronously to improve performance.
- **Centralized Database**: All rules, settings, and events are logged to a database for further analysis.
- **Security**: Supports authentication and protection against unauthorized access.

## 🛠 **Technologies:**
- **Python**: For the server-side implementation.
- **Flask**: Lightweight web framework for building the API.
- **SQLite**: Lightweight and reliable database for storing rules and events.
- **Threading**: Background task and queue processing with threads.

## 📦 **How to Install:**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourname/X-UI-FireWall.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the server:
   ```bash
   python run_server.py
   ```

4. Open a browser and go to `http://localhost:80`.

## 🧪 **Testing:**
The project has passed functional, load, and integration testing. The interface has been user-experience tested, and the system works reliably under heavy load.

## 📜 **License:**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 **Contact:**
If you have any questions, create an [issue](https://github.com/lavrentijav/X-UI-FireWall/issues).
