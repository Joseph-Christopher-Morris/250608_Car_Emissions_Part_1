# 250608_Car_Emissions_Part_1
Visual analysis of NOx vs CO₂ emissions in Euro 6 manual Volkswagen vehicles. Highlights outliers, emission patterns, and engine behavior using Python, Pandas, and Matplotlib with accessibility-focused design.

# 🚗 Volkswagen Euro 6 Emissions Analysis

This project analyzes emissions data from **Euro 6 manual Volkswagen cars**, focusing on the relationship between **NOx (Nitrogen Oxides)** and **CO₂ (Carbon Dioxide)** emissions.

Using Python, Pandas, Matplotlib, and accessibility-focused design, the visualizations highlight both general trends and key outliers in vehicle emissions performance.

---

## 📊 Key Insights

- **General Pattern:** As CO₂ emissions increase, NOx levels tend to rise — but not linearly.
- **Outlier (High NOx):** *Caddy Life BlueMotion* shows unusually high NOx (~73 mg/km) for its CO₂ class.
- **Outlier (Low NOx):** *Volkswagen Polo* achieves the lowest NOx (~13 mg/km), indicating strong emissions optimization.
- **Clusters:** Vehicles form horizontal NOx bands, suggesting shared engine technologies.
- **CO₂ Tail-off:** Very few VW manual models emit >180 g/km CO₂, likely due to strategic downsizing or auto-only powertrains.

---

## 📦 Contents

- `notebooks/` – Jupyter Notebook with code and analysis
- `plots/` – Emissions scatterplots (standard and dark mode)
- `data/` – Cleaned emissions dataset (CSV)
- `README.md` – Project description

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas
- Matplotlib
- Colorcet (colorblind-friendly palettes)
- adjustText (for clean label placement)

---

## 📁 Data Source

- [Vehicle Certification Agency (UK)](https://www.vehicle-certification-agency.gov.uk/)

---

## 📄 License

This project is released under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions are welcome — especially for:
- Adding automatic vs manual comparisons
- Including fuel types or model years
- Applying clustering algorithms (e.g., KMeans on emissions data)

---

## 🧠 Inspiration

Originally developed to visualize real-world emissions efficiency and identify standout performers (or polluters) among VW’s Euro 6 manual cars.

