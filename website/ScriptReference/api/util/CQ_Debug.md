# CQ_Debug

Provide debug and logger utilities.

## Functions

<table>
<tr>
<td>log</td>
<td>Log the information message.</td>
</tr>
<tr>
<td>warn</td>
<td>Log the warning message.</td>
</tr>
<tr>
<td>error</td>
<td>Log the error message.</td>
</tr>
</table>

## Examples

```ts
CQ_Debug.log('This is a log message!');
CQ_Debug.warn('This is a warning message!');
CQ_Debug.error('This is a error message!');
```

output

```
[LOG] This is a log message!
[WARNING] This is a warning message!
[ERROR] This is a eeror message!
```
