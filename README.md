# 🧠 Learn AI: Calculus & Neural Network Backpropagation

An interactive, visual, and mathematical guide to understanding the core calculus foundations behind Deep Learning: **Differentiation**, **Integration**, and **Neural Network Backpropagation**.

---

## 🌟 Quick Start

Open `index.html` in your web browser:
* Double-click `index.html` in your file explorer, OR
* Drag and drop `index.html` into Chrome / Edge / Firefox / Safari.

> **Zero Dependencies:** Runs 100% offline with zero installations or external build tools required.

---

## 📚 Topics Covered

### 1. 📈 Differentiation (The "Speedometer")
* **Intuition:** Measuring the instantaneous sensitivity: *"If I nudge input $x$ by a tiny amount $\Delta x$, how much does output $y$ react?"*
* **From Average to Instant:** Watching the secant line snap onto the tangent line as $\Delta x \to 0$.
* **Why Neural Nets Care:** It tells us whether turning a weight knob up or down reduces error.

### 2. 📊 Integration (The "Odometer")
* **Intuition:** Accumulating infinitely many paper-thin slices into a whole.
* **Riemann Sums:** Slicing irregular curves into rectangular strips: $\sum f(x_i) \Delta x \to \int f(x) dx$.
* **Fundamental Theorem of Calculus:** Proving why Differentiation and Integration are exact inverses of each other ($\int \frac{df}{dx} dx = f(x)$).

### 3. ⚙️ The Chain Rule (The Gearbox)
* **Intuition:** Connecting mechanical gears: if gear A turns B by $3\times$, and B turns C by $4\times$, gear A turns C by $3 \times 4 = 12\times$.
* **Math:** $\frac{dC}{dA} = \frac{dC}{dB} \times \frac{dB}{dA}$.

### 4. 🧠 Backpropagation with Real Numbers
* **Step-by-step arithmetic** for a single-neuron network with Sigmoid activation and Mean Squared Error.
* Computing local gradients:
  $$\frac{\partial L}{\partial w} = \frac{\partial L}{\partial a} \cdot \frac{\partial a}{\partial z} \cdot \frac{\partial z}{\partial w}$$
* Updating parameters via **Gradient Descent**:
  $$w_{\text{new}} = w_{\text{old}} - \eta \cdot \frac{\partial L}{\partial w}$$

---

## 🎮 Interactive Features in `index.html`

1. **Differentiation Visualizer:** Interactive slider to change $x$ and shrink $\Delta x$, showing the secant triangle collapse into the tangent line.
2. **Integration Visualizer:** Interactive slider for slice count $N$ showing coarse rectangular blocks converge into the exact analytical area.
3. **Directed Acyclic Graph (DAG):** Interactive single neuron computational graph with live gradient readouts.
4. **Live Training Sandbox:** Interactive canvas plotting the real-time Loss curve across epochs as you step or auto-train.

---

## 📖 Deep Dive Notes

For a complete, comprehensive mathematical reference and derivation notes, check out [NOTES.md](NOTES.md).
