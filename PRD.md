Samuel Akande Hostel Maintenance Complaint System

1. Overview
Course: BU-209 Backend Engineering

Project: Maintenance complaint system for Samuel Akande Hostel

This project looks at how students report faults in Samuel Akande Hostel and how those complaints are followed up. The proposed solution is a simple web system where students can report faults and check for updates, while porters and hall administrators can keep track of complaints and repairs.

2. Problem
Students currently write complaints on a plain sheet of paper and put it in a suggestion box, or record them in an old book. The space available for writing can be limited, so complaints are sometimes too brief. The book also does not clearly show when the same fault has been reported more than once.

The current process does not provide students with an acknowledgement or regular updates. Repair progress is not recorded, so students have to keep following up. According to the researcher's experience, a porter may assume that a problem has been resolved when the student stops raising it. Similar problems in different rooms may also be overlooked when a technician is available.

This affects students who need repairs and the porters responsible for organising them. Poor documentation appears to contribute to delays, although other factors such as technician availability may also play a part.

3. Research
Four residents of Samuel Akande Hostel were interviewed about maintenance problems they were facing. They were asked about the fault, how they reported it, what happened afterwards and how it affected them. Their identities are represented as R1–R4. The accounts below are summaries, not direct quotations.

R1
Problem: A damaged bed frame that collapses
Effect: The student has had to place the mattress on the floor.

R2
Problem: A leaking tap and a shower pipe that became faulty after a plumber worked on it
Effect: The student uses a low water flow to reduce the chance of the pipe coming apart.

R3
Problem: A missing mirror and damaged wardrobe
Effect: The student cannot store a reasonable portion of their belongings in the wardrobe.

R4
Problem: A faulty door that cannot lock
Effect: The student cannot properly lock their room.

The residents reported their problems using the available methods. The details requested included the student's name or identification, room number and complaint. They described frequent follow-ups and a lack of feedback. One resident reported that a pipe failed again two days after it was fixed; the interview summary does not identify which resident gave that account. The others' problems were reported as unresolved. The residents also spoke positively about the porter's attitude.

Four interviews provide useful examples, but they do not show how common these problems are across the whole hostel. The description of staff procedures comes from the researcher's account and still needs to be confirmed with hostel staff.

4. Evidence
E01
Finding: A damaged bed frame has left a student sleeping on a mattress on the floor.
Source: R1

E02
Finding: A student reports that a shower pipe became faulty after a plumbing repair.
Source: R2

E03
Finding: A damaged wardrobe limits the space available for a student's belongings.
Source: R3

E04
Finding: A faulty door cannot be locked.
Source: R4

E05
Finding: Residents use paper in a suggestion box or an old complaints book.
Source: Resident interviews and researcher's account

E06
Finding: Limited writing space can lead to vague descriptions.
Source: Researcher's account

E07
Finding: The book does not clearly indicate repeated reports about the same fault.
Source: Researcher's account

E08
Finding: Students do not receive a clear acknowledgement or regular progress updates and follow up frequently.
Source: Combined resident interviews

E09
Finding: A pipe reportedly failed again two days after a repair.
Source: Resident interview summary

E10
Finding: Porters or hall administrators assign workers; repair progress is not recorded.
Source: Researcher's account

E11
Finding: Similar faults in different rooms can be overlooked when work is arranged.
Source: Researcher's account

E12
Finding: Residents mentioned the porter's positive attitude.
Source: Combined resident interviews

5. Current Alternatives
Paper and suggestion box
How it helps: Students can submit a written complaint.
Where it falls short: Writing space may be limited, and students have no easy way to check progress.

Complaints book
How it helps: Complaints can be recorded in one place.
Where it falls short: Repeated reports are not clearly identified, and progress is not tracked.

Following up with the porter
How it helps: Gives students another chance to raise an issue.
Where it falls short: Students have to keep asking and may still not receive clear updates.

