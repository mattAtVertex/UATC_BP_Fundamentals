# Door With Lock Set Up

<h3><strong>Door with lock setup:</strong></h3>
<h4 style="padding-left: 40px;"><strong>Step 1: Create A New Blueprint</strong></h4>
<p style="padding-left: 40px;"><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18411/preview?verifier=6gplXgwzesMBC1FkUkgU1Y1T3m8Pfn2hNAjXv5DQ" alt="image.png" width="425" height="340" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18411" data-api-returntype="File"></p>
<p style="padding-left: 40px;">In the content browser right click menu, select "Blueprint Class". Choose actor as the parent class and name the new asset "BP _Door"</p>
<h4 style="padding-left: 40px;"><strong>Step 2: Open The Blueprint</strong></h4>
<p style="padding-left: 40px;">In the content browser double click on the new asset BP _door. After a second the blueprint should open onto the viewport.</p>
<h4 style="padding-left: 40px;"><strong>Step 3: Add Component Doorframe</strong></h4>
<p style="padding-left: 40px;">In the upper-left of your Blueprint Editor, click "Add Component". Choose "Static Mesh" and name it "Doorframe_Mesh"</p>
<p style="padding-left: 40px;">In the Details Panel, we can assign values to components to hold by default. Assign <strong>SM_Doorframe </strong>to the <em>Doorframe_Mesh</em> component.</p>
<h4 style="padding-left: 40px;"><strong>Step 4: Add Secondary Component</strong></h4>
<p style="padding-left: 40px;">For this step we need to create another static mesh component. Drag the new component to the Doorframe_Mesh Component. The new component should indent and be located underneath. Now, your new component is a child of the doorframe. Name the new component "Door _Mesh. Assign <strong>SM_Door</strong> to the door mesh component. In the viewport move the door to align the proper way in the frame.</p>
<h4 style="padding-left: 40px;"><strong>Step 5: Add Trigger Component</strong></h4>
<p style="padding-left: 40px;">As we have done in the last two steps, we're going to add another component. Add the "Box Collision" component. Name the new component "OverlapZone". In the viewport move the box collision to the center of the door scale the collision to match the width and height of the door frame. Scale the depth to allow for actors to interact with the collision on either side of the door frame.</p>