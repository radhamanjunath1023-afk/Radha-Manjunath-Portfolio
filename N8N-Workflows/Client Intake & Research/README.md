## Client Intake & Research Automation

### Problem statement
Manually reviewing form submissions and researching clients is slow and inconsistent.

### Workflow Breakdown

1. **Trigger:**  User submits a Tally form

2. **Data Intake:** Tally sends form data to an n8n Webhook

3. **Input Reading:** AI Agent reads form fields (client, need, tone, context)

4. **Conditional Research:** Agent uses Google Search (SerpApi) only when external research is required

5. **AI Processing:** Agent acts like a virtual assistant to analyze needs and context

6. **Structured Output:** Results are returned in a fixed, clean schema using a Structured Output Parser

### Output 
A structured AI-generated result including client summary, research points, and ready-to-use email content.

---
## Workflow Demo


---
## Screenshot of Workflow

![Screenshot](./ClientIntake_research.png)




