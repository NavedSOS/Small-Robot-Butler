# Small Robot Butler 🤖🔧

## Overview
This project is a low-cost robotic butler designed to assist engineers and hobbyists.
The robot can:

- 🚶 Move autonomously and avoid obstacles
- 🎙️ Accept voice commands (via smartphone or future voice module)
- 📦 Store and deliver tools (e.g., screwdriver, nuts, bolts) using servo-based pop-up slots
- 🧹 Provide basic vacuum cleaning support for drilling dust

**Budget target:** $200–299 for prototype.

---

## Features (Current / Planned)
- **Mobility:** 2-wheel drive with motor driver + obstacle avoidance sensors
- **Voice Control:** Initial version via smartphone app → future standalone voice module
- **Tool Management:** Servo-controlled storage slots that pop up items on command
- **Vacuum Assist:** Small DC motor fan for cleaning dust from drilling/woodwork
- **Expandable:** Easy to add more sensors, trays, or app integration

---

## Project Roadmap

### Phase 1 – Base Robot (Mobility + Obstacle Avoidance)
- [ ] ESP32 + Motor driver (TB6612) setup
- [ ] DC motors + chassis assembled
- [ ] Ultrasonic sensors for obstacle detection

### Phase 2 – Voice Control
- [ ] Connect smartphone app (Bluetooth/Wi-Fi) for voice → text → command
- [ ] Basic commands: come here, stop, move left/right

### Phase 3 – Tool Storage + Pop-up Mechanism
- [ ] Add servos for tool trays
- [ ] Voice command triggers servo to present tool

### Phase 4 – Extra Functions
- [ ] Mini vacuum for dust cleaning
- [ ] Upgrade to standalone voice module
- [ ] Mobile app with tool inventory

---

## Why This Project?
Engineers often lose time searching for tools.
This robot makes tool access hands-free and fast while also being an affordable entry into robotics.
Long-term, this concept could evolve into:

- Workshop assistant robots
- Household robotic helpers
- University-level robotics research collaboration

---

## Author
👤 Md Naved Ansari  
Aspiring Computer Science + Robotics student  
Passionate about affordable robotics & AI  
Dream: To study at NUS and create useful, real-world robots
