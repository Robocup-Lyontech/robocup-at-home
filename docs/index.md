---
permalink: /
layout: default
title: Discussions about Architectures
---

### Test de l'integration mermaid svg

<div class="mermaid">
sequenceDiagram
    loop Daily query
        Alice->>Bob: Hello Bob, how are you?
        alt is sick
            Bob->>Alice: Not so good :(
        else is well
            Bob->>Alice: Feeling fresh like a daisy
        end

        opt Extra response
            Bob->>Alice: Thanks for asking
        end
    end
</div>

---

<div class="mermaid">
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
  </div>
  
<div class="mermaid">
    gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
</div>

 <div class="mermaid">
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
</div>
<div class="mermaid">
        gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid

        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d

        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d

        section Documentation
        Describe gantt syntax               :active, a1, after des1, 3d
        Add gantt diagram to demo page      :after a1  , 20h
        Add another diagram to demo page    :doc1, after a1  , 48h

        section Last section
        Describe gantt syntax               :after doc1, 3d
        Add gantt diagram to demo page      : 20h
        Add another diagram to demo page    : 48h
  </div>

<div class="mermaid">	 
	 graph LR
		A[Hard edge] -->B(Round edge)
		B --> C{Decision}
		C -->|One| D[Result one]
		C -->|Two| E[Result two]
</div>
	
<div class="mermaid">	 
		classDiagram
		Class01 <|-- AveryLongClass : Cool
		Class03 *-- Class04
		Class05 o-- Class06
		Class07 .. Class08
		Class09 --> C2 : Where am i?
		Class09 --* C3
		Class09 --|> Class07
		Class07 : equals()
		Class07 : Object[] elementData
		Class01 : size()
		Class01 : int chimp
		Class01 : int gorilla
		Class08 <--> C2: Cool label
</div>
<div class="mermaid">	
    sequenceDiagram
	    Alice->>Bob: Hello Bob, how are you?
	    alt is sick
	    Bob->>Alice: Not so good :(
	    else is well
	    Bob->>Alice: Feeling fresh like a daisy
	    end
	    opt Extra response
	    Bob->>Alice: Thanks for asking
	    end
</div>
<div class="mermaid">	
	graph LR
		A[Physics Based Model]-->B(Feature Identification);
		B-->C(Feature Encoding);
		B-->b1((segmentation));
		C-->D(Data Analytics);
		C-->c1((spatial statistics));
		D-->|collaborate|E{Design};
		D-->d1((PCA));
		E-->|iterate|A;
</div>
	
<div class="mermaid">	
		graph LR
		id1(Start)-->id2(Stop)
		style id1 fill:#f9f,stroke:#333,stroke-width:4px
		style id2 fill:#ccf,stroke:#f66,stroke-width:2px,stroke-dasharray: 5, 	
</div>
<div class="mermaid">	
		graph TD
		B["fa:fa-twitter for peace"]
		B-->C[fa:fa-ban forbidden]
		B-->D(fa:fa-spinner);
		B-->E(A fa:fa-camera-retro perhaps?);
</div>
<div class="mermaid">	
		graph TD
		B["fa:fa-twitter for peace"]
		B-->C[fa:fa-ban forbidden]
		B-->D("fa:fa-spinner fa-spin");
		B-->E(A fa:fa-camera-retro perhaps?);
</div>

<style>
    .cssClass > rect{
        fill:#FF0000;
        stroke:#FFFF00;
        stroke-width:4px;
    }
</style>


<div class="mermaid">	
graph LR;
    A-->B[AAA<span>BBB</span>];
    B-->D;
    class A cssClass;
</div>


  
