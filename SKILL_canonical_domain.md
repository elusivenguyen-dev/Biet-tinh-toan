---
name: canonical-domain
version: 1.0.0
category: Enterprise Architecture
status: Canonical
maturity: Enterprise-grade
language: vi-VN
scope: Multi-domain enterprise modeling
primary_output: Canonical Domain Model
---

# CANONICAL DOMAIN SKILL
## Thiết kế, chuẩn hóa và vận hành một domain chuẩn trong EnterpriseOS / UESM

## 1. Purpose

Skill này dùng để biến một chủ đề, chức năng, capability, hệ thống hoặc lĩnh vực nghiệp vụ thành một **Canonical Domain** có thể:

- được con người hiểu và quản trị;
- được biểu diễn bằng ontology và knowledge graph;
- được kích hoạt bằng runtime;
- được đo lường, kiểm soát và audit;
- được tích hợp vào OrgOS, EnterpriseOS và UESM;
- được mở rộng thành Digital Twin và AI-Agent Governance;
- học hỏi, tiến hóa và duy trì continuity.

Skill không chỉ tạo taxonomy hoặc tài liệu mô tả. Nó tạo một domain có cấu trúc chuẩn, boundary rõ, object chuẩn, relationship chuẩn, lifecycle rõ, governance rõ và khả năng thực thi.

---

# 2. Core Definition

```text
CANONICAL DOMAIN
=
Purpose
× Boundary
× Ontology
× Objects
× Relationships
× States
× Events
× Rules
× Decisions
× Workflows
× Evidence
× Measurements
× Governance
× Runtime
× Knowledge
× Learning
× Evolution
× Continuity
```

Nói ngắn:

```text
Canonical Domain
=
một miền doanh nghiệp được định nghĩa thống nhất,
có thể đọc, vận hành, kiểm soát, đo lường,
tích hợp, mô phỏng, học và tiến hóa.
```

---

# 3. When to Use

Kích hoạt skill khi người dùng yêu cầu:

- chuẩn hóa một domain;
- xây domain model;
- thiết kế capability domain;
- hợp nhất nhiều framework cùng chủ đề;
- xây ontology hoặc knowledge graph;
- chuyển một framework thành operating system;
- thiết kế runtime, register, governance hoặc maturity model;
- tích hợp domain vào OrgOS, EnterpriseOS hoặc UESM;
- xây domain-ready cho AI, Digital Twin, automation hoặc audit;
- xác định canonical objects, relationships, events, states, rules và outputs.

Ví dụ domain:

```text
Organization
Strategy
Governance
Capital
Capability
Decision
Process
Execution
Evidence
Measurement
Risk
Knowledge
Learning
Evolution
Continuity
Customer
Finance
Technology
Data
M&A
Market Intelligence
```

---

# 4. Do Not Use As

Không dùng skill này như:

- danh sách thuật ngữ đơn thuần;
- sơ đồ phòng ban;
- SOP đơn lẻ;
- checklist không có meta-model;
- framework chỉ để tham khảo;
- bản mô tả hiện trạng không có target model;
- dashboard tách rời evidence và decision;
- knowledge base không có governance và lifecycle.

---

# 5. Canonical Domain Position

```text
EnterpriseOS
│
├── Enterprise Meta-Model
├── Shared Platform Services
├── Cross-Cutting Layers
│
├── Canonical Domains
│   ├── Strategy Domain
│   ├── Governance Domain
│   ├── Capital Domain
│   ├── Capability Domain
│   ├── Organization Domain
│   ├── Decision Domain
│   ├── Process Domain
│   ├── Execution Domain
│   ├── Evidence Domain
│   ├── Measurement Domain
│   ├── Learning Domain
│   └── Continuity Domain
│
└── Domain Runtimes
```

Một Canonical Domain là **đơn vị kiến trúc chuẩn** nằm giữa Enterprise Meta-Model và các runtime thực thi.

---

# 6. Five First Principles

```text
EXIST
↓
UNDERSTAND
↓
CREATE
↓
COORDINATE
↓
CONTINUE
```

## 6.1 EXIST

Xác định domain tồn tại vì sao, boundary ở đâu và các object nào thật sự tồn tại.

## 6.2 UNDERSTAND

