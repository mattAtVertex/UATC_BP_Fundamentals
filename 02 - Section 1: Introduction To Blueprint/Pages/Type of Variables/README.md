# Type of Variables

<h2 data-speechify-highlight="true"><strong>Type of Variables</strong></h2>
<p>In Unreal Engine, a variable is a named container that can hold a value, such as a number, a string of text, or an object reference. Variables are commonly used in blueprints.</p>
<p data-speechify-highlight="true">Variables can be declared in blueprint scripts or in C++ code and can have different data types, such as integers, floating-point numbers, booleans, strings, vectors, or object references. Each variable has a unique name that is used to identify it and access its value.</p>
<p>Variables can be used to store and manipulate data in different ways, depending on the game logic and functionality. For example, variables can be used to store a player's health, a score, a position in 3D space, or a reference to an object in the game world. They can also be used to pass data between different blueprint nodes or to trigger events and actions based on certain conditions or inputs.</p>
<p>Overall, variables are an essential component of game development in Unreal Engine, providing a flexible and powerful way to store and manipulate data in blueprints and C++ code.</p>
<h3 style="padding-left: 40px;"><strong>List of Variables</strong></h3>
<ol>
<li><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18140/preview?verifier=80T8fh0IDhvYjlxzFRl0v4ryvb8gbx5vWCW7DjKu" alt="BP_Variables.png" width="658" height="448" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18140" data-api-returntype="File">
<p><strong>Boolean: </strong>A<strong><em> Boolean variable</em></strong> can hold one of two values, true or false. It is commonly used to represent conditions or states in the game.</p>
</li>
<li><strong>Byte: </strong><span>A <strong><em>Byte variable</em></strong> is commonly used in situations where only a small range of values is needed, such as for storing simple state information, like holding an index to an array of values.</span></li>
<li>
<p><strong>Integer:</strong> An <em><strong>Integer variable</strong></em> holds whole numbers, such as -3, 0, or 42. It is used to store numeric values, such as scores or quantities.</p>
</li>
<li>
<p><strong>Float:</strong> A<strong> <em>Float variable</em></strong> holds decimal numbers, such as 3.14 or 0.5. It is used for storing values that require precision, such as position coordinates or physics properties.</p>
</li>
<li><strong>Name:</strong>&nbsp;<span> The&nbsp;<em><strong>Name variable</strong></em> is a type of variable that can be used in blueprints to store a name or identifier.</span></li>
<li>
<p><strong>String:</strong> A <em><strong>String variable</strong></em> holds a sequence of characters, such as "Hello, World!" or "Player Name". It is used for storing text-based information.</p>
</li>
<li><strong>Text:</strong>&nbsp;<span>The&nbsp;<strong>Text variable</strong> is a type of variable that can be used in blueprints to store a string of text.</span></li>
<li>
<p><strong>Vector:</strong> A <strong>Vector variable</strong> holds three Float values, representing a position in 3D space. It is commonly used for storing position or direction information.</p>
</li>
<li>
<p><strong>Rotator: </strong>A <em><strong>Rotator variable</strong></em> holds three Float values, representing a rotation in 3D space. It is commonly used for storing rotation or orientation information.</p>
</li>
<li>
<p><strong>Transform: </strong>A <strong><em>Transform variable </em></strong>holds a combination of a Vector and a Rotator, representing a position and rotation in 3D space. It is commonly used for storing the position and orientation of an object in the game world.</p>
</li>
<li>
<p><strong>Object Reference: </strong>An <em><strong>Object Reference variable</strong></em> holds a reference to an object in the game world, such as a character, weapon, or other asset. It is used for storing references to objects that are used in the game logic.</p>
</li>
<li>
<p><strong>Class Reference:</strong> A <em><strong>Class Reference variable</strong></em> holds a reference to a class in the game, rather than an instance of that class. It is used for storing information about a class, such as its name, properties, and methods.</p>
</li>
</ol>
<p>Overall, these variable types provide a wide range of data storage and manipulation capabilities in Unreal Engine blueprints, allowing developers to create complex game logic and behavior.</p>
<h3><strong>Get and Set variables:</strong></h3>
<p class="speechify-inbox-player">In Unreal Engine 5 Blueprints, "Get" and "Set" are nodes used to retrieve or modify the value of a variable or a property of an object.</p>
<ul>
<li class="speechify-inbox-player">"<strong>Get</strong>" nodes are used to retrieve the value of a variable or a property of an object. For example, a "Get Player Controller" node can be used to retrieve the player controller object that is currently controlling the game.</li>
<li class="speechify-inbox-player">"<strong>Set</strong>" nodes are used to modify the value of a variable or a property of an object. For example, a "Set Player Score" node can be used to modify the score variable of the player.</li>
</ul>
<p class="speechify-inbox-player">In both cases, the nodes are linked to the variable or property they are accessing or modifying, and the value is passed between the nodes through a pin system. For instance, if you use a "Get Player Score" node, the score value is returned as a pin that can be passed on to other nodes that require this value.</p>
<p class="speechify-inbox-player">These nodes can be used to perform a wide range of tasks within a Blueprint script, such as retrieving or modifying the state of objects, manipulating game logic, and implementing gameplay mechanics. The ability to get and set values using nodes is an essential feature of Blueprint scripting in Unreal Engine 5, providing a flexible and powerful way to create complex and dynamic game mechanics.</p>