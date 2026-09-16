# Keenly Team Sync | 09/13/26

- **Question generation feedback**: @Leo flagged that AI-generated questions sometimes lack enough source context—students shouldn't have to infer material was covered from a function's name alone. @Berk and @Peter Perry will tighten the prompt, and the team agreed to add manual question entry + bulk upload (e.g. Quizlet-style flashcards) as an alternative to full AI generation. @Leo volunteered to help build out a flashcard bank for lab material.
- **Approval workflow**: flexible by design—CAs can draft their own questions with @Leo (and Ian) approving, or @Sebastián can self-approve AI-generated sets.
- **Attendance via RAG Race**: joining a RAG Race auto-marks a student present, with manual TA override for stragglers past the grace period. **Confirmed this covers lab attendance only**—lecture stays on the separate scan-code system.
- **Recurring RAG Races**: new repeat button lets a lab's RAG Race recur weekly per section (e.g. Lab A/B) without resetting the questions each time.
- **Stripe billing**: backend built and tested, not yet live in the frontend. Flow will be course-gated—students can create an account but can't join a specific course until they enter the join code and pay.
- **Group Exercises**: now supported—one submission packet per study group instead of per student, with configurable due-date/resubmission rules.
- **Automation ask**: @Sebastián wants individual (Mon/Wed) and group (Tue/Thu) exercises auto-generated weekly (e.g. every Saturday) for his approval, then auto-scheduled once approved. @Peter Perry confirmed it's buildable.
- **Schedule check-in**: semester has slipped about half a week (two missed Mondays)—Input now falls on Monday, Booleans on Wednesday. Sebastián confirmed this still tracks fine against the syllabus.
- **Approval risk**: the whole rollout is contingent on NYU/administrative sign-off landing before Wednesday—everything downstream is on hold until then.

### **To-Do List**:

- @Sebastián:
    - Send @Leo links to his lecture notes (Input/Booleans) so labs can be updated to match the shifted schedule.
    - Follow up by email with NYU/administration Monday night if no approval response by then.
    - Get @Berk Esencan a building pass for Tuesday's in-person meeting (and Friday's lab, if approved in time).
- @Berk Esencan and @Peter Perry:
    - Prep a RAG Race for Friday's lab session (Inputs) so TAs get a hands-on walkthrough at Tuesday's meeting.
    - Tighten the question-generation prompt, and build out manual entry + bulk upload of question sets.
    - Finish wiring automated attendance off RAG Race participation, and get Stripe billing live in the frontend.
    - Build the recurring weekly auto-generation/approval/auto-schedule flow for individual and group exercises.
- @Leo:
    - Start building a bank of pre-made questions/flashcards for lab material.
    - Coordinate with Ian on approving any TA-submitted RAG Race questions.
- @here:
    - Attend Tuesday's meeting—@Berk Esencan in person, @Peter Perry via Zoom (traveling), rest in person.
    - Possible short Wednesday-night meeting to review the Stripe/billing frontend, contingent on approval landing by then.

Good energy tonight—Leo noted how far the app's come since the first demo, and the plan for Tuesday is set.
