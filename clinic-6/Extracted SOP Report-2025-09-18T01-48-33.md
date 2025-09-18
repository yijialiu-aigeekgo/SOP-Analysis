# Extracted SOP Report Report

**Generated:** 2025-09-18T01:48:33.264Z
**Report Type:** Extracted SOP Report

---

Based on the provided patient visit records, I'll analyze these two cases to demonstrate the workflow mapping methodology. However, I notice that only partial visit data has been provided (visits appear incomplete - no provider encounter or checkout phases shown).

## Patient Categorization Summary

**From the provided samples:**
- **iHealth Follow-Up**: P2 Dehui (existing DM patient in UC program)
- **iHealth Enrollment**: P3 Yuehong (new patient being introduced to UC program)
- **Total Patients Shown**: 2

## Duration Calculation Methodology

**Actual durations extracted from source data:**

### P2 Dehui (iHealth F/U):
- Check-in: 2 minutes (explicitly stated)
- Lobby wait: 6 minutes (explicitly stated)
- Vitals collection: 2 minutes (explicitly stated)
- A1C testing: Not specified

### P3 Yuehong (iHealth Enrollment):
- Check-in: 2 minutes (explicitly stated)
- Lobby wait/forms: 22 minutes (explicitly stated)
- Vital room activities: 18 minutes total (explicitly stated)
  - This includes vitals, medication reconciliation, chief complaint, and EKG

**Note:** Since only 1-2 patients are shown per category, statistical averages cannot be reliably calculated. More patient data would be needed for meaningful averages.

## Workflow Tables

### iHealth Follow-Up Workflow (Based on P2 Dehui)

| Location | Role | SOP Task | Task Code | Duration (from actual data) |
|----------|------|----------|-----------|----------------------------|
| Front Desk | MA | Patient Registration | CI.1 | 2 minutes (1 patient) |
| Lobby | Patient | Waiting | - | 6 minutes (1 patient) |
| Vital Room | MA | Standard Vitals Collection | PP.1 | 2 minutes (1 patient) |
| Vital Room | CA/CM | DB/HTN Specific Vitals (A1C testing) | PP.2 | Not specified |

### iHealth Enrollment Workflow (Based on P3 Yuehong)

| Location | Role | SOP Task | Task Code | Duration (from actual data) |
|----------|------|----------|-----------|----------------------------|
| Front Desk | Front Desk Staff | Patient Registration | CI.1 | 2 minutes (1 patient) |
| Lobby | Patient | Intake Forms Management | CI.3 | 22 minutes (1 patient) |
| Lobby | MA | Demographics Update | CI.2 | Included in lobby time |
| Vital Room | MA | 1) Standard Vitals Collection<br>2) Medication Reconciliation<br>3) Chief Complaint Capture<br>4) EKG (extra task) | PP.1<br>PP.4<br>PP.3<br>- | 18 minutes total (1 patient)<br>Individual task durations not specified |
| Vital Room | CA/CM | UC Program Introduction (extra task) | - | Included in the 18 minutes |

## Data Limitations

**Critical gaps identified:**
1. **Insufficient sample size**: Only 1 patient shown per workflow type - cannot calculate meaningful averages
2. **Incomplete visits**: Records end at vital room stage - no provider encounter or checkout data
3. **Bundled durations**: P3's vital room activities (18 minutes) includes multiple tasks without individual breakdowns
4. **Missing durations**: P2's A1C testing duration not specified

## Key Observations

1. **New patient complexity**: The iHealth enrollment patient (P3) spent significantly more time in pre-provider activities (22 minutes for forms, 18 minutes in vital room) compared to the follow-up patient (P2: 2 minutes for vitals)

2. **UC integration**: Both visits show UC staff involvement during vital signs collection, suggesting integrated care coordination at the pre-provider stage

3. **Extra tasks noted**: EKG performance and UC program explanation were documented as additions to standard SOP tasks

**Recommendation**: To create statistically valid workflow standards, analyze complete visit records for at least 10-15 patients per category, including provider encounters and checkout procedures.