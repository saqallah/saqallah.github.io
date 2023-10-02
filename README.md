# Data Analyst

#### Technical Skills: Python, Java, MATLAB, Microsoft Power BI, Dashboards, Problem Solving, Data Cleansing, Data Visualization (DataViz), Data Analysis, SQL, Tableau, R, KPI, SAP, QGIS, Statistics, Excel, Spreadsheets, Data Warehousing, Statistical Data Analysis, Git

## Education							       		
- M.S., Digital Engineering	| Bauhaus-Universität Weimar, Germany (_October 2020 - August 2023_)	 			        		
- B.S., Civil Engineering | Jordan University of Science and Technology, Jordan (_October 2013 - March 2018_)

## Work Experience
**Thesis Researcher (Data Analyst) @ Webis.de, Germany (_January 2023 - August 2023_)**
*Conducted research on real-world events' impact on Wikipedia, utilizing data analysis and Python programming.*
- Analyzed Wikipedia editing trends during events.
- Created informative data visualizations.
- Proficient in Python, Pandas, NumPy, and Matplotlib.
- Ensured data accuracy through rigorous cleaning.
- Developed a novel methodology for event impact assessment.
- Derived meaningful conclusions, enhancing understanding of online community behavior during events.


**Civil Structural Engineer @ Creative Urban Designs, Jordan (_April 2018 - September 2020_)**
## Projects
### Thesis: Quantifying the Effects of Real-World Events on Wikipedia
[Link](https://webis.de/for-students/completed-theses.html#saqallah_2023)

**Objective:**
Quantitatively analyze the influence of real-world events on English Wikipedia editing behavior.

**Subobjectives:**
- Investigating Event Impact on overall editing activity: Understand how real-world events affect overall editing activity on English Wikipedia.
- Exploring Editing Behavior Patterns: Identify patterns in editing behavior around real-world events, including editing bursts, revisions, and changes in focus.
- Variations Across Event Categories: Explore if event types (e.g., armed conflicts, elections, disasters) lead to distinct editing behavior patterns.
- Wikipedia's Response via Article Protection: Analyze how Wikipedia protects articles related to events to prevent vandalism and misinformation.

**Development of Analysis Methodology:**

### Step 1: Acquiring Editing Data
Relevant editing data obtained from the reproduction of Kiesel et al.'s [2017] paper "Spatio-temporal Analysis of Reverted Wikipedia Edits," using authors' open-source software.

### Step 2: Determining Time Frames around Events

#### a) 12th month period:
- Graphical interpretation.
- Includes 6 months before and 6 months after events.
- Assess distinct patterns beyond immediate pre/post-event periods.

#### b) 8-week period:
- Analyze 4 weeks before and 4 weeks after the event (Quantifying editing behavior changes before and after the event).
- Comparing to identify shifts and trends.

### Step 3: Operationalizing Key Metrics

a) Total Edits: Measure of overall editing activity and engagement.

b) Reverted Edits: Indication of conflicts or disagreements among editors.

c) Vandalism-Reverted Edits: Highlighting malicious attempts to manipulate content.

d) Top Articles and their Contributions: Identifying topics that attract the most attention.

e) Number of Protected Articles: Understanding Wikipedia editors' response to events.

### Step 4: Selecting Relevant Wikipedia Articles

Definition of Relevant Article:
- A "relevant article" pertains directly to the event under study.
- Provides specific information, details, and perspectives about the event.

Four Approaches Explored:

a) Main Article: Limits editing behavior comparison before and after the event (Main articles often lack pre-event editing data).

b) Main Category: Many unrelated articles; missing relevant ones.

c) Directly Related Category: Inconsistent, lacks direct connections.

d) **Title-Based Search (chosen)**: Iterative process for relevance, ensures high relevance to the event, and consistent.

### Step 5: Quantifying Effects with Statistics

- Conducting comparative analysis of key metrics before and after events.
- Computing relative change and supporting it using Cohen's d.
- Examining top 10 contributing articles and their protection status.
- Comparing events within categories and across different categories.

### Results:

#### Quantification of Event Impact:

1) **Overall Editing Activity:**
   - Increased editing activity is observed after events across all categories.
   - The Russian invasion of Ukraine event had the highest total edits due to its global impact.
   - The Tigray War exhibited the highest effect size (d = 2.42***), indicating sustained activity.
![Overall editing](/assets/img/project_1/overall_editing.png)


2) **Reverted Edits:**
   - The Tigray War had the highest effect size on reverted edits (d = 1.45***).
   - The Russian invasion of Ukraine and the Israel-Palestine crisis had lower reverting rates.


3) **Vandalism-Reverted Edits:**
   - The Same-sex marriage legislation event had the highest effect size for vandalism-reverted edits (d = 0.70*).
   - Controversial topics likely contributed to the increased vandalism-reverted edits.
![reverted edits](/assets/img/project_1/reverted_edits.png)


4) **Article Protection and Vandalism:**
   - Armed conflict-related articles are more protected due to their vulnerability.
   - The Same-sex marriage article is still prone to vandalism despite protection.
![article protection](/assets/img/project_1/article_protection.png)

5) **Editorial Biases:**
   - United States events received higher editing activity compared to similar events from other countries.
![edit bais](/assets/img/project_1/edit_bais.png)

6) **Registered Users Contributions:**
   - The majority of edits during events were made by registered users.
   - The lowest registered edits were 71% during the 94th Academy Awards event.
   - The highest registered edits were 96% during the 2021 Israel-Palestine crisis event.
   - Registered users demonstrate consistent dedication to updating and enhancing Wikipedia's content.

These results provide a comprehensive understanding of how real-world events impact English Wikipedia editing behavior, including increased activity, differences in reverted edits, vandalism-reverted edits, article protection, editorial biases, and the contributions of registered users during various events.
