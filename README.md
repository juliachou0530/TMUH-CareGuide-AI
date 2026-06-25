# TMUH CareGuide AI Personalized

這是一個以 Streamlit 建立的個人化衛教手冊展示系統。  
使用者可以透過 Subject ID 查詢病患資料，並查看系統產生的個人化衛教 PDF。

## Demo

Streamlit App：  
https://tmuh-careguide-ai-personalized.streamlit.app/

## 專案結構

```text
.
├─ ui_from_nlpllmclass/
│  └─ app_ui.py
├─ input/
│  ├─ patient_profiles.csv
│  └─ hosp/
│     ├─ patients.csv.gz
│     └─ admissions.csv.gz
├─ output/
│  └─ 10040025_衛教手冊.pdf
├─ requirements.txt
├─ .gitignore
└─ README.md
