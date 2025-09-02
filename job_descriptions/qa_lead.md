# QA Champion (or Principal QA)

## Role Summary: The Player-Coach

The **QA Champion (or Principal QA)** is a senior, hands-on quality expert who leads by example from within a squad. They are the technical quality reference within their product domain, combining the day-to-day responsibilities of a Product QA with the additional duties of technical oversight, mentorship, and innovation for their peers.

They are the quintessential "player-coach": a role model who not only directs from the sidelines but actively participates on the field. They demonstrate excellence through their own high-level execution while simultaneously raising the technical bar, resolving complex blockers, and ensuring methodological consistency for all Product QAs in their domain, acting as a quality multiplier.

## Core Role Mission: Technical Leader, Supervisor, and Expert Executor

The QA Champion is an expert QA with advanced capabilities, embedded in a squad, who **acts as a Product QA in their daily work.** They combine high-level practical execution with technical leadership and a cross-cutting view of all squads and Product QAs under their domain. They are the first line of technical leadership, responsible for translating the QA Manager's global strategy into effective, coherent, and high-quality execution on the ground, ensuring the vision materializes into tangible practices.

## Key Responsibility Areas

These are the domains where the QA Champion leads and excels.

<ol>
  <li><strong>Expert Execution as a Product QA</strong></li>
  
  Serves as a practical benchmark for excellence within their own squad.

  <ul>
    <li><strong>Assumes all responsibilities of a Product QA</strong> within their assigned squad, including quality definition, test automation, and release management. Their work sets the standard for others to follow in terms of quality, efficiency, and best practices, serving as a reference implementation that other QAs can consult and emulate.</li>
  </ul>
  
  <li><strong>Technical and Methodological Reference</strong></li>
  
  Acts as the foremost quality expert within their domain, providing guidance and unblocking their peers.

  <ul>
    <li><strong>Possesses a deep understanding</strong> of the product architecture, business logic, and technologies to propose and oversee sophisticated testing solutions. For example, they define <strong>complex integration tests</strong> (to be executed by Development), specifying critical flows and service touchpoints, and lead <strong>performance analyses</strong>, identifying bottlenecks and proposing improvements.</li>
    <li><strong>Serves as the primary technical consultant</strong> for other Product QAs, helping them solve complex automation challenges (like handling dynamic test data or interacting with tricky web elements) and navigate architectural hurdles that impact testability.</li>
  </ul>

  <li><strong>Innovation and Continuous Improvement</strong></li>
  
  Drives technical innovation from the ground up.

  <ul>
    <li><strong>Acts as the engine of technical evolution.</strong> They are responsible for researching, proposing, and leading the execution of <strong>proofs of concept (PoCs)</strong> for new tools, libraries, and methodologies. This involves not just testing the technology but also assessing its cultural fit and scalability within the existing ecosystem.</li>
    <li><strong>Presents viable PoCs</strong> to the QA Manager for strategic approval, providing data-driven arguments, such as comparative performance metrics, reduction in execution times, or improved bug detection, to justify the investment in their adoption.</li>
  </ul>

  <li><strong>Conflict Resolution and Cross-Cutting Vision</strong></li>
  
  Maintains a holistic view of quality across their domain and acts as the first point of contact for issues.

  <ul>
    <li><strong>Acts as the first point of contact</strong> for resolving the day-to-day technical or process conflicts of Product QAs, such as debates over the best automation strategy for a feature or discrepancies in interpreting an acceptance criterion.</li>
    <li><strong>Maintains a cross-cutting view</strong> of the status, performance, and challenges of all squads in their domain. This is achieved through dashboard supervision, report reviews, and maintaining continuous, fluid communication with their Product QA peers, detecting patterns or recurring problems that might go unnoticed at the single-team level.</li>
  </ul>

  <li><strong>Tactical Alignment and Strategic Communication</strong></li>
  
  Functions as the crucial link between on-the-ground execution and high-level strategy.

  <ul>
    <li><strong>Acts as the main liaison with the QA Manager.</strong> They are responsible for overseeing their own work and that of their team, reporting on it, proposing improvements from a technical perspective, and receiving strategic direction from the company, ensuring global decisions are understood and correctly applied.</li>
    <li><strong>Translates the QA Manager's strategic objectives</strong> (e.g., "reduce production failures by 15%") into tactical, actionable plans for the Product QAs in their domain (e.g., "implement a new layer of contract tests in service X").</li>
  </ul>

  <li><strong>Quality Assurance and Code Review</strong></li>
  
  Ensures the long-term health and scalability of the team's automated testing assets.

  <ul>
    <li><strong>Guarantees the health, consistency, and scalability</strong> of the automated test repository. Their Pull Request reviews focus not only on functionality but also on maintainability, test performance, and adherence to established design patterns.</li>
    <li><strong>Mentors other QAs</strong> through the code review process to improve their coding standards and architectural thinking, explaining the "why" behind each suggestion to foster deep learning.</li>
  </ul>
