# Extracted SOP Report Report

**Generated:** 2025-09-19T08:47:45.842Z
**Report Type:** Extracted SOP Report

---

# Clinic Workflow Analysis and SOP Mapping

## Patient Categorization Summary
- **iHealth Follow-Up**: 1 patient (P1 Dehui - DM)
- **iHealth New Patient**: 1 patient (P2 Dane - DM/HTN, new to clinic and iHealth)

## Duration Calculation Methodology

### Data Extraction Method:
- All durations extracted directly from "Duration" column in visit logs
- Where explicit durations provided (e.g., "2 min"), exact values used
- Where no duration specified, marked as "Not specified"

### Actual Duration Data Found:
**P1 Dehui (iHealth F/U):**
- Check-in: 2 min
- Lobby wait: 6 min 
- Vitals collection: 2 min
- A1C testing: Not specified

**P2 Dane (iHealth New):**
- Check-in: 2 mins
- Forms/lobby wait: 22 mins
- Vitals & intake: 18 mins
- Other tasks: Not specified

## Workflow Tables

### iHealth Follow-Up Workflow

| Location | Role | SOP Task | Task Code | Average Duration |
|----------|------|----------|-----------|------------------|
| Front Desk | MA | Patient Registration | CI.1 | 2 min (1 patient data) |
| Lobby | Patient | Waiting | - | 6 min (1 patient data) |
| Vital Room | MA | Standard Vitals Collection (weight, BP) | PP.1 | 2 min (1 patient data) |
| Vital Room | CA/CM | DB/HTN Specific Vitals (A1C testing) | PP.2 | Not specified |

### iHealth New Patient Workflow

| Location | Role | SOP Task | Task Code | Average Duration |
|----------|------|----------|-----------|------------------|
| Front Desk | MA/Front Desk | 1) Patient Registration<br>2) Provide intake forms | CI.1, CI.3 | Registration: 2 mins (1 patient data)<br>Forms: Included in 2 mins |
| Lobby | Patient | 1) Complete intake forms<br>2) Family assistance with documentation | CI.3 | 22 mins total (1 patient data) |
| Lobby | MA | Demographics Update (collect ID, insurance, pharmacy info) | CI.2 | Not specified (occurred during 22 min lobby period) |
| Vital Room | MA | 1) Standard Vitals Collection<br>2) Medication Reconciliation<br>3) Chief Complaint Capture<br>4) Comprehensive social history (Extra)<br>5) EKG (Extra) | PP.1, PP.3, PP.4 | 18 mins total for all tasks (1 patient data)<br>Individual task durations not specified |
| Vital Room | CA/CM | UC Program eligibility screening (Extra) | - | Not specified (occurred during 18 min vital room period) |

## Data Limitations
- **Insufficient data for averages**: Only 1 patient per scenario, so averages cannot be calculated across multiple patients
- **Missing duration data**: Several tasks lack specific duration information (marked as "Not specified")
- **Bundled activities**: P2's vital room activities (18 mins) included multiple tasks without individual durations

## Key Workflow Observations

1. **New Patient vs Follow-Up Complexity**: New iHealth patients have significantly more complex workflows including:
   - Intake forms completion (22 mins vs 0 for follow-up)
   - Demographics collection
   - Comprehensive social history
   - Additional screening procedures (EKG)

2. **Wait Times**: New patients experienced longer lobby wait (22 mins vs 6 mins), primarily due to forms completion

3. **UC Integration**: Both workflows include UC staff involvement:
   - Follow-up: A1C testing by CA/CM
   - New patient: Eligibility screening and program explanation

4. **Extra Tasks**: New patient visits included several non-SOP tasks (social history, EKG, UC screening) that extended the pre-provider workflow time

5. **Role Distribution**: MAs handle most pre-provider tasks, with CA/CM specifically involved for diabetes-related activities