@echo off
chcp 65001
set PYTHONIOENCODING=utf-8
cd /d "%~dp0"

:: 建立報告檔標題
echo # 作業一自動批改報告 > report1.md
echo 產生時間: %date% %time% >> report1.md
echo. >> report1.md

:: --- 開始循環測試學生 ---

echo 正在處理: D110611065...
echo ## 學生: D110611065 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110611065\hw1-110611065.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110611065\hw1-110611065.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110611065\hw1-110611065.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110611065\hw1-110611065.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D110701033...
echo ## 學生: D110701033 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110701033\hw1-110701033.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110701033\hw1-110701033.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110701033\hw1-110701033.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110701033\hw1-110701033.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D110705053...
echo ## 學生: D110705053 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110705053\hw1-110705053.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110705053\hw1-110705053.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110705053\hw1-110705053.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D110705053\hw1-110705053.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D111651021...
echo ## 學生: D111651021 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111651021\hw1-111651021.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111651021\hw1-111651021.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111651021\hw1-111651021.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111651021\hw1-111651021.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D111652025...
echo ## 學生: D111652025 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111652025\hw1-111652025.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111652025\hw1-111652025.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111652025\hw1-111652025.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111652025\hw1-111652025.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D111654029...
echo ## 學生: D111654029 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111654029\hw1-111654029.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111654029\hw1-111654029.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111654029\hw1-111654029.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111654029\hw1-111654029.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D111700007...
echo ## 學生: D111700007 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111700007\hw1-111700007.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111700007\hw1-111700007.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111700007\hw1-111700007.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111700007\hw1-111700007.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D111701035...
echo ## 學生: D111701035 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111701035\hw1-111701035.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111701035\hw1-111701035.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111701035\hw1-111701035.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111701035\hw1-111701035.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D111704011...
echo ## 學生: D111704011 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111704011\hw1-111704011.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111704011\hw1-111704011.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111704011\hw1-111704011.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D111704011\hw1-111704011.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112350014...
echo ## 學生: D112350014 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350014\hw1-112350014.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350014\hw1-112350014.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350014\hw1-112350014.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350014\hw1-112350014.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112350020...
echo ## 學生: D112350020 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350020\hw1-112350020.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350020\hw1-112350020.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350020\hw1-112350020.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350020\hw1-112350020.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112350045...
echo ## 學生: D112350045 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350045\hw1-112350045.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350045\hw1-112350045.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350045\hw1-112350045.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350045\hw1-112350045.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112350079...
echo ## 學生: D112350079 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350079\HW1-112350079.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350079\HW1-112350079.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350079\HW1-112350079.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112350079\HW1-112350079.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112611024...
echo ## 學生: D112611024 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611024\hw1-112611024.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611024\hw1-112611024.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611024\hw1-112611024.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611024\hw1-112611024.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112611049...
echo ## 學生: D112611049 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611049\hw1-112611049.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611049\hw1-112611049.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611049\hw1-112611049.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112611049\hw1-112611049.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112613017...
echo ## 學生: D112613017 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613017\hw1-112613017.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613017\hw1-112613017.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613017\hw1-112613017.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613017\hw1-112613017.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112613037...
echo ## 學生: D112613037 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613037\hw1-112613037.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613037\hw1-112613037.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613037\hw1-112613037.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112613037\hw1-112613037.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112705016...
echo ## 學生: D112705016 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705016\hw1-112705016.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705016\hw1-112705016.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705016\hw1-112705016.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705016\hw1-112705016.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D112705076...
echo ## 學生: D112705076 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705076\hw1-112705076.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705076\hw1-112705076.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705076\hw1-112705076.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D112705076\hw1-112705076.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113350058...
echo ## 學生: D113350058 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113350058\hw1-113350058.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113350058\hw1-113350058.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113350058\hw1-113350058.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113350058\hw1-113350058.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113450014...
echo ## 學生: D113450014 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113450014\hw1_113450014_py.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113450014\hw1_113450014_py.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113450014\hw1_113450014_py.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113450014\hw1_113450014_py.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113611019...
echo ## 學生: D113611019 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611019\hw1-113611019.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611019\hw1-113611019.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611019\hw1-113611019.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611019\hw1-113611019.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113611023...
echo ## 學生: D113611023 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611023\hw1-113611023.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611023\hw1-113611023.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611023\hw1-113611023.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611023\hw1-113611023.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113611027...
echo ## 學生: D113611027 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611027\hw1-113611027.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611027\hw1-113611027.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611027\hw1-113611027.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611027\hw1-113611027.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113611056...
echo ## 學生: D113611056 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611056\hw1-113611056.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611056\hw1-113611056.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611056\hw1-113611056.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611056\hw1-113611056.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113611085...
echo ## 學生: D113611085 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611085\hw1-113611085.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611085\hw1-113611085.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611085\hw1-113611085.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611085\hw1-113611085.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113611108...
echo ## 學生: D113611108 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611108\hw1-113611108.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611108\hw1-113611108.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611108\hw1-113611108.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113611108\hw1-113611108.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113701062...
echo ## 學生: D113701062 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113701062\hw1-113701062.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113701062\hw1-113701062.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113701062\hw1-113701062.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113701062\hw1-113701062.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D113704054...
echo ## 學生: D113704054 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113704054\hw1-113704054.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113704054\hw1-113704054.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113704054\hw1-113704054.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D113704054\hw1-113704054.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114101109...
echo ## 學生: D114101109 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114101109\hw1-114101109.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114101109\hw1-114101109.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114101109\hw1-114101109.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114101109\hw1-114101109.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114150027...
echo ## 學生: D114150027 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114150027\hw1-114150027.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114150027\hw1-114150027.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114150027\hw1-114150027.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114150027\hw1-114150027.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114304010...
echo ## 學生: D114304010 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114304010\hw1-11434010.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114304010\hw1-11434010.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114304010\hw1-11434010.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114304010\hw1-11434010.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114481030...
echo ## 學生: D114481030 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114481030\hw1-114481030.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114481030\hw1-114481030.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114481030\hw1-114481030.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114481030\hw1-114481030.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114483023...
echo ## 學生: D114483023 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114483023\hw1-114483023.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114483023\hw1-114483023.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114483023\hw1-114483023.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114483023\hw1-114483023.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114612043...
echo ## 學生: D114612043 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612043\hw1-114612043.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612043\hw1-114612043.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612043\hw1-114612043.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612043\hw1-114612043.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114612045...
echo ## 學生: D114612045 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612045\hw1-114612045.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612045\hw1-114612045.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612045\hw1-114612045.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612045\hw1-114612045.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114612113...
echo ## 學生: D114612113 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612113\hw1-114612113.py.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612113\hw1-114612113.py.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612113\hw1-114612113.py.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612113\hw1-114612113.py.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114612119...
echo ## 學生: D114612119 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612119\hw1-114612119.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612119\hw1-114612119.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612119\hw1-114612119.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114612119\hw1-114612119.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114652002...
echo ## 學生: D114652002 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652002\u114652002.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652002\u114652002.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652002\u114652002.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652002\u114652002.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114652015...
echo ## 學生: D114652015 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652015\hw1-114652015.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652015\hw1-114652015.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652015\hw1-114652015.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652015\hw1-114652015.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114652019...
echo ## 學生: D114652019 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652019\hw1-114652019.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652019\hw1-114652019.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652019\hw1-114652019.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652019\hw1-114652019.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114652049...
echo ## 學生: D114652049 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652049\_hw1-114652049.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652049\_hw1-114652049.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652049\_hw1-114652049.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652049\_hw1-114652049.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D114652059...
echo ## 學生: D114652059 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652059\hw1-114652059.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652059\hw1-114652059.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652059\hw1-114652059.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D114652059\hw1-114652059.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo 正在處理: D614001032...
echo ## 學生: D614001032 >> report1.md
echo ```text >> report1.md
(echo 1)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D614001032\hw1-614001032.py" >> report1.md 2>&1
(echo 10)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D614001032\hw1-614001032.py" >> report1.md 2>&1
(echo 100)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D614001032\hw1-614001032.py" >> report1.md 2>&1
(echo -5)| python "Homework1Lab2.6.1.10Operatorsandexpressions\D614001032\hw1-614001032.py" >> report1.md 2>&1
echo ``` >> report1.md
echo. >> report1.md

echo ========================================
echo 作業一全班測試完畢！請查看資料夾中的 report1.md 檔案。
pause