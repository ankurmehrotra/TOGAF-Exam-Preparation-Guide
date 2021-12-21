# TOGAF Certification Exam Preparation Guide and Notes
Purpose: This document is created for preparation of TOGAF certification notes (9.2). This is done for self study, completeness and accuracy are not guaranteed.

If you found my notes useful, you can <a href="https://www.buymeacoffee.com/ankurmehrotra" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>


# What is an architecture framework
1. A conceptual structure used to develop, implement, govern, and sustain an
architecture
2. Provides a practical starting point for an Architecture Project
3. It should describe a method for designing target state of the enterprise in
terms of a set of building blocks, and for showing how the building blocks
fit together

** Quick Summary: TOGAF Framework has 6 parts to it, and one of the is ADM. ADM by itself has Preliminary phase and Phases A to H.**

# TOGAF Framework
It has 6 parts, 
1. ADM - Development Method, read below for more detail on it.
2. ADM Guidelines and techniques - Guidelines help adapt ADM, Technique support specific tasks of ADM like task planning, gap analysis etc...
3. Architecture content framework: Detailed model of work products i.e. artifacts and deliverables and the Architecture Building blocks these deliverables represent
4. Enterprise continuum: Repository for future reuse, how to establish it.
5. Architecture capability framework: Provides guidance for establishing an architecture practice in a company, what capabilities they should include, what roles and skills.
6. TOGAF Library: Provides templates, guidance and technique to help implement togaf. Reference Library.

Each Phase will be learned in the next notes, every phase has its own Objectives, input, output and steps. This is what is usually referred in questions.

