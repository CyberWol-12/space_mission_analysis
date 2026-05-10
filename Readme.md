#  Space Mission Analytics: A Journey Through the Stars (1957 - Present)

## 👋 Welcome to the Project!
**Hello! I am Divya, thankyou for visiting here😊. This repository contains my deep-dive analysis into the history of global space exploration, covering every recorded mission from the launch of Sputnik in 1957 to the modern era of commercial spaceflight.**

**The goal of this project is to decode the patterns of the "Final Frontier." By analyzing nearly 70 years of launch data, I aim to provide an evidence-based perspective on how technology, economics, and geopolitics have shaped our journey into space.**



##  What You Will Learn from This Project
*By exploring this notebook, you will see a complete Data Science pipeline in action. Here is what we cover:*

* **Data Engineering:** Cleaning complex date formats and handling multi-currency financial data.
* **Superpower Rivalry:** A comparative study of the USA vs. USSR/Russia launch volumes.
* **Economic Analysis:** Visualizing the shifting costs of reaching orbit over decades.
* **Success Metrics:** Analyzing mission reliability and the "learning curve" of rocket science.



## Tech Stack & Skills
* **Language:** Python 3.x
* **Data Wrangling:** `Pandas`, `NumPy`
* **Data Visualization:** `Matplotlib`, `Seaborn`, `Plotly Express` (Interactive)
* **Time-Series Analysis:** Year-on-Year (YoY) Growth & Trend Modeling
* **Geospatial Analysis:** Interactive Choropleth Mapping for global launch density



## Key Insights & Visualizations

### 1. The Global Launch Footprint (Choropleth Map)
I utilized **Plotly Express** to create an interactive map identifying "Launch Intensity" by country. While the USA and Russia lead historically, the data highlights the rapid emergence of China and India as global space powers.
![Global Launch Intensity Map](image.png)

### 2. The Cold War Space Race (USA vs USSR)
I analyzed the intense rivalry between the two superpowers up to 1991. The data shows that while the USA achieved iconic milestones like the Moon landing, the USSR maintained a massive, consistent launch volume throughout the 70s and 80s.

** (a) Distribution of Mission Costs (Price in USD Millions)**
!['Distribution of Mission Costs (Price in USD Millions)](image0.png)

** (b) Global Distribution of Space Missions (1957 - 2026)**
!['Global Distribution of Space Missions (1957 - 2026)'](image1.png)

### 3. Economic Trends (Month-on-Month Space Mission Launches (1957 - Present))
Using a time-series trend, I identified how the **Average Price of Rocket Launches** has evolved. From the expensive Shuttle era to the modern cost-reduction driven by private players like SpaceX, space is becoming more accessible.
**Month-on-Month Space Mission Launches (1957 - Present)**
!['Month-on-Month Space Mission Launches (1957 - Present)'](image2.png)

### 4. Mission Reliability & Success Rates
By calculating the **Failure Rate (%)** over time, the project reveals the technological "Learning Curve." Failure probability was nearly 40% in the late 1950s but has dropped to under 5% in the modern era.

** (a) Average Price of Rocket Launches Over Time (1957 - Present)**
!['Average Price of Rocket Launches Over Time (1957 - Present)'](image3.png)

** (b) Space Launch Trends: Top 10 Organizations Over Time**
![Space Launch Trends: Top 10 Organizations Over Time](image4.png)

### 5. Total numbrer of launches of the (USA vs USSR)
I analyzed total number of launches between usa ans usse . The data shows that while the USA achieved iconic milestones like the Moon landing, the USSR maintained a massive, consistent launch volume throughout the 70s and 80s.

** (a) Total Mission Launches: USA vs USSR (including Kazakhstan)
![Total Mission Launches: USA vs USSR (including Kazakhstan)](image5.png)


## ** Strategic Dominance & Global Leadership**

### **1. Dominant Organisations (The Era of Giants)**
Maine analyze kiya ki har saal kis organisation ne space par raaj kiya. Data se pata chala ki space history do bade hisson mein banti hui hai:
* **1970s - 1980s:** Ye poora daur **RVSN USSR** (Strategic Rocket Forces) ke naam raha. Unka launch volume itna zyada tha ki koi aur agency unke aas-paas bhi nahi thi.
* **2018 - 2020:** Yahan se dominance shift hui. **CASC (China)** aur **SpaceX** ne purani sarkari agencies ko piche chhodkar naye record banaye.
![Dominant Organisation Year-on-Year](image6.png)

### **2. Leading Countries: Total vs. Success**
Kya sabse zyada launch karne wala desh hi hamesha winner hota hai? Maine **Total Launches** aur **Successful Launches** ko compare kiya:
* **Quantity Leader:** USSR ne volume mein lead kiya (1960s-1990).
* **Quality Leader:** Jab humne sirf "Success" filter kiya, toh kayi saalon mein **USA** ne USSR ko piche chhod diya, jo ye dikhata hai ki unka success rate behtar tha.
![Leading Country Analysis](image7.png)

##  Data Cleaning & Preprocessing
To ensure an accurate analysis, several critical data cleaning steps were performed:
* **ISO Country Mapping:** Extracted country names from the "Location" field and standardized them for mapping (grouping USSR/Kazakhstan/Russia correctly).
* **Financial Formatting:** Cleaned the "Price" column by removing commas and currency symbols, converting them into numeric floats for analysis.
* **Datetime Conversion:** Converted mixed date formats to `datetime64[ns]` to extract Years and Months for time-series trend modeling.



##  Final Reflections & Conclusions
* **USSR's Volume:** Historically, the USSR (and its legacy sites in Kazakhstan) held the record for the highest frequency of launches for several decades.
* **Technological Maturity:** Rocket science has become exponentially more reliable, with failure rates hitting historic lows in the 21st century.
* **The Commercial Surge:** Post-2010 data shows a massive spike in activity, reflecting the rise of private organizations and global satellite constellations.



## AUTHOR:--
**DIVYA UPADHYAY 😊😊**
