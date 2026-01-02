## ✨ Features

* **Hybrid Invisibility System**
  Combines character transparency with temporary HRP offsetting to simulate invisibility while keeping the character logically stable.

* **Temporary Restore on Interaction**
  Automatically restores the character position when:

  * Attacking
  * Interacting (E / F)
  * Mouse clicks
    This ensures interactions register correctly and prevents broken states.

* **Modern Draggable UI**
  Frame-based UI with rounded corners and clean layout.
  The interface can be freely dragged without jitter or conflicts.

* **Label-Based Toggle**
  Toggle invisibility safely by:

  * Clicking the status label
  * Pressing the **H key**

* **Real-Time Depth Control Slider**
  Adjust underground offset depth dynamically (range 1–500).
  Changes apply instantly and affect the hybrid offset logic directly.

* **Smooth Input Handling**
  Slider interaction does not interfere with UI dragging.
  Global input release prevents mouse lock, chat issues, or stuck UI states.

* **Respawn Safe**
  Automatically rescans the character on respawn and resets visibility to prevent duplicated connections or broken behavior.

* **Clean Connection Management**
  All event connections are tracked and safely disconnected, allowing the script to be re-executed without memory leaks.

---

## 🎮 Controls

| Action              | Input             |
| ------------------- | ----------------- |
| Toggle Invisibility | **H key**         |
| Toggle Invisibility | Click UI Label    |
| Adjust Depth        | Drag Slider       |
| Move UI             | Drag UI Frame     |
| Auto Restore        | Attack / Interact |

---

## 🧪 Intended Use

* Educational reference for Roblox scripting
* Learning hybrid invisibility techniques
* Studying UI drag & slider input handling
* Character offset and camera behavior experiments
* Safe testing in controlled environments

---

## ❌ What This Script Does NOT Do

* Does **not** modify server-side data
* Does **not** bypass server validation
* Does **not** provide invincibility
* Does **not** include automation, farming, or exploit logic

---

## ⚠️ Disclaimer

This project is shared **for educational and testing purposes only**.
Use responsibly and only in environments where you have permission to test.

The author is **not responsible** for misuse or violations of Roblox’s Terms of Service.
