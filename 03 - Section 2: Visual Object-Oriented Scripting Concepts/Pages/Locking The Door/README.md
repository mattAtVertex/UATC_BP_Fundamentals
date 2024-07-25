# Locking The Door

<h3><strong>Locking The Door</strong></h3>
<h4><strong>Step 1: Create Condition Logic</strong></h4>
<p>We will need a variable for status of the lock. Return to the blueprint and on the left-hand side find the menu option for variables and click the plus symbol to variables in my blueprint tab. Name the new variable "IsLocked?", we will set the variable type to Boolean. Select the new variable "Islocked?", enable Instance Editable, by clicking on the visibility icon next to the variable. When the eye is open, we can edit it inside of the level editor but if it is closed, we can only alter it in the blueprint.</p>
<h4><strong>Step 2: Engage Condition Logic</strong></h4>
<p>Drag is locked? Into the event graph. When released select "Get IsLocked?" This will allow us to get the current status of the variable, whether it be true or false. Right click and create a branch node. Plug in the "Get IsLocked?" into the red condition pin.</p>
<h4><strong>Step 3: Test Condition Logic</strong></h4>
<p>Return to the level editor, select the BP_Door in the level. On the right-hand side under the details panel look for the "IsLocked?", if this is not visible then we may have forgotten to enable instance editable back in the blueprint. Once it is visible in the details make sure it is set to true. then we can hit play and test our conditional logic. While is locked is true the door should not open, but if we set it to false the door should open as it had before.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>