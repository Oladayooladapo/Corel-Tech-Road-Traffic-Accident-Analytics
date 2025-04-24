
# Road Traffic Accidents Analysis – UK (Corel Tech Project)

## Project Overview
This project explores patterns in UK road traffic accidents to uncover critical risk factors and provide data-driven recommendations for safety improvements. Leveraging Excel, Power BI, and statistical techniques, I conducted a full-cycle analysis—from data cleaning to dashboard insights—aimed at supporting road safety policy decisions and resource allocation.

---

## Objectives
- Analyze historical traffic accident data to identify key trends and correlations.
- Support decision-makers in crafting **targeted road safety strategies**.
- Help prioritize infrastructure investments based on evidence.
- Highlight accident hotspots, peak periods, and high-risk conditions.

---

## Data Summary
**Source:** UK open road traffic accident datasets  
**Format:** Raw and semi-structured Excel files  
**Key Variables:**
- Date, Time, Location (Urban/Rural)
- Accident Severity
- Vehicles Involved & Casualties
- Weather, Lighting, Road Surface Conditions
- Junction Type, Speed Limits, Police Region

---

## 🛠️ Data Cleaning & Preparation
Performed in Excel:
- Reformatted date/time fields and standardized number columns.
- Cleaned categorical values (e.g., replacing nulls in junction controls with modal values).
- Ensured consistency for visualizations and statistical reliability.

---

## Descriptive Statistics & Key Insights

### **Casualties per Accident**
- **Avg. casualties:** 1.36 (most accidents cause only 1 injury)
- **Outliers:** Few but severe incidents with up to 48 casualties
- **Skewed distribution** toward lower severity, but heavy-tailed

###  **Vehicle Involvement**
- **Avg. vehicles:** 1.83  
- **Most common:** Two-vehicle collisions  
- **Rare:** Multi-vehicle (up to 32) pile-ups

###  **Speed Limits**
- **Avg. speed zone:** 39 mph  
- **Majority:** 65% of accidents happen in **30 mph urban zones**  
- Speed limits do **not strongly predict** vehicle count or casualty severity

---

## Correlation Observations
| Variable Pair | Correlation | Interpretation |
|---------------|-------------|----------------|
| Vehicles vs. Casualties | 0.23 | More vehicles, slightly more casualties |
| Speed Limit vs. Casualties | 0.14 | High-speed areas → marginally higher casualty risk |
| Speed Limit vs. Vehicles | 0.08 | No meaningful relationship |

---

## Dashboard Highlights (Power BI)
- **High-risk cities:** Birmingham, Leeds, Manchester, Bradford, Westminster, Sheffield, Liverpool
- **Peak accident hours:** 9 AM & 5 PM (rush hours)
- **Conditions:** 79% of crashes in **clear weather**, 68% on **dry roads**
- **Severity:** 86% are **“Slight”**, 13% “Serious”, 1% fatal
- **Vehicle Type:** 77% of accidents involve cars
- **Junctions:** Most crashes occur at **“Give Way”** or uncontrolled intersections

---

## Recommendations

### **Infrastructure Improvements**
- Replace high-risk junctions with roundabouts/traffic lights
- Enhance road signage, lighting, and surface maintenance
- Use smart traffic signals and install more speed cameras

### **Policy & Regulation**
- Stricter penalties for speeding, distracted, and drunk driving
- Mandatory telematics in commercial vehicles
- Expand public transport to reduce peak-hour accidents

### **Awareness Campaigns**
- Train new and elderly drivers
- Road safety education in schools
- Community feedback forums on local road safety

---

## Project Takeaways
This project reflects my capabilities in:
- Transforming complex datasets into strategic insights
- Applying descriptive and inferential statistics
- Visual storytelling using Power BI
- Bridging business and technical perspectives through analysis

---

## What's Included in the Repository
- Cleaned datasets (XLSX)
- Pivot tables (XLSX)
- Excel dashboard (PNG)
- Full analysis scripts


# Define the file path
file_path = Path("/mnt/data/road_traffic_accident_analysis_oladayo.md")

# Write the markdown content to the file
file_path.write_text(markdown_content)

file_path.name  # Return the file name for download link in next message

