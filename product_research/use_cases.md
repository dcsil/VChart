# Use Cases

## MVP:

### 1. AI-Powered Auto-Save Voice Charting (Hands-Free Documentation)

Nurses don’t have time to manually type notes or review transcriptions between patients. VChart allows them to record their observations via voice input, and the system automatically transcribes and charts the information in real time.

#### Steps:

1. Nurse opens the web app on mobile between patients.
2. Selects a patient profile from the list.
3. Nurse initiates a new entry.
4. Taps the voice recording button and speaks.
5. AI transcribes speech in real time and immediately saves the structured chart entry to the system.
6. The entry is marked as pending review for later edits.

#### MVP Scope:

- Register and login to the VChart web app.
- Real-time speech-to-text transcription.
- Automatic saving of transcriptions to the patient’s chart.
- Ability to mark entries as "Pending Review."
- Basic mobile-friendly web interface for recording and saving entries.

---

### 2. Quick Chart Review and Editing on a Computer

Since voice-charted entries are auto-saved in real time, nurses must later review and finalize them. VChart allows nurses or supervisors to edit AI-generated charts in under 30 seconds.

#### Steps:

1. Nurse logs into the VChart web app.
2. Navigates to the “Pending Review” chart entries.
3. Selects a patient chart to review.
4. Reads the AI-generated chart entry.
5. Makes quick edits if necessary.
6. Exports to PDF/email.

#### MVP Scope:

- Web-based interface for reviewing pending chart entries.
- Basic form editor for making quick modifications.
- Ability to mark entries as "Finalized."
- Export functionality (PDF/Email).

---

### 3. Manage Patient List

Nurses need to dynamically manage their patient list to reflect the patients they are currently attending to. This includes adding new patients and removing those who are no longer under their care.

#### Steps:

1. Nurse logs into the VChart web app.
2. Adds a new patient by filling in essential information such as name, room number, and any other relevant details.
3. Identifies and removes patients from the list who are no longer under their care.

#### MVP Scope:

- Basic CRUD functionality for patient management.
- Ability to add new patients and remove patients no longer under care.

---

### 4. HIPAA Compliance and Data Security

VChart ensures the confidentiality, integrity, and availability of protected health information (PHI) by implementing robust security measures.

#### MVP Scope:

- Secure data storage for patient information.
- Secure authentication and session management.

---

## Post-MVP:

### 1. Enhanced HIPAA Compliance and Security Measures

#### Post-MVP Scope:

- Role-based access control (RBAC) for users:
  - Admins: Add and delete patients.
  - Nurses: Select patients under care.
  - IT: Handle password recovery.
- Data encryption for stored and transmitted data.
- Audit logging of access and modifications.

---

### 2. Integrate with existing EHRs

VChart will integrate with EHRs to allow nurses to chart directly from the EHR.

#### Post-MVP Scope:

- API integration with major EHR systems.
- Data synchronization between VChart and EHRs.
- Seamless user experience for documentation within hospital workflows.