An improved paper register could also help if it included references, status and follow-up details. A web system is proposed because it could make the same information easier for both students and porters to find. An existing university tool has not been assessed and should be checked before development.

6. Proposed Solution
The proposed solution is a web-based maintenance complaint system for Samuel Akande Hostel. A student can submit a complaint with their room number, fault category and description. The system gives the complaint a reference number so the student can find it later.

A porter or hall administrator can view complaints, assign a worker and update their status. Students can check the updates and indicate whether the issue has been fixed. Staff can also filter complaints by category to see similar faults in different rooms.

The system can make complaints easier to track, but it cannot supply repair materials or guarantee that a technician will be available.

7. Users
Student
Responsibility: Report a fault, check its status and confirm if it has been resolved.

Porter or hall administrator
Responsibility: Review complaints, assign workers, update progress and follow up on unresolved faults.

Technician
Responsibility: Carry out the repair and tell the porter what was done or why it could not be completed.

Technicians do not need their own accounts in the first version. The porter records updates on their behalf.

8. Goals and Measures
Make reporting clearer
How it can be checked: Check whether submitted complaints include a room or location, category and useful description.

Reduce uncertainty
How it can be checked: Check whether students can find their complaint reference and current status.

Improve accountability
How it can be checked: Check whether assigned complaints show the worker or team responsible.

Reduce repeated follow-ups
How it can be checked: Compare how often students ask for status updates before and during a trial, if a baseline can be collected.

Improve closure accuracy
How it can be checked: Check how many complaints marked as fixed are confirmed or reopened by students.

Make similar faults easier to find
How it can be checked: Test whether staff can filter complaints by fault category.

These are proposed measures. No baseline or trial results have been collected yet.

9. Minimum Viable Product (MVP)
The MVP is the first version needed to report and track a complaint from submission to resolution. It includes:
1. Student and staff sign-in.
2. A form to report a fault, including location, category and description.
3. A reference number for each complaint.
4. A student page showing their complaints, status and updates.
5. A staff page for viewing and filtering complaints.
6. Assignment of a technician or maintenance team by a porter.
7. Status updates and short progress notes.
8. Student confirmation or reopening when a repair is incomplete.
The first version will not include a separate technician account, payment processing, spare-parts management, photo uploads, automatic scheduling, SMS or a mobile app. Students without access can ask a porter to enter a complaint on their behalf. The porter should give them the reference and record updates for them when needed.
10. Complaint Workflow
11. A student signs in and submits the location, category and description of a fault.
12. The system checks that the required information is present and displays a reference number.
13. A porter reviews the complaint and assigns a worker when one is available.
14. The porter updates the status and adds a short note when there is progress or a delay.
15. After a repair, the porter marks the complaint Resolved and records what was done.
16. The student checks the repair. If it is fixed, the student confirms and the complaint becomes Closed. If not, the student can reopen it and explain the problem.
Submitted
Meaning: The complaint has been received by the system.

Under review
Meaning: The porter has seen the complaint and is assessing it.

Assigned
Meaning: A worker or team has been given the task.

In progress
Meaning: Repair work has started.

On hold
Meaning: Work cannot continue for now; the porter records the reason.

Resolved
Meaning: The porter reports that the repair is complete.

Closed
Meaning: The student confirms that the fault is fixed.

Reopened
Meaning: The student reports that the fault remains or has returned.

A complaint should not be closed simply because the student stops following up. Similar faults in different rooms should remain separate complaints, even when staff arrange for the same technician to handle them. A repeated report about the same fault can be noted by staff so the earlier history is not missed.

11. Functional Requirements
FR1
Requirement: Students and staff can sign in.
Priority: Must
Evidence: E05, E10
Acceptance criteria: A student can view their own complaints; authorised staff can view complaints for the hostel.

FR2
Requirement: A student can submit a fault.
Priority: Must
Evidence: E01–E06
Acceptance criteria: The form requires a location, category and description. It displays an error if any required field is missing.

