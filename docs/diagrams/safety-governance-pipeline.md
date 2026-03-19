flowchart TD

A[Learner Input or Generated Content]
A --> B[Input Validation]

B --> C1[Content Safety Screening]
B --> C2[Developmental Appropriateness Check]
B --> C3[Linguistic Accuracy Review]

C1 --> D[Moderation Decision Layer]
C2 --> D
C3 --> D

D --> E1[Approve for Agent Processing]
D --> E2[Flag for Revision or Restriction]

E1 --> F[Agent Execution]
F --> G[Generated Instructional Output]

G --> H[Output Validation]

H --> I1[Safety Compliance Check]
H --> I2[Pedagogical Integrity Check]
H --> I3[Context Sensitivity Review]

I1 --> J[Final Governance Decision]
I2 --> J
I3 --> J

J --> K1[Deliver to Learner]
J --> K2[Escalate for Human Review]

K1 --> L[Audit Logging]
K2 --> L
