# fire-stuff
graph TD
    A[Start Assessment] --> B{Is it a Project or Program?}
    B -->|Project| C[Assess Against 7 Values]
    B -->|Program| C
    C --> D{Well-being:
    1. Improves HDI factors?
    2. Aligns with SDGs?}
    D -->|Yes| E[Record Positive for Well-being]
    D -->|No| F{Equality:
    1. Promotes equal access to justice?
    2. Addresses gender/racial/income equality?}
    E --> F
    F -->|Yes| G[Record Positive for Equality]
    F -->|No| H{Empowerment:
    1. Improves work opportunities?
    2. Enhances education access?
    3. Improves health access?}
    G --> H
    H -->|Yes| I[Record Positive for Empowerment]
    H -->|No| J{Sustainability:
    1. Meets current needs without compromising future?
    2. Reduces resource exploitation?
    3. Prioritizes renewable resources?}
    I --> J
    J -->|Yes| K[Record Positive for Sustainability]
    J -->|No| L{Human Rights:
    1. Upholds universal human rights?
    2. Protects against discrimination?}
    K --> L
    L -->|Yes| M[Record Positive for Human Rights]
    L -->|No| N{Cultural Freedom:
    1. Promotes individual identity expression?
    2. Reduces social exclusion?}
    M --> N
    N -->|Yes| O[Record Positive for Cultural Freedom]
    N -->|No| P{Responsibility:
    1. Identifies/carries out aid responsibilities?
    2. Navigates conflicts with integrity?
    3. Combats corruption?}
    O --> P
    P -->|Yes| Q[Record Positive for Responsibility]
    P -->|No| R[No more criteria to check]
    Q --> R
    R --> S[Calculate Overall Score]
    S --> T[Generate Evaluation Report]
    T --> U[End Assessment]
