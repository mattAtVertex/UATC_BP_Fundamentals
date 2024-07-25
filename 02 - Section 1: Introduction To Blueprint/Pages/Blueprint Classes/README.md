# Blueprint Classes

<p>&nbsp;</p>
<p><span>A&nbsp;</span><strong><em>Blueprint Class</em></strong><span>, which is often shortened as&nbsp;</span><strong><em>Blueprint</em></strong><span>, is an asset that allows content creators to easily add functionality on top of existing gameplay classes.&nbsp;</span><em>Blueprints</em><span>&nbsp;are created inside of Unreal Editor visually, instead of by typing code, and saved as assets in a content package. These essentially define a new class or type of Actor which can then be placed into maps as instances that behave like any other type of Actor.</span></p>
<p>&nbsp;</p>
<h3 id="parentclasses" style="padding-left: 40px;">Parent Classes</h3>
<p title="">There are several different types of Blueprints that you can create, however before doing so you will need to specify the<span>&nbsp;</span><strong>Parent Class</strong><span>&nbsp;</span>in which the Blueprint will be based. Selecting a Parent Class allows you to inherit properties from the Parent to use in the Blueprint you are creating.</p>
<p title="">Below are the most common Parent Classes used when creating a new Blueprint:</p>
<table style="border-collapse: collapse; width: 97.9497%; height: 174px;" border="1" cellspacing="10" cellpadding="10">
<tbody>
<tr style="height: 29px;">
<td style="width: 18.174%; text-align: center; height: 29px;">Class Type</td>
<td style="width: 81.7308%; height: 29px;">&nbsp; &nbsp;Description</td>
</tr>
<tr style="height: 29px;">
<td style="width: 18.174%; height: 29px; text-align: center;"><strong>Actor</strong></td>
<td style="width: 81.7308%; height: 29px;"><span>&nbsp; An Actor is an object that can be placed or spawned in the world.</span></td>
</tr>
<tr style="height: 29px;">
<td style="width: 18.174%; height: 29px; text-align: center;"><strong>Pawn</strong></td>
<td style="width: 81.7308%;" align=""><span>&nbsp; A Pawn is an Actor that can be "possessed" and receive input from a Controller.</span></td>
</tr>
<tr style="height: 29px;">
<td style="width: 18.174%; height: 29px; text-align: center;"><strong>Character</strong></td>
<td style="width: 81.7308%;" align=""><span>&nbsp; A Character is a Pawn that includes the ability to walk, run, jump, and more.</span></td>
</tr>
<tr style="height: 29px;">
<td style="width: 18.174%; height: 29px; text-align: center;"><strong>Player Controller</strong></td>
<td style="width: 81.7308%; height: 29px;"><span>&nbsp; A Player Controller is an Actor responsible for controlling a Pawn used by the player.</span></td>
</tr>
<tr style="height: 29px;">
<td style="width: 18.174%; height: 29px; text-align: center;"><strong>Game Mode</strong></td>
<td style="width: 81.7308%; height: 29px;"><span>&nbsp; A Game Mode defines the game being played, its rules, scoring, and other faces of the game type.</span></td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p title="">While the above are the most common, all existing classes can be used as the Parent Class for a new Blueprint (even other Blueprint Classes).</p>
<p title="Click to listen" data-speechify-highlight="true" data-speechify-no-background="true">For example, say you created an<span>&nbsp;</span><strong>Actor Blueprint</strong><span>&nbsp;</span>called<span>&nbsp;</span><em>Animals</em><span>&nbsp;</span>and in it provided some script that all animals share such as<span>&nbsp;</span><em>Hunger</em>,<span>&nbsp;</span><em>Thirst</em>,<span>&nbsp;</span><em>Energy</em>, or whatever script you wanted. Then you created another Blueprint called<span>&nbsp;</span><em>Dogs</em><span>&nbsp;</span>and selected your<span>&nbsp;</span><em>Animals</em><span>&nbsp;</span>Blueprint Class as the Parent Class; you can then provide specific functionality that applies to only dogs within the<span>&nbsp;</span><em>Dogs</em><span>&nbsp;</span>Blueprint such as<span>&nbsp;</span><em>Play Fetch</em><span>&nbsp;</span>or<span>&nbsp;</span><em>Roll Over</em><span>&nbsp;</span>while inheriting the functionality that all animals share from the<span>&nbsp;</span><em>Animals</em><span>&nbsp;</span>Blueprint.</p>