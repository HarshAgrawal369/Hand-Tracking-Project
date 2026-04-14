🚀 About This Project

This project is my attempt to bridge the gap between Mediapipe’s Bazel ecosystem and a CMake-based C++ workflow.

Instead of sticking to the usual Python demos, I pushed this into a high-performance C++ implementation, focusing on:

Better execution speed ⚡
More control over system-level integration 🧠
Cleaner modular structure for scaling 📦

At its core, this is a real-time hand tracking system with a lightweight GUI for interaction.

🛠️ How to Run
mkdir build
cd build
cmake ..
make
./main
🧩 What I Built
🔗 Integrated Mediapipe (Bazel) into a CMake project
✋ Developed a real-time hand tracking demo
🎛️ Added a Dear ImGUI interface for visualization and controls
⚔️ Challenges I Tackled

This project wasn’t just plug-and-play — it involved solving some pretty interesting problems:

Bazel ↔ CMake Integration
Mediapipe is designed around Bazel, so making it work smoothly with CMake required deep digging and custom adjustments.
Performance Bottlenecks in Python
Initial implementation in Python was limited (CPU-only + slower execution), which pushed me toward C++.
Rewriting in C++
Migrating logic from Python to C++ while maintaining functionality and improving speed.
Using Mediapipe as a Library
Instead of treating it as a standalone framework, I modified and structured it to behave like a reusable library.
📁 Project Structure
HandTrackingProject → Main CMake-based application
Mediapipe → Custom fork used as a submodule
🙌 Credits & References
Mediapipe — the backbone of the hand tracking system
LibMP — helpful reference for structuring the integration
🧠 Why This Matters

This project reflects how I approach engineering problems:

I don’t just use tools — I understand and adapt them
I optimize for performance and scalability
I’m comfortable working across different ecosystems (Python → C++)