# ADM
![image](https://user-images.githubusercontent.com/15048072/145709719-0b4cd67c-6d08-4768-bcf3-cb185c0fc6c5.png)

1. Preliminary Phase : The goal is to prepare for creating Architecture Capability
2. Phase A Architecture Vision : Create statement of work, is a the beginning of an iteration, Sets Scope and expectations of Architecture process.
3. Phase B Business Architecture :  Indicate how business is organized, and how it connects to goals (sounds like fluff! this is mostly about as-is and to-be states). Contains roles, business processes,functions, services and links between functions. Steps 
4. Phase C Information Systems Architecture : Document Data and Application architecture for a project. Which of those architecture comes first depends on our scope.
5. Phase D Technology Architecture : Principles of design, evolution of an It System including hardware/software/integrations
6. Phase E Opportunities and Solutions :  Initial implementation planning, identify major projects, what kind of solutions can be made
7. Phase F Migration Planning : With output of E, plan for Implementation and Migration.
8. Phase G Implementation Governance : Provide architecture oversight for implementation, define architecture constraints for implementation, write Business Value realization
9. Phase H Architecture Change management :  Provide a monitoring and change management process, create a way on how architecture change will be done in future.

All this while, we continue to validate against requirements.


![image](https://user-images.githubusercontent.com/15048072/146609146-16ebddba-7e49-4cdf-bdd1-3042fc46350f.png)

Notes:
1. ADM Phases has Inputs and Output deliverables, some phases modify outputs from older phases.
2. Versions like 0.1 indicate documents are still outline stage, while higher versions like v1.0 indicate formally reviewed deliverable (this is a question!)
3. ADM can be adapted, based on industry, vertical or geographies.
4. ADM Must be governed by an Architecture Board, which needs a Governance Repository to manage artifacts, reference data, process data and audit info.
5. Architecture activity scope can be constrained due to resource, people or finance availibility.
6. Scoping of architecture activity can be limited by : Breadth, Domains (Business, data, technology, application), Depth (enterprise to capability level) or time.
7. Architecture can haves levels like Strategic (highest), Segment and Capability (lowest)

# ADM In detail (from the view of Objectives and Approach)

# ADM Preliminary Phase

**Goal**: Create request for Architecture Work (for an identified architecture capability)
**Activities**?
1. Understand business environment
2. Get committment from management
3. Agree on SCOPE
4. Establish Architecture Principles (Read Page 201 in personal Member edition)
5. Establish Governance structure
6. Customization of togaf framework

**Architecture principles** are an initial input of Preliminary phase. TOGAF gives guidelines to make principles and some generic principles to start with. Two domains of principles: Architecture and Enterprise. Remember the key headings on principles for the exam and what is difference between Rationale and Implications. Finally, these are written to "Guide decision making within an enterprise".

# Phase A: Architecture Vision
Goal: Create draft architecture definition document.
What happens in this phase?
1. Initiates one iteration of architecture process.
2. Creates architecture vision (note, vision is Phase A and not preliminary) - Its a high level vision
3. Create Statement of architecture work (and get approval)
4. Create Comms. plan
5. Create draft architecture definition document (it has purpose, how it will be achieved, high level desccription of baseline and target, business scenarios)

So largely this phase defines the Scope Of architecture activity.

# Phase B: Business Architecture
Goal: Create Draft Architecture requirement specification document.

Other goals: Create target business architecture  that describes how the enterpise need to operate to achieve its goals. Also identify components for architecture roadmap from baseline to target.
If baseline does not exist already in any repository, then make this too!
Techniques: Business Capability Maps, Organization Maps,Value streams
Role of Architecture repository : The team needs to determine what is to be picked from repository (Standards, building blocks, industry specific architecture, or business architecture views)

# Phase C: Information Systems architecture
Goal: Develop the Target Information Systems (Data and Application) Architecture, describing how the enterprise's Information Systems Architecture will enable the Business
Architecture and the Architecture Vision, in a way that addresses the Statement for Architecture Work and stakeholder concerns

Approach
This Phase has both data and application architecture, does not matter which goes first.

# Phase D: Technology Architecture
Goal: Develop the Target Technology Architecture that enables the Architecture Vision, target business, data, and application building blocks to be delivered through technology components and technology services, in a way that addresses the Statement of Architecture Work stakeholder concerns
• Identify candidate Architecture Roadmap components based upon gaps
between the Baseline and Target Technology Architectures

Approach: 
Review repository, including TRF or existing ITIL repository. COnsider for new technological opportunities.

# Phase E: Opportunities and Solutions
Goal; To create architecture roadmap, implementation and migration plan
Also, break down the work to solution building blocks, the changes are grouped into work packages.

# Phase F: Migration Planning
Goal; To finalize detailed implementation plan and finalize architecture roadmap from Phase E
Perform cost benefit analysis on the work done in Phase E, and a risk assessment.
Ensure, business value and cost is understood by stakeholders.

# Phase G: Implementation Governance
Goal: Is to provide architeture governance to the solutions being implemented. The architecture contract (signed) is main output
How?
This phase connects architeture and implementation organization. The goal is to ensure that architecture is translated correctly, using organizations project and program methodologies.

# Phase H: Architecture Change Management
Goal:
• Ensure that the architecture lifecycle is maintained
• Ensure that the Architecture Governance Framework is executed
• Ensure that the enterprise Architecture Capability meets current requirements
Now changes can be incremental, simplification and re-architecting. Each must be evaluated and defined to plan the next stage.

# Requirement Management (Central circle?)
It applies to all stages, is central to ADM
TOGAF does not specify tools or process for requirements, it suggests business scenarios or using specific software.
Idealy requirement repository should be maintained, in this stage no prioritization is done, thats only in phases.

# ADM Guidelines and Techniques

We focus on some techniques only, as questions ask about their definition:
1. **Business Scenarios:** An Architecture can only be successful if it meets requirments, and supports business objectives. This technique helps identify and understand business requirements that architecture must do. A business scenario describes business/tech environments, or process or applications which architecture exercise targets. It also describes actors involved and outcomes. Used mostly in phase A, but also shows up in others.
2. **Business Transformation Readiness Assessment**: This is a readiness assessment done in Phase A, to check if the Enterprise can do the architecture change. Its a join cross team effort. Its actions are usually done in Phase E and F.
3. **Capability Based Planning** : Planning engineering and delivery of capabilites. It is done across the board and connecs all phases.
4. **Risk Management:** This a flow of identifying, classifying, planning mitigation and monitoring. Monitoring is done in Phase G (implementation governance).

# Architecture Governance 
Governance is how Enterprise architectures are managed and controlled.
It is established in preliminary phase.
The Board must assure that ADM is adhered to, this is a key tenet.
Governance is also super important in G to H phases (implementation and change).

Governance can be local, Global or regional. It can be also Technology Governance, IT Governance and Architecture Governance
This section has guidelines on how architecture governance should be setup, and why. It also talks about Architecture board, their roles and finally Architecture contracts.
Architecture contracts:Joint agreements between development partners and sponsors on the deliverables, qualify and fitness for purpose of an architecture

Architecture Compliance: Prepare Project Impact assessment and Performance Architecture compliance review.
How does a compliance review help (again exam specific needs):
1. Catch error in project architecture early
2. Ensure best practices are applied
3. Identify where standards must also be changed
4. Identify gaps and communication them.

Architecture Views and Viewpoints (again questions on definition).
1. Concerns are interests in a system relevant to one or more of its stakeholders. 
2. An Architecture View is a representation of a system from the perspective of a related set of concerns. A representation of an overall architecture with meaning to
one or more stakeholders in the system
3. Architecture Viewpoint defines the perspective from which an architecture view is taken.


# Architecture Content Framework (Part IV)
It gives a list of outputs
Four key words to know:
1. Deliverables: Formal products, they are contractually specified, can contain many artifacts.
2. Artifacts: Fine products which describe architecture from a viewpoint. Examples: Use cases,diagrams,architecture requirements. Catalogs (list of things), Matrices (relationships),Diagrams (pictures)
3. ABB or Architecture Building blocks : Components which can be combined with others to deliver architectures or solns. Its architecture documentation and used mostly in Phase A,B,C,D

So how does Content framework map to the ADM? While ADM describes what work should be done to create architecture, the Content framework describes how it should look like


# Enterprise continuum (part V of framework)
A model for structuring a virtual repository and methods for classifying architecture and solution artifacts. It really becomes the Architecture repository.
It promotes reuse, and common language.
It can be split into:
1. Architecture Continuum: Foundational architectures to common system architectures to industry specific architectures (generic to specific)
2. Solutions Continuum: Foundation Solutions to common system solutions to industry specific (Generic to specific). They form a solution inventory or reuse library for the org.

Now Architectures support solutions and vice versa.
The Continuum:
o contains complete and work‐in‐progress solutions
o is a "framework‐within‐a‐framework”
o has few internal assets, at first
o grows by adding reusable building blocks

One word on tools: They are used to manage artifacts in continuum

_Architecture Repository_
1. Architecture Metamodel describes the architecture framework in use within the
Enterprise
2. Architecture Landscape: shows the state of the operating Enterprise at particular points in time (Strategic, segment or capability)
3. Reference Library: contains re usable architecture work products
4. Standards Information Base: defines the compliance criteria for work governed by  archiecture
5. Governance Log: captures results of governance activity
6. Architecture Capability: describes the organisation, roles, skills and responsibilities of the Enterprise Architecture practice
7. Architecture Requirements Repository: provides a view of all authorized architecture requirements which have been agreed with the Architecture Board
8. Solutions Landscape: presents an architectural representation of the SBBs supporting the Architecture Landscape which have been planned or deployed by the enterprise

