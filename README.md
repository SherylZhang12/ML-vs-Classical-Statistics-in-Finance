# ML-vs-Classical-Statistics-in-Finance

## 📌 Project Overview
This repository is a structured knowledge base comparing **Machine Learning (ML)** and **Classical Statistical** methods across multiple financial modeling tasks.  

For each **task**, we:
1. Define the problem and objectives
2. Document **Classical Baselines** and **ML Approaches**
3. Compare methods side-by-side for the same problem
4. Review relevant literature
5. Write a final **Decision Memo** with conclusions and recommendations

---

## 🗂 Repository Structure
Task Library/
│
├── Asset Pricing/
│   ├── Asset Pricing comparison/            # Main ML vs Classical comparison for Asset Pricing
│   │   ├── 00_overview.md                    # Scope, background, and objectives
│   │   ├── 01_evaluation-metrics.md          # Evaluation criteria and metrics
│   │   ├── 02_classical-baselines/           # Classical approaches for each sub-problem
│   │   │   ├── portfolio-optimization.md
│   │   │   ├── Representation & Pricing.md
│   │   │   ├── Risk-measures-var-es.md
│   │   │   ├── Risk-premium.md
│   │   │   └── Time-Series Forecasting.md
│   │   ├── 03_ml-approaches/                 # ML approaches for each sub-problem
│   │   │   ├── Portfolio-optimization.md
│   │   │   ├── repr-and-pricing.md
│   │   │   ├── risk-measures-var-es.md
│   │   │   ├── Risk-premium.md
│   │   │   └── time-series.md
│   │   ├── 04_classic-vs-ml_comparison.md    # Cross-method comparison per problem
│   │   └── 05_decision-memo.md               # Final recommendations for Asset Pricing
│   │
│   └── literature-review/                    # Related literature notes & summaries
│
├── Risk VaR/                                 # Same folder structure as Asset Pricing
├── Time-Series Forecasting/                  # Same folder structure as Asset Pricing
├── Unsupervised, Factor Discovery/           # Same folder structure as Asset Pricing
└── Volatility Modeling/                      # Same folder structure as Asset Pricing

---

## 📑 File Format for Method Analysis
Each `.md` file inside `02_classical-baselines` and `03_ml-approaches` follows this structure:

Problem & Objective

Briefly describe the problem and its role in finance.

Baselines

List the baseline models/approaches.

Strengths

List of advantages.

Limitations

List of drawbacks or challenges.

---
## 🔄 Workflow
1. **Literature Review (First Step)**  
   - Search and collect all relevant literature for the current task  
   - Document each paper in the `literature-review` folder with:
     - Title, authors, year
     - Problem addressed
     - Method summary
     - Results summary
     - Strengths & weaknesses
   - Ensure coverage of both **Classical** and **ML** approaches

2. **Per-Problem Documentation**  
   - Classify methods by specific problem under the task (e.g., Risk Premium, Portfolio Optimization)  
   - For each problem, write in the corresponding `.md` file under:
     - `02_classical-baselines` (for Classical approaches)  
     - `03_ml-approaches` (for ML approaches)  
   - Follow the template:
     ```
     ## Problem & Objective
     ## Baselines
     ## Strengths
     ## Limitations
     ```

3. **Comparison**  
   - Summarize findings for each problem in `04_classic-vs-ml_comparison.md`  
   - Highlight similarities, differences, advantages, limitations, and applicable scenarios

4. **Decision Memo (Final Step)**  
   - After all problems for the task are documented and compared, write
   - `00_overviwe.md`, `01_evaluation-metrics.md`,`05_decision-memo.md`  
   - Provide:
     - Overall conclusions for the task
     - Recommended approaches
     - Future research opportunities
    
---

## 📚 Literature Review Guidelines
Each literature note should include:
- **Paper Title, Authors, Year**
- **Problem addressed**
- **Method summary**
- **Results summary**
- **ML vs Classical**
- **Strengths & Weaknesses** in the context of the task


