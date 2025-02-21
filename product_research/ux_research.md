# UX Research

## Scenarios Presented
### Scenario 1: Add New Patient Note
- "You are a nurse at a hospital and you need to add a new voice-recorded note entry for a patient. 
- "First, login to the app and selected the desired patient, then add the note entry by starting the voice recording."

### Scenario 2: Review and Edit Patient Note
- "You are a nurse who just finished taking care of the patient. You are in the hallway now and you need to review the note you just recorded for the patient."
- "Find the note that is pending review, review the note and make any necessary edits, then mark the note as reviewed."
- "You want to export the reviewed note to a PDF or email to share it with the doctor. Try to do that as well."

### Scenario 3: Add New Patient
- "You are assigned to a new patient and you need to add them to the system. You need to add the patient's name, room number, and any other relevant details."

## Prototype
Our [prototype](https://www.figma.com/design/G6naIVKZHbgCryc2KHK6va/VChart?t=y8U36YAhE7QKgLIt-1) is available on Figma.

## Overview of People Interviewed
- Michelle Ark (CSC491 Course Instructor)
- Shaveena Jeyaraj (Nurse at North York General Hospital)

## Summarized Notes
### Michelle Ark
- Prefers a manual save option for voice-recorded entries to ensure they are saved.
- Suggests removing the logout button from every screen to discourage app exits.
- Recommends adding account settings/preferences for user customization.

### Shaveena Jeyaraj
- Notes that the login screen shouldn't need a "forgot password" option, as accounts are typically handled by IT.
- Suggests that adding a patient should be an admin task and shouldn't be done by nurses.
- Currently only name, room number, and diagnosis are available for identification. Recommends using name, age, and date of birth for identification instead.
- The diagnosis of a patient isn't prone to change, so it's not necessary to call it an "initial diagnosis", just "diagnosis" would suffice.
- Suggests changing "history" to "log" in patient information.
- Recommends taking a look at Cerner & Epic and copying the fields and information they have in their software.
- The UX from voice to chart was unintuitive; suggests auto-populating and highlighting fields after voice input, with auto-save for review and submission via phone or computer.

## Appendix (Raw Notes)
### Michelle Ark
Michelle mentioned she would like to save the voice-recorded entry manually, otherwise she’s nervous to go back, because she's unsure if the entry was truly saved. In addition, in case autosave fails, having an option to save the entry manually would be helpful too.

Also, logout button shouldn’t be on every screen, making her wanting to quit the app, which is not desirable. There's no way to change account settings, maybe add account settings/preferences?

### Shaveena Jeyaraj
Login Screen:
- Normally there is no forgot password option, dealt with by IT (they set it all up and deal with it)

Add a Patient: 
- This should not exist, an admin would do this (through the actual system), but there should be a feature to select the patients that are yours (personal list)

Patient List:
- Should have name, age, and date of birth for identifier 

Patient Information:
- No “initial”, just “diagnosis”. Under patient info need to add more information: 
  - Mimic cerner & epic for all required information
- Change history to “log”

New Entry 
- Mimic cerner & epic for all required information, like should be vitals 
- UX from voice → chart is unintuitive. After you speak, the chart should auto-populate and highlight the populated fields, then auto-save for review, then you can review on your phone or computer (integrated with whatever system) and submit the chart
