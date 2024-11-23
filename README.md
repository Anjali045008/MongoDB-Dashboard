# Biodiversity Insights: Conservation Status and Species Distribution in USA

## Objective
The purpose of this project is to analyze and visualize biodiversity data collected across counties in the United States. By understanding the distribution of species, their conservation statuses, and geographical biodiversity hotspots, the project aims to provide actionable insights to guide conservation efforts and highlight species that require urgent attention.

---

## Dataset Description
**Source:** New York State Department of Environmental Conservation (NYS DEC)  
**Metadata Updated:** February 28, 2022  

The dataset consolidates biodiversity information from three key databases:
1. **New York Natural Heritage Program biodiversity database:** Rare animals, rare plants, and significant natural communities, such as wetlands, forests, and streams.
2. **2nd NYS Breeding Bird Atlas Project database (2000-2005):** Birds documented as breeding during the atlas project.
3. **NYS Reptile and Amphibian Database:** Reptiles and amphibians records, primarily from the NYS Amphibian & Reptile Atlas Project (1990-1999).

### Key Features in the Dataset:
- **County**: Geographical region.
- **Category**: High-level classification (Animal, Plant, Natural Community).
- **Taxonomic Group/Subgroup**: Group and subgroup classification (e.g., Birds, Amphibians, Flowering Plants).
- **Scientific Name** and **Common Name**: Identifiers of species.
- **Year Last Documented**: Last observed year range.
- **NY Listing Status**: Legal protection status in New York.
- **Federal Listing Status**: National-level conservation status.
- **State and Global Conservation Rank**: Prioritization for conservation (e.g., S1 to S5, G1 to G5).
- **Distribution Status**: Confirmation of species presence.

---

## About the Dashboard
This interactive dashboard was built using **MongoDB Charts** to visualize the dataset effectively and answer specific research questions. The graphs were designed to reflect key aspects of biodiversity conservation and distribution across the USA.  

![Biodiversity Insights_ Conservation Status and Species Distribution in USA](https://github.com/user-attachments/assets/d6e27a79-5280-445f-b32d-ccecd5bfe247)

### Dashboard Questions and Corresponding Visualizations:
#### **General Overview**
1. **Q1: How many distinct species and samples are being monitored?**  
   - **Visualization:** Two KPI cards displaying the total number of distinct species (`1,582`) and samples studied (`20,507`).

#### **Species Categorization**
2. **Q2: How is biodiversity distributed across the main categories (Animals, Plants, Natural Communities)?**  
   - **Visualization:** Donut chart showing the proportion of species across the three categories.
3. **Q3: Which taxonomic groups dominate the dataset?**  
   - **Visualization:** Pie chart highlighting taxonomic group distribution.

#### **Conservation Efforts**
4. **Q4: How are species distributed across various conservation statuses (Protected, Threatened, Endangered)?**  
   - **Visualization:** Bar chart representing the count of species under various NY Listing and Federal Listing statuses.
5. **Q5: What is the global and state conservation rank distribution of species?**  
   - **Visualization:** Stacked bar chart analyzing State and Global Conservation Ranks.

#### **Geographical Insights**
6. **Q6: Which counties have the highest species counts and are considered biodiversity hotspots?**  
   - **Visualization:** Bar chart listing the top 10 counties with the richest biodiversity.
7. **Q7: How do conservation statuses vary across counties?**  
   - **Visualization:** Heatmap correlating species categories and conservation status across counties.

#### **Priority Areas**
8. **Q8: Which taxonomic groups or species are most endangered?**  
   - **Visualization:** Horizontal bar chart focusing on endangered taxonomic groups.
9. **Q9: What regions require immediate conservation focus based on the State and Global Conservation Ranks?**  
   - **Visualization:** Stacked column chart showing the distribution of critically imperiled species across states.

#### **Common Species**
10. **Q10: Which species are most frequently mentioned, and how does this reflect their ecological importance or monitoring focus?**  
    - **Visualization:** Word cloud highlighting frequently occurring species such as the American Robin and American Toad.

---

## Insights Drawn
1. **General Overview**  
   - There are **1,582 distinct species** and **20,507 samples** studied, reflecting the scale of biodiversity monitoring efforts.

2. **Distribution Across Categories**  
   - Animals dominate the dataset, followed by plants and natural communities, indicating a focus on fauna in biodiversity studies.

3. **Endangered and Threatened Species**  
   - Birds and flowering plants are the most endangered groups. However, amphibians and reptiles also face significant conservation challenges.

4. **Species Distribution by Conservation Status**  
   - Species listed as "Protected" or under "Special Concern" represent a large proportion, emphasizing conservation priorities for legally protected species.

5. **Geographical Biodiversity Hotspots**  
   - Counties such as **Suffolk** and **Orange** are biodiversity hotspots, with the highest species counts. These areas may require targeted conservation efforts.

6. **Conservation Rank Analysis**  
   - Species in **S1 (critically imperiled)** and **G1 (globally critically imperiled)** demand immediate conservation interventions.

7. **Common Species**  
   - Species like the American Robin and American Toad are frequently observed, possibly due to their prevalence or monitoring focus.

---

## Learnings
1. **MongoDB as a Visualization Tool**  
   - Gained hands-on experience creating visually appealing and interactive dashboards using MongoDB Charts.

2. **Biodiversity Data Analysis**  
   - Developed expertise in interpreting complex biodiversity datasets and identifying trends across categories and geographies.

3. **Conservation Insights**  
   - Enhanced understanding of conservation priorities and strategies for species protection.

4. **Data-Driven Decision-Making**  
   - Improved skills in using data to guide conservation actions and communicate findings effectively.

---

## **Managerial Insights**
- Prioritize Endangered Groups: Focus on conservation programs for birds, flowering plants, amphibians, and reptiles.
- Target Biodiversity Hotspots: Allocate resources to counties like Suffolk and Orange with high species diversity.
- Strengthen Legal Protections: Update laws and improve enforcement for "Protected" and "Special Concern" species.
- Address Critically Imperiled Species: Direct funds and research toward S1 (state) and G1 (global) ranked species.
- Balance Monitoring Efforts: Improve monitoring of underrepresented species while maintaining focus on common species.
- Foster Regional Collaboration: Coordinate conservation strategies across counties to pool resources and expertise.
- Engage Communities: Promote eco-friendly practices and incentivize local participation in conservation efforts.

## How to Use the Dashboard
1. Load the dataset into a MongoDB collection.
2. Connect MongoDB Charts to the dataset.
3. Recreate the visualizations by replicating the aggregation queries and chart designs outlined in this README.

---

## Future Improvements
1. Expand the dataset to include additional states or regions for a more comprehensive biodiversity analysis.
2. Integrate time-series data to study trends in biodiversity changes over decades.
3. Include predictive models to forecast conservation risks based on current trends.

---

Feel free to contribute to this project by providing suggestions or extending the dataset to other geographies!
