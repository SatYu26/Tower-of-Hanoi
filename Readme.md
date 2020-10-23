# Tower of Hanoi

Tower of Hanoi is a mathematical puzzle where we have three rods and n disks.<br>
The objective of the puzzle is to move the entire stack to another rod,<br>
obeying the following simple rules:<br>
<ul>
<li>Only one disk can be moved at a time.</li>
<li>Each move consists of taking the upper disk from one of the stacks and disk can only be moved if it is the uppermost disk on a stack.</li>
<li>No disk may be placed on top of a smaller disk.</li>
<li><b>Note:</b> Transferring the top (n-1) disks from source rod to Auxiliary rod can again be thought of as a fresh problem and can be solved in the same manner.</li>
</ul>

### Example Output

```
Move disk 1 from source A to destination C
Move disk 2 from source A to destination B
Move disk 1 from source C to destination B
Move disk 3 from source A to destination C
Move disk 1 from source B to destination A
Move disk 2 from source B to destination C
Move disk 1 from source A to destination C
Move disk 4 from source A to destination B
Move disk 1 from source C to destination B
Move disk 2 from source C to destination A
Move disk 1 from source B to destination A
Move disk 3 from source C to destination B
Move disk 1 from source A to destination C
Move disk 2 from source A to destination B
Move disk 1 from source C to destination B
```