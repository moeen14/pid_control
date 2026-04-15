# PID Control Interactive Demo

🌐 **Live Demo:**  
https://pid-control.moeen14-aiub.workers.dev/

---

This is a simplified interactive web-based PID controller simulation designed for educational use in control systems courses.

Unlike the greenhouse version, this demo focuses on core PID behavior without external disturbances, making it ideal for understanding fundamental tuning concepts.

---

## 🔧 Features

- Tune PID parameters:
  - Kp (Proportional)
  - Ki (Integral)
  - Kd (Derivative)
- Step-changing setpoint (3 segments over time)
- Real-time system response visualization
- Performance metrics:
  - IAE (Integral of Absolute Error)
  - Overshoot Penalty
  - Control Effort
  - Total Cost (J)
  - Score

---

## 🚀 How to Use

### Online (Recommended)
Open:
👉 https://pid-control.moeen14-aiub.workers.dev/

---

### Run Locally
Download the repository and open:


index.html


in any modern web browser.

---

## 🎯 Objective

Tune PID gains to minimize:


J = 1.0 × IAE + 2.0 × Overshoot + 0.2 × Control Effort


Score is computed as:


Score = 10000 / (1 + J)


- Lower J → better control  
- Higher Score → better performance  

---

## 🎓 Educational Use

This tool is designed for:

- PID tuning practice
- Control systems coursework
- Classroom demonstrations
- Quick experimentation without disturbances

---

## 📦 Project Structure


├── index.html # Full simulator (frontend + logic)
├── README.md
└── LICENSE


---

## 👨‍💻 Author

**Moeen Ul Islam**  
Mississippi State University  

---

## 🌐 Deployment

Hosted using **Cloudflare Workers**

---

## 📌 Citation

If you use this tool for teaching, research, or coursework, please cite:

Moeen Ul Islam, "PID Control Interactive Demo", 2026.  
Available at: https://pid-control.moeen14-aiub.workers.dev/

---

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

---

## ⭐ Support

If you find this useful:

- ⭐ Star the repository  
- 🍴 Fork it  
- 📢 Share with others  

