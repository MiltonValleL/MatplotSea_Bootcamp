<div align="center">

# Python Data Visualization Masterclass: Matplotlib & Seaborn

### Course Repository · Maven Analytics
**Advanced data visualization, storytelling & business intelligence with Matplotlib & Seaborn**

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3498db?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter_Lab-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow?style=flat-square)

</div>

---

## Course Info

| Field | Detail |
|---|---|
| **Course** | Python Data Visualization Masterclass: Matplotlib & Seaborn |
| **Instructor** | Chris Bruehl — Lead Python Instructor, Maven Analytics |
| **Platform** | Udemy |
| **Duration** | 7.5 hours · 94 lectures |
| **Projects** | 3 real-world case studies + comprehensive visualization exercises |
| **Part of** | [ml-engineering-bootcamp](https://github.com/MiltonValleL/ml-engineering-bootcamp) — Data Analysis Stack |
| **Prerequisites** | [Pandas_Bootcamp](https://github.com/MiltonValleL/Pandas_Bootcamp) OR solid understanding of NumPy/Pandas |

<br><br>

---

## Learning Objectives

By the end of this course, you'll be able to:

- ✅ Master **Matplotlib's object-oriented API** for building publication-quality visualizations
- ✅ Design and customize **20+ chart types**: line, bar, scatter, histogram, box, violin, heatmap, etc.
- ✅ Apply **advanced formatting techniques**: subplots, GridSpec, style sheets, color palettes
- ✅ Build **statistical visualizations** with Seaborn: pair plots, joint plots, facet grids
- ✅ Implement **best practices** for data storytelling, visual design, and communication
- ✅ Create **professional reports** combining multiple charts and insights
- ✅ Use **color theory** and design principles to communicate data effectively

<br><br>

---

## What This Covers

| Library | Topics |
|---|---|
| **Matplotlib** | Figure/Axes architecture · Line charts · Bar charts · Scatter plots · Histograms · Pie/Donut charts · Subplots · GridSpec · Style sheets · Advanced formatting · Color customization |
| **Seaborn** | Categorical plots · Distribution plots · Box & violin plots · Pair plots · Joint plots · Heat maps · Facet grids · Statistical estimation · Color palettes |
| **Visualization Best Practices** | Chart selection · Visual hierarchy · Color accessibility · Storytelling · Report design |

<br><br>

---

## Course Outline & Progress

### Module 1 — Intro to Python Data Visualization
- [x] Data visualization frameworks and libraries
- [x] Best practices for chart selection
- [x] Effective formatting principles
- [x] Visual storytelling fundamentals
- [x] Common visualization errors

### Module 2 — Matplotlib Fundamentals
- [x] Figure and Axes architecture (the OOP API)
- [x] Building line charts
- [x] Building bar charts
- [ ] Building scatter plots
- [ ] Building histograms
- [ ] Building pie & donut charts
- [ ] Common chart customization techniques

### 🏁 **PROJECT #1** — Analyzing the Global Coffee Market
- [ ] Load and explore coffee market data (CSV)
- [ ] Create multi-chart visualizations for volume analysis
- [ ] Visualize price trends by country and region
- [ ] Communicate key insights with Matplotlib
- [ ] **Deliverable**: Comprehensive coffee market analysis notebook

| Project Details | |
|---|---|
| **Dataset** | Global coffee trader data · Volume & price by country |
| **Skills Applied** | Data loading · Exploratory visualization · Matplotlib customization |
| **Notebook** | [`project-1-coffee-market.ipynb`](#) |
| **Status** | ⏳ Pending |

---

### Module 3 — Advanced Formatting & Customization
- [ ] Multi-chart figure layouts
- [ ] Subplots and figure-level control
- [ ] GridSpec for complex layouts
- [ ] Custom colors and color palettes
- [ ] Style sheets and rcParams
- [ ] Annotations and text customization
- [ ] Saving high-quality figures

### 🏁 **PROJECT #2** — Visualizing Global Coffee Production
- [ ] Continue coffee market analysis with advanced techniques
- [ ] Build multi-chart report with custom layouts
- [ ] Apply professional styling and branding
- [ ] Create publication-ready figures
- [ ] **Deliverable**: Polished coffee production report

| Project Details | |
|---|---|
| **Dataset** | Global coffee production data (continued from Project #1) |
| **Skills Applied** | Advanced Matplotlib · Report design · Professional styling |
| **Notebook** | [`project-2-coffee-production.ipynb`](#) |
| **Status** | ⏳ Pending |

---

### Module 4 — Data Visualization with Seaborn
- [ ] Seaborn fundamentals and integration with Matplotlib
- [ ] Categorical plots (stripplot, swarmplot, boxplot, violinplot)
- [ ] Distribution plots (histplot, kdeplot, rugplot)
- [ ] Bivariate plots (scatterplot with regression)
- [ ] Multi-plot grids (FacetGrid, PairGrid, JointGrid)
- [ ] Heat maps and correlation matrices
- [ ] Color palettes and semantic mapping
- [ ] Statistical estimation and confidence intervals

### 🏁 **PROJECT #3** — Analyzing Used Car Sales
- [ ] Load and explore automotive auction dataset
- [ ] Conduct exploratory data analysis with Seaborn
- [ ] Visualize price distributions, market trends, and vehicle attributes
- [ ] Create multi-dimensional comparisons with FacetGrids
- [ ] Build heat maps for feature correlations
- [ ] Synthesize findings into actionable insights
- [ ] **Deliverable**: Comprehensive used car market analysis

| Project Details | |
|---|---|
| **Dataset** | Automotive auction data · Vehicle specs, pricing, market conditions |
| **Skills Applied** | Seaborn · Statistical visualization · Complex multi-chart reports |
| **Notebook** | [`project-3-used-cars.ipynb`](#) |
| **Status** | ⏳ Pending |

<br><br>

---

## Key Concepts — Personal Notes

> *This section will be updated as the course progresses. These are working notes on the fundamental mental models for visualization.*

| Concept | Description | Notes |
|---|---|---|
| **Figure & Axes** | Container hierarchy in Matplotlib OOP API | Figure is the top-level container; Axes is where you plot. Always prefer `fig, ax = plt.subplots()` over `plt.plot()` |
| **Vectorization in Plotting** | Plotting large arrays efficiently | NumPy/Matplotlib integration allows pushing rendering into optimized C code |
| **Color Mapping** | Encoding data dimensions into color | Use colormap for continuous data; categorical palettes for discrete groups |
| **Statistical Layers** | Layering raw data with aggregations in Seaborn | Seaborn's `hue`, `style`, `size` parameters encode additional dimensions |
| **Faceting** | Small multiples to show relationships across groups | FacetGrid/PairGrid reveals patterns not visible in single plots |
| **Visual Hierarchy** | Directing viewer attention intentionally | Size, color saturation, position encode importance |
| **Aspect Ratio & Whitespace** | Design principles for clarity | Golden ratio (~1.618) often optimal for plots; negative space improves readability |

<br><br>

---

## Tips & Tricks Reference

| Task | Code Pattern |
|---|---|
| **Create figure with specific size & DPI** | `fig, ax = plt.subplots(figsize=(12, 6), dpi=100)` |
| **Access and modify rcParams globally** | `plt.rcParams['font.size'] = 12` or `plt.rcParams.update({'axes.labelsize': 11})` |
| **Build subplots grid** | `fig, axes = plt.subplots(2, 3, figsize=(15, 10))` |
| **Use GridSpec for complex layouts** | `gs = fig.add_gridspec(3, 3, hspace=0.3, wspace=0.3)` then `ax = fig.add_subplot(gs[0, :2])` |
| **Apply style sheets** | `plt.style.use('seaborn-v0_8-darkgrid')` (check available with `plt.style.available`) |
| **Iterate over subplot axes** | `for ax in axes.flat: ax.set_xlabel('X Label')` |
| **Save figure with transparency** | `fig.savefig('plot.png', dpi=300, bbox_inches='tight', transparent=True)` |
| **Create Seaborn heatmap** | `sns.heatmap(corr_matrix, annot=True, cmap='coolwarm', ax=ax)` |
| **Build FacetGrid** | `g = sns.FacetGrid(df, col='category', row='region', height=4)` then `g.map(sns.scatterplot, 'x', 'y')` |
| **Customize Seaborn palette** | `sns.set_palette('husl')` or pass `palette='Set2'` to plotting function |

<br><br>

---

## Prerequisites & Setup

### Required Knowledge
- ✅ Solid understanding of **NumPy arrays** (indexing, slicing, broadcasting)
- ✅ Competency with **Pandas DataFrames** (basic filtering, groupby, aggregation)
- ✅ Python basics: functions, loops, conditionals, data types
- ✅ Comfort with Jupyter Notebooks

### Recommended Prior Courses
- [Pandas_Bootcamp](https://github.com/MiltonValleL/Pandas_Bootcamp) — Essential for data manipulation skills
- NumPy fundamentals — Covered in Maven's NumPy & Pandas Masterclass

### Environment Setup
```bash
# Create conda environment
conda create -n matplotlib-seaborn python=3.11 jupyter numpy pandas matplotlib seaborn

# Activate
conda activate matplotlib-seaborn

# Install optional packages
pip install scikit-learn  # For regression examples in Seaborn
```

<br><br>

---

## Projects Summary

### Project #1: Global Coffee Market Analysis
**Role**: Data Consultant at Maven Consulting Group  
**Challenge**: Visualize volume and price trends across international markets  
**Deliverables**:
- Multi-chart exploration of coffee market data
- Volume analysis by country and region
- Price trend visualizations
- Matplotlib-driven analysis notebook

**Skills Practiced**: Data loading · Matplotlib chart types · Basic customization · Exploratory visualization

---

### Project #2: Global Coffee Production Report
**Role**: Senior Data Consultant  
**Challenge**: Create a polished, professional report on coffee production trends  
**Deliverables**:
- Advanced multi-chart layouts with GridSpec
- Custom color schemes and branding
- Publication-ready figure styling
- Comprehensive analysis report

**Skills Practiced**: Advanced Matplotlib · Report design · Professional styling · Subplot architecture

---

### Project #3: Used Car Sales Analysis
**Role**: Analytics Lead for Vehicle Acquisition Team  
**Challenge**: Identify patterns in automotive auction data to inform purchasing decisions  
**Deliverables**:
- Exploratory data analysis with Seaborn
- Price distribution and market trends
- Multi-dimensional comparisons with FacetGrids
- Correlation heat maps and insights
- Actionable recommendations based on visualization

**Skills Practiced**: Seaborn statistical plots · Complex multi-plot layouts · Color mapping · Visual storytelling

<br><br>

---

## Integration with ML Bootcamp

This course is **Part 2 of the Data Analysis Stack** in the broader ML Engineering Bootcamp:

| Module | Course | Focus | Status |
|---|---|---|---|
| **1. Foundation** | Pandas_Bootcamp | Data manipulation, aggregation, reshaping | ✅ Complete |
| **2. Visualization** | MatplotSea_Bootcamp | Data visualization, reporting, storytelling | 🔄 In Progress |
| **3. Statistics** | _TBD_ | Hypothesis testing, distributions, inference | ⏳ Planned |
| **4. ML Foundations** | _TBD_ | Scikit-Learn, model evaluation, pipelines | ⏳ Planned |

<br><br>

---

## Resources & References

### Official Documentation
- [Matplotlib Official Docs](https://matplotlib.org/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/index.html) — Hundreds of examples
- [Seaborn Official Docs](https://seaborn.pydata.org/)
- [Seaborn Gallery](https://seaborn.pydata.org/examples/index.html) — Statistical visualization examples

### Recommended Books & Resources
- **Matplotlib**
  - *Matplotlib for Python Developers* by Nicolas P. Rougier (free online)
  - *Interactive Data Visualization with Matplotlib* by Packt
  - **Chapter 9-10** of *Python for Data Analysis* by Wes McKinney

- **Seaborn & Statistical Visualization**
  - *Fundamentals of Data Visualization* by Claus O. Wilke (free online)
  - *The Visual Display of Quantitative Information* by Edward Tufte (classic)

- **Data Storytelling**
  - *Storytelling with Data* by Cole Nussbaumer Knaflic
  - *The Grammar of Graphics* by Leland Wilkinson (foundation theory)

### Online Resources
- [Real Python — Matplotlib Tutorials](https://realpython.com/python-matplotlib-guide/)
- [Real Python — Seaborn Tutorials](https://realpython.com/python-seaborn/)
- [Matplotlib — Style Sheets Reference](https://matplotlib.org/stable/gallery/style_sheets/style_sheets_reference.html)

<br><br>

---

## Connect

> **Milton R. Valle Lora**
>
> Senior Electrical Engineer → ML Engineer in transition
>
> Cochabamba, Bolivia

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miltonvallelora/)
[![GitHub](https://img.shields.io/badge/GitHub-MiltonValleL-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MiltonValleL)
[![ML_Bootcamp](https://img.shields.io/badge/ML_Bootcamp-Foundation-6e40c9?style=flat-square&logo=github&logoColor=white)](https://github.com/MiltonValleL/ml-engineering-bootcamp)

---

<div align="center">
<sub>Part of the ML Engineering Bootcamp · Data Analysis Stack · Updated as modules are completed</sub>
</div>
