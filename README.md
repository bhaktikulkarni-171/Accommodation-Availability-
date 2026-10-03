# 🏠 Accommodation Availability Dashboard

Google Looker Studio par bana ek interactive **Real-Time Analytics Dashboard** jo multiple locations mein accommodation listings, monthly rent trends, aur overall room availability ko track aur analyze karta hai.

## 📌 Overview

Accommodation Availability Dashboard rental properties ka **centralized view** provide karta hai.

Key metrics jaise **average rent, available rooms**, aur property details jaise **water supply, parking, tenant preference** ko visual charts aur dynamic filters ke through clean layout mein represent kiya gaya hai.

## ✨ Features

* **Key Metrics KPI Summary:**  
  Overall record count **(32 rooms)**, average monthly rent **(₹9,006)**, aur available rooms count **(3)** ko KPI cards ke through display karta hai.

* **Area-Wise Rent Analysis:**  
  Multiple locations jaise **CIDCO, Garkheda, Mukundwadi, Waluj**, etc. ka average monthly rent comparison aur record count bar chart mein dikhata hai.

* **Tenant Category Breakdown:**  
  Donut chart ke through room availability ka category-wise split **(Students, Working Professionals, Families, Anyone)** analyze karta hai.

* **Detailed Room Listing Table:**  
  Individual properties ka detailed breakdown show karta hai, jisme **Area, Property Type (Room / 2 BHK), Rent, Water Availability, Parking, aur Room Counts** include hain.

* **Interactive Area Filter:**  
  Specific locality ke basis par live filtering provide karta hai, jisse users required accommodation information easily find kar sakte hain.

## 🛠️ Tech Stack

* **Google Looker Studio:** Dashboard design & data visualization
* **Google Sheets / CSV:** Data source & data management

## 📁 Project Structure

```text
accommodation-dashboard/
├── data/
│   └── accommodation_data.csv
├── assets/
│   └── dashboard_preview.png
├── docs/
│   └── setup_instructions.md
└── README.md
```

## 📊 Data Schema / Format

Dashboard dataset mein ye primary fields maintain kiye gaye hain:

`Area, Property_Type, Monthly_Rent, Water_Available, Parking_Available, Rooms_Available, Tenant_Type`

### Sample Data

```text
"CIDCO (N-1 to N-12)","Room",5000,"Yes","No",2,"Students"

"Aurangpura","Room",3500,"Yes","No",1,"Working Professionals"

"Osmanpura","2 BHK",8000,"Yes","No",3,"Family"
```

## 🚀 Usage & Access

1. **Dashboard Link:** Open the Looker Studio Report.

2. **Filter by Area:**  
   Dropdown menu mein desired locality select karein, jaise **CIDCO** ya **Mukundwadi**.

3. **Analyze Trends:**  
   Dynamic bar chart aur donut chart ke through local rent average aur tenant category split observe karein.

4. **Check Room Details:**  
   Detailed table mein water availability, parking, rent, aur available room counts check karein.

## ⚙️ How It Works

1. Dataset **Google Sheets / CSV** se Google Looker Studio ke saath connect hota hai.

2. Calculated metrics compute hote hain, jaise **average rent per area** aur **total available inventory**.

3. Visual components jaise **Bar Charts, Donut Chart, KPI Scorecards, aur Tables** connected data ko visualize karte hain.

4. **Area Filter Controls** ke through users dashboard ko interactively filter aur analyze kar sakte hain.

## 🔮 Future Improvements

* Map view widget for geographic location mapping
* Advanced price-range filters **(Budget vs Premium)**
* Direct contact button/link for property owners
* More detailed accommodation search and comparison options

## 👤 Author

**Bhakti Kulkarni**

Email: kulkarnibhakti171@gmail.com
