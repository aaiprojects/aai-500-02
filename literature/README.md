# **Descriptive Statistical Analysis of US Accident Data**

## **Introduction**
The dataset analyzed represents a large-scale collection of accident reports from 49 states in the United States, spanning multiple years. This data, sourced from transportation departments, law enforcement, and traffic sensors, provides insights into accident severity, environmental conditions, and geographical distribution.

---

## **1. Summary Statistics**

### **1.1 Pre-Processing and Data Cleaning**
- The dataset initially contained **7,100,352 accident records**.
- Features such as **Temperature, Wind Speed, Visibility, and Humidity** were cleaned by removing records with more than **5% missing values**.
- The data was then re-evaluated, with the structure confirming **22 selected attributes** were retained.

### **1.2 Key Statistics**
- **Accident Severity:** The dataset contains severity levels ranging from **1 (least severe) to 4 (most severe)**, with a mean severity of **2.2**.
- **Distance Covered:** The average accident distance was **0.57 miles**, but extreme values extended beyond **400 miles**.
- **Weather Conditions:** The most frequent weather condition reported was **"Fair"**, while visibility ranged from **0 to 140 miles**.
- **Traffic Infrastructure:** More than **60% of accidents** occurred near **traffic signals or junctions**.

---

## **2. Geographic Distribution of Accidents**
A histogram was generated to analyze accident frequency by state. Key insights include:

- **California (CA) has the highest number of recorded accidents (1,566,965 cases), followed by Florida (835,321) and Texas (538,947).**
- States such as **South Dakota, Vermont, and Maine** reported significantly fewer accidents, each with fewer than **3,000 incidents**.
- The **top five states contribute over 50% of all accident records**, suggesting a strong correlation with urban density and road infrastructure.

![Histogram of Accidents by State](uploaded-histogram.png)

The histogram confirms a **skewed distribution**, where a handful of states dominate the accident count, likely due to **population density, urbanization, and road congestion.**

---

## **3. Statistical Observations & Key Findings**

### **3.1 Climate and Traffic Features**
- **Average temperature at accident sites:** **61.8°F**, with extremes as low as **-89°F** and as high as **207°F**.
- **Wind speed distribution:** The majority of accidents occurred in regions with **low wind speeds (~7.7 mph on average)**, reducing the likelihood of extreme weather-related crashes.
- **Most accidents occurred during the daytime**, with over **70% reported during "Day" conditions.**

### **3.2 Impact of Traffic Conditions**
- **Junction & Traffic Signals:** More than **50% of accidents** were reported near traffic intersections.
- **Speed & Visibility:** The **majority of accidents occurred in areas with visibility of 10 miles or more**, challenging the assumption that poor visibility directly leads to more accidents.

