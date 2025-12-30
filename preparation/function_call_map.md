## ⏱ Function Call Timeline – Session P003

<details>
<summary>Voir la timeline complète 🎧</summary>

```python
# 🟢 Patient Verification
check_patient_exists(first_name="Maria", last_name="Garcia", date_of_birth="1975-08-22")
verify_patient_identity(
    patient_id="P001",
    identifier_1_type="phone", identifier_1_value="5550100",
    identifier_2_type="address_zip", identifier_2_value="12345"
)
get_patient_demographics(patient_id="P001", verified=True)

# 🟡 Appointment Management
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

# 🔵 Clinic Info
get_clinic_hours()
get_clinic_directions()
check_business_hours()

# 🟣 New Patient & Escalation
create_new_patient_record(
    first_name="Alice",
    last_name="Brown",
    date_of_birth="1990-01-10",
    phone="555-0110",
    email="alice.brown@email.com",
    insurance="Aetna",
    address_zip="12346",
    provider="Dr. Chen"
)
escalate_to_staff(
    patient_id="P001",
    priority="emergency",
    message="Patient showing critical symptoms"
)
