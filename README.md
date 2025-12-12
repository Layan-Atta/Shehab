# ☄️ Shahab Project: Real-Time AI model "fastest for ideal MVP"

**Leveraging Edge AI for rapid, privacy-first image detection directly in the browser.**

---

## 🚀 Why This Architecture? (The Hackathon Strategy)

In a hackathon environment, **time-to-market** and **completeness** are key. Instead of spending 48 hours reinventing the wheel with custom model architecture, we strategically utilized **Transfer Learning** via Google's Teachable Machine (based on MobileNet).

**This approach allowed us to:**
1.  **Prioritize UX & Integration:** Shift focus from hyperparameter tuning to building a functional, user-friendly web interface.
2.  **Ensure Stability:** Use a battle-tested model backbone (TensorFlow.js) that runs smoothly on consumer hardware.
3.  **Deliver a Full MVP:** Submit a fully working, deployable solution rather than a broken prototype.

> *"We don't just write code; we ship solutions. By using TF.js, we bring AI to the client-side, reducing server costs and latency."*

---

## 🛠️ Tech Stack

* **Core Engine:** TensorFlow.js (Client-side AI).
* **Model:** Teachable Machine (Transfer Learning on MobileNet).
* **Frontend:** HTML5, JavaScript (Vanilla).
* **Deployment:** GitHub Pages / Vercel (Ready to deploy).

---

## 📦 How to Run

This project is built to run effortlessly without complex Python environment setups.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/shahab-model.git](https://github.com/yourusername/shahab-model.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd shahab-model
    ```
3.  **Run Locally:**
    Simply open the `index.html` file in your browser.
    *Note: For better webcam permissions handling, it is recommended to use a local server (e.g., Live Server in VS Code).*

---

## 🧠 Model Performance

The model was trained on a custom dataset focusing on specific classes to ensure high accuracy in real-time scenarios. The inference happens entirely in the browser using WebGL acceleration.

---

## 🔮 Future Improvements

* Integration with backend APIs for data logging.
* Mobile-responsive UI enhancements.
* Expanding the dataset for edge-case handling.
