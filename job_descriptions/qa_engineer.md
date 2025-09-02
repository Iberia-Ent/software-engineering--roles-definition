# Product QA

## Role Summary: The Guardian of Quality

The **Product QA** is the facilitator and the conscience of quality, deeply embedded within a product squad. They act as the critical voice that constantly asks whether the proposed solution is robust, usable, and truly solves the user's problem. Their role is eminently practical but focuses on ensuring the quality of the entire development process, guaranteeing that all team members adhere to the defined standards. They work side-by-side with developers and the Product Owner to ensure requirements are well-defined and that the necessary tests to cover them are correctly implemented by the developers. Their main coding responsibility is the development and maintenance of End-to-End (E2E) test scripts, acting as the implementer and protector of the product's overall quality.

## Core Role Mission: Operational Quality Agent in the Squad

The Product QA is directly responsible for facilitating and ensuring quality in the daily work of a product squad. Their mission is to be the first and last line of defense for quality at the process and team strategy level; the first, by validating the clarity of requirements, and the last, by ensuring E2E tests cover critical flows before they reach the user. They are the implementer of the E2E testing strategy and the guardian of quality standards at every stage, ensuring each delivery meets the defined standards. They report functionally to the QA Champion of their domain, with whom they collaborate for technical growth and methodological alignment, while their operational dedication is 100% to their squad.

## Key Responsibility Areas

These are the domains where the Product QA's contributions are most critical.

<ol>
  <li><strong>Test Strategy and Planning</strong></li>
  
  Translates high-level objectives into concrete action plans at the sprint level.

  <ul>
    <li><strong>Defines and establishes a testing strategy for each sprint</strong> based on its scope, always aligned with the global strategy set by the QA Manager and the tactical guidance of the QA Champion. This involves analyzing the risks of each story (e.g., a change in the payment flow carries a much higher risk than a text change on a static page), deciding the balance between tests to be implemented by developers (unit, integration) and E2E tests, and planning the necessary regression to avoid unexpected side effects.</li>
  </ul>

  <li><strong>Defect Prevention (Static Testing)</strong></li>
  
  Identifies problems before they become code, saving valuable time and resources.

  <ul>
    <li><strong>Actively participates in requirements definition sessions</strong> with the PO and Business to perform an early assessment of user stories. Through the review of epics and user stories (static testing), they identify ambiguities, contradictions, hidden dependencies, and potential edge cases. Their goal is to reduce the cost of errors by ensuring quality is built-in from the idea's conception, not just as a final validation step.</li>
  </ul>

  <li><strong>Ensuring the Definition of Ready (DoR)</strong></li>
  
  Acts as the quality gatekeeper, ensuring stories are well-defined before development begins.

  <ul>
    <li><strong>Is responsible for determining when a story meets the Definition of Ready (DoR),</strong> ensuring it is complete, clear, and ready for technical refinement. By doing this, they protect the development team's time and focus, preventing the rework, inaccurate estimates, and frustration that arise from ambiguous or incomplete requirements.</li>
  </ul>

  <li><strong>Test Design and Supervision</strong></li>
  
  Designs the testing strategy and supervises its correct implementation by the development team.

  <ul>
    <li><strong>Creates detailed test cases in Xray</strong> that define what needs to be tested, serving as a quality "contract." They are responsible for ensuring the development team translates these cases into effective unit and integration tests. They supervise the results of the tests implemented by developers, act as a consultant for them when defining complex test cases, and perform exploratory testing in high-risk areas where their intuition and product knowledge are key.</li>
  </ul>

  <li><strong>E2E Test Automation</strong></li>
  
  Builds the automated safety net that allows the team to move fast and with confidence.

  <ul>
    <li><strong>Codes and maintains End-to-End (E2E) test scripts</strong> using the tools selected in the global strategy (e.g., WebdriverIO, Karate). This is their primary development task and is crucial for enabling continuous delivery, as these tests simulate real user journeys through the application, validating that the most important business flows (like registration, purchase, or search) work correctly from start to finish.</li>
  </ul>
</ol>

## Specific Tasks and Activities

These are the concrete actions the Product QA performs to fulfill their responsibilities.

### Definition Phase:

