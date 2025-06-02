# Iran Public Transport Data

📍 **Open data repository for public transportation networks in Iran**  
🚍 Starting with **Tehran BRT** – aiming to expand to other cities and modes in the future.

---

## 📦 About the Project

This project provides open, structured, and developer-friendly data for public transportation systems across Iran.  
The dataset currently includes detailed station and line data for the **BRT (Bus Rapid Transit)** lines in **Tehran**.

---

## 🚧 Current Coverage

| City    | Mode  | Status       |
|---------|-------|--------------|
| Tehran  | BRT   | ✅ Available |

---

## 📁 Repository Structure

```
iran-public-transport/
├── .gitignore               
├── data/
│   └── tehran/
│       └── bus/
│           ├── brt/      
│           │   └── tehran_brt_stations.json     
│           └── vahed/
│               └── tehran_vahed_stations.json
├── scripts/                      
├── LICENSE
└── README.md
```

---

## 🧩 Use Cases

- Mapping & navigation apps  
- Civic and urban planning tools  
- Academic and research projects  
- Data visualization experiments

---

## 🤝 Contributing

Want to help expand the project to your city or add other transport modes? Pull requests are welcome! 


---


### 🛠 Contribution Guide

If you’d like to contribute to this project, please consider the following:

- Tehran BRT lines use numeric IDs such as `101` for **Line 1** and `103` for **Line 3**.
- You can extract accurate station data using the **Neshan app**:
  - Each station’s **latitude and longitude** is shown with high precision and is *directly copyable*.
  - The **full address** of each station is also available and *copyable* from the app.
- You may also refer to online BRT route maps to identify the correct station order.
- When contributing or updating data:
  - Use at least **6 decimal places** for coordinates.
  - Follow the JSON file format strictly (`lines.json`, `stations.json`).
  - Submit your changes via a **Pull Request**.


---

## 📜 License

This project is licensed under the **Open Database License (ODbL) v1.0**.  
You are free to share, modify, and use the database, as long as you attribute the source and keep any derivative works open under the same license.

Full license text: [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1.0/)

Attribution is appreciated if you use or share the data.  
© 2025 Mohammad Amin Amirkolaei Andy — pg.mohammadamin@gmail.com

---

## ✨ Credits

Created by **[MohammadAmin-Andy](https://github.com/MohammadAmin-Andy)**  
Special thanks to open-source contributors and city data enthusiasts.