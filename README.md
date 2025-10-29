🚴‍♀️ Cyclist Ride Analysis Dashboard (Power BI)

🧾 Project Overview
This Power BI dashboard analyzes **bike-sharing usage trends** for a fictional Cyclistic company.  
The goal is to compare **member** vs **casual rider** behaviors and identify patterns in **ride duration, bike type usage, time of day, and popular stations**.

This project was completed as part of the **Google Data Analytics Capstone** case study — “How do annual members and casual riders use Cyclistic bikes differently?”



 Objectives
- Compare **ride patterns** between casual and member riders.  
- Identify **peak hours** and **popular days** for bike usage.  
- Analyze **bike type preferences**.  
- Determine **top start and end stations**.  
- Provide data-driven recommendations to convert casual riders into annual members.

---

 📂 Dataset Details
- **Source:** Cyclistic (Divvy Bikes) Q1–Q4 public dataset from [Divvy Data Portal](https://divvy-tripdata.s3.amazonaws.com/index.html)  
- **Data Fields Include:**  
  - `ride_id`  
  - `rideable_type`  
  - `started_at`, `ended_at`  
  - `member_casual`  
  - `start_station_name`, `end_station_name`  
  - `ride_length`, `day_of_week`, `month`, `hour`

---

  Key Insights

 Rider Distribution
- **Members:** 57.89%  
- **Casual Riders:** 42.11%

 📊 Overall Statistics
 **Total Rides:** 5 Million  
 **Average Ride Duration:** 18.5 minutes  
 **Weekend Rides:** 1 Million  
 **Total Members:** 3 Million  
 **Total Casuals:** 2 Million  

 Ride Patterns
- Peak usage on **Saturdays and Sundays** for casuals.  
- Members maintain consistent rides across weekdays.  
- Evening rides are more common for members; casuals prefer afternoon rides.

 Bike Type Usage
| Bike Type | Members | Casual Riders |
|------------|----------|---------------|
| Classic Bikes | ✅ Most used | ✅ Popular |
| Electric Bikes | ⚡ Increasing trend | ⚡ Preferred by casuals |
| Docked Bikes | ❌ Least used | ❌ Rare usage |

 Popular Start & End Stations
- **Top Stations:**  
  - Streeter Dr & Grand Ave  
  - DuSable Lake Shore Dr & Monroe St  
  - Michigan Ave & Oak St  

These are major tourist and leisure areas — preferred by **casual riders**.



 Tools & Technologies Used
| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Dashboard development |
| **Microsoft Excel / SQL** | Data cleaning & transformation |
| **DAX** | Calculated columns and KPIs |
| **OpenStreetMap & Bing Maps** | Geo-visuals for station mapping |

---

Dashboard Features
- Dynamic filters for:
  - **Month**, **Time of Day**, **Rider Type**, **Bike Type**
- Key Metrics Cards:
  - Total Rides, Weekend Rides, Average Duration, Member & Casual Count
- Visuals:
  - Bar, Line, and Donut charts  
  - Map visual (station usage)  
  - Peak hour trends  




Files
-  **Power BI File:** [Download `.pbix`](https://drive.google.com/file/d/1M8cS63JFXJz09JadQ8XT0Zo_xb6mi2W_/view?usp=sharing)
 
- **Dashboard Report (PDF):** [View Report](reports/Cyclists_R\project.pdf)  
-**Dashboard Preview:**  
  ![Dashboard Preview](Images/cyc1.png,cyc2.png)

*(Make sure to upload these files with matching names and folders.)*

---

 Learnings
- Gained hands-on experience in **data cleaning, visualization, and storytelling**.  
- Understood **user segmentation** between casual and member riders.  
- Learned to design **interactive dashboards** and communicate data insights effectively.

---

 Recommendations
- Launch **membership promotions** targeting casual riders who frequently ride on weekends.  
- Improve **electric bike availability** at top casual stations.  
- Focus marketing on **tourist-heavy locations** (like Streeter Dr & Grand Ave).

---

👩‍💻 Author
**Insherah Majid**  
🎓 B.Tech in Information Technology  
📊 Data Analyst | 💡 Power BI | 📈 Data Storytelling  
📍 Srinagar, Kashmir  

🔗 [LinkedIn](#) (add your link)  
📧 insherahmajid@example.com (optional)



 Feedback
If you found this project useful or inspiring, feel free to ⭐ **star the repo** or connect with me on LinkedIn!  



🟢 *Created as part of my Google Data Analytics Capstone to demonstrate end-to-end Power BI analysis skills.*


## 📁 Project Structure

