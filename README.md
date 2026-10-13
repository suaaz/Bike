# 🏍️ MotoMechanics: Bike Components Explained

> **A clean, human guide to motorcycle anatomy, how components fit together, and how iconic racing brands unlock mind-bending speed — explained simply with zero boring equations.**

Live Website: **[https://suaaz.github.io/Bike/](https://suaaz.github.io/Bike/)**

---

## 🌟 What This Site Features

1. **🧸 Explain Like I'm 5 (Child Mode)**
   - Every single component comes with a fun, relatable real-world analogy (cheetah muscles, skeletons, sticky sneakers, superhero armor) so anyone of any age can immediately grasp how it works.
2. **🧩 How It Fits Into The Whole Bike**
   - Clear architectural descriptions of where the part is physically located, what it connects to, and how it cooperates with the rest of the machine.
3. **⚡ How It Makes The Bike Faster & Better (Zero Math!)**
   - No physics calculus or dry engineering jargon. Plain-English breakdowns of acceleration, cornering traction, downforce, and braking depth.
4. **🏆 Real Racing Brand Tricks**
   - Specific engineering highlights from **Ducati**, **Yamaha**, **Kawasaki**, **BMW Motorrad**, **Honda**, **KTM**, and **Aprilia**.
5. **🎨 Illustrations & Photography**
   - 12 high-resolution vector SVGs built right into the repository for guaranteed offline/instant loading, alongside high-res photography and fallback resilience.
6. **✨ Modern Clean Design**
   - Dark/Light mode toggle.
   - Child-friendly reading mode toggle.
   - Quick Anatomy Hotspot Jump bar.
   - Real-time search by component name, brand, or feature.
   - Category filtering (Power & Drive, Chassis & Handling, Aerodynamics & Body, Wheels & Brakes, Electronics & Tech).

---

## 📁 Project Structure

```text
bike/
├── index.html            # Main responsive web application
├── style.css             # Modern automotive design system (dark & light theme)
├── data/
│   └── components.json   # Comprehensive dataset covering all 12 bike components
├── images/
│   ├── engine.svg        # 4-cylinder powerplant vector illustration
│   ├── frame.svg         # Trellis and twin-spar chassis vector
│   ├── aero.svg          # Wind-tunnel streamlines & winglets vector
│   ├── brakes.svg        # Floating rotor & Brembo monobloc caliper
│   ├── suspension.svg    # USD inverted forks & progressive monoshock
│   ├── exhaust.svg       # Hydroformed titanium 4-into-1 exhaust
│   ├── tires.svg         # Carbon rim & racing slick tread
│   ├── quickshifter.svg  # Shift rod load cell & 50ms quickshifter
│   ├── swingarm.svg      # Single-sided sculpted aluminum swingarm
│   ├── electronics.svg   # 6-axis IMU gyro & traction control brain
│   ├── ram-air.svg       # High-speed nose ram-air duct
│   └── chain.svg         # 520 race chain & final drive sprockets
└── README.md
```

---

## 🚀 Running Locally

Simply open `index.html` in any web browser:
- Double click `index.html`, or
- Run a quick local server:
  ```powershell
  python -m http.server 8000
  ```
  and visit `http://localhost:8000`.
