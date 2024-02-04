# Workflow Example

This document outlines the workflow using a flowchart.

```mermaid
graph TD;
    A[Start] --> B[Process 1] ;
    B[Process 1]-->|Link to [Repo 1](https://github.com/AlaaDiab7)| C[Process 2];
    C[Process 2] -->|Link to [Repo 2](https://github.com/wepe/MachineLearning)| D[End];
```
other attempt:

```mermaid
graph TD;
    [Start] --> [Process 1] ;
    [Process 1]-->|Link to [Repo 1]| [Process 2];
    [Process 2] -->|Link to [Repo 2]| [End];
```



Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
