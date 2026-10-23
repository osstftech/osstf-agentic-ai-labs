# Learning roadmap

Status: planned; implementations and SDK versions will be verified before publication.

| Lab | Language | Concept | Completion evidence |
|---|---|---|---|
| L01 | Python | Tool contracts and bounded tool loops | Valid call, invalid arguments, step-limit tests |
| L02 | Java | Identity-aware tool authorization | Trusted context and resource-denial tests |
| L03 | JavaScript | Scoped retrieval and citation integrity | Selected book/section boundaries and source validation |
| L04 | Python | Routing and execution budgets | Allowed capabilities, ambiguity and termination |
| L05 | Java | Owned sessions and context separation | Resume, ownership and book-switch tests |
| L06 | JavaScript | Streaming, retry and result recovery | Duplicate request, disconnect and recovery tests |
| L07 | Python | Agent evaluation and regression | Retrieval, tool trajectory and answer-support checks |

Each lab will explain what to do, how to do it, why the boundary matters and how to verify the outcome. JavaScript support and APIs will be checked against the selected ADK version; language differences will be documented rather than hidden.

Every released lab needs pinned dependencies, setup/cleanup, synthetic fixtures, offline tests, expected outputs and known limitations. Live model demonstrations are optional and separately labelled.

