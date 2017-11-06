# General Manager description

## Scenario to cover

<div>
<img src="https://g.gravizo.com/svg? @startuml;

actor User; participant &quot;First Class&quot; as A; participant &quot;Second Class&quot; as B; participant &quot;Last Class&quot; as C;

User -> A: DoWork; activate A;

A -> B: Create Request; activate B;

B -> C: DoWork; activate C;

C --> B: WorkDone; destroy C;

B --> A: Request Created; deactivate B;

A --> User: Done; deactivate A;

@enduml" />
</div>
