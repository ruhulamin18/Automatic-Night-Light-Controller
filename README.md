# 🌙 Automatic Night Light Controller

A simple, low-cost, and energy-efficient electronic system that automatically turns on an LED in the dark and turns it off in the presence of light. This project uses basic components like a 7400 NAND gate IC and an LDR (Light Dependent Resistor), making it ideal for students, hobbyists, and beginners in digital logic design.

---

## 📘 Project Overview

The Automatic Night Light Controller demonstrates how digital logic gates and analog sensors can work together to solve real-world problems. The system senses ambient light using an LDR and controls an LED through a NAND gate circuit. It is designed without any microcontroller, emphasizing the use of basic electronics and logic gate principles.

---

## 🎯 Objectives

- Design and implement a night light system using NAND logic gates and an LDR.
- Demonstrate the practical use of logic gates in automation.
- Provide an energy-efficient solution using minimal hardware.
- Offer a beginner-friendly electronics project for learning digital logic design.

---

## 🧰 Components Used

| Component           | Description                  |
|---------------------|------------------------------|
| 7400 IC             | Quad 2-input NAND gate       |
| LDR                 | Light Dependent Resistor     |
| Resistors           | For voltage divider network  |
| LED                 | Light output indicator       |
| Breadboard          | For circuit assembly         |
| Jumper Wires        | For connections              |
| DC Power Supply     | 5V–9V battery or adapter     |

---

## ⚙️ How It Works

- The LDR and a resistor form a voltage divider that senses light intensity.
- The output voltage is fed into a NAND gate circuit using a 7400 IC.
- When the ambient light level drops below a threshold (i.e., darkness), the NAND gate logic turns on the LED.
- When the environment is bright, the LED remains off.

---

## 📈 Performance

- **Reliable switching**: The LED accurately turns on in dark conditions and off in bright light.
- **No false triggering**: The logic circuit ensures consistent operation.
- **Limitation**: The light sensitivity is fixed in this version (no variable threshold).

---

## 💡 Applications

- Automatic outdoor or indoor lighting.
- Night lights for bedrooms or hallways.
- Educational demonstration of digital logic.
- Low-cost solutions for energy conservation.

---

## 🔧 Future Enhancements

- Add a **potentiometer** to adjust light sensitivity manually.
- Use a **transistor or relay** to drive higher-power loads (e.g., bulbs or fans).
- Incorporate a **solar panel** and rechargeable battery for off-grid use.
- Add **additional indicators** like buzzers or dual LEDs for multi-functional alerts.

---

## 🌍 Social and Environmental Impact

- **Improves safety** with automatic lighting at night.
- **Reduces energy waste** by turning lights off in daylight.
- **Supports sustainability** through efficient design and potential solar power integration.
- Promotes awareness of **ethical and responsible electronics design**.

---

## 🧑‍🤝‍🧑 Team Members & Contributions

| Name                  | ID           | Contribution                                             |
|-----------------------|--------------|----------------------------------------------------------|
| Redwan Ahmed Rafi     | 232-15-374   | Project coordination, circuit design, documentation      |
| Md. Ruhul Amin        | 232-15-727   | Hardware implementation, testing, calibration            |
| Md. Mahfujur Rahman   | 232-15-324   | Component collection, circuit building support           |
| Mst. Nafiza Nazneen   | 232-15-545   | Report formatting, circuit arrangement assistance        |
| Zeehan Mahmud         | 232-15-831   | Application ideas, demonstration support                 |

---

## 🏫 Academic Information

- **Course:** CSE224 – Digital Logic Design Lab  
- **Department:** Computer Science & Engineering (CSE)  
- **University:** Daffodil International University, Bangladesh  
- **Supervisor:** Zannatul Mawa Koli, Lecturer  
- **Submission Date:** April 16, 2025  

---

## 📚 References

1. Floyd, T. L. (2014). *Digital Fundamentals* (11th ed.). Pearson.  
2. Horowitz, P., & Hill, W. (2015). *The Art of Electronics* (3rd ed.). Cambridge University Press.  
3. Scherz, P., & Monk, S. (2016). *Practical Electronics for Inventors* (4th ed.). McGraw-Hill.  
4. IEEE Std 1888 – *IEEE Guide for Sustainable Energy Use* (2020).  
5. Gershenfeld, N. (2000). *The Physics of Information Technology*. Cambridge University Press.  

---

## 📄 License

This project is shared for educational and academic purposes. Feel free to use, adapt, or extend it for personal or non-commercial use. Please give credit to the original team.