Hiểu cấu trúc, cơ chế, flow, power, governance, incentives và de facto reality của domain.

## 6.3 CREATE

Thiết kế target model, canonical objects, policies, workflows, runtime và outputs.

## 6.4 COORDINATE

Liên kết domain với các domain khác bằng interfaces, events, APIs, evidence và decision rights.

## 6.5 CONTINUE

Bảo đảm domain có lifecycle, versioning, institutional memory, learning, evolution và continuity.

---

# 7. Universal Domain Lifecycle

```text
Purpose
↓
Question
↓
Reality
↓
Evidence
↓
Diagnosis
↓
Boundary
↓
Ontology
↓
Model
↓
Design
↓
Governance
↓
Runtime
↓
Execution
↓
Observability
↓
Measurement
↓
Learning
↓
Adaptation
↓
Evolution
↓
Continuity
```

---

# 8. Canonical Domain Architecture

## L00 — Domain Purpose

### Core question

```text
Why does this domain exist?
```

### Required outputs

- Domain Purpose
- Value Contribution
- Stakeholder Outcomes
- Constitutional Principles
- Non-negotiable Boundaries
- Success Definition

---

## L01 — Domain Boundary

### Core questions

```text
What is inside?
What is outside?
Where are the interfaces?
What belongs to adjacent domains?
```

### Required outputs

- Domain Boundary Map
- In-Scope / Out-of-Scope
- Context Map
- Dependency Map
- Interface Catalogue

---

## L02 — Domain Reality

### Core questions

```text
What actually exists?
What is formally defined?
What is de facto operating?
What is missing, hidden or uncertain?
```

### Required outputs

- Current-State Baseline
- Formal vs Actual Map
- Constraint Register
- Assumption Register
- Unknowns Register
- Failure and Bottleneck Map

---

## L03 — Domain Ontology

### Core question

```text
What kinds of things exist in this domain?
```

### Required outputs

- Entity Classes
- Object Types
- Attributes
- Relationship Types
- Event Types
- State Types
- Rule Types
- Evidence Types
- Metric Types

---

## L04 — Canonical Object Model

Mỗi object phải có:

```text
Object ID
Object Type
Name
Purpose
Owner
Authority
State
Lifecycle
Attributes
Relationships
Inputs
Outputs
Rules
Events
Evidence
Measurements
Risks
Controls
Version
Continuity Requirement
```

### Minimum object categories

```text
Purpose Object
Actor Object
Capability Object
Organization Object
Decision Object
Policy Object
Process Object
Workflow Object
Task Object
Evidence Object
Metric Object
Risk Object
Control Object
Knowledge Object
Technology Object
Change Object
```

---

## L05 — Relationship Model

### Required relationship classes

```text
Drives
Requires
Owns
Performs
Authorizes
Approves
Controls
Depends On
Inputs To
Outputs To
Generates
Measures
Evidences
Escalates To
Learns From
Supersedes
Continues
```

### Relationship rule

Mọi object critical phải được nối với:

```text
Purpose
Owner
Authority
Workflow
Evidence
Measurement
Lifecycle
```

---

## L06 — State Model

```text
Proposed
↓
Draft
↓
Designed
↓
Validated
↓
Approved
↓
Active
↓
Observed
↓
Measured
↓
Improved
↓
Deprecated
↓
Archived
```

Mỗi state transition phải có:

- trigger;
- authorized actor;
- rule;
- evidence;
- timestamp;
- version;
- exception path.

---

## L07 — Event Model

### Universal event types

```text
Created
Changed
Assigned
Approved
Rejected
Activated
Executed
Measured
Threshold Breached
Risk Triggered
Control Failed
Evidence Missing
Escalated
Reviewed
Improved
Deprecated
Archived
```

### Event requirements

```text
Event ID
Source
Timestamp
Actor
Object
Previous State
New State
Rule Applied
Evidence
Outcome
```

---

## L08 — Governance Model

```text
Domain Governance
=
Purpose
× Authority
× Decision Rights
× Accountability
× Policy
× Control
× Evidence
× Review
× Escalation
× Assurance
```

### Required governance outputs

- Domain Charter
- Decision Catalogue
- Reserved Matters
- Delegation of Authority
- Policy Hierarchy
- Control Framework
- Review Cadence
- Escalation Matrix
- Assurance Model

