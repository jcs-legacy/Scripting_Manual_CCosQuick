# CQ_Animator

Handle multiple animations (CQ_Animation) object for controlling the 
flow/display from each animations that have been manage by this class.


## Variables

<table>
<tr>
<td>animations</td>
<td>List of animation that this animator controls.</td>
</tr>
<tr>
<td>currentAnimation</td>
<td>Current animation that are being displayed.</td>
</tr>
</table>

## Functions

<table>
<tr>
<td>playAnimation</td>
<td>Play the animation by index in the array.</td>
</tr>
<tr>
<td>playOneShot</td>
<td>Play one animation but does not loop.</td>
</tr>
<tr>
<td>stopAnimation</td>
<td>Stop the animation at point/moment and reset the frame 
the first frame of the animation.</td>
</tr>
<tr>
<td>pauseAnimation</td>
<td>Pause the animation at point/moment.</td>
</tr>
<tr>
<td>unPauseAnimation</td>
<td>Unpause the animation at point/moment.</td>
</tr>
</table>

