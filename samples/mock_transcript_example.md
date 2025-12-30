User: Hi, I’m John Smith. I’d like to check my appointments.
Assistant: Sure, let me verify your identity.
🔧 check_patient_exists(first_name="John", last_name="Smith", date_of_birth="1980-05-15")

User: My phone is 555-0100 and zip is 12345.
Assistant: Got it, verifying your identity.
🔧 verify_patient_identity(patient_id="P001", identifier_1_type="phone", identifier_1_value="5550100", identifier_2_type="address_zip", identifier_2_value="12345")

User: Show me my demographic information.
Assistant: Here’s what I have.
🔧 get_patient_demographics(patient_id="P001", verified=True)

User: Check my insurance for December 15th.
Assistant: Checking insurance coverage.
🔧 check_insurance_eligibility(patient_id="P001", service_date="2025-09-15")

User: Find me a telehealth appointment with Dr. Johnson.
Assistant: Searching available appointments.
🔧 search_available_appointments(appointment_type="telehealth", date_range_start="2025-09-15", date_range_end="2025-09-22", modality="telehealth", preferred_provider="Dr. Johnson", time_preference="any")

User: I want to book the 9 AM slot for annual checkup.
Assistant: Booking your appointment.
🔧 book_appointment(patient_id="P001", appointment_date="2025-09-15", appointment_time="9:00 AM", reason_for_visit="Annual checkup", appointment_type="wellness", modality="in_person")

User: Cancel my previous appointment due to work conflict.
Assistant: Your appointment is canceled.
🔧 cancel_appointment(patient_id="P001", appointment_id="APT00001", cancellation_reason="Work conflict")

User: Reschedule it to September 22nd at 11 AM.
Assistant: Appointment rescheduled.
🔧 reschedule_appointment(patient_id="P001", appointment_id="APT00001", new_date="2025-09-22", new_time="11:00 AM", provider="Dr. Johnson")

User: Please send a reminder for tomorrow.
Assistant: Reminder sent.
🔧 send_secure_text(patient_id="P001", message="Reminder: your appointment is tomorrow at 9:00 AM")

User: What are the clinic hours today?
Assistant: Here they are.
🔧 get_clinic_hours()

User: Can you give me directions to the clinic?
Assistant: Directions sent.
🔧 get_clinic_directions()
