# COMP2850 HCI Assessment: Evaluation & Redesign Portfolio

**Student**: [201807668]
**Submission date**: [DD/MM/YYYY]
**Academic Year**: 2025-26

---

## Privacy & Ethics Statement

- [✅] I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names)
- [✅] I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible)
- [✅] I confirm all participants gave informed consent
- [✅] I confirm this work is my own (AI tools used for code assistance are cited below)
---
**AI tools used** (if any):   
No AI tools were used.

## 1. Protocol & Tasks

### Link to Needs-Finding (LO2)

## **Story S1: Confirmation Feedback**  
**Situation**: When I submit a form (add task, edit task, delete task)  
**Motivation**: I want immediate, explicit confirmation that the action succeeded  
**Outcome**: So I can trust the interface without refreshing to verify  
**Underlying need**: Because lack of confirmation causes anxiety about whether the use of the website is correct, and requires reloading the page which is inefficient

**Evidence**: Participant A  
**Inclusion risk**: Low digital Literacy, Cognitive
**Type**: Job story  
**How does Task 1-4 test this**: TOOOOOOOOOOOOOOOOO DOOOOOOOOO

## **Story S2: Edit Button**  
**Situation**: When I want make changes to an existing task
**Motivation**: I want to be able to modify the task without deleting and rewriting it  
**Outcome**: So I can efficiently correct a mistake I make  
**Underlying need**: Because inefficient corrections of user mistakes can increase frustraion 

**Evidence**: Participant B   
**Inclusion risk**: Low digital Literacy    
**Type**: Job story  
**How does Task 2 test this**: TOOOOOOOOOOOOOOOOOO DOOOOOOOOOOO

## **Story S3: Real time task filtering button**  
**Situation**: When I want to look for an existing task
**Motivation**: I want to filter tasks to find the one I want
**Outcome**: Task is filtered as the user enters the desired match 
**Underlying need**: The user must scroll through all existing tasks, which can take up time and can be prone to a mistake in not noticing the desired task within a long list  

**Evidence**: Participant C   
**Inclusion risk**: Low vision    
**Type**: Job story   
**How does Task 1 test this**:TOOOOOOOOOOOOOOOOOOO DOOOOOOOOOOO

## **Story S4: Large UI buttons**  
**Situation**: When I want complete an action using interactables (buttons) on screen
**Motivation**: I want to be able to easily see where to click
**Outcome**: Buttons span most of the length of the screen and use constrasting colours
**Underlying need**: Users want an easy to use UI where it is clear how to complete an action 

**Evidence**: Participant C   
**Inclusion risk**: Low vision    
**Type**: Job story   
**How does Task 1 test this**:TOOOOOOOOOOOOOOOOOOO DOOOOOOOOOOO

---

## Task descriptions 

To complete this, I used four tasks T1-T4 that test the core functions of the program, and are able to cover all critical components of the program.

## Task T1: Filter Tasks

**Scenario**:
"You've been asked to find all tasks containing the word 'buy'. Use the filter box to show only matching tasks, then count how many existing tasks remain."

**Setup**:
- Pre-populate task list with 10 tasks, 3 containing "Buy" in title
- Example: "buy dinner", "buy 6 apples", "write a list of people to buy gifts for", plus 7 others

**Success criteria**:
- Participant uses filter box (types "buy")
- Participant reports correct number of tasks (4 tasks)
- Completed within 2 minutes
- No validation errors

**Metrics**:
- Time from page load to stating count (ms)
- Completion (0 = fail, 1 = success)
- Validation errors (number of tasks)
- Confidence rating (1–5): "How confident are you that you found all matching tasks?"

**Accessibility checks**:
- "Buy" count announced by screen reader?
- Keyboard-only completion possible?
- Works with JS disabled?

---

## Task T2: Edit Task Description

**Scenario**:
"The task 'Complete portfolio by Thursday' is incorrectly listed. Change it to 'Complete portfolio by Friday' and save the change."

**Setup**:
- Task ID 5: "Complete portfolio by Thursday" (visible in list)
- Participant must click Edit, change task text, save task

**Success criteria**:
- Participant enters task edit mode
- Participant updates task description correctly
- Change persists after save
- Completed within 90 seconds
- No validation errors

**Metrics**:
- Time from click Edit to save confirmation (ms)
- Completion (0 = fail / 1 = success)
- Validation errors (incorrect task changed)
- Confidence rating (1–5)

**Accessibility checks**:
- Status message "Updated [title]" announced?
- Program remains focused on edited task?
- Works with keyboard only?
- Works with JS disabled?

---

## Task T3: Delete Taks

**Scenario**:
"You have completed "Buy dinner", "Worksheet 2", "Worksheet 3", delete the tasks from the list"

**Setup**:
- Pre-populated task list 
- Tasks to delete visible in list

**Success criteria**:
- Participant deletes exact 3 tasks 
- Taks no longer present in list
- Confirmation of each deleted task
- Completed within 90 seconds

