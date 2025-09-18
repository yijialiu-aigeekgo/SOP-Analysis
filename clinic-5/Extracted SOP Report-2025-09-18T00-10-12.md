# Extracted SOP Report Report

**Generated:** 2025-09-18T00:10:12.157Z
**Report Type:** Extracted SOP Report

---

I'll analyze the clinic visit data and create standardized workflow tables following the strict requirements for duration calculation.

## Patient Categorization Summary

**iHealth Enrollment**: 0 patients (no new UC enrollment activities observed)
**iHealth Follow-Up**: 3 patients (all three patients - Elizabeth, Kim, and George - are existing iHealth patients)
**Non-iHealth/Regular Visits**: 0 patients

## Duration Calculation Methodology

I will extract exact durations from the visit logs where provided and show all calculations:

### Patient 1 (Elizabeth) - Durations Found:
- Lobby wait/forms: 19 mins
- MA rooming: 1 min  
- Weight measurement: 1 min
- Vitals/chief complaint: 1 min
- CA/CM consultation: 6 mins
- Provider history/labs: 4 mins
- Physical exam/orders: 3 mins
- Provider wrap-up: 1 min

### Patient 2 (Kim) - Durations Found:
- Lobby wait: 26 mins
- Vitals: 1 min
- Provider consultation: 3 mins
- CA/CM medication refill: 2 mins

### Patient 3 (George) - Durations Found:
- Check-in: 3 mins
- Lobby wait: 3 mins
- Provider chart review: 2 mins
- Lab review: 2 mins
- History taking: 1 min
- Physical exam: 1 min
- Additional history: 3 mins
- Lab orders: 1 min
- Provider wrap-up: 1 min
- CA/CM vitals review: 8 mins

## iHealth Follow-Up Visit Workflow Table

| Location | Role | SOP Task | Task Code | Average Duration |
|----------|------|----------|-----------|------------------|
| Front Desk | Front Desk | Patient Registration | CI.1 | Check-in: 3 mins (only George had duration)<br>**Insufficient data for average** |
| Lobby | Patient | Waiting and form completion | CI.3 | Elizabeth: 19 mins<br>Kim: 26 mins<br>George: 3 mins<br>**Average: 16 mins** |
| Vital Room/Hallway | MA | 1) Rooming<br>2) Standard Vitals Collection | PP.1<br>PP.2 | Rooming: 1 min (Elizabeth only)<br>Vitals: 1 min (Elizabeth & Kim)<br>**Insufficient data for rooming average** |
| Exam Room | MA | Chief Complaint Capture | PP.3 | Elizabeth: 1 min<br>**Insufficient data for average** |
| Exam Room | CA/CM | 1) Medication Reconciliation<br>2) UC Device/Program tasks<br>3) Patient Summary Review<br>4) DB/HTN Specific Vitals (post-visit) | PP.5<br>-<br>PP.7<br>PP.2.1 | Med reconciliation: 6 mins (Elizabeth only)<br>Summary review: Not specified<br>DB/HTN vitals: 8 mins (George only)<br>**Insufficient data for averages** |
| Exam Room | MD/NP | 1) History Taking<br>2) Lab & Imaging Review<br>3) Physical Exam<br>4) Lab Orders<br>5) Assessment & Plan<br>6) Patient Education | CE.1<br>CE.5<br>CE.2<br>CE.6<br>CE.7<br>CE.8 | History: Elizabeth: 4 mins, George: 1+3 mins<br>**Average: 4 mins**<br>Lab review: George: 2 mins<br>**Insufficient data for average**<br>Physical exam: Elizabeth: 3 mins, George: 1 min<br>**Average: 2 mins**<br>Lab orders: George: 1 min<br>**Insufficient data for average**<br>Assessment: Elizabeth: 1 min, George: 1 min<br>**Average: 1 min** |
| Exam Room | MD/NP | Extra tasks (insurance coordination, consultation) | - | Kim consultation: 3 mins<br