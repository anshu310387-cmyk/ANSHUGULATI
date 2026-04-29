 HR Tech System Builder · AI Automation · HRIS
 What This System Does
Transforms HR operations from manual processing to automated decision systems:
Routes grievances to the right team — under 1 second
Automates daily HR reporting — 700+ employees, zero manual work
Delivers real-time analytics across 6 departments
Eliminates repetitive HR admin at every touchpoint
 System Architecture
Employee Request
→ Google Form (Structured Intake)
→ n8n / Zapier (Pipeline Trigger)
→ Groq AI — LLaMA 3.3 (Classify · Route · Draft)
→ Google Sheets (Storage + Audit Log)
→ Gmail (Notification)
→ Dashboard (Real-time Insights)
 PeopleOS — AI-Powered HR Operations System
End-to-end HR automation system built for a fast-growing company whose HR team was
overwhelmed by manual operations.
peopleos-hr-operations/
├── workflows/
│    
│    
│    
├── grievance-workflow.json        
├── reporting-pipeline.json         Complete
 Complete
└── hr-policy-bot.json              In Progress
├── dashboards/
│    
├── grievance-dashboard.png
│    
└── department-dashboard.png
└── README.md
 Core System Modules
Each module targets a specific HR bottleneck — designed to work independently and as
part of the full system.
1 · Grievance & Query Intelligence
n8n Zapier Groq AI Google Sheets Gmail
Classifies grievance type automatically — Payroll, IT, HR
Routes to correct team in under 1 second
Logs full audit trail in Google Sheets
Sends employee tracking confirmation instantly
HR Policy Bot answers policy queries via AI — no human needed
Result: 12 min → under 1 sec · 100% accuracy · 75% less manual effort
2 · Automated Reporting Pipeline
n8n Groq AI Google Sheets Gmail JavaScript
Triggers daily at 10 AM — zero human involvement
Pulls live data across 700+ employees automatically
Processes onboarding, grievance, and department metrics
Generates visual HTML dashboard with AI summary
Delivers to director via email — runs every day without fail
Result: 6 departments · fully automated · zero manual work
3 · Workforce Tracking System
Lovable No-Code Live Production
Separate structured flow per workforce type — Regular, Client Visit, Remote
Clean data capture replacing messy Excel tracking
Deployed and active in production today
 Live App → track-happy-hours.lovable.app
 Analytics Dashboard
Metric Result
Grievances Tracked 340+
Employees in System 700+
Avg Routing Time < 1 second
Departments Operations · HR · Risk · Sales · IT · Finance
 Impact
Before After
Manual routing — 12 min/case Automated — < 1 second
87% routing accuracy 100% accuracy
8 hrs/week HR admin 2 hrs/week — 75% reduction
15% SLA breach rate < 5% breach rate
Manual daily reporting Fully automated pipeline
Manual policy responses AI-generated instant replies
 Business Value
Removes human dependency from repetitive HR decisions
Gives leadership real-time visibility without manual effort
Improves accuracy and response speed at every touchpoint
Scales HR operations without adding headcount
 My Contribution
Architected the Grievance & Query Intelligence module end-to-end
Designed the HR Policy Bot — AI-powered instant response system
Implemented real-time analytics dashboard tracking 340+ cases
Delivered fully automated daily reporting pipeline
Deployed live Workforce Tracking app in production
Built Zapier HR query automation workflow
 Live Proof
Production attendance tracking app — deployed and active
Live grievance intake system — accepting real submissions
Automated reporting pipeline — running daily without intervention
 Tech Stack
Automation: n8n · Zapier
AI / LLM: Groq API · LLaMA 3.3 70B · Claude AI
No-Code: Lovable
Data: Google Sheets · Google Forms · Google Drive
Notifications: Gmail · WhatsApp Business (in progress)
HRIS: Workday HCM · SAP SuccessFactors
 Currently
 Completing HR Policy Bot — WhatsApp Business API integration
 GenAI Bootcamp — AI systems for HR professionals
 Open to HRIS Analyst · HR Tech · People Analytics roles
<div align="center">
“HR technology should free people to do human work. Everything else should run itself.”
LinkedIn · 
Live App
</div>