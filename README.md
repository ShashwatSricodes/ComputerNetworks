# 🛰️ Hop-by-Hop & Go-Back-N ARQ Simulator

A fully interactive **Automatic Repeat reQuest (ARQ)** simulation built using **HTML, CSS, and JavaScript**, demonstrating how reliable data transfer is achieved in computer networks through acknowledgment and retransmission.

This project visually explains both **Go-Back-N ARQ** and **Hop-by-Hop ARQ** mechanisms with dynamic animations and user control over frame loss, window size, and network hops.

---

## 🚀 Features

### 🎯 Go-Back-N ARQ
- Implements the sliding-window protocol.
- Sender transmits multiple frames (up to `N`) before requiring ACKs.
- On frame loss, **entire window** is retransmitted from the first unacknowledged frame.
- User can:
  - Set **window size (N)** and **total frames**.
  - Choose **lost frames** (e.g., `2, 5`) for simulation.
  - Observe realistic animation with retransmission and ACK reception.

### 🔁 Hop-by-Hop ARQ
- Demonstrates data transmission across **multiple intermediate hops** (like routers).
- Each hop performs **individual acknowledgment** before forwarding the frame to the next hop.
- Supports **custom frame loss at specific hops**, e.g.:
