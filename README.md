# tripleten-online-pythonapp

## 📌 Project Overview
tripleten-online-pythonapp is a **data visualization and analytics project** built with **Streamlit**.  
The goal of this sprint was to:
- Provide a **clean datasource** for analysis.  
- Create **dynamic charts** to explore insights interactively.  
- Deploy the application (`app.py`) to **Render**, making it publicly accessible at:  
👉 [https://tt-project-sprint7.onrender.com/](https://tt-project-sprint7.onrender.com/)

---

## 🚀 Features
- **Interactive Charts**: Visualizations update dynamically based on user input.  
- **Datasource Integration**: ETL pipeline prepares and loads data for analysis.  
- **Web Deployment**: Hosted on Render using Streamlit for easy access.  
- **Scalable Design**: Ready to extend with additional datasets or dashboards.  

---

## 🛠️ Tech Stack
- **Python 3.9+**  
- **Streamlit** (for UI and deployment)  
- **Pandas / NumPy** (for data wrangling)  
- **Matplotlib / Plotly / Seaborn** (for charting)  
- **ETL scripts** (to prepare datasource)  

---

## 📂 Project Structure

```
TT_Project_Sprint7/
│
├── data/                # Raw and processed datasource files
├── notebooks/           # Jupyter notebooks for exploration
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TT_Project_Sprint7.git
   cd TT_Project_Sprint7
	```
	
2. Install dependencies:
   ```bash
	pip install -r requirements.txt
	```
	
3. Run the app locally:
   ```bash
	streamlit run app.py
	```
	
4. Open your browser at http://localhost:8501.


## 🌐 Deployment
The app is deployed on **Render** and can be accessed here:  
👉 [https://tt-project-sprint7.onrender.com/](https://tt-project-sprint7.onrender.com/)

Deployment steps included:
- Creating a Render service.  
- Linking the GitHub repository.  
- Configuring `requirements.txt` and `start command` (`streamlit run app.py`).  

---

## 📊 Example Use Cases
- Explore **sales trends** across time.  
- Compare **categories or regions** dynamically.  
- Generate **interactive dashboards** for stakeholders.  

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to modify.

---

## 📜 License
This project is licensed under the MIT License. See `LICENSE` for details.
