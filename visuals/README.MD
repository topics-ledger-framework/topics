# 🧪 TLF Interactive Visualizations

Welcome to the `visuals` directory. This folder contains a collection of single-page HTML/JavaScript simulations created during the foundational research phase of the **Topics Ledger Framework (TLF)**. 

## 📌 About These Simulations

Before the high-dimensional tensor computations were deployed on Google Cloud, these lightweight interactive modules were built to visually conceptualize the core mathematics of the framework. They serve as interactive sandboxes bridging abstract theory and visual intuition. 

By experimenting with these pages, you can explore the mechanics of:
* The transition from the Void (pure superposition) to Consensus (a stable Topic).
* Directed Acyclic Graph (DAG) structural logic and causal ledger generation.
* The mathematical constraints of the Grover Rewind.
* The interplay between thermodynamic friction ($\epsilon_k$) and Shannon Entropy ($H_{DM}$).

## 🚀 How to Run

Because these are standalone, single-page web applications, there are no complex dependencies, builds, or backend servers required.

1. **Clone or Download:** Pull this repository to your local machine.
2. **Open in Browser:** Simply double-click any `.html` file in this folder to run it in a modern web browser (Chrome, Firefox, Safari, Edge).
3. **Interact:** Use the on-screen controls to adjust the mathematical parameters and watch the topology react in real-time.

> **Note for Developers:** If you are running into CORS (Cross-Origin Resource Sharing) issues due to local JavaScript module imports, you can spin up a quick local server from this directory using your terminal: `python -m http.server 8000`

## 📂 Simulation Index

*(Update this list with your actual HTML filenames)*

* 📄 **`example_simulation_1.html`** - *Description of what this visualizes (e.g., Interactive causal web formation).*
* 📄 **`example_simulation_2.html`** - *Description of what this visualizes (e.g., 2D cross-section of the probability ocean).*
* 📄 **`example_simulation_3.html`** - *Description of what this visualizes (e.g., Real-time entropy cooling and coupling drag).*

## 🛠️ Technology

These visualizers are built strictly using standard web technologies (HTML5 Canvas and Vanilla JavaScript). This architectural choice was made to ensure the underlying math remains completely transparent and accessible to anyone reviewing the TLF theory, without burying the logic behind heavy UI frameworks.
