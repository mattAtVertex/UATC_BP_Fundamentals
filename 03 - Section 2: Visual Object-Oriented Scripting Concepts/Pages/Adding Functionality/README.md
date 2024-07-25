# Adding Functionality

<h3><strong>Adding Functionality</strong></h3>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18413/preview?verifier=CsRZ1HaOh9ZFQ1HpHpNRlnj0Lt853X91fLn83hs7" alt="image.png" width="594" height="429" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18413" data-api-returntype="File"></p>
<p>&nbsp;</p>
<h4><strong>Step 1: Add Component Overlaps</strong></h4>
<p><span style="color: var(--ic-brand-font-color-dark); font-family: inherit; font-size: 1rem;">Select OverlapZone (Box Collision Component). In the details panel scroll down to the events.</span></p>
<p>We Need:</p>
<ul>
<li>On Component Begin Overlap</li>
<li>On Component End Overlap</li>
</ul>
<h4><strong>Step 2: Create Debug</strong></h4>
<p>It is important to know whether the blueprint is functioning correctly or not, to assure that the blueprint is functioning correctly we are going to add a component to debug.</p>
<p>On the two Red Event nodes drag off the white execution pin and create a "Srint String" node for each overlap node. Change the text in each of them so we know which one is currently functioning. For the begin overlap change the string to "In" and for the end overlap change the string to "Out".</p>
<h4><strong>Step 3: Test</strong></h4>
<p><span style="color: var(--ic-brand-font-color-dark); font-family: inherit; font-size: 1rem;">On the upper left hand corner hit compile and save. Return to the level and Place the BP underscored door in the level. Use the play button To begin interacting in the level. Check the corner of your screen while you're outside of the collision it should read "Out" and when you go into the collision it should read "In".</span></p>
<h4><strong>Step 4: Enable and Disable Input</strong></h4>
<p>Delete the print strings and instead create "Get Player Controller". From the get player controller we will drag off the blue pin and create a "Enable Input" and a "Disable Input". Align the "Enable Input" with Begin Overlap. Align the "Disable Input" with the End Overlap.</p>
<h4><strong>Step 5: Use Input</strong></h4>
<p>Right click and add event "Input Action Interact". Next to it right click and add a "Flip Flop" node. Connect the Input Action to the Flip Flop from the execution pin title "Pressed". Lastly, Right click and add a timeline node. Rename the timeline node to "Open/Close Door".</p>
<h4><strong>Step 6: Create Animation</strong></h4>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18415/preview?verifier=9O6uIF7I9hHe0vYFiETCfU5wwwGCvhZOT989OVvz" alt="image.png" width="457" height="210" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18415" data-api-returntype="File"></p>
<p>Double click on the "Open/Close Door" (Timeline Node), to open a new tab. Click on the "F" shaped button to make a "Float Track", Name it "Door</p>
<p><span style="color: var(--ic-brand-font-color-dark); font-family: inherit; font-size: 1rem;">&nbsp;Rotation".&nbsp; Shift left click to place a key frame.</span></p>
<p style="padding-left: 40px; text-align: left;">Put down two keyframes:</p>
<ul>
<li>The first at 0 seconds and a value of 0</li>
<li>the 2nd at one second and a value of 1</li>
</ul>
<p>Set the "Length" of the animation to 1.</p>
<h4><strong>Step 7: Add Rotation</strong></h4>
<p><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18416/preview?verifier=UOS8jOx903j6qUw92KQOEEKaHTXh4AXpbNTk84n1" alt="image.png" width="588" height="322" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18416" data-api-returntype="File"></p>
<p>Drag out the Door Mesh Component to the Event Graph, add a "Set Relative Rotation". From the "new rotation" purple pin create a "Lerp Rotator", plug in the "door rotation" from the timeline node into the alpha input of the lerp.</p>
<h4><strong>Step 8: test interaction</strong></h4>
<p>To assure that the blueprint is functioning correctly, return to the level and try to interact with the door making sure that it functions as anticipated. After hitting play while not in the collision use the "E" key to make sure that the door does not open. Then move your player to the door collision and hit the "E" key we should get an open and then a close for the second hit of E. Afterwards leave the collision of the door and make sure that we have a disable, and the door does not open when striking E outside of the collision.</p>
<p>&nbsp;</p>