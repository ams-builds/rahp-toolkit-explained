# Jargon Buster

Simple explanations of the technical words in this project. The README does not use these terms where possible. This file gives the exact words for persons who want them. Many definitions come from the RAHP glossary in the source repository (`method/glossary/terms/`).

**Agent**
An AI system that does tasks for a person or an organization.

**Claim**
A statement that must be correct for the system to be safe. RAHP calls this a "proposition".

**Consequential action**
An action that can have a large effect on rights, money, access, safety, authority, privacy, or an external system.

**Control**
A measure that decreases, finds, contains, or repairs a risk. Example: a check of the status immediately before the system approves a payment.

**Control plane**
The place where a correction goes. Examples are the specification, the code, a test, an operator control, governance, and the user experience. RAHP selects one primary control plane for each finding.

**Evidence**
Information that supports or does not support a claim, a decision, or a finding. In RAHP, evidence must come from a real source. An opinion of an AI is not evidence.

**Fail-closed**
To stop a consequential action when a necessary safety condition is not known. Example: if the system cannot get the current status, it stops the high-risk action.

**Finding**
A specific problem that a review found. A finding needs attention or a recorded decision.

**Governance**
The rules about who has authority, who makes decisions, and who is responsible.

**Guardrail**
A rule that blocks or stops an unacceptable condition. A guardrail is stronger than usual guidance. Example: do not let a consequential action continue if the system cannot find current authority.

**Harm**
A bad effect on a person, a group, an organization, or the public. RAHP has 24 harm patterns in eight groups. Examples are manipulation, wrongful exclusion, unnecessary disclosure, and unauthorized consequential action.

**INDETERMINATE**
The RAHP result when the evidence cannot give a safe answer. This repository calls it NOT SURE.

**Mandate**
The purpose and the limits of the work that an agent does for a person. Example: an agent can compare travel options but cannot buy one without approval.

**Persona**
A role that a person or a system has. Examples are the person that the system serves, the operator of an agent, and the person that makes a decision from the evidence. RAHP uses personas to find who gets the harm and who has the power.

**Principal**
The person or organization that an agent works for.

**Provenance**
Information about the source of an item, an action, or a decision, and how it changed over time.

**RAHP**
Risk Assessment and Harms Prevention. A method that tells you if a system deserves trust. It starts with persons and harms, and it ends with evidence and actions.

**Reassessment**
A new review after a change to the system, the evidence, or the conditions of use. RAHP examines only the parts that the change has an effect on, if possible.

**Redress**
A process that corrects a harmful or incorrect result. Example: a person who was wrongly excluded can appeal and get access again.

**Residual risk**
The risk that remains after the controls and guardrails are in place.

**Specification**
A document that gives the requirements of a system. The specification tells other persons how the system must operate.
