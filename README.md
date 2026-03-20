# Additive Manufacturing-Based Multi-Bioinspired Fog Collection System

> Designing a nature-inspired fog collector using 3D printing to address global water scarcity.  
> Advanced Manufacturing Research |

---

## 📌 Project Overview

10% of Earth's freshwater exists in the atmosphere as fog, a vast, untapped resource. This project develops an **artificial fog collection system** using additive manufacturing, drawing inspiration from nature's most effective water-harvesting organisms. By replicating micro- and nanoscale surface structures found in cactus spines, spider silk, rice leaves, and *Nepenthes alata* (pitcher plant), the system significantly improves droplet capture, transport, and collection efficiency.

---

## 🌿 Bioinspired Design Elements

| Biological Inspiration | Mechanism Used |
|------------------------|----------------|
| **Cactus spines** | Directional water transport via Laplace pressure gradient |
| **Spider silk** | Alternating hydrophilic/hydrophobic regions for droplet capture |
| **Rice leaves** | Micro-scale capillary action for rapid water transport |
| **Nepenthes alata** | Slippery surfaces for effortless droplet removal |

---

## 🎯 Objectives

1. Use additive manufacturing to fabricate micro- and nanoscale surface patterns inspired by natural water-harvesting structures
2. Optimize wettability, surface texture, and structural orientation to enhance condensation and droplet transport
3. Evaluate water collection rates and droplet dynamics under controlled fog chamber conditions
4. Develop a scalable manufacturing process (µ-CLIP or FDM) for real-world deployment in arid and fog-prone regions

---

## ⚙️ Design Features

The integrated design combines **5 bioinspired components:**

- **Cactus spines** - 4-spine node system with 15° and 25° lean angles and a 10° tip taper for optimal Laplace pressure-driven water transport
- **Rice leaf boomerang pattern** — 30° bottom angle channels for directional water flow
- **Spider web structure** - triangular convex-to-concave spindle knots (125 µm large, 50 µm small) for droplet capture
- **Node channel** - internal channel structure for water collection
- **C-IAPGs** (Controlled Interfacial Asymmetrical Patterned Grooves) - simplified grooves for directing water to a central reservoir

**Base dimensions (1.0 scale):** Height = 1.699 mm | Base = 3.5 mm × 3.5 mm  
**Successfully printed at 2.0 scale** with spider webs intact

---

## 🛠️ Fabrication Methods

### MicroCLIP (Micro Continuous Liquid Interface Production)
- Advanced UV photopolymerization with oxygen-inhibited "dead zone" for continuous resin renewal
- Micron-scale resolution without mechanical layer separation
- Materials tested: **PEGDA** (97.5% PEGDA + 0.5% UV absorber + 2% Irgacure 819) and **HDDA** (96.9% HDDA + 0.1% UV absorber + 3% Irgacure 819)
- **HDDA preferred** for superior structural clarity and precision in intricate biomimetic patterns

### DLP (Digital Light Processing) 3D Printing
- Layer thickness: 30 µm for smooth surfaces and accurate feature replication
- Photosensitive resin with UV curing
- **Superior scalability and structural clarity** compared to MicroCLIP for complex designs
- DLP selected as the preferred fabrication method overall

---

## 🔬 Key Physics & Mechanisms

**Condensation:** Dropwise condensation preferred - lower thermal resistance accelerates water collection. Surface wettability categories:
- Superhydrophilic: contact angle < 5°
- Hydrophilic: contact angle < 90°
- Hydrophobic: contact angle 90°–150°
- Superhydrophobic: contact angle > 150°

**Water Transport:** Driven by Laplace pressure gradient on conical surfaces, capillary action in microchannels, and gravitational forces — enabling water movement even against gravity.

---

## 📊 Results

- Preliminary results indicate a potential **up to 15% improvement** in water collection efficiency in practical applications
- DLP printing demonstrated superior replication of biomimetic patterns over MicroCLIP
- Microscopic analysis confirmed accurate reproduction of micro-scale features
- Hydrophobic coatings enhanced water transmission efficiency
- Durability testing under real-world conditions is ongoing

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Project_Report.pdf` | Full research report with methods, results, and CAD figures |
| `Project_Proposal.pdf` | Original research proposal and task schedule |
| `Literature_Review.pdf` | Review of 12 bioinspired fog collection studies with numerical data |

---

## 👥 Team

| Name |
|------|
| Garima Bhakuni |
| Shah Nipu |
| Jeet Ramesh Khut |
| Zerek Leyva |

**Supervisor:** Dr. Xiangfan Chen

---

## 🌍 Broader Impact

Water scarcity affects over 4 billion people worldwide. This fog collection system offers a scalable, energy-efficient, and geographically unrestricted alternative to desalination and groundwater extraction — particularly valuable for rural and underserved communities in arid, fog-prone regions.

---

## 📚 Selected Key References

- Liu et al. (2021) — Rapid 3D Printing of Bioinspired Hybrid Structures, *ACS Applied Materials & Interfaces*
- Li et al. (2020) — 3D-Printed Cactus-Inspired Spine Structures, *Advanced Materials Interfaces*
- Yu et al. (2022) — Fog Harvesting Devices Inspired from Single to Multiple Creatures, *Advanced Functional Materials*
- Jamil et al. (2023) — Bioinspired Slippery Asymmetric Bumps of Candle Soot Coating, *Colloids and Surfaces A*

> Full reference list available in the project report.
