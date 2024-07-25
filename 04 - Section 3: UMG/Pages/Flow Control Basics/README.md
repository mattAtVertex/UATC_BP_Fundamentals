# Flow Control Basics

<h3><strong>Flow Control Basics<img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18422/preview?verifier=6MQqFtsXsqruzLU9y4DfBPBF9SPLIliFxgMIKmBc" alt="image.png" width="427" height="507" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18422" data-api-returntype="File"></strong></h3>
<p><span>In Unreal Engine 5 Blueprints, flow control refers to the ability to control the execution flow of your script, allowing you to make decisions and execute different sets of instructions based on conditions. Here are some of the basic flow control nodes and concepts in Unreal Engine 5 Blueprints:</span></p>
<ol>
<li class="speechify-inbox-player">
<p>Branch Node:</p>
<ul>
<li class="speechify-inbox-player">The Branch node is a fundamental flow control node in Blueprints that allows you to make decisions based on conditions.</li>
<li class="speechify-inbox-player">It takes a Boolean input and has two execution outputs: one for the true condition and another for the false condition.</li>
<li class="speechify-inbox-player">By connecting different nodes to the respective outputs of the Branch node, you can define different sets of instructions to be executed based on the condition.</li>
</ul>
</li>
<li class="speechify-inbox-player">
<p>If/Else Nodes:</p>
<ul>
<li class="speechify-inbox-player">The If and If/Else nodes provide a more explicit way to handle conditional branching in Blueprints.</li>
<li class="speechify-inbox-player">The If node takes a Boolean condition as input and has a single execution output. If the condition is true, the connected nodes will be executed.</li>
<li class="speechify-inbox-player">The If/Else node takes a Boolean condition as input and has two execution outputs: one for the true condition and another for the false condition. Only one set of connected nodes will be executed, based on the condition.</li>
</ul>
</li>
<li>
<p>Flip Flop Node:</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li>The Flip Flop node is a convenient way to toggle between two states or execute two sets of instructions alternately.</li>
<li>It has a single execution input and two execution outputs: One output is triggered on the first execution, and the other output is triggered on the second execution.</li>
<li>Each time the Flip Flop node receives an execution input, it toggles between the two outputs, allowing you to perform different actions on each state change.</li>
</ul>
</li>
</ul>
</li>
<li>
<p>Sequence Node:</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li>The Sequence node is used to execute a sequence of actions or nodes in a specific order, one after another.</li>
<li>It provides a linear flow of execution, ensuring that each connected node is executed in the order they are connected.</li>
<li>The Sequence node has multiple execution outputs, and each output triggers the connected node or set of nodes in the defined sequence.</li>
<li>This node is particularly useful when you want to ensure a specific order of execution or perform a series of actions step by step.</li>
</ul>
</li>
</ul>
</li>
<li class="speechify-inbox-player">
<p>Loops:</p>
<ul>
<li class="speechify-inbox-player">Loops are used to repeatedly execute a set of instructions until a certain condition is met.</li>
<li class="speechify-inbox-player">Unreal Engine 5 Blueprints support several loop types, including For Loops and While Loops.</li>
<li class="speechify-inbox-player">For Loops are used when you know the number of iterations in advance, such as iterating over an array.</li>
<li class="speechify-inbox-player">While Loops are used when you want to execute a set of instructions until a specific condition becomes false.</li>
</ul>
</li>
<li class="speechify-inbox-player">
<p>Gate Nodes:</p>
<ul>
<li class="speechify-inbox-player">Gate nodes allow you to control the flow of execution by enabling or disabling it based on certain conditions.</li>
<li class="speechify-inbox-player">They have an input and an output execution pin, and they only allow execution to pass through when the gate is open.</li>
<li class="speechify-inbox-player">You can control the state of the gate using Blueprint variables or other conditions.</li>
</ul>
</li>
</ol>
<p class="speechify-inbox-player">These are some of the basic flow control nodes and concepts in Unreal Engine 5 Blueprints. They provide you with the tools to make decisions, handle conditions, and control the flow of execution in your scripts, allowing you to create dynamic and interactive behaviors in your game or application.</p>