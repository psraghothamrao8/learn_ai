# 🧠 Learn AI: Calculus & Neural Network Backpropagation

An interactive, visual, and mathematical guide to understanding the core calculus foundations behind Deep Learning: **Differentiation**, **Integration**, and **Neural Network Backpropagation**.

---

## 🌟 Quick Start

Open `index.html` in your web browser:
* Double-click `index.html` in your file explorer, OR
* Drag and drop `index.html` into Chrome / Edge / Firefox / Safari.

> **Zero Dependencies:** Runs 100% offline with zero installations or external build tools required.

---

## 📚 Topics & Interactive Visual Labs in `index.html`

### 1. 📈 Differentiation Lab (Speedometer)
* Interactive $\Delta x \to 0$ slider showing the secant line snap onto the tangent line.

### 2. 📊 Integration Lab (Odometer)
* Riemann sum slider ($N = 2 \dots 60$) showing coarse rectangular blocks converge into the exact area.

### 3. 📐 Formula Derivations Lab (Geometric Proofs)
* **Power Rule ($x^2 \to 2x$):** Interactive expanding square showing why the derivative is the two outer border strips ($2x$) while the tiny corner ($h^2$) vanishes.
* **Product Rule ($(uv)' = u'v + uv'$):** Interactive expanding rectangle showing the two growing edge strips.
* **Why $(e^x)' = e^x$:** Interactive height vs slope mirror showing that height and slope are identical at all points.
* **Why "+ C" (Lost Shift):** Interactive slider moving the curve vertically while proving the derivative graph remains completely frozen.
* **Fundamental Theorem of Calculus:** The telescoping domino cancellation proof of $F(b) - F(a) = \int_a^b f(x) dx$.
* **Integration by Parts:** Interactive 2D partitioned box visualizer ($\int u dv = uv - \int v du$).

### 4. ⚙️ The Chain Rule & 🧠 Backpropagation
* Full mathematical breakdown with concrete numbers ($x=2, w=0.5, y=1$).
* Live interactive DAG with real-time gradient readouts.
* Live Training Sandbox with real-time Loss curve canvas and **Auto-Train** animation.

---

## 📖 Deep Dive Notes
For full mathematical derivations, check out [NOTES.md](NOTES.md).
