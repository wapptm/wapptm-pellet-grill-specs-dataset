# wapptm-pellet-grill-specs-dataset
# Wood Pellet Grill & Smoker Specifications Dataset (2026)

[![Website](https://img.shields.io/badge/Website-GrillingYard.com-orange)](https://grillingyard.com)
[![Models Indexed](https://img.shields.io/badge/Models_Indexed-270%2B-blue)](https://grillingyard.com)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

An open, structured specification reference and utility collection for wood pellet grills and smokers. This repository provides standardized technical data samples alongside direct access to interactive sizing calculators, side-by-side comparison tools, and archived manufacturer PDF manuals.

👉 **Explore the full searchable database of 270+ models:** [GrillingYard.com](https://grillingyard.com)

---

## 📊 What's Included in the Full Portal

While this repository hosts a lightweight sample dataset (`data/sample-pellet-grills.csv`) for quick reference and data analysis, the full platform at **[GrillingYard](https://grillingyard.com)** covers:

* **271+ Indexed Pellet Grill Models:** Standardized technical specs across major brands including Traeger, Pit Boss, Camp Chef, recteq, Weber, Z Grills, Green Mountain Grills, Yoder, and Lone Star Grillz.
* **Side-by-Side Specification Matrix:** Compare primary vs. secondary cooking area (sq. in.), hopper capacity (lbs), temperature range (°F), PID controller types, auger construction, and warranty terms.
* **Manufacturer Owner's Manuals Archive:** Direct access to downloadable PDF manuals and assembly guides hosted at [manuals.grillingyard.com](https://manuals.grillingyard.com) for troubleshooting, part replacement, and maintenance.

---

## 🛠️ Free Interactive BBQ & Pellet Calculators

We maintain a suite of free, browser-based estimation tools designed to take the guesswork out of outdoor cooking and grill sizing:

* **[Pellet Consumption Calculator](https://grillingyard.com/tools/pellet-consumption-calculator/):** Estimate how many pounds of wood pellets you will burn based on ambient outdoor temperature, target cooking temperature, grill insulation, and cook duration.
* **[BBQ Party Food Calculator](https://grillingyard.com/tools/bbq-party-calculator/):** Calculate exact raw meat quantities (brisket, pulled pork, ribs, chicken, burgers) and side portions based on guest count and appetite levels.
* **[Pellet Grill Size Chart & Guide](https://grillingyard.com/tools/pellet-grill-size-chart/):** Visual capacity breakdown showing how many racks of ribs, whole chickens, or pork butts fit on standard cooking grates (400 sq. in. to 1,200+ sq. in.).
* **[Wood Pellet Flavor Pairing Guide](https://grillingyard.com/tools/wood-pellet-pairing-guide/):** Match hardwood pellet profiles (Hickory, Mesquite, Apple, Cherry, Oak, Pecan) with specific meats and smoking temperatures.

---

## 📁 Sample Data Schema (`data/sample-pellet-grills.csv`)

The sample CSV included in this repository follows a standardized schema used across our database:

| Column | Type | Description |
| :--- | :--- | :--- |
| `brand` | String | Manufacturer name (e.g., Traeger, Camp Chef, recteq) |
| `model` | String | Official model designation |
| `primary_cooking_area_sq_in` | Integer | Main grate cooking surface in square inches |
| `total_cooking_area_sq_in` | Integer | Combined main + upper rack cooking area in square inches |
| `hopper_capacity_lbs` | Integer | Maximum wood pellet hopper capacity in pounds |
| `min_temp_f` | Integer | Lowest regulated smoking temperature (°F) |
| `max_temp_f` | Integer | Maximum searing/grilling temperature (°F) |
| `pid_controller` | Boolean | Whether the unit features a PID temperature algorithm |
| `wifi_bluetooth` | String | Wireless connectivity support (WiFi, Bluetooth, None) |

---

## 🔍 Popular Comparison Guides & Reviews

* **Head-to-Head Model Comparisons:** Detailed spec-by-spec breakdowns (e.g., *Traeger Woodridge vs. Camp Chef Woodwind Pro*, *Pit Boss 1150 DX vs. recteq Deck Boss 900*, *Weber Searwood 600 vs. Traeger Ironwood*).
* **Buyer's Guides by Category:** Curated selections for best compact/portable pellet grills, high-heat searing models, heavy-duty insulated smokers, and budget-friendly units under $500 / $1,000.

Browse all guides and interactive tools at **[https://grillingyard.com](https://grillingyard.com)**.

---

## 🤝 Contributing & Data Corrections

Manufacturer specifications occasionally change across model revisions. If you spot a spec discrepancy, firmware update, or have a missing owner's manual PDF to contribute:

1. Open an **Issue** in this repository with the brand, model number, and updated detail.
2. Or leave a verified note directly on the corresponding model page at [GrillingYard.com](https://grillingyard.com).

## 📜 Citation & License

The sample dataset in this repository is licensed under **CC BY 4.0**. If you use these standardized figures in a blog post, video review, or research project, please attribute the source with a link to **[GrillingYard.com](https://grillingyard.com)**.