</ol>

## Specific Tasks and Activities

These are the concrete actions the QA Champion performs to fulfill their responsibilities.

### Early-Stage Participation:

<ul>
  <li><strong>As an active member of their own squad, they attend refinement and planning sessions</strong> to challenge requirements, ask "what if the external service fails?" or "how do we handle this edge case?", and ensure user stories are born "testable" with clear and unambiguous acceptance criteria.</li>
  <li><strong>Collaborates closely with their squad's Tech Lead</strong> to influence the technical design of solutions, promoting "testability" in the code from its inception, for example, by advocating for dependency injection or exposing test IDs in the frontend.</li>
</ul>

### Technical Leadership and Peer Supervision:

<ul>
  <li><strong>Mediates technical or process conflicts</strong> that may arise in the day-to-day work of Product QAs, facilitating a consensus-based solution before it needs to be escalated to the QA Manager.</li>
  <li><strong>Intervenes punctually in other squads within their domain</strong> to help redirect processes or solve complex problems, always in collaboration with and at the request of the corresponding Product QA, acting as a facilitator, not an imposing authority figure.</li>
  <li><strong>Leads code review sessions</strong> and pair testing with other Product QAs to share knowledge, unify standards, and solve complex problems together, turning challenges into learning opportunities for the entire team.</li>
  <li><strong>Supervises the health of CI/CD pipelines and dashboards</strong> in their domain, teaching their peers to interpret data—to not just see the "what" (a failed test) but to understand the "why" (the root cause) and act accordingly.</li>
  <li><strong>Reviews and approves QA Pull Requests (PRs)</strong> from other team members, providing constructive and actionable feedback to help raise the team's overall technical level.</li>
</ul>

### Communication and Reporting:

<ul>
  <li><strong>Participates in the follow-up sessions</strong> with the QA Manager to report on the status of their domain, propose PoCs, and receive strategic direction, providing a detailed and technical view of the teams' reality.</li>
  <li><strong>Consolidates quality reports from their domain,</strong> adding a layer of analysis and context to transform raw data (e.g., "85% green tests") into actionable information for the QA Manager (e.g., "the 15% of failures are concentrated in the payment flow; I suggest prioritizing its refactoring").</li>
  <li><strong>Coordinates cross-cutting quality initiatives,</strong> such as implementing E2E tests that span multiple services or teams within their domain, ensuring collaboration and proper integration between the parts.</li>
</ul>

## What We Expect from a QA Champion (or Principal QA)

<ul>
  <li><strong>Deep Technical Expertise:</strong> Mastery of test automation frameworks, programming languages, software design patterns, CI/CD pipelines, and modern QA methodologies. They must be able to solve the team's most challenging technical problems with autonomy and proficiency.</li>
  <li><strong>Leadership by Example:</strong> A "player-coach" mindset. They are in the trenches, demonstrating best practices through their own work and inspiring others to strive for the same level of excellence. Their credibility is born from their demonstrated technical competence.</li>
  <li><strong>Mentorship and Coaching Skills:</strong> a genuine passion for helping others grow. They are patient, empathetic, and capable of providing clear, constructive feedback to elevate their peers' skills, fostering their autonomy and confidence.</li>
  <li><strong>Proactive Problem-Solving:</strong> The ability to anticipate technical challenges, identify bottlenecks, and take the initiative to resolve them before they affect team velocity or product quality. They think in terms of prevention, not just reaction.</li>
  <li><strong>Strong Communication and Mediation Skills:</strong> The ability to clearly articulate complex technical concepts to different audiences (both technical and non-technical stakeholders) and to effectively mediate disagreements to find productive, consensus-based solutions.</li>
</ul>
