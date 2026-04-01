# SRL-RAG-STEM-Learning-Study (N=102)
### 探討生成式 AI 結合自我調節學習與 RAG 技術對高中生 STEM 學習之影響
### Exploring the Impact of Generative AI with SRL and RAG on High School STEM Learning
### Instructor: [Pecu Tsai](https://github.com/pecu)

## 📝 Project Overview
This repository contains the dataset and analysis for a randomized controlled trial (RCT) investigating how AI Agents integrating **Self-Regulated Learning (SRL)** and **Retrieval-Augmented Generation (RAG)** function as cognitive and psychological scaffolds for high school students.

Situated in Taiwan—within high school STEM practical courses—this study examines the intervention's impact on **AIoT-STEM Knowledge**, **Programming Self-Efficacy (CPSES)**, **Cognitive Load (CLQ)**, and **Learning Engagement** during a 10-week "Smart Streetlight" project.

By analyzing data from **102 participants**, this study provides high statistical power to explore the psychological and performance-based effects of AI pedagogical agents in a hands-on learning environment.

## 📊 Key Findings (N=102)

### 1. Robust Empowerment in Self-Efficacy ($p < .001$)
* **Cognitive Scaffolding**: Participants using AI Agents (SRL+RAG) demonstrated a significant leap in programming self-efficacy ($F(1, 99) = 6741.41$, $p < .001$) and subject knowledge ($F(1, 99) = 776.78$, $p < .001$).
* **Effect Size**: The intervention showed a partial eta squared ($\eta_p^2$) of **.986** for self-efficacy, indicating a near-universal positive impact.
* **So What?** AI acts as a "performance cue" that simplifies complex programming logic into manageable technical execution, allowing students to overcome the "anxiety of coding".

### 2. Significant Optimization of Cognitive Load ($p < .001$)
* **Cognitive Firewall**: The **Experimental Group** exhibited a pronounced reduction in extraneous cognitive load ($t(100) = -50.57, p < .001, d = 10.01$) compared to the Control Group.
* **So What?** RAG technology serves as a "knowledge filter," protecting students from information overload and allowing them to allocate more mental resources to core problem-solving.

### 3. Emotional Buffer through Learning Engagement ($p < .001$)
* **Resilience Loop**: In the face of complex hardware debugging, the **AI Group** maintained a stable and significantly higher engagement state ($t(100) = 96.47, p < .001, d = 19.10$).
* **So What?** SRL-integrated AI initiates a cycle of social validation and immediate feedback that slowly internalizes into sustained motivation and emotional resilience.

### 4. High-Quality Performance Verification ($ICC = .992$)
* **Rating Reliability**: The **CPAM matrix** analysis revealed extremely high inter-rater reliability, confirming the objective quality of students' "Smart Streetlight" projects.
* **So What?** Practical success, validated by objective criteria, is the most effective way to transition students from passive learners into "performance-based" creators.

---

## 🔬 Methodology & Statistics
* **Participants**: $N = 102$ ($n_{exp} = 51, n_{ctrl} = 51$).
* **Analysis**: Analysis of Covariance (ANCOVA), Independent Samples T-test, and Inter-rater Reliability (ICC).
* **Reliability**: High internal consistency across all scales (Cronbach's $\alpha$: 0.75–0.90).

## 📖 中文摘要
本研究採隨機對照實驗（$N=102$），探討整合「自我調節學習 (SRL)」與「檢索增強生成 (RAG)」之 AI 代理人對高中生 STEM 學習之影響。核心發現如下：
1. **效能賦能**：AI 支架顯著拉抬程式設計自我效能感 ($p < .001$)，並建立學生的技術表現基準點。
2. **認知減壓**：RAG 技術精準支援知識檢索，顯著降低學習過程中的不必要認知負荷 ($p < .001$)。
3. **情緒緩衝**：AI 互動與 SRL 引導有效提升學生的學習投入度，進而增強面對複雜實作任務時的情緒韌性。
4. **品質保證**：經 CPAM 評分矩陣驗證，實驗組作品在功能完整性與邏輯性上展現顯著優勢 ($ICC = .992$)。

---

## 🛠️ Usage
Create a virtual environment and install dependencies:

```bash
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt

## Run

Place your Excel file in the repo root (default: `data_all.xlsx`) and run:

```bash
python analysis.py
```

## 📜 Reference
[Analysis Code](https://github.com/peculab/genai-psafety)
