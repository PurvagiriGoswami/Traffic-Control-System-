<h1 align="center">🚦 IoT-Based Smart Traffic Control System 🚗</h1>

<p align="center">
  A real-time, sensor-driven smart traffic control solution built using IoT to reduce congestion, enhance road safety, and improve emergency response time.
</p>

<p align="center">
  <img src="https://github.com/PurvagiriGoswami/Traffic-Control-System/assets/your-image-path/traffic-banner.gif" alt="Traffic System Banner" width="600"/>
</p>

---

## 📌 Project Overview

The **IoT Traffic Control System** is an intelligent system designed to monitor and manage vehicular traffic using sensors and microcontrollers. It dynamically adjusts traffic signals based on real-time traffic density and provides priority for emergency vehicles.

---

## 💡 Key Features

- 🟢 **Smart Traffic Light Control** — Automatically adjusts light timings based on traffic density.
- 🚑 **Emergency Vehicle Detection** — Prioritizes ambulances, fire trucks, etc., by sensing RF modules.
- 📈 **Real-time Monitoring** — Displays current traffic flow and status of signals.
- 🔧 **Low-Cost Hardware** — Uses budget-friendly components like Arduino, IR sensors, and RF modules.
- 📡 **Scalable Design** — Suitable for 4-way intersections and easily scalable to multiple junctions.

---

## 🔧 Hardware Used

| Component             | Quantity | Description                           |
|----------------------|----------|---------------------------------------|
| Arduino UNO          | 1        | Main microcontroller                  |
| IR Sensors           | 4        | Traffic density detection             |
| RF Transmitter/Receiver | 1 Pair | Emergency vehicle detection           |
| LEDs (Red, Yellow, Green) | 12  | Traffic signal lights                 |
| Breadboard & Wires   | -        | For circuit connections               |
| Power Supply         | -        | 5V regulated input                    |

---

## 🔌 Circuit Diagram

<p align="center">
  <img width="1181" height="795" alt="circuit-diagram" src="https://github.com/user-attachments/assets/fa863023-748c-4438-a086-56a281fe69ae" />
  <alt="Circuit Diagram" width="500"/>
</p>

---

## 🖥️ Working Principle

1. **Traffic Monitoring:** IR sensors detect vehicle presence and calculate traffic density.
2. **Signal Decision:** Arduino adjusts signal duration based on highest traffic flow.
3. **Emergency Override:** When an emergency RF signal is received, all other paths are stopped to give way.
4. **Loop Execution:** The system continues in a loop, constantly adapting to new traffic patterns.

---

## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/PurvagiriGoswami/Traffic-Control-System.git
   ```

2. Upload the code:
   - Open `traffic_control.ino` using Arduino IDE.
   - Select the correct COM port and board (Arduino UNO).
   - Click `Upload`.

3. Connect all hardware as shown in the circuit diagram.

---

## 👨‍💻 Author

- **Purvagiri Goswami**  
  📧 purvagirigoswami@email.com  
  🌐 [LinkedIn](https://www.linkedin.com/in/purvagirigoswami) | [GitHub](https://github.com/PurvagiriGoswami)

---

## 🏁 Future Improvements

- Integration with mobile app for live status.
- Camera-based vehicle recognition.
- Real-time data analytics dashboard.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> 💬 *Feel free to fork this project, suggest improvements, or contribute!*