FR3
Requirement: Each submitted complaint receives a reference.
Priority: Must
Evidence: E07, E08
Acceptance criteria: A successfully submitted complaint displays a unique reference and appears in the student's complaint list.

FR4
Requirement: Students can check progress.
Priority: Must
Evidence: E08
Acceptance criteria: The student can see the current status and notes for their own complaint.

FR5
Requirement: Staff can view and filter complaints.
Priority: Must
Evidence: E07, E11
Acceptance criteria: Staff can find complaints by reference and filter them by category or status, including similar faults in different rooms.

FR6
Requirement: Staff can assign a worker and update progress.
Priority: Must
Evidence: E10, E11
Acceptance criteria: The assigned worker or team, current status and any progress note appear on the complaint. A reason is required when a complaint is put on hold.

FR7
Requirement: Staff can record a completed repair.
Priority: Must
Evidence: E09, E10
Acceptance criteria: Staff can mark a complaint resolved and describe the work done. It is not yet marked closed.

FR8
Requirement: A student can confirm or reopen a repair.
Priority: Must
Evidence: E09
Acceptance criteria: The student can confirm a resolved complaint or reopen it with a reason. Earlier updates remain visible.

FR9
Requirement: A porter can help a student submit a complaint.
Priority: Must
Evidence: E05, E12
Acceptance criteria: Staff can enter the complaint for a student and provide its reference; the record indicates that staff entered it.

12. Data Requirements
Student identifier and role
Why it is needed: To associate complaints with the correct student and control access.

Complaint reference
Why it is needed: To find and follow up on a specific report.

Room or location
Why it is needed: To show where the fault is.

Fault category and description
Why it is needed: To explain the problem and help staff group similar work.

Assigned worker or team
Why it is needed: To show who is responsible for the repair.

Status, notes and update times
Why it is needed: To show progress and retain a simple history.

Repair outcome and student response
Why it is needed: To show whether a repair was confirmed or reopened.

Only authorised staff should see the hostel complaint list. Students should see only their own complaints. The hostel should decide how accounts are verified and how long records are kept before the system is used.

13. Non-Functional Requirements
• Security: Sign-in and access controls should prevent students from viewing or changing another student's complaint.

• Usability: The reporting form should be simple to complete on a phone and clearly identify missing information.

• Reliability: A complaint should only be shown as submitted after it has been saved. If submission fails, the student should see an error and be able to try again.

• Privacy: The system should collect only information needed to report and manage repairs.

• Record keeping: Previous status updates should remain available when a complaint is reopened.

• Accessibility: Labels and status messages should use clear text and should not depend on colour alone.

14. Assumptions and Risks
Porters may not have time to update the system.
Response: Discuss responsibilities with hostel staff and keep updates short.

Some students may not have reliable access to the system.
Response: Allow a porter to enter and follow up on a complaint for them.

Repairs may still be delayed by unavailable technicians or materials.
Response: Record the reason for the delay; the system does not guarantee faster repairs.

A repair may fail again.
Response: Allow students to reopen a complaint and keep its earlier history.

Four resident interviews may not reflect everyone's experience.
Response: Speak to more residents and hostel staff before building or expanding the system.

Urgent faults may need immediate attention.
Response: Confirm and display the hostel's emergency contact procedure; the tracker is not an emergency service.

15. Testing and Next Steps
Before development, confirm the current process with a porter or hall administrator and check whether the university already has a suitable system. Discuss who will manage accounts, assign workers and update complaints.

A small trial in Samuel Akande Hostel could then test whether students can submit complaints, find updates and reopen failed repairs, and whether porters can manage their work list. Test cases should also cover missing form details, an unsuccessful submission and attempts to view another student's complaint. Feedback from the trial can be used to improve the system before considering other hostels.

16. Sources
• Interview summaries from four Samuel Akande Hostel residents, identified as R1–R4.

• Researcher's account of the hostel's reporting and maintenance process.

• BU-209 Backend Engineering Week 4 assignment brief.