
# NidhiLens
### Explainable Rural Development Fund Analytics

## Problem Statement
Government schemes like MGNREGA generate large amounts of public data on expenditure, employment, and development works. However, this information is scattered across complex government portals, making it difficult to analyze fund distribution, identify disparities, and compare development outcomes across regions.

## Proposed Solution
NidhiLens is a web-based analytics platform that collects and processes public MGNREGA data to analyze rural development expenditure and employment patterns at the district, block, and Gram Panchayat levels.

The platform goes beyond conventional dashboards by identifying unusual expenditure patterns and providing explainable, data-driven comparisons.

## Key Features
- **Automated Data Processing:** Collect, clean, validate, and organize government datasets.
- **Expenditure Analysis:** Visualize spending across regions, work categories, and financial years.
- **Employment Analytics:** Compare expenditure with employment generated (person-days).
- **Disparity Detection:** Identify unusual allocation patterns using statistical methods.
- **Allocation Simulator:** Explore hypothetical fund distributions under different allocation policies.
- **Interactive Dashboard:** Compare regions through charts, tables, and filters.

## Technical Approach
- **Frontend:** React.js, TypeScript, Tailwind CSS
- **Backend:** Python, FastAPI
- **Database:** SQLite / PostgreSQL
- **Data Processing:** Pandas, NumPy, Bash, Unix utilities
- **Analytics:** Statistical analysis, inequality metrics, anomaly detection
- **Visualization:** Recharts, Matplotlib
- **Development Tools:** Git, Makefile, Linux, debugging and profiling tools

## Data Sources
- MGNREGA Management Information System (MIS)
- Government expenditure and employment reports

## Expected Outcome
A reproducible, data-driven system that makes rural development spending easier to investigate, highlights potential disparities, and enables transparent exploration of alternative resource-allocation strategies.
