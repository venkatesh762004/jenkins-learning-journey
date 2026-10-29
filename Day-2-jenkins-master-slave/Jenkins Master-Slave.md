📘 Jenkins Master-Slave (Controller-Agent) Architecture
🚀 What is Jenkins?
Jenkins is an open-source automation server used to implement CI/CD pipelines.

It helps to:

Build applications
Run tests
Deploy code automatically
🧠 Jenkins Architecture
Jenkins follows a Master-Slave architecture (now called Controller-Agent).

🔹 Components
1️⃣ Master (Controller)
The Master is the main Jenkins server.

Responsibilities:

Manage pipelines (jobs)
Schedule builds
Monitor execution
Assign jobs to agents
Provide UI (dashboard)
2️⃣ Slave (Agent)
The Slave (Agent) is a worker machine.

Responsibilities:

Execute build jobs
Run scripts and commands
Handle workload from master
👉 Agents can be:

Linux machines
Windows machines
Cloud instances (AWS EC2, etc.)
🔄 How It Works
Developer Push Code
        ↓
   Jenkins Master
        ↓
 Assign Job to Agent
        ↓
   Agent Executes Job
        ↓
   Send Result to Master
        ↓
   Display in Dashboard