# ========================
# ESAPI script  "EB_Bio3D"
# ========================
# 
# 
# Background:
# ===========
# 
# In radiation oncology, different fractionation schemes 
# can be compared converting the actual dose into the equivalent dose in 2 Gy fractions (EQD2). 
# The focus of the current project was to create an ESAPI script (Eclipse Scripting API) 
# for this kind of biological dose correction of the 3D dose matrix displayed 
# in the radiation treatment planning system Eclipse 
# (Aria, Varian Medical Systems, A SIEMENS Healthineers Company). 
# Thereby, the goal was to make the biological dose correction topologically visible by conversion 
# of the entire 3D dose distribution, thereby providing an additional tool for plan evaluation.
# 
# Results:
# ========
# 
# In C#, a script for the biological dose correction of the 3D dose matrix was generated ("EB_Bio3D").
# The script was implemented and successfully tested using real life patient cases.
# 
# Conclusion:
# ===========
# 
# The above mentioned software was developed and implemented. 
# Tests were performed on several patient plans 
# and confirm the correct functioning of the ESAPI script "EB_Bio3D". 
# A clinical test run will be started.
# 
#
# Technicals
# ==========
#
# For proper operation the path to the ExcelFile "EB_Bio3D.xlsx" must be adapted!
# See in "EB_Bio3D.cs", line 837.
# See     837 oWB = oXL.Workbooks.Open("Q:/ESAPI/Plugins/EB_Bio3D/EB_Bio3D.xlsx");
#
#
# ===============================
# Remarks, Licences, Limitations:
# ===============================
# 
# The content of this repository ("EB_Bio3D") is not allowed for clinical use!
# It is only for the purpose of publication!
# The copyright belongs exclusively to the author of "EB_Bio3D"!
# 
# 
# Germany, Neuruppin,  May the 12th 2021
# Dr. Eyck Blank
# 
