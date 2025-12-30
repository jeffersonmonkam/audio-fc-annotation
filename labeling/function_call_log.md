## ⏱ Function Call Timeline – Session P001 (John Smith)

<details>
<summary>Voir la timeline complète 🎧</summary>

```python
# 🟢 Patient Verification (0:05 – 0:20)
check_patient_exists(first_name="John", last_name="Smith", date_of_birth="1980-05-15")
verify_patient_identity(
    patient_id="P001",
    identifier_1_type="phone", identifier_1_value="5550100",
    identifier_2_type="address_zip", identifier_2_value="12345"
)
get_patient_demographics(patient_id="P001", verified=True)

# 🟡 Appointment Management (0:20 – 1:00)
check_insurance_eligibility(patient_id="P001", service_date="2025-09-15")
search_available_appointments(
    appointment_type="telehealth",
    date_range_start="2025-09-15",
    date_range_end="2025-09-22",
    modality="telehealth",
    preferred_provider="Dr. Johnson",
    time_preference="any"
)
get_patient_appointments(patient_id="P001")
book_appointment(
    patient_id="P001",
    appointment_date="2025-09-15",
    appointment_time="9:00 AM",
    reason_for_visit="Annual checkup",
    appointment_type="wellness",
    modality="in_person"
)

# 🔵 Follow-up & Clinic Info (1:15 – 2:15)
cancel_appointment(
    patient_id="P001",
    appointment_id="APT00001",
    cancellation_reason="Work conflict"
)
reschedule_appointment(
    patient_id="P001",
    appointment_id="APT00001",
    new_date="2025-09-22",
    new_time="11:00 AM",
    provider="Dr. Johnson"
)
send_secure_text(
    patient_id="P001",
    message="Reminder: your appointment is tomorrow at 9:00 AM"
)
get_clinic_hours()
get_clinic_directions()
