# AI Appointment Scheduler


AI-powered appointment booking assistant that handles meeting scheduling through natural conversation.



### Features

- 📅 Schedules meetings via chat ("Book a meeting tomorrow at 2 PM")
- 🔍 Detects scheduling conflicts automatically
- 👤 Looks up contact emails
- ⏱️ Handles custom durations (30 min, 1 hour, etc.)
- 🚨 Suggests alternatives when times conflict

### Workflow

User Chat Input<br>
↓<br>
AI Agent (GPT-3.5)<br>
├─→ Get Meetings (check conflicts)<br>
├─→ Get Contact Details (lookup email)<br>
└─→ Schedule Meeting (create event)<br>
↓<br>
Google Calendar <br>



### Evaluation

Tested with **6 scenarios** covering scheduling, conflicts, and edge cases <br>

Inputs for evaluation & output of each workflow run is recorded in [Test Case Data](./Appointment%20Booking%20-Test%20Case%20Data.csv)

**Workflow Loom Video Demo** -------> [Agentic AI Appointment Scheduling](https://www.loom.com/share/5bfb1e5ed7d14efbae9e9fe58fdd3d8e)<br>
**Screenshot of Workflow** ---------> [Appointment scheduling Agent](./Screenshot.png) <br>


