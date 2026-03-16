# 📡 WSN Energy Simulator

### Energy Consumption Estimation in Wireless Sensor Networks

An **interactive visualization tool** to estimate and compare **energy consumption in Wireless Sensor Networks (WSN)** using **clustered and non-clustered communication models**.

This project demonstrates how **clustering improves energy efficiency** in sensor networks by reducing transmission distance and aggregating data.

---

## 🚀 Features

✔ Interactive **network topology visualization**
✔ Step-by-step **packet transmission simulation**
✔ Comparison of **Clustered vs Non-Clustered communication**
✔ **Energy consumption estimation** for sensor nodes
✔ Animated **packet movement using SVG**
✔ Timeline-based simulation control

---

## 🧠 Concepts Demonstrated

* Wireless Sensor Networks (WSN)
* Sensor Node Communication
* Cluster Head Aggregation
* Energy Efficient Routing
* Transmission Energy Calculation

---

## 🖥️ Simulation Scenarios

### 1️⃣ Non-Clustered Communication

Sensor nodes send data **directly to the base station**.

⚠ High energy consumption due to long transmission distance.

```
Sensor Nodes → Base Station
```

---

### 2️⃣ Clustered Communication

Sensor nodes send data to a **Cluster Head**, which aggregates data and forwards it.

✔ Reduced transmission distance
✔ Lower energy consumption

```
Sensor Nodes → Cluster Head → Base Station
```

---

## ⚡ Energy Calculation

Transmission energy is estimated using the equation:

```
Etx = (Eelec × k) + (Eamp × k × d²)
```

Where:

* **Eelec** = Energy consumed by transmitter electronics
* **Eamp** = Energy consumed by amplifier
* **k** = Packet size (bits)
* **d** = Distance between nodes

---

## 🛠 Technologies Used

* HTML5
* CSS3
* JavaScript
* SVG Animation

---

## 📂 Project Structure

```
wsn-energy-simulator
│
├── index.html
├── README.md
├── LICENSE
```

---

## ▶ How to Run

1. Clone the repository

```
git clone https://github.com/yourusername/wsn-energy-simulator.git
```

2. Open the project folder

3. Run the simulator by opening:

```
index.html
```

in your browser.

---

## 📚 Educational Purpose

This project was developed to help students understand:

* Energy efficiency in wireless sensor networks
* Advantages of clustering techniques
* Sensor node communication models

---

## 👩‍💻 Author

**Anuja**

---

## 📄 License

This project is licensed under the **MIT License**.