**Metrics**:
- Time from focus in list to third confirmation (ms)
- Completion (0 = fail / 1 = success)
- Validation errors (if they delete the wrong task)
- Confidence rating (1–5)

**Accessibility checks**:
- Status message "Task [title] deleted" announced?
- "Deleted [Title]" confirmation displayed?
- Works with JS disabled?

---

## Task Order

**Recommended sequence**:
1. **Warm-up** (untimed): "Add 2 tasks, and view tasks in the listto understand the core program function"
2. T1 (Filter) — Low/Medium complexity, tests search
3. T2 (Edit) — Tests inline interaction, validation
4. T3 (Delete) — Destructive action, tests confirmation
6. **Debrief** (qualitative): Open-ended questions

**Counterbalance** If testing multiple participants, alternate the T2/T3 order to avoid learning effects that could compound from both searching and manipulating pre-existing tasks in the list.

---

## Notes for Facilitator

- **Do not help** unless participant is completely stuck (>3 min). Note as "facilitated" in observations.
- **Think-aloud optional**: Ask participants to narrate their thoughts if comfortable. Not required.
- **Screen reader users**: Allow extra time for navigation. Log SR-specific observations separately.
- **Keyboard-only**: Offer keyboard-only variant to a participant for comparison.
- **No-JS**: Test at least 1 participant with JS disabled to verify parity.

---

## Success Definitions

**Completion codes**:
- `1` = Task completed as intended, with the correct qualifications
- `0.5` = Task completed as intended with some margin of error (e.g., applied filter, but gave the wrong count)
- `0` = Task uncompleted, or task completed with a large margin of error

**Time bounds**:
- T1: 120s
- T2: 90s
- T3: 90s

If the time is exceeded when completing a task, prompt: "Would you like to continue, or shall we move to the next task?"

# Informed Consent Protocol 

**Module**: COMP2850 Human-Computer Interaction
**Activity**: Low-risk needs-finding (peer interviews)
**Date**: [2025-12-10]
**Researcher**: [Christian Brooks/201807668]

---

## Before starting (read aloud)

"This is a short (10-15 min approx) usability test. I will ask you to complete 4 tasks while I take notes from my observations. The test is on the interface, and any problems or difficulty is a reflection of the program. It is an intention of the test to identify this, so there is no wrong answers, and you should not feel pressured to perform to any expected outcome."

## Data Collected

**Will collect**:
- Task completion times (from server logs)
- Task completion success (0/0.5/1)
- Errors or validation issues
- User given confidence rating
- Researcher notes including user hesitation and accessibility issues if applicable

**Will NOT collect**:
- Your name (unless you want acknowledgement credit)
- Student ID, email, or any personally identifiable information (PII)
- Device details beyond "screen reader" or "keyboard-only" when applicable

**Session details**
Each user assigned a unique and random session code (like "TOOOO DOOOO") which will be shown in the logs. You can request all data linked to you session code at any time, including any point in the future.

I'll assign you a random session code (like `TOOOOO DOOOO`) which will appear in the logs. You can request that I delete all data linked to your session code at any time, even after today.


## Data Storage

- **Where**: Private Git repository on my laptop (not shared publicly)
- **Access**: Me, lab partner, teaching staff (if requested for marking)
- **Duration**: Until end of Semester 1 (January 2025), then deleted OR anonymised for portfolio

## Your Rights (UK GDPR / Data Protection Act 2018)

- **Withdraw**: There is no requirement to finish and any task, or the whole test can be stopped at any time no questions asked
- **Access**: Ask to see your data (I'll show notes)
- **Erasure**: Request deletion (email me with date/pseudonym)
- **Complain**: University Data Protection Officer: dpo@leeds.ac.uk

## Consent Confirmation

Before starting, I will ask:
- [ ] Purpose explained clearly?
- [ ] Understand what data I'll collect?
- [ ] Know you can stop anytime?
- [ ] Consent to participate?

Any questions before we begin?

**Verbal consent sufficient**. If yes, I'll note:
- Date/time: [YYYY-MM-DD HH:MM]
- Pseudonym: [e.g., "Participant A"]
- Consent confirmed: [Initials]

Record in `/submission/consent/consent-log.md`:
Date: - Participant code: - Session ID: - Consent: Verbal consent givem.

---

## Opt-Out Process

If you change your mind:
1. Email: [qjqj5914@leeds.ac.uk]
2. Include: interview date + pseudonym

**Opt-out path**: If participant requests deletion (within 48 hours complete):
1. Open `data/metrics.csv`
2. Delete all rows where with participent [session_id]
3. Note in `consent-log.md`: "Data deleted on request [date]"

---

## Contact

**Researcher**: [Christian Brooks], [qjqj5914@leeds.ac.uk]
**Module Lead**: Dr. [Amy Brereton], [A.M.Brereton@leeds.ac.uk]
**University Ethics**: ethics@leeds.ac.uk

---

**Template source**: COMP2850 HCI, University of Leeds
**Reference**: ICO (2024). Guide to GDPR, <https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/>

