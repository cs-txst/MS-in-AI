# Degree Guide & Flowchart

---

This guide provides a sample roadmap for completing the Master of Science in Artificial Intelligence in two years. The program is flexible, and you should work with the graduate advisor to create a degree plan that best fits your academic and career goals.

Our 30-hour program consists of **4 Core Courses**, **4 AI Electives**, and **2 Open Electives**. The sample plans below assume a student takes a mix of 2-3 courses (6-9 credit hours) per semester.

### Sample Degree Plan: Fall Start

This is a sample path for a student beginning the program in a Fall semester.

*   **Year 1, Fall** (9 credit hours)
    *   `CS 5329` Algorithm Design and Analysis (Core)
    *   AI-Related Elective
    *   Open Elective

*   **Year 1, Spring** (9 credit hours)
    *   `CS 5315` Responsible and Trustworthy AI (Core)
    *   `CS 5346` Advanced Artificial Intelligence (Core)
    *   AI-Related Elective

*   **Year 2, Fall** (6 credit hours)
    *   AI-Related Elective
    *   AI-Related Elective

*   **Year 2, Spring** (6 credit hours)
    *   `CS 5369L` Machine Learning and Applications (Core)
    *   Open Elective

### Sample Degree Plan: Spring Start

This is a sample path for a student beginning the program in a Spring semester. This path front-loads the core requirements.

*   **Year 1, Spring** (9 credit hours)
    *   `CS 5315` Responsible and Trustworthy AI (Core)
    *   `CS 5346` Advanced Artificial Intelligence (Core)
    *   `CS 5369L` Machine Learning and Applications (Core)

*   **Year 1, Fall** (6 credit hours)
    *   `CS 5329` Algorithm Design and Analysis (Core)
    *   AI-Related Elective

*   **Year 2, Spring** (9 credit hours)
    *   AI-Related Elective
    *   AI-Related Elective
    *   Open Elective

*   **Year 2, Fall** (6 credit hours)
    *   AI-Related Elective
    *   Open Elective

---

### Degree Program Flowchart

This chart provides a visual overview of the M.S. in AI degree structure.

```mermaid
graph TD
    A[Start: MS in AI Program <br/> 30 Credit Hours] --> B{Program Structure};
    B --> C[4 Core Courses <br/> 12 Credit Hours];
    B --> D[4 AI Electives <br/> 12 Credit Hours];
    B --> E[2 Open Electives <br/> 6 Credit Hours];

    C --> C1[CS 5315: Responsible AI];
    C --> C2[CS 5329: Algorithms];
    C --> C3[CS 5346: Advanced AI];
    C --> C4[CS 5369L: Machine Learning];

    D --> D1["Examples:<br/>- Generative AI<br/>- Deep Learning<br/>- Robotics<br/>- NLP"];

    E --> E1["Any 5000+<br/>CS Graduate Course"];
    
    subgraph End Goal
        F[Complete 30 Hours]
    end

    C1 --> F;
    C2 --> F;
    C3 --> F;
    C4 --> F;
    D1 --> F;
    E1 --> F;
    
    F --> G([MS in AI Degree Awarded]);