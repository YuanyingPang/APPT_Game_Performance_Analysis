# APPT Research Project: Predicting Adherence to Gamified Cognitive Training Using Early Phase Game Performance Data: Towards a Just-In-Time Adherence Promotion Strategy

## Overview
This repository contains the code and data used for the research paper titled "Predicting Adherence to Gamified Cognitive Training Using Early Phase Game Performance Data: Towards a Just-In-Time Adherence Promotion Strategy"

## Contents
- `code/`: Directory containing the source code.
- `Data/tidy_datasets_v2/`: Directory containing sample data.


## Requirements
- Python 3.x
- Necessary packages: numpy, pandas, scikit-learn, SHAP, sklearn, statsmodels, scipy, seaborn, random

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/YuanyingPang/APPT_Game_Performance_Analysis.git
## Data Dictionary
### appt_df_game_v2_st_20210419.csv
Variable	Variable Descriptions
player_guid	Participant identifier (distinct from experiment tag identifier)
experiment_tag	Experiment tag identifier
task	The name of different cognitive training games
condition	Experimental condition
task_start_time	The start time of this session (y-m-dTh:m:s)
task_end_time	The end time of this session(y-m-dTh:m:s)
task_level	The level they played for this session
task_outcome	The outcome of this game
task_session_secs	How many seconds they played for this session
dt_weekday_val	The number of the day of the week
date_tablet_given	The date when they received the tablet
days_between_firstgame_tablet_given	The number of days from receiving the tablet to first playing the game.
days_since_first_session	The number of days from the first game to this session.
studyweek_num	The number of weeks they’ve played these games.
![image](https://github.com/YuanyingPang/APPT_Game_Performance_Analysis/assets/61800926/250b560f-84ff-4e3a-83fd-823a999e56c8)

### appt_df_v2_adherence_1
Variable	Variable Descriptions
experiment_tag	Experiment tag identifier
first_start_time	The first time they start this training (y/m/d)
last_start_time	The last time they used this training (y/m/d)
last_end_time	The last time they end this training (y/m/d)
condition	experimental condition
z_ufov3	z-score for UFOV task
z_digitsymb	z-score for digit symbol
z_ravens	z-score for Ravens
z_lettersets	z-score for Letter sets (MF V2)
z_hopkins_immediate	z-score for Hopkins memory test, immediate recall
z_hopkins_delayed	z-score for Hopkins memory test, delayed recall
z_rey_immediate	z-score for Rey’s AVLT, immediate recall
z_rey_delayed	z-score for Rey’s AVLT, delayed recall
z_iadl	z-score for IADL survey
z_indp	z-score for Brain Training Independence measure
z_nict	z-score for NICT
z_mseq	z-score for MSEQ
z_pdq	z-score for Perceived Deficits questionnaire (PDQ)
z_gse	z-score for General Self-efficacy (GSE)
z_tse	z-score for Technology Self-efficacy (TSE)
z_cpq	z-score for Computer Proficiency Questionnaire (CPQ)
z_mdpq	z-score for Mobile Device Proficiency Questionnaire (MDPQ)
z_techreadiness	z-score for tech readiness questionnaire
composite_tech_proficiency	Composite score for technology proficiency
composite_selfefficacy	Composite score for self-efficacy
composite_iadl	Composite score for perceived benefits
composite_reasoning	Composite score for objective cognition reasoning
composite_subj_cognition	Composite score for subjective cognition
composite_obj_cognition_processingspeed	Composite score for objective processing speed
composite_obj_cognition_memory_immediaterecall	Composite score for objective immediate recall
composite_obj_cognition_memory_delayedrecall	Composite score for objective delayed recall
composite_obj_cognition_memory_immediate_and_delayed_recall	Composite score for immediate and delayed recall
![image](https://github.com/YuanyingPang/APPT_Game_Performance_Analysis/assets/61800926/f76db58c-9c0a-467d-bcad-dabc7da5da85)


