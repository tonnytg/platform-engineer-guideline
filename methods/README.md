# Methods for Platform Engineer

For platform engineers, a structured approach involving conversation, mapping, and applying tools can be highly effective. Here's a breakdown of the methods and techniques:

## Conversation (Discovery and Understanding)

Goal: Establish a clear understanding of the product's needs, developer pain points, and the business goals. This phase focuses on communication and collaboration.
Technique:
Stakeholder Interviews: Engage with developers, product managers, and operations teams to understand their challenges, workflows, and the tools they rely on.
Questionnaires & Surveys: Use structured questions to gather data on recurring issues, tool preferences, and friction points in the workflow.
Workshops: Conduct collaborative sessions where teams express their needs, allowing for real-time feedback.
Key Outcomes: Identification of pain points, desired outcomes, and an understanding of current tooling or gaps in the workflow.


## Approach (Framing and Strategy)
Goal: Once you have collected insights from the discovery phase, outline a strategy and set the technical direction.

Technique:

### Problem Framing:

Define the main problems to be solved, based on conversations. Map these problems to potential platform solutions.
Platform Roadmap: Develop a roadmap that outlines high-level goals, timelines, and key milestones for platform adoption or tool integration.
Priority Setting: Rank issues based on impact and effort, identifying quick wins and long-term investments.
Key Outcomes: A clear plan of action, prioritized based on user needs and business objectives.

Mapping (Design and Blueprint)
Goal: Design the architecture and workflows that will provide solutions to the identified challenges.

Technique:

### Technology Mapping:

Identify tools and technologies that can help solve the problems. For instance, using Kubernetes for orchestration, Terraform for infrastructure as code, or Jenkins for CI/CD pipelines.
Workflow Diagrams: Create flowcharts or diagrams to visualize how the platform and tools will integrate with current processes.
Capabilities Mapping: Align tools with their capabilities, mapping them to business needs. Ensure tools like Prometheus (monitoring) or Grafana (visualization) are matched with their use cases.
Key Outcomes: Well-documented architecture, toolchain, and workflows that will be implemented.

Application (Implementation and Feedback Loop)
Goal: Apply the chosen solutions, implementing them in a controlled environment with iterative feedback.

Technique:

### Pilot Projects:

Start with small, contained implementations or proof-of-concepts to validate the effectiveness of the solution before scaling.
Automation: Apply automation to reduce manual intervention (e.g., using Ansible or Chef for configuration management).
Monitoring & Observability: Implement monitoring systems (e.g., OpenTelemetry, Prometheus) to observe the impact of changes in real-time.
Feedback Loops: Continuously gather feedback from users post-deployment to improve the tools and workflows. Use regular retrospectives and metrics tracking to ensure the platform meets its goals.
Key Outcomes: A functional platform with developer adoption and ongoing improvements based on real-world feedback.

### Summary of the Process:

Conversation: Talk to users to understand pain points.
Approach: Strategize and prioritize based on insights.
Mapping: Design a technical blueprint with the right tools.
Application: Implement solutions with iterative feedback.
By following this process, platform engineers can effectively introduce tools and solutions that align with business needs while improving developer experience and efficiency.