---

## L09 — Capability Model

```text
Capability
=
Knowledge
× Skill
× Method
× Tool
× Judgment
× Evidence
× Practice
× Learning
```

### Required outputs

- Capability Map
- Capability Owner
- Maturity Level
- Capability Gap
- Dependency Map
- Investment Requirement
- Capability KPI
- Continuity Requirement

---

## L10 — Flow Model

Mỗi domain phải xác định các flow chính:

```text
Information Flow
Decision Flow
Authority Flow
Resource Flow
Work Flow
Evidence Flow
Risk Flow
Knowledge Flow
Value Flow
Learning Flow
Continuity Flow
```

### Flow diagnostic

```text
Trace the flow
Locate bottlenecks
Detect leakage
Identify controller
Measure delay
Detect distortion
Redesign path
```

---

## L11 — Process and Workflow Model

```text
Trigger
→ Input
→ Decision
→ Activity
→ Control
→ Output
→ Evidence
→ Measurement
→ Exception
→ Learning
```

Mỗi workflow phải có:

- Workflow ID
- Purpose
- Trigger
- Owner
- Participants
- Decision nodes
- Inputs
- Steps
- Outputs
- Controls
- Evidence
- SLA
- Exceptions
- Escalation
- Metrics
- Version

---

## L12 — Runtime Model

```text
Domain Runtime
=
Objects
× States
× Events
× Rules
× Decisions
× Workflows
× Evidence
× Measurements
× Feedback
```

### Runtime services

```text
Create
Read
Update
Approve
Reject
Assign
Authorize
Execute
Measure
Escalate
Audit
Learn
Simulate
Retire
Archive
```

---

## L13 — Evidence Model

```text
Evidence
=
Proof of Reality
+ Proof of Decision
+ Proof of Execution
+ Proof of Control
+ Proof of Outcome
```

### Evidence requirements

- Evidence ID
- Source
- Owner
- Object Link
- Event Link
- Timestamp
- Integrity Status
- Retention Rule
- Access Rule
- Audit Status

---

## L14 — Measurement and Index Model

```text
Reality
→ Variable
→ Metric
→ Measurement
→ Index
→ Interpretation
→ Decision
```

### Required outputs

- KPI Register
- KRI Register
- KQI Register
- Index Architecture
- Thresholds
- Alerts
- Decision Rules
- Dashboard

---

## L15 — Risk and Control Model

```text
Risk
→ Cause
→ Event
→ Impact
→ Control
→ Evidence
→ Residual Risk
→ Decision
```

### Required outputs

- Risk Register
- Control Register
- Failure Modes
- Control Owner
- Control Frequency
- Evidence Requirement
- Residual Risk
- Escalation Rule

---

## L16 — Knowledge Model

```text
Evidence
→ Information
→ Insight
→ Knowledge
→ Standard
→ Practice
→ Capability
→ Institutional Memory
```

### Required outputs

- Knowledge Taxonomy
- Knowledge Assets
- Playbooks
- SOP Repository
- Lessons Learned
- Decision Memory
- Pattern Library
- Version History

---

## L17 — Observability Model

Domain phải quan sát được:

```text
State
Events
Performance
Risk
Control
Evidence
Capacity
Bottleneck
Exception
Change
Learning
Continuity
```

### Required outputs

- Domain Dashboard
- Event Log
- State View
- Alert System
- Exception Queue
- Audit Trail
- Health Score

---

## L18 — Learning Model

```text
Outcome
→ Variance
→ Root Cause
→ Lesson
→ Change Request
→ Pilot
→ Adoption
→ Standard Update
```

### Required outputs

- Lessons-Learned Register
- Improvement Backlog
- Root-Cause Library
- Adaptation Portfolio
- Adoption Evidence

---

## L19 — Evolution Model

### Core questions

```text
What is becoming obsolete?
What new capability is required?
What should be redesigned, replaced or retired?
```

### Required outputs

- Evolution Hypotheses
- Target Architecture
- Architecture Versions
- Retirement Decisions
- Evolution Roadmap
- Optionality Map

---

## L20 — Continuity Model

```text
Continuity
=
Critical Role
× Backup
× Successor
× Knowledge Asset
× Recovery Plan
× Transferability
× Institutional Memory
```

