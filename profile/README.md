# VerbaTechTeam
> *We create words that devices understand.*

Welcome to the **VerbaTechTeam** GitHub organization. We develop advanced software ecosystems for precision control of addressable LED lighting, building modern communication layers between users and hardware.

### 💡 Our Vision
We are developing the **Waterflow Pixel (WP)** system – a modular solution based on **REST** architecture. It enables seamless management of device visual layers, ranging from high-level business logic to direct pixel manipulation.

### 🚀 Waterflow Pixel System Architecture
Our ecosystem consists of specialized layers that communicate with each other in real-time:
  * **Waterflow Pixel Interface (WPI)** – The communication and logic layer.
      * **[wpi-core](https://github.com/VerbaTechTeam/wpi-core)** – *[In development]* The main API core written in **Java**, responsible for low-level logic and interface stability.
  * **Waterflow Pixel Unit (WPU)** – The execution and hardware layer.
      * **[waterflow-pixel-unit](https://github.com/VerbaTechTeam/waterflow-pixel-unit)** – **MicroPython**-based firmware for **Raspberry Pi Pico 2W**. The hardware runs its own **HTTP server with a REST API**, allowing for direct control of physical LED strips over the network.

### 🛠️ Tech Stack
  * **Java** – Development of the system core, business logic, and frontend layers.
  * **REST API** – The communication standard (HTTP) connecting all system modules.
  * **MicroPython** – Embedded solutions providing efficient hardware handling on the Raspberry Pi Silicon platform.

### 📅 Roadmap
In the future, we plan to expand the ecosystem with:

  * **Waterflow Pixel Controller (WPC)** – Dedicated control tools, including the **wpc-desktop** application.
  * **wpu-emulator** – A tool for testing lighting logic without the need for physical hardware.

### Getting Started
The current primary entry points for system development are the **[wpi-core](https://www.google.com/search?q=https://github.com/VerbaTechTeam/wpi-core)** and the **[waterflow-pixel-unit](https://github.com/VerbaTechTeam/waterflow-pixel-unit)**. We invite you to explore our repositories and join us in building the Waterflow Pixel standard.
