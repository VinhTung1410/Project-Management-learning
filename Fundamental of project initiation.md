graph TD
    %% Main Node
    Initiation[<b>Project Initiation Phase</b><br/>Foundational Step]

    %% Key Responsibilities
    Initiation --> PM_Roles[<b>PM Responsibilities</b>]
    PM_Roles --> R1[Research & Documentation]
    PM_Roles --> R2[Stakeholder Discussions]
    PM_Roles --> R3[Defining Project Scope]

    %% Core Components
    Initiation --> Components[<b>Key Components</b>]
    subgraph Core[The 6 Pillars]
    Components --> C1[<b>Goals</b>: Clear objectives]
    Components --> C2[<b>Scope</b>: Boundaries of work]
    Components --> C3[<b>Deliverables</b>: Tangible outputs]
    Components --> C4[<b>Success Criteria</b>: Measuring success]
    Components --> C5[<b>Stakeholders</b>: People involved]
    Components --> C6[<b>Resources</b>: Budget/People/Tools]
    end

    %% Cost Benefit Analysis
    Initiation --> CBA[<b>Cost-Benefit Analysis</b>]
    CBA --> Benefits[<b>Benefits</b>]
    CBA --> Costs[<b>Costs</b>]
    
    subgraph CBA_Details[Evaluation]
    Benefits --> B_Tan[Tangible: Revenue, time saved]
    Benefits --> B_Int[Intangible: Brand perception, satisfaction]
    Costs --> C_Tan[One-time vs. Ongoing costs]
    Costs --> C_Int[Risks to morale or reputation]
    end

    %% ROI Calculation
    CBA --> ROI[<b>ROI Calculation</b>]
    ROI --- Formula["Formula: ((Gains - Costs) / Costs) x 100"]
    
    %% Styling
    style Initiation fill:#f9f,stroke:#333,stroke-width:4px
    style ROI fill:#dfd,stroke:#333
    style Core fill:#f0f0f0,stroke:#999