### Required outputs

- Critical Object Register
- Succession Register
- Backup Coverage
- Recovery Procedures
- Knowledge Transfer Plan
- Continuity Readiness Index

---

# 9. Cross-Cutting Platform Layers

Mọi Canonical Domain phải tích hợp bốn lớp xuyên suốt:

```text
Information & Data
Risk & Control
Technology & AI
Observability
```

Và sáu foundation mở rộng:

```text
Culture & Trust
Resource
Change & Transformation
Evidence
Measurement
Meta-Governance
```

---

# 10. Canonical Domain Deliverables

## Minimum viable domain pack

```text
01 Domain Charter
02 Domain Boundary Map
03 Current-State Baseline
04 Domain Ontology
05 Canonical Object Register
06 Relationship Catalogue
07 State and Event Model
08 Governance Architecture
09 Capability Map
10 Flow Map
11 Process and Workflow Register
12 Evidence Register
13 KPI/KRI/KQI Register
14 Risk and Control Register
15 Runtime Specification
16 Knowledge Repository Structure
17 Learning Register
18 Evolution Roadmap
19 Continuity Architecture
20 Domain Integration Map
```

## Enterprise-grade domain pack

Bổ sung:

```text
Knowledge Graph Schema
Executable Runtime Specification
API and Event Contracts
Digital Twin Model
AI-Agent Roles
Simulation Scenarios
Continuous Assurance Rules
Maturity and Scoring Model
Quality Gates
Version Governance
```

---

# 11. Standard Registers

```text
Domain_Register
Object_Register
Relationship_Register
State_Register
Event_Register
Rule_Register
Decision_Register
Policy_Register
Capability_Register
Flow_Register
Process_Register
Workflow_Register
Interface_Register
Evidence_Register
Metric_Register
Index_Register
Risk_Register
Control_Register
Knowledge_Register
Change_Register
Learning_Register
Evolution_Register
Continuity_Register
```

---

# 12. Canonical Domain Repository

```text
canonical-domain/
│
├── skill.md
├── 00-purpose/
├── 01-boundary/
├── 02-reality/
├── 03-ontology/
├── 04-objects/
├── 05-relationships/
├── 06-states/
├── 07-events/
├── 08-rules/
├── 09-governance/
├── 10-capability/
├── 11-flows/
├── 12-processes/
├── 13-workflows/
├── 14-runtime/
├── 15-evidence/
├── 16-measurement/
├── 17-risk-controls/
├── 18-knowledge/
├── 19-observability/
├── 20-learning/
├── 21-evolution/
├── 22-continuity/
├── knowledge-graph/
├── digital-twin/
├── ai-agents/
├── simulations/
├── templates/
├── registers/
├── dashboards/
├── quality-gates/
└── examples/
```

---

# 13. Quality Gates

## Gate 1 — Purpose Integrity

- Purpose rõ.
- Stakeholder value rõ.
- Boundary đạo đức và pháp lý rõ.

## Gate 2 — Boundary Integrity

- Không overlap mơ hồ với adjacent domains.
- Có interface owner.
- Có dependency map.

## Gate 3 — Ontology Integrity

- Object classes không trùng nghĩa.
- Relationship types có hướng và semantics rõ.
- State, event và rule tách biệt.

## Gate 4 — Governance Integrity

- Mỗi decision có một final owner.
- Authority tương xứng accountability.
- Reserved matters và delegation không xung đột.

## Gate 5 — Runtime Readiness

Mỗi object critical có:

```text
Owner
State
Trigger
Rule
Workflow
Evidence
Metric
Escalation
```

## Gate 6 — Evidence Integrity

- Evidence truy vết được.
- Source rõ.
- Retention và access rõ.
- Có audit trail.

## Gate 7 — Measurement Integrity

- Metric gắn với decision.
- Threshold rõ.
- Index không thay thế metric gốc.
- Dashboard dẫn tới hành động.

## Gate 8 — Learning Integrity

- Variance dẫn tới root cause.
- Lesson dẫn tới change.
- Change có adoption evidence.

## Gate 9 — Evolution Integrity

- Có version architecture.
- Có retirement rule.
- Có target-state roadmap.

## Gate 10 — Continuity Integrity

