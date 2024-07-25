# Score & Time Pickup

<h3 style="font-family: 'Lato Extended', Lato, 'Helvetica Neue', Helvetica, Arial, sans-serif;"><strong><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18440/preview?verifier=gCCnKh2tnmnbR28tO5KenPsPtBSgil6OJ6VFICN1" alt="Untitled-1-27.png" width="732" height="412" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18440" data-api-returntype="File"></strong></h3>
<h3><strong>Score &amp; Time Pickup</strong></h3>
<p>For this step, we want to create the logic and behavior to calculate the time and score. So we are going to create a blueprint to collect and manage the increase of score and time.</p>
<h4><strong>Step 1: Create Blueprint</strong></h4>
<p>In the content browser right click and go to blueprint class create an actor class blueprint.</p>
<h4><strong>Step 2: Set Components</strong></h4>
<p>For this blueprint we will need two components first add a sphere collision and then add a static mesh component. The static mesh to Shape_Torus and make the sphere collision a child of the Taurus.</p>
<h4><strong>Step 3: Create Behavior</strong></h4>
<p>Select the sphere collision navigate to the details panel and create a on "Component Begin Overlap". In the event graph pull off the execution pin and create a branch node. From the blue pin other actor create a "Does Implement Interface" and connect the red pin to the condition of the branch. Make sure the interface is set to "Vehicle Interface". From the branch node pull up the true execution pin and create a reference to "Pick Up Object". To keep track of the score and time we'll create two variables, both these variables will be integer. Name one "Time" and the other "Score".</p>
<h4><strong>Step 4: Actor Dismiss</strong></h4>
<p>For the final part of the logic, we need to dismiss the collectible, otherwise we could continue to collect from the same object. Off of the reference for pickup object create a "Destroy Actor" node.</p>
<p>&nbsp;</p>