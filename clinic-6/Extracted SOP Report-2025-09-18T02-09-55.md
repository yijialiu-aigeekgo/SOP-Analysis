# Extracted SOP Report Report

**Generated:** 2025-09-18T02:09:55.325Z
**Report Type:** Extracted SOP Report

---

Based on the provided visit records, here's my analysis following the prompt requirements:

## Patient Categorization Summary
- **iHealth Enrollment**: P3 Yuehong (new patient with DM/HTN, UC education provided)
- **iHealth Follow-Up**: P2 Dehui (existing iHealth patient with DM)
- **Total Patients Analyzed**: 2

## Duration Calculation Methodology

**Extracted Duration Data from Visit Logs:**

**P2 Dehui:**
- Check-in: 2 min (explicitly stated)
- Lobby wait: 6 min (explicitly stated) 
- Vitals: 2 min (explicitly stated)
- A1C test: Not specified

**P3 Yuehong:**
- Check-in: 2 mins (explicitly stated)
- Lobby wait/forms: 22 mins (explicitly stated)
- Vital room activities: 18 mins (explicitly stated for combined tasks)

**Note:** P3's vital room duration (18 mins) covers multiple tasks but individual task breakdowns are not provided in the source data.

## Workflow Table: iHealth Enrollment (Based on P3 Yuehong)

| Location | Role | SOP Task | Task Code | Average Duration |
|----------|------|----------|-----------|------------------|
| Front Desk | MA/Front Desk | Patient Registration<br>Provide intake forms | CI.1 | 2 mins (single patient data) |
| Lobby | Patient | Complete intake forms | - | 22 mins (single patient data) |
| Lobby | MA | Demographics Update<br>• Verify phone/email<br>• Confirm pharmacy<br>• Scan insurance | CI.3 | Duration included in lobby time |
| Vital Room | MA | 1) Rooming<br>2) Standard Vitals Collection<br>3) Medication Reconciliation<br>4) Chief Complaint Capture<br>5) EKG (Extra Task)<br>6) Social History (Extra Task) | PP.1<br>PP.2<br>PP.4<br>PP.5 | Combined duration: 18 mins<br>(Individual task durations not specified) |
| Vital Room | CA/CM | Patient Education - UC program basics | PE.1 | Duration included in 18 mins total |

## Workflow Table: iHealth Follow-Up (Based on P2 Dehui)

| Location | Role | SOP Task | Task Code | Average Duration |
|----------|------|----------|-----------|------------------|
| Front Desk | MA | Patient Registration | CI.1 | 2 min (single patient data) |
| Lobby | Patient | Wait time | - | 6 min (single patient data) |
| Vital Room | MA | Standard Vitals Collection<br>• Weight<br>• Blood pressure | PP.2 | 2 min (single patient data) |
| Vital Room | CA/CM | DB/HTN Specific Vitals<br>• A1C testing | PP.3 | Not specified |

## Data Limitations

1. **Insufficient Sample Size**: Only one patient per scenario prevents true average calculation
2. **Missing Duration Data**: 
   - P2: A1C testing duration not specified
   - P3: Individual task durations within the 18-minute vital room period cannot be determined
3. **Combined Activities**: P3's vital room activities were recorded as a single 18-minute block, making it impossible to determine individual task durations

## Key Workflow Observations

1. **New Patient Complexity**: iHealth enrollment visits (P3) involve significantly more time (42+ mins total) compared to follow-up visits (P2: 10+ mins total)

2. **Role Distribution**: 
   - MAs handle most tasks in both scenarios
   - CA/CM involvement focuses on condition-specific testing (A1C) and UC program education

3. **Extra Tasks in New Visits**: New patient visits include additional assessments (EKG, comprehensive social history) not part of standard SOP

4. **Documentation Gap**: The source data provides total duration for combined activities but lacks granular task-level timing needed for detailed workflow optimization