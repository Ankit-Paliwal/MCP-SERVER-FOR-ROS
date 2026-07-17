<h1 align="center">🤖 ROS & LLM Integration Bridge 🧠</h1>

<div align="center">

![ROS](https://img.shields.io/badge/ROS-Supported-brightgreen?style=for-the-badge)
![ROS2](https://img.shields.io/badge/ROS2-Supported-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=for-the-badge)

*Empowering robots with Large Language Models for seamless, bidirectional communication.*[cite: 1]
    
</div>

<p align="center">
  <img src="https://github.com/robotmcp/ros-mcp-server/blob/main/docs/images/framework.png" alt="Framework Overview"/>
</p>

---

## ✨ Why Choose This Bridge?

- 🚫 **Zero Modifications Required:** Easily integrate the `rosbridge` node without altering your existing robot source code.[cite: 1]
- 🔄 **True Bidirectional Interaction:** LLMs can both control the robot's actions and monitor its environment in real-time.[cite: 1]
- 🧠 **Comprehensive Context Awareness:** Gain full access to publish/subscribe topics, service calls, action executions, sensor readings, and parameter tuning.[cite: 1]
- 🔍 **Intelligent Discovery:** The system automatically guides the AI to understand available ROS topics, custom types, and services, ensuring flawless syntax execution.[cite: 1]
- 🌐 **Universal Client Support:** Built on the open MCP standard, making it fully compatible with Claude, Gemini, ChatGPT, Cursor, and Codex CLI.[cite: 1]
- ⚡ **Cross-Version Compatibility:** Works flawlessly across ROS 1 and ROS 2 distributions (including Jazzy and Humble).[cite: 1]

---

## 🎥 Action Showcases

<p align="center">
  <a href="https://youtu.be/Yy1loJAn9sA">
    <img src="https://github.com/robotmcp/ros-mcp-server/blob/main/docs/images/MCP%20Demos%20Slide%20-%207to12s.gif" alt="Demos" width="80%"/>
  </a>
</p>

### 🏭 1. Industrial Robot Diagnostics
Connects AI agents to production robots using only technical manuals as a reference. The AI autonomously discovers custom topic syntaxes, executes diagnostic tests (like vacuum/gripper tests), identifies anomalies, and reports the root cause.[cite: 1]

<p align="center">
  <a href="https://youtu.be/EhZNFULz9P4">
    <img src="https://github.com/robotmcp/ros-mcp-server/blob/main/docs/images/ROS%20MCP%20Gripper%20vacuum%20test.jpg" width="400" alt="Industrial Robot Test" />
  </a>
</p>

### 🗣️ 2. Natural Language Mobile Navigation
Command your mobile robots with simple phrases like, *"Grab a Coke from the fridge & go to the living room."* The AI utilizes Nav2 (SLAM) for mapping/navigation and MoveIt for manipulation, operating entirely autonomously.[cite: 1]

<p align="center">
  <img src="https://github.com/robotmcp/ros-mcp-server/blob/main/docs/images/Wilson%20thumbnail.jpg" width="400" alt="Mobile Robot Control" />
</p>  

### 🐕 3. Simulated Quadruped Control (NVIDIA Isaac Sim)
Interpret natural language commands to navigate and control quadruped robots directly within the NVIDIA Isaac Sim environment.[cite: 1]

<p align="center">
  <a href="https://www.youtube.com/watch?v=9StFx4lnvmc">
    <img src="https://img.youtube.com/vi/9StFx4lnvmc/maxresdefault.jpg" width="400" alt="Quadruped Simulation" />
  </a>
</p>  

---

## 🚀 Getting Started

To start integrating LLMs with your ROS setup, please refer to our **[Installation Guide](docs/install/installation.md)**.[cite: 1]

This tool is ready to be paired with any MCP-compatible client, including Claude Desktop, Gemini CLI, ChatGPT, and Cursor.[cite: 1]

<p align="center">
  <img src="https://github.com/robotmcp/ros-mcp-server/blob/main/docs/images/MCP_topology.png" alt="Topology Overview"/>
</p>

---

## 📚 Additional Resources & Tutorials

Explore the **[Examples Directory](examples)** to find more use cases and implementation strategies.[cite: 1]

---

## 🤝 How to Contribute

We encourage community contributions to make this project even better:
- 🐛 Bug fixes and documentation improvements
- ✨ New features (e.g., advanced permissions, action support)
- 📖 Additional tutorials and real-world examples

Please review our **[Contributing Guidelines](docs/contributing.md)** to get started.[cite: 1]

---

## 📜 Licensing

This software is released under the **[Apache License 2.0](LICENSE)**.[cite: 1]