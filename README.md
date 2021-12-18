# TOGAF Certification Exam Preparation Guide and Notes
Purpose: This document is created for preparation of TOGAF certification notes. This is done for self study, completeness and accuracy are not guaranteed.



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

# Architecture Content Framework
Four key words to know:
1. Deliverables: Formal products, they are contractually specified, can contain many artifacts.
2. Artifacts: Fine products which describe architecture from a viewpoint. Examples: Use cases,diagrams,architecture requirements. Catalogs (list of things), Matrices (relationships),Diagrams (pictures)
3. ABB or Architecture Building blocks : Components which can be combined with others to deliver architectures or solns. Its architecture documentation and used mostly in Phase A,B,C,D
