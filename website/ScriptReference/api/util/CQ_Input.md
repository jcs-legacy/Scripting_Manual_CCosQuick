# CQ_Input

Input handle.

## Variables

<table>
<tr>
<td>mousePosition</td>
<td>Position of the mouse on the screen.</td>
</tr>
</table>

## Functions

<table>
<tr>
<td>cleanInputBuffer</td>
<td>
Clean the input buffer every frame. Remember to call this in order to get the 
correct output for the event loop.
</td>
</tr>
<tr>
<td>getMouseButtonUp</td>
<td>Check if a mouse button click is up this frame.</td>
</tr>
<tr>
<td>getMouseButtonDown</td>
<td>Check if a mouse button click in this frame.</td>
</tr>
<tr>
<td>getMouseButton</td>
<td>Check if a mouse button is pressed at the moment.</td>
</tr>
<tr>
<td>getKeyUp</td>
<td>Check if the key is up this frame.</td>
</tr>
<tr>
<td>getKeyDown</td>
<td>Check if the key is down this frame.</td>
</tr>
<tr>
<td>getKey</td>
<td>Check if the key is held at the moment.</td>
</tr>
</table>

## Examples

Example.ts

```ts
class Example {
    protected update(dt : number) : void {
        let mousePos : cc.Vec2 = CQ_Input.mousePosition;
        cc.log('Mouse Position: %s - %s', mousePos.x, mousePos.y);
    
        if (CQ_Input.getKeyDown(CQ_KeyCode.A)) {
            cc.log('A key is down!');
        }
    }
}
```
