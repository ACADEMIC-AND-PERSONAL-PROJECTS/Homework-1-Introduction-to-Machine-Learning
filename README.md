<div align="center">

<!-- HERO BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,30:16213e,70:0f3460,100:1a1a2e&height=300&section=header&text=HW1%20:%20Introduction%20to%20Machine%20Learning&fontSize=38&fontColor=ffffff&animation=twinkling" width="100%"/>

<!-- TYPING INTRO -->
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=16&pause=1000&color=00d4ff&center=true&vCenter=true&width=600&lines=Machine+Learning+Zoomcamp+2026;DataTalks+Club;Homework+1+-+Pandas+%26+NumPy+Fundamentals&center=true" alt="Typing SVG" />

</div>

<!-- FLOATING ANIMATION CSS -->
<style>
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
}
.anime-float {
  animation: float 3s ease-in-out infinite;
  display: inline-block;
}
</style>

<!-- TECH ICONS -->
<p align="center">
<img width="40" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" />
<img width="40" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" />
<img width="40" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" />
<img width="40" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" />
<img width="40" height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter" />
</p>

---

<!-- ABOUT -->
<table>
<tr>
<td width="60%">

### About

First assignment of the **Machine Learning Zoomcamp 2026** organized by **DataTalks Club**. You can enroll in the course here: [courses.datatalks.club/ml-zoomcamp-2026](https://courses.datatalks.club/ml-zoomcamp-2026/).

This project covers the fundamentals of data analysis using Pandas and NumPy on a real-world dataset: vehicle fuel efficiency.

The **car_fuel_efficiency_2026.csv** dataset contains 10,000 vehicle records with technical specifications (displacement, horsepower, weight, etc.) and their fuel efficiency in MPG.

</td>
<td width="40%" align="center">

<img src="avatar.png" width="180" alt="Avatar" style="border-radius: 20px; object-fit: cover;">

</td>
</tr>
</table>

---

<!-- STATS BAR -->
<table>
<tr>
<td align="center" width="120">

**10K**
Rows

</td>
<td align="center" width="120">

**11**
Columns

</td>
<td align="center" width="120">

**7**
Questions

</td>
<td align="center" width="120">

**3**
Fuel Types

</td>
</tr>
</table>

---

<!-- QUESTIONS -->
### Homework Questions

<table>
<tr>
<td width="50%">

#### Q1 - Q4 : Exploration

- **Q1** : Installed Pandas version (`3.0.5`)
- **Q2** : Number of records (`10,000`)
- **Q3** : Unique fuel types (`Gasoline`, `Diesel`, `Hybrid`)
- **Q4** : Columns with missing values (`horsepower` : 877, `acceleration` : 264)

</td>
<td width="50%">

#### Q5 - Q7 : Advanced Analysis

- **Q5** : Maximum fuel efficiency for Asian vehicles (`41.2` MPG)
- **Q6** : Median horsepower before/after imputation (`254` -> `252`)
- **Q7** : Matrix multiplication and matrix inversion with NumPy
  - Linear algebra: `X.T @ X`, `np.linalg.inv`, weight vector computation

</td>
</tr>
</table>

---

<!-- KEY CONCEPTS -->
### Key Concepts

<table>
<tr>
<td width="33%">

#### Pandas
- CSV reading
- `describe()`, `value_counts()`
- `fillna()` for imputation
- Conditional filtering

</td>
<td width="34%">

#### NumPy
- Arrays and matrices
- Transposition (`X.T`)
- Matrix multiplication (`@`)
- Matrix inversion (`linalg.inv`)

</td>
<td width="33%">

#### Data Cleaning
- Missing value detection
- Mode imputation
- Post-treatment verification

</td>
</tr>
</table>

---

<!-- STRUCTURE -->
### Project Structure

```
HW1/
├── car_fuel_efficiency_2026.csv   # Dataset (10K vehicles)
├── notebook.ipynb                 # Notebook with solutions
├── main.py                        # Entry point
├── pyproject.toml                 # Project configuration
└── README.md
```

---

<!-- SETUP -->
### Installation

```bash
# Clone the repo
git clone <repo-url>
cd HW1

# Install dependencies (with uv)
uv sync

# Launch the notebook
uv run jupyter notebook notebook.ipynb
```

---

<!-- DATASET PREVIEW -->
### Dataset Preview

| model_year | origin | fuel_type | drivetrain | horsepower | vehicle_weight | fuel_efficiency_mpg |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 2006 | Europe | Gasoline | Front-wheel drive | 243.0 | 3870 | 31.9 |
| 2008 | Europe | Diesel | Front-wheel drive | 272.0 | 4210 | 31.3 |
| 1996 | Asia | Gasoline | Front-wheel drive | 267.0 | 4240 | 27.5 |
| 1989 | Europe | Gasoline | Front-wheel drive | 258.0 | 4490 | 28.5 |
| 1994 | USA | Diesel | Front-wheel drive | 304.0 | 4510 | 31.0 |

---

<!-- FOOTER -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>

**Machine Learning Zoomcamp 2026 -- DataTalks Club**

</div>
