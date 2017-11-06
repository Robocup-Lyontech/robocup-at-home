# General Manager description

## Scenario to cover

<div>
<img src="https://g.gravizo.com/svg? @startuml;

actor User; participant &quot;First Class&quot; as A; participant &quot;Second Class&quot; as B; participant &quot;Last Class&quot; as C;

User -&gt; A: DoWork; activate A;

A -&gt; B: Create Request; activate B;

B -&gt; C: DoWork; activate C;

C --&gt; B: WorkDone; destroy C;

B --&gt; A: Request Created; deactivate B;

A --&gt; User: Done; deactivate A;

@enduml " />
</div>
