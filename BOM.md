# P26 UAP-4030 — Bill of Materials (BOM)

## ⚠️ Heavy-Lift Reality Check

Lifting 40 kg requires a completely different setup than the ultra-light endurance drones. The original transcript parts were designed for maximum endurance (3-hour flight), not heavy lifting.

Key differences needed:
- **Thicker wiring** (16AWG or lower, not 18AWG)
- **Beefier ESCs** (high-current rated)
- **Stronger frame** (octocopter or X8 coaxial setup)
- **Higher-kV motors** or more motors total

---

## Reference Parts (Needs Revision for 40kg Payload)

### Propulsion & Power

| Component | Specification | Notes | Heavy-Lift Adjustment Needed? |
|-----------|---------------|-------|--------------------------------|
| Motors | T-Motor MN1005 V2 90KV | Massive low-kV powerhouses | ⚠️ May need higher kV or more motors |
| Propellers | T-Motor G40 (40-inch) carbon fiber | Huge 40" carbon blades | ✅ Good starting point |
| ESC | Hargrave NanoDrive 4-in-1 ESC | Compact high-current ESC | ⚠️ Need higher amp rating |
| Batteries | Tattu NMC semi-solid state LiPo | Weight-reduced | ⚠️ Higher capacity needed for 40kg |
| Power Connectors | XT60 connectors | | ⚠️ Upgrade to XT90 or Anderson PP |
| Motor Wiring | 18AWG wire | Ultra-light but low-amp | ❌ Need 14-16AWG minimum |

### Flight Controller & Electronics

| Component | Specification | Notes |
|----------------------------|----------------------------------------|-------|
| Flight Controller | TBS Lucid H7 | High-performance FC |
| GPS/Compass Unit | Matic Trident Tested GPS | Reliable positioning |
| Video Transmitter / Camera | DJI O4 Air Unit | FPV system |

### Frame & Hardware

| Component | Specification | Notes |
|----------------------------|----------------------------------------------------|-------|
| Arms | Carbon fiber tubes (1.6 m per axis) | Creates 800 mm arm length |
| Motor Mounts | 3D-printed (version 2) | Minimalist 4-bolt clamp |
| Central Hub | 3D-printed (version 2) | With integrated battery plate |
| Landing Gear | Reinforced standoffs | Protects massive props |
| Hardware | Bolts, nuts, carbon fiber standoffs | Anti-rotation fixes |

---

## TODO: Heavy-Lift Edition BOM

- [ ] Research heavy-lift motor options (≥10kg thrust per motor minimum)
- [ ] Select appropriate ESCs (≥100A continuous per motor)
- [ ] Calculate battery requirements (capacity × C-rating)
- [ ] Design frame for 8+ motors (octocopter or X8)
- [ ] Select proper gauge wiring

---

*This BOM is a starting point. Heavy-lift components must be sized for the 40kg payload.*