<ul>
  <li><strong>Actively participate in requirements definition sessions</strong> with the PO and Business, applying static testing techniques to assess the quality and integrity of stories and asking the tough questions early on to uncover unstated assumptions.</li>
  <li><strong>Validate and sign off on the Definition of Ready (DoR)</strong> for user stories, acting as a formal quality checkpoint before work moves to technical refinement, ensuring the "what" is clear before discussing the "how."</li>
  <li><strong>Create test cases</strong> for development and E2E in Xray, using Gherkin to ensure clarity. They link these cases directly to requirements, creating an auditable traceability matrix that proves the functionality is fully covered.</li>
  <li><strong>Collaborate on writing Acceptance Criteria</strong> that are clear, concise, unambiguous, and, above all, verifiable, leaving no room for interpretation and serving as a solid foundation for developers to implement their tests.</li>
  <li><strong>Design a lightweight and agile test plan</strong> for each feature, often documented as a checklist or comments within the ticket itself, focusing on efficiency and delivering maximum value with minimum effort.</li>
</ul>

### Construction Phase:

<ul>
  <li><strong>Code the scripts for E2E test cases</strong> in parallel with development, making this their main technical implementation task and ensuring automation coverage grows at the same pace as the product.</li>
  <li><strong>Supervise the implementation of tests</strong> by developers, often through pair-reviewing or consulting sessions, and perform focused <strong>exploratory testing,</strong> where they apply their product knowledge to investigate high-risk areas that automation might miss.</li>
  <li><strong>Foster a quality culture</strong> by participating in code reviews (PRs) to provide a quality-focused perspective. Their feedback helps validate that the implemented business logic aligns with the user story's intent and that the associated tests provide adequate coverage, collaborating with developers and Tech Leads to enhance overall quality.</li>
  <li><strong>Ensure the regression test suite</strong> (composed of developer tests and E2E tests) is up-to-date, reliable, and runs automatically with every change, acting as the primary owner of its health and effectiveness.</li>
</ul>

### Defect Management:

<ul>
  <li><strong>Detect, log, and document defects</strong> clearly and concisely. A good bug report includes a descriptive title, exact steps to reproduce, the expected vs. actual result, and supporting artifacts like screenshots, videos, or logs to minimize resolution time.</li>
  <li><strong>Perform the initial triage of defects</strong> with the Product Owner to prioritize them based on real business impact and technical urgency, ensuring the team focuses on what matters most and not on noise.</li>
  <li><strong>Track defects to their resolution</strong> and subsequent validation, verifying not only that the bug has been fixed but also that the solution has not introduced new regressions, thus closing the full defect lifecycle.</li>  
</ul>

### Integration and Deployment (CI/CD):

<ul>
  <li><strong>Integrate their automated E2E tests into the CI/CD pipeline,</strong> ensuring that every new piece of code is automatically validated against critical user flows.</li>
  <li><strong>Monitor and analyze the results of pipeline executions,</strong> being the first to react to a failure. They perform a quick initial diagnosis to distinguish between an infrastructure failure, a flaky test, or a real bug in the product, unblocking the team quickly.</li>  
</ul>

### Communication and Culture:

<ul>
  <li><strong>Act as the go-to person and ambassador for quality</strong> within the squad, promoting best practices, reminding the team of the importance of acceptance criteria in daily meetings, and celebrating quality wins in retrospectives.</li>
  <li><strong>Provide constant and constructive feedback</strong> to the team and showcase the tangible value of their work in demos, for example, by explaining how an automated test prevented a critical bug in production, making the ROI of quality visible.</li>
  <li><strong>Collect and share the squad's quality metrics</strong> with the QA Champion, providing the necessary context for the data to become useful, actionable information for continuous improvement.</li>  
</ul>

## What We Expect from a Product QA

<ul>
  <li><strong>Technical Competence:</strong> Solid practical skills in E2E test automation tools (e.g., WebdriverIO, Karate), test case management systems (e.g., Xray), and a deep understanding of the testing pyramid to guide and advise developers with credibility.</li>
  <li><strong>Meticulous Attention to Detail:</strong> A sharp, trained eye for identifying inconsistencies, ambiguities, and potential errors in both requirements and software, seeing what others might miss in the daily rush.</li>
  <li><strong>Collaborative and Coaching Mindset:</strong> The ability to work effectively and guide developers in implementing tests, not as a supervisor, but as a partner. This translates to sitting down with a developer to review the testing strategy for a new feature.</li>  
  <li><strong>Proactive and Inquisitive Attitude:</strong> a natural curiosity to ask "what if...?" and to proactively explore the system beyond the explicit requirements. They don't wait to be told what to test; they investigate APIs, check logs, and constantly think about how a user might "break" the application.</li>  
  <li><strong>Clear Communication Skills:</strong> The ability to articulate test plans, acceptance criteria, and defect reports in a clear, concise, and unambiguous way, adapting their language to ensure everyone on the team, technical or not, understands the quality strategy and status.</li>  
</ul>
