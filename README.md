 ResolveProof

**Verify the Reality. Not Just the Status.

ResolveProof is an AI-powered civic verification tool which verifies, after a department has marked a civic complaint as resolved, whether the complaint was resolved or not. The aim is to help resolve the disconnect between the official complaint status and the actual situation.

Problem Statement :

In some cases, a complaint may be noted as solved in a formal system, but in fact the issue remains unsolved. A nearby school and an exposed electrical wire, for instance, could still be a hazard even if the complaint status shifts to resolved. This results in a lack of trust and makes it harder for citizens to be sure that their complaints have been heard.

Our Solution :

ResolveProof offers an independent verification process based on community feedback, photo evidence, AI-assisted analysis and civic risk assessment. Rather than depending merely on an official status update, it assesses available evidence to figure out whether or not the reported challenge seems to have been resolved.

Citizens in the vicinity who have chosen to opt-in can reply YES, NO or CAN'T TELL and include supporting photographs. The system assesses the evidence and returns a Verification Result. ResolveProof can create an evidence based escalation report if a resolution is contested or the presence of a serious hazard is detected.

How It Works :

- Citizen raises civic concern.
- The department works on the complaint and marks it as resolved.
- ResolveProof starts an independent verification process.
Local residents offer comments and send in photographs.
Evidence is assessed using AI-assisted checks and consensus by the community.
Evidence and risk are used to produce a verification result from the system.
An escalation can be created if needed to take further action.
It restarts re-verification after the problem is solved.

The possible outcomes are: Verified Resolved, Insufficient Evidence, Resolution Challenged or Critical Escalation. The outcomes enable people to differentiate between the certainty of resolution and uncertainty, potential unresolved issues, and serious hazards.

Technology Used :

ResolveProof technology stack is planned as:

React / Next.js - Frontend.
- Python and FastAPI to create APIs in the backend.
- PostgreSQL database for storing complaint and verification information.
Gemma 4 API for AI-driven evidence summaries and structured reports.
- Computer Vision to detect duplicates and relevance of images.
- Custom verification and risk logic for analyzing evidence and prioritizing civic issues.
TinyFish for communicating with supported external or simulated grievance portals during escalation.

Gemma 4 enables evidence analysis and report generation whereas ResolveProof does the verification rules and decision process. TinyFish is not the decision making process, but rather an external layer of web interactions.

Example :

Suppose someone notifies the police of a bare wire in the vicinity of a school. The department deems the complaint resolved, but the neighbors say the wire is still out there and they've got pictures. ResolveProof assesses all the evidence and the risk of potential safety. If there is evidence that supports an unresolved critical hazard, the case can be flagged for escalation. Once the wire has been repaired the problem is checked once more.

Vision :

We aim to improve civic complaint resolution in ways that are transparent, trustworthy and evidence-based. ResolveProof is not intended as a substitution for existing government complaint systems. It, on the other hand, introduces an independent layer that verifies if the problem has been resolved or not.

Project Status :

ResolveProof is a prototype of a hackathon application. To be effective, features like integration with Gemma 4, Evidence Verification Workflow, Risk Assessment and External Portal interaction need to be integrated and tested before they are fully functional.

Calculate the truth of a proof. The status of some people is not a reflection of their worth.
