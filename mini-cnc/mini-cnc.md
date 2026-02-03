```mermaid
flowchart TD

A["Start"] -->|Zero| B(0)

B --> C{Let me think}

C -->|One| D[1]

C -->|Two| E[2]

C -->|Three| F[3]

subgraph s1["Image embed test"]

n1@{ img: "./assets/test_raster.png" }

end
```
