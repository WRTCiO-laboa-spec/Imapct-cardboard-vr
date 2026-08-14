# ImpactCBVR

Welcome to ImpactCBVR. This project is designed to be efficient, private, and entirely user-focused.

## Getting Started
If you want to know how to get started or how to use the software, please check out the tutorial video. It covers everything you need to know to get up and running:

👉 **[Watch the Tutorial Video Here](https://youtu.be/6FqNF10jrx8)**

---

## Project Status: Early Stages
Please keep in mind that this is just the beginning of our journey. As an early-stage project, the software might still be a bit "unripe" and rough around the edges—but we are constantly working to improve and refine it!

## Join the Community
Have suggestions, feedback, or found a bug? We’d love to hear from you. Come join our Discord server to share your thoughts and help shape the future of this project:

👉 **[Join our Discord here](https://discord.gg/9RWSnSWNCq)**

---

## About ImpactCBVR
We believe software should be accessible and lightweight. That is why ImpactCBVR takes a different approach than traditional desktop applications.

### How it works (Technical Overview)
ImpactCBVR utilizes a **Client-Server architecture** that runs entirely on your local machine.

1. **Python Backend Engine (`/server`):** The logic is powered by a Python server. When you launch the provided script, it spins up a local HTTP server that performs the heavy lifting, data processing, and backend computations.
2. **Browser-based Interface (`/client`):** Instead of using a bulky desktop framework, we use your web browser as the user interface. The `client/` folder contains standard web assets (`index.html`, `style.css`, and `app.js`).
3. **Local API Communication:** Your web browser connects to the local Python server via internal requests. This allows the frontend (what you see) and the backend (where the data is processed) to work together seamlessly on your computer.

### Why this approach is better
* **No App Installation:** Forget about complex installation wizards or bulky software that clutters your system registry. Since this runs as a local website, you simply launch the server and open it in your browser.
* **100% Free & Open:** No paywalls, no subscriptions, and no hidden features. We believe in providing a tool that is fully functional for everyone, forever.
* **Lightweight & Fast:** By leveraging your browser as the GUI, the application remains incredibly responsive and does not consume the high system resources that traditional desktop applications require.
* **Data Privacy:** Because the processing happens locally on your machine, your workflow remains entirely within your control. No data is sent to external servers.

---

## Project Structure
* 📂 `/client`: Contains the frontend assets (HTML, CSS, and JavaScript) that provide the user interface.
* 📂 `/server`: Contains the Python backend logic and the startup script that keeps everything running.
