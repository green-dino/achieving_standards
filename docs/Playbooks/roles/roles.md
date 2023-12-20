# Roles

Roles

User (A)
Work Role (B)
Problem (C)
Change (D)
Request (E)
Change Control Record (F)
Document Control Information (G)
Change Implementation Plan (H)
Communication and Notification (I)
Risk Assessment and Control (J)
Document References (K)
Evaluation (L)
Fulfillment (M)
Framework (N)
Loops (O)
Functions (P)
Playbooks (Q)
Mappings (R)
Roles (S)
Blocks (T)
Task (U)
User (V)
Role Selected (W)
Trouble Tickets (X)
View (Y)


```mermaid
graph TD

subgraph Using Roles
  Roles[Using Roles]
  PlayLevelRoles[Using Roles at the Play Level]
  IncludeR
  oles[Including Roles: Dynamic Reuse]
  ImportRoles[Importing Roles: Static Reuse]
  RoleValidation[Role Argument Validation]

  Roles --> PlayLevelRoles
  Roles --> IncludeRoles
  Roles --> ImportRoles
  Roles --> RoleValidation
end

PlayLevelRoles --> RoleSyntax[Role Syntax in Play]
PlayLevelRoles --> RoleVars[Role Variables]
PlayLevelRoles --> RoleTags[Role Tags]
PlayLevelRoles --> RoleConditionals[Role Conditionals]

IncludeRoles --> IncludeSyntax[Include Syntax]
IncludeRoles --> IncludeWithItems[Include with_items]
IncludeRoles --> IncludeWithVars[Include with_vars]

ImportRoles --> ImportSyntax[Import Syntax]
ImportRoles --> ImportWithItems[Import with_items]
ImportRoles --> ImportWithVars[Import with_vars]

RoleValidation --> RoleValidationSyntax[Role Validation Syntax]
RoleValidation --> RoleValidationTasks[Role Validation Tasks]

```

```mermaid
graph LR
    A(User)
    B(Work Role)
    C(Problem)
    D(Change)
    E(Request)
    F(Change Control Record)
    G(Document Control Information)
    H(Change Implementation Plan)
    I(Communication and Notification)
    J(Risk Assessment and Control)
    K(Document References)
    L(Evaluation)
    M(Fulfillment)
    N(Framework)
    O(Loops)
    P(Functions)
    Q(Playbooks)
    R(Mappings)
    S(Roles)
    T(Blocks)
    U(Task)
    V(User)
    W(Role Selected)
    X(Trouble Tickets)
    Y(View)

    A(User) -->|Initiates| B(Work Role)
    B(Work Role) -->|Addresses| C(Problem)
    B(Work Role) -->|Initiates| D(Change)
    B(Work Role) -->|Submits| E(Request)
    C(Problem) -->|Links to| F(Change Control Record)
    D(Change) -->|Links to| F(Change Control Record)
    E(Request) -->|Links to| F(Change Control Record)
    F(Change Control Record) -->|Captures| G(Document Control Information)
    F(Change Control Record) -->|Captures| H(Change Implementation Plan)
    F(Change Control Record) -->|Determines| I(Communication and Notification)
    F(Change Control Record) -->|Assesses| J(Risk Assessment and Control)
    F(Change Control Record) -->|References| K(Document References)
    C(Problem) -->|Links to| F(Change Control Record)
    D(Change) -->|Conducts| L(Evaluation)
    E(Request) -->|Initiates| M(Fulfillment)
    N(Framework) -->|Incorporates| O(Loops)
    N(Framework) -->|Incorporates| P(Functions)
    Q(Playbooks) -->|Maps| R(Mappings)
    Q(Playbooks) -->|Maps| S(Roles)
    T(Blocks) -->|Assigns| U(Task)
    V(User) -->|Selects| W(Role Selected)
    W(Role Selected) -->|Manages| X(Trouble Tickets)
    X(Trouble Tickets) -->|Provides| Y(View)
```