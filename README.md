# Data Analytics capstone
# 🎬 Movie Magic — Data-Driven Insights for Indie Filmmakers

> *Empowering independent filmmakers with actionable, evidence-based insights to maximize ROI and pitch projects confidently to investors.*

---

## **Table of Contents**
1. [Project Overview](#project-overview)  
2. [Problem Statement](#problem-statement)  
3. [Objectives](#objectives)  
4. [Data Sources & Tools](#data-sources--tools)  
5. [Methodology](#methodology)  
6. [Key Insights](#key-insights)  
7. [Business & Investor Value](#business--investor-value)  
8. [Dashboard & Deployment](#dashboard--deployment)  
9. [Limitations](#limitations)  
10. [Future Improvements](#future-improvements)  
11. [Links & Resources](#links--resources)  

---

## **Project Overview**
Independent filmmakers often struggle to convince investors due to limited evidence of potential financial performance. **Movie Magic** provides a data-driven framework for evaluating which genres, directors, and actors consistently deliver strong returns, while identifying underserved market opportunities for creative differentiation.

---

## **Problem Statement**
Independent filmmakers face a critical challenge: **they need to pitch projects to investors with clear evidence of potential success**, but lack access to structured, quantitative insights that show which genres, directors, and actors are most likely to deliver high returns.  

Read more: https://brendachebyte.hashnode.dev/movie-magic-a-data-driven-approach-to-maximizing-roi-for-indie-filmmakers?showSharer=true

Specifically, investors want answers to questions like:  
- Which **movie genres** yield the highest ROI?  
- Which genres are **critically acclaimed** versus financially successful?  
- Which **directors** consistently produce profitable movies (≥3 films)?  
- Which **actors** repeatedly contribute to high ROI projects (≥6 films)?  
- Which genres are **oversaturated**, and which are underserved yet lucrative (saturation vs opportunity)?  
- How do **yearly trends** in genres affect potential investment decisions?

Without these insights, indie filmmakers risk pitching projects that are **financially unviable**, overproduced, or misaligned with audience demand. This project addresses these gaps by providing a **data-backed framework** to inform investor pitches and creative decisions.

---

## **Objectives**
- Identify high-ROI and high-rated movie genres from 2018–2025  
- Highlight directors and actors with repeatable commercial success  
- Map genre saturation vs opportunity to guide strategic project selection  
- Produce a clean, analytics-ready dataset  
- Develop an interactive dashboard for investor presentations  

---

## **Data Sources & Tools**
**Data Sources:**  
- TMDB API — movie metadata, cast, crew, budgets, revenue, ratings  

**Tools & Libraries:**  
- **Python & Pandas** — data cleaning, transformation, feature engineering  
- **Tableau Public** — interactive dashboards  
- **Google Cloud Storage / BigQuery** — data storage & querying  
- **Markdown / GitHub** — documentation & project hosting  

---

## **Methodology**
1. **Data Collection:** Extracted movie information via TMDB API, restricted to films released 2018–2025.  
2. **Data Cleaning:** Removed duplicates, normalized multi-value columns (genres, cast, directors), and filtered for complete financial data.  
3. **Feature Engineering:** Calculated ROI, derived director/actor experience counts, and created saturation vs opportunity metrics.  
4. **Analysis:**  
   - Ranked genres by ROI and audience rating  
   - Identified directors and actors meeting consistency thresholds  
   - Tracked yearly trends per genre  
   - Created quadrant analysis for genre saturation vs opportunity  
5. **Visualization:** Published an interactive Tableau dashboard to highlight findings.  

---

## **Key Insights**
### **Genres**
- **Animation** — highest ROI (7.49x) and top audience rating (7.49/10)  
- **Horror** — high ROI, low production cost, underserved market  
- **Mystery** — underproduced but profitable niche  

### **Directors**
- **M. Night Shyamalan** — 4.72x ROI, high-concept low-budget thrillers  
- **David Leitch, Guy Ritchie** — mid-tier ROI, consistent film output  

### **Actors**
- **Florence Pugh, Chris Pratt, Anya Taylor-Joy** — high ROI actors with 6+ films  
- **Dwayne Johnson, Ryan Reynolds** — strong global appeal and marketability  

### **Saturation vs Opportunity**
- **High Opportunity + Low Saturation:** Mystery, Music — excellent for indie differentiation  
- **High Opportunity + High Saturation:** Animation, Horror — popular but competitive  
- **Low Opportunity + Low ROI:** War, niche genres to avoid for indie pitching  

---

## **Business & Investor Value**
- **Filmmakers:** Data-backed decision-making for genre, director, and casting selection  
- **Investors:** Reduced financial risk and improved project screening  
- **Studios:** Strategic planning using repeatable ROI insights  
- **Community Impact:** Encourages underserved genres and supports creative diversity  

---

## **Dashboard & Deployment**
**Interactive Tableau Dashboard:**  
[Movie Magic Dashboard](https://public.tableau.com/app/profile/brenda.chebet/viz/MovieMagic_17632735735980/Dashboard1?publish=yes)  

**Deployment Options:**  
- Lovable Portfolio Website  
- GitHub Pages  
- Firebase Hosting  

---

## **Limitations**
- Marketing spend not included in ROI calculations  
- Only TMDB data used; streaming platforms revenue excluded  
- Profit vs ROI not inflation-adjusted  

---

## **Future Improvements**
- Predictive ML model for new movie ROI  
- Budget feasibility and scenario simulation by genre  
- Annotate director/actor charts with genres and notable films  
- Regional market performance analysis  

---

## **Links & Resources**
- **Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/brenda.chebet/viz/MovieMagic_17632735735980/Dashboard1?publish=yes)  
- **Portfolio:** [Lovable.dev Project Page](https://lovable.dev/)  
- **GitHub Repository:** *Add your repo link here*  
- **Dataset:** `movies_final_for_tableau.csv`  
