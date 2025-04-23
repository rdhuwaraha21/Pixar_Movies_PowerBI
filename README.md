
# Pixar BI Dashboard – 30 Years of Data-Driven Storytelling

> **Goal**: Build a Power BI dashboard to decode Pixar’s creative, financial, and critical success drivers over a 30-year period through interactive storytelling, advanced DAX, and performance insights.

---

##  What This Project Reveals

- **28 Films** analyzed from 1995–2024  
- Financial Performance Analysis & Correlation 
- Top-performing subgenres & creators revealed using ROI, IMDb, and RT metrics  
- Award-winning trends correlated with budget, audience scores, and revenue

---

##  Dashboard Pages

| Page | Focus |
|------|-------|
| **Executive Overview** | Key KPIs, profit trends, awards, ROI, Public Score Analysis |
| **Financial Playbook** | Budget vs. Box Office, Financial Performance, Correlation between Movie income vs Budget, Public scores, Awards won |
| **Subgenre & Talent Insights** | ROI by subgenre, creative team analysis, one-vs-multi-film creators |
| **Awards & Impact**(A Summary) | Award types, nominations, creator contribution to wins |


---

##  What I Did (BI Workflow)

1. **Framed Questions**  
   - who and which(Movies, Subgenres) are the highest Cash generators?
   - Who are Pixar’s most valuable creators?  
   - Which subgenres offer the highest overall impacts?  
   - Do public scores or awards better predict success and how correlated to financial performance?
   - finding the best way to invest in next.

2. **Data Preparation**  
   - Merged six tables (`films`, `box office`, `people`, `genres`, etc.)  
   - Modeled relationships and cleaned inconsistencies via Power Query
     
3. **Data Cleaning & Modeling (Power Query)**
   - Removed inconsistencies (e.g., budget/box office nulls).
   - Modeled relationships (1:* and many-to-many joins).
   - Used bridge tables for creators and subgenres.

3. **DAX + Calculations**  
   - 2 measure tables created 
   - ROI %, Avg Box Office, Ratings, Awards  
   - Custom visuals with tooltips, thresholds, dynamic filters

4. **Visual & UX Design**  
   - Tabs for user flow  
   - Interactive cards and filters  
   - Clean Pixar-themed layout for storytelling
   - Tooltip-driven storytelling

5. **Insights Framing**  
   - Added executive-ready interpretations  
   - Connected creator roles to film outcomes  
   - Focused on business value, not just stats

---

##  Insights That Matter

- *Toy Story* remains Pixar’s highest ROI film (1215%)  
- *Inside Out 2* is the top-grossing Pixar film ever ($1.7B)  
- Multi-role creators often correlate with lower film ROI  
- Subgenres like *Teen Drama* and *Buddy Comedy* deliver high ROI from low budgets  
- Audience ratings are stronger ROI predictors than awards
- Sequel movies generating high financial returns, but interms of Scores and Awards mixed outcome can be seen

---
