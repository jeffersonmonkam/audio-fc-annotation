## 🗣 Example User Utterances & Corresponding Function Calls

<details>
<summary> All phrases and functions 🎤</summary>

| User Utterance | Function Call |
|----------------|---------------|
| "I need to check if John Smith with birthdate 1980-05-15 is in your system" | `check_patient_exists(first_name="John", last_name="Smith", date_of_birth="1980-05-15")` |
| "Can you look up Maria Garcia, born August 22, 1975?" | `check_patient_exists(first_name="Maria", last_name="Garcia", date_of_birth="1975-08-22")` |
| "Verify my identity - my phone is 555-0100 and zip code is 12345" | `verify_patient_identity(patient_id="P001", identifier_1_type="phone", identifier_1_value="5550100", identifier_2_type="address_zip", identifier_2_value="12345")` |
| "Show me my demographic information" | `get_patient_demographics(patient_id="P001", verified=True)` |
| "Check my insurance coverage for December 15th, 2025" | `check_insurance_eligibility(patient_id="P001", service_date="2025-12-15")` |
| "Find me a telehealth appointment next week with Dr. Johnson" | `search_available_appointments(appointment_type="telehealth", date_range_start="2025-09-15", date_range_end="2025-09-22", modality="telehealth", preferred_provider="Dr. Johnson", time_preference="any")` |
| "Show me my upcoming appointments" | `get_patient_appointments(patient_id="P001")` |
| "Book that 9 AM slot on September 15th for my annual checkup" | `book_appointment(patient_id="P001", appointment_date="2025-09-15", appointment_time="9:00 AM", reason_for_visit="Annual checkup", appointment_type="wellness", modality="in_person")` |
| "Cancel my appointment APT00001 due to a work conflict" | `cancel_appointment(patient_id="P001", appointment_id="APT00001", cancellation_reason="Work conflict")` |
| "Reschedule my appointment APT00001 to September 22nd at 11 AM" | `reschedule_appointment(patient_id="P001", appointment_id="APT00001", new_date="2025-09-22", new_time="11:00 AM", provider="Dr. Johnson")` |
| "Send me a reminder for my appointment tomorrow at 9 AM" | `send_secure_text(patient_id="P001", message="Reminder: your appointment is tomorrow at 9:00 AM")` |
| "What are the clinic hours today?" | `get_clinic_hours()` |
| "Can you give me directions to the clinic?" | `get_clinic_directions()` |
| "Create a new patient record for Alice Brown" | `create_new_patient_record(first_name="Alice", last_name="Brown", date_of_birth="1990-01-10", phone="555-0110", email="alice.brown@email.com", insurance="Aetna", address_zip="12346", provider="Dr. Chen")` |
| "Escalate to staff, emergency patient" | `escalate_to_staff(patient_id="P001", priority="emergency", message="Patient showing critical symptoms")` |

</details>


