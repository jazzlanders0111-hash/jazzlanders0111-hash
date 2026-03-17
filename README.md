<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:21262D&height=220&section=header&text=Justine%20%22Jazz%22%20Gambe&fontSize=44&fontColor=f1f5f9&fontAlignY=36&desc=Data%20Analyst%20%7C%20Python%20%7C%20SQL%20%7C%20Licensed%20Professional%20Teacher&descAlignY=56&descSize=16&descColor=cbd5e1&animation=fadeIn" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=64748B&center=true&vCenter=true&width=680&lines=Turning+raw+data+into+business+decisions.;I+don%27t+just+show+you+the+numbers.+I+make+you+feel+them.;Python+%7C+SQL+%7C+PostgreSQL+%7C+End-to-End+Analytics.;Always+asking%3A+%22What+does+the+data+actually+say%3F%22" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Justine_Gambe-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/justine-gambe-615209391/)
[![Twitter](https://img.shields.io/badge/Twitter-@jazzlanders0111-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/jazzlanders0111)
[![Email](https://img.shields.io/badge/Email-jazzlanders0111%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jazzlanders0111@gmail.com)
[![Open to Work](https://img.shields.io/badge/Status-Open_to_Work-00B37E?style=for-the-badge&logo=checkmarx&logoColor=white)]()

</div>

---

## 📂 Projects

### 🛒 End-to-End E-Commerce Analytics Pipeline
> *34,500 transactions. 7,903 customers. Two years of data. Six different business problems, one dataset.*

Built this from scratch. The goal was simple: help a business understand what is actually going on with their data, from spotting the anomalies all the way to figuring out what is driving their performance and what is hurting it. Six notebooks, each attacking a different problem, because e-commerce is complex and you cannot just look at one angle and call it done. Every result I questioned, every insight I made sure connected to something the business could actually act on. Not just numbers for the sake of numbers.

| Notebook | Question | Key Finding |
|---|---|---|
| NB01 - Data Engineering | Can we trust the data? | 17 behavioural features engineered. Median order $56.82 vs mean $170, 3x gap from outlier skew. |
| NB02 - Sales & Forecasting | What drives revenue? | Electronics = 56.6% (structural risk). ARIMA MAPE 12.21%. Discounts net-positive: +75.1% LTV. |
| NB03 - Segmentation | Who are the customers? | k-means (k=4, bootstrap ARI=0.939). HVAR: 6% of customers, 24.7% of revenue. |
| NB04 - Churn Prediction | Who is about to leave? | ROC-AUC 0.498, data ceiling documented honestly. Return behaviour = 52.7% of model signal. |
| NB05 - Fraud Detection | Who is gaming the system? | $96,822 exposure. 232 High/Critical customers flagged across 3 independent methods. |
| NB06 - Cohort Retention | What is a new customer worth? | M+1 retention 15.2%. HVAR LTV $2,237 = 3.45x Loyal. One structural onboarding gap identified. |

**Stack:** Python · pandas · NumPy · scikit-learn · XGBoost · statsmodels · scipy · scikit-posthocs · Pandera · pytest · Plotly · Matplotlib · seaborn · PyArrow · PyYAML · Jupyter

[![View Project](https://img.shields.io/badge/View_Project-end--to--end--ecommerce-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jazzlanders0111-hash/end-to-end-ecommerce-analytics-project)

---

### 📊 From Lead to Seller: Olist B2B Sales Funnel Analysis
> *8,000 leads. 842 closed deals. One question: what does it actually take to convert a seller?*

Everyone uses the Olist e-commerce dataset. I went for the marketing funnel side instead because I wanted to analyze something most people skip. E-commerce is already complex enough to follow up on given how many things are moving at once, so I focused on a different angle: how does Olist actually bring sellers onto their platform, which channels are worth the investment, which seller types close fast, and who on the sales team is doing the heavy lifting. Built and analyzed entirely in PostgreSQL, from cleaning to findings.

| Section | Focus | Key Finding |
|---|---|---|
| Funnel Overview | Overall health | 10.53% overall conversion. Feb-Mar 2018 cohorts converted best at 14%+ |
| Lead Source Analysis | Channel quality | Direct traffic converts well (11.22%) and closes fast (31 days), best overall channel |
| Sales Performance | Speed and team | Average 48.5 days to close. Top SDR closed 73% more deals than 2nd place |

**Stack:** PostgreSQL · pgAdmin · CTEs · Window Functions · TEMP TABLEs · Date arithmetic · Cohort analysis

[![View Project](https://img.shields.io/badge/View_Project-Olist--B2B--Sales--Funnel-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jazzlanders0111-hash/Olist-B2B-Sales-Funnel-Analysis)

---

### 👥 HR Employee Attrition Analysis
> *1,470 employees. 16.12% left. One risk model that predicted 8 in 10 high-risk employees correctly.*

Most HR attrition projects stop at bar charts by department. I went further. Built the full analysis in PostgreSQL from overview to a validated risk scoring model that assigns each employee a score based on 6 compounding risk factors. The model cleanly separates low risk from high risk employees across every level with no noise in the pattern. Something an HR team could actually run every month and act on.

| Section | Focus | Key Finding |
|---|---|---|
| Attrition Overview | Baseline | 16.12% overall. Sales Representatives at 39.76%, nearly 4 in 10 left |
| Work Factors | Controllable conditions | Overtime employees leave at 3x the rate of non-overtime employees |
| Career and Satisfaction | Employee profiles | Early career (0-5 yrs) leave at 4x the rate of veterans (21+ yrs) |
| Risk Scoring Model | Combined prediction | Score 5 employees: 81.82% attrition. Score 0: 6.60%. 12x difference |

**Stack:** PostgreSQL · pgAdmin · CTEs · CASE WHEN scoring · Binary flag aggregation · TEMP TABLEs

[![View Project](https://img.shields.io/badge/View_Project-HR--Employee--Attrition-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jazzlanders0111-hash/HR-Employee-Attrition-Analysis)

---

## 🎓 Certifications

<div align="center">
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/bd0b1979-627e-452d-ad78-46bb9b5502a6" width="400"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ce9af939-9f60-4ec2-82be-5b2011c3987b" width="400"/>
    </td>
  </tr>
</table>
</div>
---

## 🎯 Currently

```
[▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] E-Commerce Analytics Pipeline       - Complete ✓
[▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] Olist B2B Sales Funnel Analysis     - Complete ✓
[▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] HR Employee Attrition Analysis      - Complete ✓
[▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] DataCamp Associate Data Analyst     - Certified ✓
[░░░░░░░░░░░░░░░░░░░░] Tableau Dashboard                   - Up next
[░░░░░░░░░░░░░░░░░░░░] Applying                            - Soon
```

---

## 🛠️ Tech Stack

**Languages & Querying**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Data & Analytics**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-ARIMA-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

**Machine Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge&logo=python&logoColor=white)
![scikit-posthocs](https://img.shields.io/badge/scikit--posthocs-Post_Hoc_Tests-8B5CF6?style=for-the-badge&logo=python&logoColor=white)

**Visualization**

![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C9BE8?style=for-the-badge&logo=python&logoColor=white)

**Data Engineering & Quality**

![Pandera](https://img.shields.io/badge/Pandera-Schema_Validation-00B37E?style=for-the-badge&logo=python&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-Unit_Testing-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![PyArrow](https://img.shields.io/badge/PyArrow-Parquet-E25822?style=for-the-badge&logo=apache&logoColor=white)
![PyYAML](https://img.shields.io/badge/PyYAML-Config_Driven-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

**Tools**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![pgAdmin](https://img.shields.io/badge/pgAdmin-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

> *Tableau and Power BI, next on the roadmap.*

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=jazzlanders0111-hash&theme=github-dark&hide_border=true)](https://git.io/streak-stats)

<br/>

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jazzlanders0111-hash&layout=compact&theme=github_dark&hide_border=true)

</div>

---

## 👋 About Me

```python
jazz = {
    "name"       : "Justine 'Jazz' Gambe",
    "location"   : "Philippines 🇵🇭  →  Open to Any Remote 🌐",
    "background" : "Licensed Professional Teacher (LPT), Major: English → Data Analyst",
    "focus"      : ["Business Analytics", "Customer Intelligence", "SQL"],
    "currently"  : "Building. Learning. Always asking what the data actually says.",
}
```

Before I ever knew data analytics existed as a career, I was already
doing it in my own way — breaking down systems, tracking patterns,
asking what the numbers actually meant. That instinct wasn't learned.
It was just how I processed things.

It carried into everything I touched. When I make music, I'm checking
the volume levels, the filters, the reverb, the LFO, every minor detail
of the sound until it feels right. In games, I gravitate toward the
baron lane as a tank or bruiser, not because it's flashy, but because
absorbing pressure and creating space for teammates to do their job is
the role that actually wins. I get obsessive about what I care about,
and once something clicks I go all the way in.

Analytics hit that same nerve because it combines two things I genuinely
enjoy: figuring out how a system works, and explaining what I found in
a way that actually lands with whoever is listening.

That second part is where the teaching background comes in. I'm a
Licensed Professional Teacher (LPT) in the Philippines, board certified,
Major in English. For years I translated complicated material for people
who had no prior context for it, in real time, in front of real people
who needed to actually understand, not just nod along. Most analysts
with strong technical skills never built that muscle. I started there.

I hold myself to a high standard on everything I put out. I don't move
on until the logic holds and I'm comfortable defending every decision.
That's just how I'm wired.

I keep learning every day, even the minor details. That part of me never stops.

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/justine-gambe-615209391/)
[![Email](https://img.shields.io/badge/Email-Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jazzlanders0111@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-@jazzlanders0111-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/jazzlanders0111)

*Open to remote Data Analyst roles. Any timezone flexible.*

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21262D,50:161B22,100:0D1117&height=100&section=footer" width="100%"/>
</div>
