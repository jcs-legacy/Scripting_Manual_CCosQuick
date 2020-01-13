# CQ_Button

Base button for easier implementation.

## Functions

<table>
<tr>
<td>onclick</td>
<td>Callback for this button when is clicked.</td>
</tr>
</table>

### Exampls

```js
export default class Example extends CQ_Button {
    // Override the callback function.
    public onclick() : void {
        cc.log('Button clicked!');
    }
}
```
