# Door Lock Button

<h3><strong>Door Lock Button</strong></h3>
<p>next we will create a button to lock and unlock our door. It will be interactive and also use an exposed variable to target BP_Door it is assigned to</p>
<h4><strong>Step 1: Create Lock</strong></h4>
<p>Create a new blueprint actor and name it "BP_Button".</p>
<h4><strong>Step 2: Add Components</strong></h4>
<p>Open our blueprint for the button. Again, we are going to add a static mesh component and name it "ButtonMesh". Set the static mesh property to "SM_CornerFrame". Also add a box collision component and name it "OverlapZone", Also set it as a child to the button mesh. Scale the box collision so that it covers in front of the button mesh.</p>
<h4><strong>Step 3: Create Interaction Logic</strong></h4>
<p>Just like the door we're going to create a begin overlap and end overlap components. The setup is going to be identical to the door with an enable and disable input as well as a get player controller. And an input action interact node to end off with.&nbsp;</p>
<p>&nbsp;</p>