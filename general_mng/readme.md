# General Manager description

## Scenario to cover
<div>
   <img src="https://g.gravizo.com/svg?
  digraph G {
    aize =&quot;4,4&quot;;
    main [shape=box];
    main -&gt; parse [weight=8];
    parse -&gt; execute;
    main -&gt; init [style=dotted];
    main -&gt; cleanup;
    execute -&gt; { make_string; printf}
    init -&gt; make_string;
    edge [color=red];
    main -&gt; printf [style=bold,label=&quot;100 times&quot;];
    make_string [label=&quot;make a string&quot;];
    node [shape=box,style=filled,color=&quot;.7 .3 1.0&quot;];
    execute -&gt; compare;
  }" />
</div>