- Critical role có backup.
- Critical knowledge được chuyển giao.
- Domain không phụ thuộc một cá nhân.

---

# 14. Maturity Model

```text
M0 — Undefined
M1 — Documented
M2 — Standardized
M3 — Governed
M4 — Executable
M5 — Observable
M6 — Integrated
M7 — Intelligent
M8 — Simulatable
M9 — Adaptive
M10 — Self-Evolving and Continuity-Ready
```

## M0 — Undefined

Domain tồn tại bằng kinh nghiệm và cá nhân.

## M1 — Documented

Có tài liệu nhưng chưa có canonical model.

## M2 — Standardized

Có object, register, process và terminology chuẩn.

## M3 — Governed

Có owner, authority, policy, control và review.

## M4 — Executable

Có runtime, state, event, workflow và evidence.

## M5 — Observable

Có dashboard, logs, alerts và audit trail.

## M6 — Integrated

Domain liên kết với adjacent domains và EnterpriseOS.

## M7 — Intelligent

Có analytical models, recommendations và AI support.

## M8 — Simulatable

Có Digital Twin và scenario simulation.

## M9 — Adaptive

Runtime tự điều chỉnh trong governance boundaries.

## M10 — Self-Evolving

Domain có meta-governance, controlled evolution và continuity.

---

# 15. Scoring Model

Thang điểm 0–5:

```text
0 = không tồn tại
1 = ad hoc
2 = documented
3 = controlled
4 = integrated and evidence-driven
5 = executable, observable, adaptive and continuity-ready
```

## Score dimensions

```text
Purpose and Boundary          8%
Ontology and Objects         10%
Relationships and Integration 8%
Governance                   10%
Capability                    8%
Flow and Process              8%
Runtime                      10%
Evidence                      8%
Measurement                   8%
Risk and Control              6%
Knowledge and Learning        6%
Technology and AI             4%
Evolution                     3%
Continuity                    3%
Total                       100%
```

---

# 16. Failure Modes

## Structural failures

```text
Undefined boundary
Duplicate object types
Disconnected registers
Unowned capability
Broken interfaces
```

## Governance failures

```text
Multiple final decision owners
Authority without accountability
Accountability without authority
Policy without enforcement
Control without evidence
```

## Runtime failures

```text
Design not activated
State changes not logged
Workflow bypass
Exceptions unmanaged
Evidence missing
```

## Measurement failures

```text
Vanity metrics
Index without source metrics
Threshold without decision rule
Dashboard without owner
```

## Learning failures

```text
Lessons not institutionalized
Change without adoption
Repeated failure without root cause
Version drift
```

## Continuity failures

```text
Founder dependency
Critical-role dependency
Knowledge trapped in individuals
No successor
No recovery plan
```

---

# 17. De Facto Validation

Skill phải luôn so sánh:

```text
Formal Domain
vs
Actual Domain
```

Bắt buộc kiểm tra:

- quyền chính thức khác quyền thật ở đâu;
- policy nào bị bypass;
- actor nào kiểm soát thông tin hoặc nguồn lực;
- incentive nào tạo hành vi lệch;
- workflow nào chỉ tồn tại trên giấy;
- evidence nào không phản ánh reality;
- knowledge nào nằm trong cá nhân;
- rule ngầm nào đang tái tạo kết quả.

---

# 18. AI-Agent Architecture

## Core agents

```text
Domain Architect
Ontology Curator
Governance Advisor
Runtime Orchestrator
Evidence Auditor
Measurement Analyst
Risk Sentinel
Knowledge Curator
Evolution Advisor
Continuity Steward
```

## Agent constraints

Mỗi agent phải có:

```text
Purpose
Scope
Allowed Objects
Allowed Actions
Required Evidence
Approval Boundary
Escalation Rule
Audit Log
Human Override
```

AI không được tự thay đổi canonical ontology, governance policy hoặc reserved matter nếu chưa có phê duyệt hợp lệ.

---

# 19. Digital Twin Requirements

Domain Digital Twin phải mô phỏng được:

- object state;
- event propagation;
- flow performance;
- decision delay;
- capacity;
- risk exposure;
- control effectiveness;
- policy change;
- capability investment;
- failure scenarios;
- continuity disruption.

---

