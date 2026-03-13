# 🏠 Housing Trends — Interactive Data Visualization Web App

A Flask-based web application that visualizes housing sales trends and prices using an interactive dashboard built from real housing data (21,609 records).

## 📸 Preview

> **HOME** → Hero landing page  
> **ABOUT** → Project overview & stats  
> **DASHBOARD** → Full interactive house price analysis  
> **STORY** → 5-scene data storyboard  

---

## 🚀 Quick Start

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/housing-trends.git
cd housing-trends
```

### 2. Install dependencies
```bash
pip install flask
```

### 3. Run the app
```bash
python temp.py
```

### 4. Open in browser
```
http://localhost:5000
```

---

## 📁 Project Structure

```
housing-trends/
│
├── temp.py                          # Flask application (main entry point)
│
├── templates/
│   └── index.html                   # Main website (HOME, ABOUT, DASHBOARD, STORY)
│
├── static/
│   └── housing_dashboard.html       # Embedded interactive dashboard
│
└── README.md                        # This file
```

---

## 📊 Features

| Feature | Description |
|---|---|
| 🏠 Landing Page | Hero section with housing background, stats |
| 📊 Dashboard | Full interactive dashboard embedded via iframe |
| 🎛 Filters | Top N filters (Top 25, Top 10, Top 5) |
| 📖 Storyboard | 5 narrative scenes with insights |
| 🗃 Data Explorer | Searchable, sortable table |
| 🌐 Web Integration | Responsive design, embeddable |

---

## 📈 Visualizations (6 Total)

1. **Count of Transformed Housing Data** — KPI Card (21,609)
2. **Average Sale Prices** — KPI Card ($511,619)
3. **Area of House from Basement (Sqft)** — KPI Card (38.6M)
4. **Total Sales by Years Since Renovation** — Color-coded Bar Chart
5. **Distribution of House Age by Renovation Status** — Pie Chart
6. **House Age Distribution by Bathrooms, Bedrooms & Floors** — Grouped Bar Chart

---

## 🔢 Dataset

- **File:** `Transformed_Housing_Data2.csv`
- **Records:** 21,609 rows
- **Fields:** 35 columns
- **Source:** Washington State residential housing data

---

## 🛠 Tech Stack

- **Backend:** Python Flask
- **Frontend:** HTML5, CSS3, JavaScript
- **Charts:** Chart.js 4.4.1
- **Fonts:** Google Fonts (Bebas Neue, DM Sans)

---

## 🌐 Web Integration

To embed this dashboard in any website:

```html
<iframe 
  src="http://localhost:5000" 
  width="100%" 
  height="900px" 
  frameborder="0">
</iframe>
```

---

## 👤 Author

**Manas Goel**  
Data Visualization Project — Tableau / Web Dashboard Integration

---

## 📝 License

MIT License — free to use and modify.
