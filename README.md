# 6-Servo Sweep Project

This Arduino project controls **6 servo motors** connected to digital pins **2 to 7**.

### 🔧 Features
- All six servos sweep from 0° to 180° in smooth motion.
- After the sweep, each servo holds position at 90°.
- Code is optimized using arrays and loops for clean structure.

---

## 🖼 Preview

![servo-demo](images/servo-demo.png)

> Replace `images/servo-demo.png` with the actual image path in your repository.

---

## 📋 Components Used
- Arduino Uno (or compatible board)
- 6x Servo motors
- Jumper wires
- External power supply (recommended for 6 servos)

---

## 🚀 How to Use
1. Connect each servo to pins **2 to 7**.
2. Upload the code to your Arduino.
3. The servos will sweep for ~2 seconds, then all hold at 90°.
4. Done!

---

## 💡 Notes
- Avoid using pins 0 and 1, as they are reserved for Serial communication.
- Power your servos externally to prevent brownouts or resets.

---

## 📄 License
This project is open-source under the MIT License.