# 20. Response Protocol

Khi áp dụng skill, phản hồi nên theo cấu trúc:

```text
1. Domain Mandate
2. Core Definition
3. Boundary
4. Current Reality
5. Canonical Ontology
6. Object Model
7. Relationship Model
8. Governance
9. Capability
10. Flow
11. Process and Runtime
12. Evidence
13. Measurement
14. Risk and Control
15. Knowledge and Learning
16. Evolution
17. Continuity
18. Registers
19. Quality Gates
20. Roadmap
```

Không bắt buộc trình bày toàn bộ nếu yêu cầu hẹp, nhưng phải giữ traceability về canonical model.

---

# 21. Output Modes

## Mode A — Quick Map

Dùng khi người dùng cần overview.

Output:

- definition;
- boundary;
- 10–15 layers;
- core objects;
- master runtime;
- key outputs.

## Mode B — Diagnostic

Dùng khi cần phân tích hiện trạng.

Output:

- formal vs actual;
- gaps;
- bottlenecks;
- failure modes;
- maturity score;
- priority actions.

## Mode C — Full Design

Dùng khi xây domain mới.

Output:

- full architecture;
- ontology;
- registers;
- governance;
- runtime;
- evidence;
- metrics;
- roadmap.

## Mode D — Runtime Build

Dùng khi chuyển model thành executable system.

Output:

- state model;
- event model;
- rules;
- workflows;
- APIs;
- evidence contracts;
- observability;
- agent roles.

## Mode E — UESM Integration

Dùng khi tích hợp domain vào EnterpriseOS.

Output:

- upstream/downstream relationships;
- shared objects;
- domain boundaries;
- cross-domain events;
- shared services;
- enterprise traceability.

---

# 22. Domain Integration Contract

Mỗi Canonical Domain phải công bố:

```text
Domain ID
Domain Name
Purpose
Boundary
Owner
Upstream Domains
Downstream Domains
Shared Objects
Consumed Events
Published Events
Input Contracts
Output Contracts
Evidence Contracts
Decision Contracts
Data Contracts
Service Contracts
Risk Dependencies
Continuity Dependencies
```

---

# 23. Canonical Naming Rules

- Dùng danh từ số ít cho object type: `Role`, không dùng `Roles`.
- Tên object phải có nghĩa ổn định xuyên domain.
- Phân biệt rõ `Capability`, `Process`, `Role`, `Decision`, `Policy`.
- Không dùng `Management`, `Governance`, `Operation` thay thế lẫn nhau.
- Phân biệt:

```text
Ownership ≠ Governance
Governance ≠ Management
Management ≠ Operations
Control ≠ Approval
Reporting ≠ Accountability
Activity ≠ Outcome
Metric ≠ Index
Design ≠ Runtime
Domain ≠ Department
```

---

# 24. Canonical Traceability Chain

Mọi domain phải truy vết được:

```text
Purpose
→ Outcome
→ Capability
→ Owner
→ Decision
→ Process
→ Workflow
→ Evidence
→ Metric
→ Risk
→ Control
→ Learning
→ Evolution
→ Continuity
```

Đây là điều kiện tối thiểu để một domain được xem là canonical.

---

# 25. Completion Criteria

Một Canonical Domain được xem là hoàn chỉnh khi:

- boundary không mơ hồ;
- ontology thống nhất;
- object có định danh và owner;
- relationship truy vết được;
- decision rights rõ;
- runtime có state, event, rule và workflow;
- evidence chứng minh được reality;
- measurement dẫn tới decision;
- risk và control được tích hợp;
- knowledge được thể chế hóa;
- learning dẫn tới change;
- evolution có governance;
- continuity không phụ thuộc cá nhân;
- domain tích hợp được với EnterpriseOS;
- con người, hệ thống và AI có thể cùng đọc và vận hành.

---

# 26. Final Equation

```text
CANONICAL DOMAIN
=
Understandable
× Governable
× Executable
× Observable
× Measurable
× Auditable
× Integrable
× Learnable
× Evolvable
× Transferable
× Continuity-Ready
```

Một domain thiếu một trong các thuộc tính trên có thể vẫn tồn tại như tài liệu hoặc chức năng, nhưng chưa đạt trạng thái **Canonical Enterprise Domain**.
