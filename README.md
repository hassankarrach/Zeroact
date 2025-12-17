# Zeroact

Zeroact is a custom React-like framework written from scratch with the primary goal of **learning React internals by implementing them**, instead of treating React as a black box.

This project focuses on **how React works**, not on feature completeness or production use.

---

## 🎯 Main Goal

The main goal of Zeroact is to:

- Understand React internals deeply
- Learn how rendering, reconciliation, and hooks work under the hood
- Gain confidence reading and reasoning about React source code
- Build strong mental models instead of relying on abstractions

Zeroact is actively used in **SquidPong**, my final school project, to prove that the concepts are understood and usable in a real application.

---

## ✨ Features

- ⚛️ Function components only (no class components)
- 🧵 Fiber-based architecture
- 🔁 Incremental rendering with a scheduler
- 🪝 Custom hooks implementation:
  - `useState`
  - `useEffect`
  - `useRef`
  - `useCallback`
  - `useContext`
- 🔄 Localized re-renders (subtree updates, not full root re-renders)
- 🧠 Custom reconciliation logic
- 🧩 JSX support

---

## 🧠 What’s Implemented Manually

Zeroact re-implements core React ideas, including:

- Virtual element creation
- Fiber tree creation and traversal
- Work loop and scheduling
- Hook state storage and ordering
- Effect queues and execution
- Update propagation through the fiber tree

Every part exists to be **read, debugged, and understood**.

---

## 🕹 Used In: SquidPong

Zeroact powers the UI layer of **SquidPong**, a multiplayer game built as a final school project.

Using Zeroact in a real project validates:

- The correctness of the architecture
- Hook behavior under real interaction
- State updates, effects, and rendering performance

---

## 🚫 Non-Goals

- Production readiness
- Full React API compatibility
- Performance optimizations beyond learning needs

---

## 📚 Inspiration

- React source code
- *Build Your Own React* by Paul O’Shannessy
- Redux and React architecture patterns

---

## ⚠️ Disclaimer

Zeroact is a **learning project**.

