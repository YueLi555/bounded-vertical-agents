# Bounded Vertical Agents

**A State-and-Control Architecture for Safer Real-World AI Agents**  
Yue Li  
Founder and AI Agent Developer, U Agent  
San Jose, California

## Abstract

This working paper argues that vertical AI agents should be designed as bounded execution systems, not general-purpose autonomous workers.

In real-world business workflows, the hardest failures often come not from language generation alone, but from the software architecture around the model: task state, permissions, identity, recovery, tool timing, and final execution authority.

The paper proposes a state-and-control architecture for safer vertical agents, including:

- Narrow business boundaries
- Separation between model reasoning and execution authority
- Durable task truth
- Action event ledgers
- Policy and permission gates
- Runtime projections
- Human-confirmed final execution gates
- Evaluation harnesses for failure containment

The paper uses U Agent, a production AI email workflow system, as an implementation case study.

## Paper

📄 [Read the PDF](paper/Bounded_Vertical_Agents_Yue_Li.pdf)

## Core Thesis

Vertical AI agents should not be treated as general-purpose autonomous workers.  
They should be designed as bounded execution systems, where model reasoning is separated from state truth, policy gates, action authority, and human-confirmed irreversible actions.

## Keywords

AI agents, vertical agents, agent safety, human-in-the-loop systems, state machines, workflow automation, bounded autonomy, evaluation harnesses.

## Author

Yue Li  
Founder and AI Agent Developer, U Agent  
San Jose, California# bounded-vertical-agents
