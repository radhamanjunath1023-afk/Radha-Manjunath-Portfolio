## Client Intake & Research Automation

Manually reviewing form submissions and researching clients is slow and inconsistent.

### Workflow Breakdown

```mermaid
graph TD
    Start([User submits Tally Form]) --> Webhook[n8n Webhook: Receive Data]
    Webhook --> Agent[AI Agent: Read Form Fields]
    
    Agent --> Research{Research Required?}
    
    Research -- Yes --> Serp[Google Search: SerpApi]
    Serp --> Analyze

    Research -- No --> Analyze[AI Analysis: VA Task & Context]

    Analyze --> Schema[(Structured Output Parser)]
    Schema --> Final[Fixed Clean Schema Results]
```

### Output 
A structured AI-generated result including client summary, research points, and ready-to-use email content.

---
## Workflow Demo


---
## Screenshot of Workflow

![Screenshot](./ClientIntake_research.png)




