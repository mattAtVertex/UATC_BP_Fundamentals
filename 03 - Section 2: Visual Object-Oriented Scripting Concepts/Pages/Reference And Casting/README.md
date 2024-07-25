# Reference And Casting

<h3><strong>Reference And Casting</strong></h3>
<p>Casting allows one blueprint to reach into another and get information, make variables change and run functions. In this case we need the button to change the value of IsLocked? Which is stored in the BP_Door.</p>
<h4><strong>Step 1: Create A Reference</strong></h4>
<p>Make a new variable and change its type to an object reference. Name this new variable "DoorReference" and check on instance editable. This will allow you to assign the door in the level to be visible.</p>
<h4><strong>Step 2: Add Reference To Logic</strong><img style="float: right;" src="https://vertexschool.instructure.com/courses/289/files/18417/preview?verifier=s4G73rSuToygact1se1quQIKN7WhD3hvUz7OsrWF" alt="image.png" width="451" height="212" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/289/files/18417" data-api-returntype="File"></h4>
<p>By allowing instance editable we can assume the door reference will be assigned to specific BP underscored door instances in the level. Drag the door reference into the event graph and get it from the door reference, search for set "IsLocked?", set it to false and then attach it to pressed on the input action interact node.</p>
<h4><strong>Step 3: Test</strong></h4>
<p>Drag the BP_Button into the level and select it. Navigate to the details panel, look for door reference. Use the selection tool, eyedropper, to click on the lot BP_Door which will be assigned to the door reference.</p>
<h4><strong>Step 4: Play In Editor</strong></h4>
<p>The lock door will not open until you engage the button and press the E key. That will change the variable "ISLocked?" To false and allow you to open the door.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>