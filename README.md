# Algeria Wilayas & Communes 2026 🇩🇿

A developer-friendly and structured dataset containing all **69 wilayas (provinces)** and **1,541 communes (municipalities)** of Algeria, including **geographic coordinates (longitude/latitude)**.

---

## 📦 Dataset Overview

| Item        | Count                               |
| ----------- | ----------------------------------- |
| Wilayas     | 69                                  |
| Communes    | 1,541                               |
| Coordinates | Included                            |
| Formats     | CSV, JSON, GeoJSON, SQL, PHP, SHP*, XLSX* |
| Country     | Algeria 🇩🇿                          |

_* SHP and XLSX formats are generated automatically and available in the [Releases](../../releases) section._

---

## ✨ Features

- Complete list of **69 Algerian wilayas**
- Full coverage of **1,541 communes**
- Accurate **latitude and longitude**
- Multilingual data (**Arabic / French**)
- Available in multiple formats for easy integration
- Ready to use for **GIS, geoportals, and backend systems**

---

## 📁 Repository Structure

```
algeria-cities/
│
├── csv/       # CSV format
├── geojson/   # GeoJSON format (for GIS / maps)
├── json/      # JSON format
├── php/       # PHP arrays
├── sql/       # SQL dump / inserts
└── README.md
```

---

## 📄 Data Structure

| Column          | Type    | Description                          |
| --------------- | ------- | ------------------------------------ |
| id              | integer | Unique identifier of the commune     |
| commune_name    | string  | Commune name in Arabic               |
| commune_name_fr | string  | Commune name in French               |
| daira_name      | string  | Daira name in Arabic                 |
| daira_name_fr   | string  | Daira name in French                 |
| wilaya_code     | integer | Official wilaya numeric code         |
| wilaya_name     | string  | Wilaya name in Arabic                |
| wilaya_name_fr  | string  | Wilaya name in French                |
| code_commune    | string  | Official commune administrative code |
| Lat             | float   | Latitude                             |
| Long            | float   | Longitude                            |

---

## 🤝 Contributing

Contributions are welcome!

You can help by:

- Fixing incorrect coordinates
- Adding missing communes
- Improving data accuracy
- Enhancing formats or structure
- Improving documentation

### Steps

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request

---

## 🐞 Issues

If you find any error or want to request a feature, please open an issue:

**Issues:**
`../../issues`

Please include:

- Wilaya name
- Commune name
- Description of the issue
- Suggested correction

---

## 📜 License

MIT License

---

## ⭐ Support

If this dataset helps your project, consider giving the repository a **star** ⭐ to support future updates.
