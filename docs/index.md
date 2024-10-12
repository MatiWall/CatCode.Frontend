

```mermaid
graph TD;
    B[Plugin1] --> A[createApp] ;
    C[Plugin2] --> A ;
    D[Plugin3] --> A ;
    E[...] --> A;


```


```mermaid
graph TD;
    B[Plugin] --> A[createPlugin] ;
    C[RouteRef] --> A 
```