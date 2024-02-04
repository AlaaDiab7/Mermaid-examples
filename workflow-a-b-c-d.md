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
    A[Start] --> B[<a href='http://github.com/AlaaDiab7'>Process 1</a>] ;
    B[<a href='http://github.com/AlaaDiab7'>Process 1</a>]-->|Link to | C[<a href='http://github.com/wepe/MachineLearning'>Process 2</a>];
    C[<a href='http://github.com/wepe/MachineLearning'>Process 2</a>] -->|Link to Repo 2| D[<a href='http://google.com'>End</a>];
```
B[an <b>important</b> <a href='http://google.com'>link</a>]

---

another attempt:
```mermaid
graph TD;
    A[Start]-->B[Process 1];
    B[Process 1]-->C[Process 2];
    C[Process 2]-->D[End];
```

<a href='http://github.com/AlaaDiab7'>Process 1</a>


Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
