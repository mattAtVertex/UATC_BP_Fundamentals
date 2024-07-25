# Editing Level Blueprint

<h3><strong><br>Editing Level Blueprint</strong></h3>
<h4><strong><img src="https://vertexschool.instructure.com/courses/289/files/18448/preview?verifier=944jiDm7kMLvKp3yGW4lAFQcsHjZCCJzYai61hQr" alt="Untitled-1-13.png" width="638" height="359" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18448" data-api-returntype="File"></strong></h4>
<h4><strong>Step 1: Location Is Key</strong></h4>
<p>To start off our process we are going to edit the level of blueprint. Level has its own blueprint, so we need to make sure before we start, we're in the correct level. Once we know we're in the correct level navigate to the top center portion of your screen. Here we're going to be able to open our level blueprint.</p>
<h4><strong>Step 2: Set-Up Countdown event</strong></h4>
<p>Add a "Set Timer By Event" and link the execution PIN from the "Event Begin Play" together. Right click create "Custom Event", name it "CountDown" and link the square red output pen to the event pin and set timer by event.</p>
<h4><strong>Step 3: Score And Time Pickup</strong></h4>
<p>Create a new variable named "TimeRemaining", set the variable type to integer. Compile and then assign a default value to time remaining, let's set this to 5 as a place hold.</p>
<h4><strong><img src="https://vertexschool.instructure.com/courses/289/files/18454/preview?verifier=0BzWzX3aa0tI285bPqvM75RsCndCC3EbFFghvDiZ" alt="Untitled-1-15.png" width="690" height="388" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18454" data-api-returntype="File"></strong></h4>
<h4><strong>Step 4: Countdown And Loss Condition</strong></h4>
<p>To tie the previous steps together, we are going to pull up the execution pin of the countdown event and create a subtract node. Drag in the time remaining as a get and put it into the subtract node. Pull off the execution pin of the subtract note to create a branch node. Remember the branch node is looking for a condition. From the subtract node pull off the green output and use the less than (&lt;) With the value of zero in the lower pin to check if the time remaining is less zero and hook the red pen to the condition pin in the branch.</p>
<p>As shown in the picture to the right.</p>