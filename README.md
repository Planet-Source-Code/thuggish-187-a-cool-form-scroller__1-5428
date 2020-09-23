<div align="center">

## A Cool Form Scroller


</div>

### Description

A really cool code that will first - make the form expand down, then second - it will expand out sideways! No need to customize it to the size you want, it does that automatically. Just pop it in your code. Really easy - good beginner's code!
 
### More Info
 
Put a timer(Timer1) on the form... that's it.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[thuggish\_187](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/thuggish-187.md)
**Level**          |Beginner
**User Rating**    |3.8 (19 globes from 5 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/thuggish-187-a-cool-form-scroller__1-5428/archive/master.zip)





### Source Code

```
Dim frmHeight As Integer
Dim frmWidth As Integer
Private Sub Form_Load()
Timer1.Interval = 1
frmHeight = Form1.Height
frmWidth = Form1.Width
Form1.Height = 100
Form1.Width = 100
End Sub
Private Sub Timer1_Timer()
While Form1.Height < frmHeight
Form1.Height = Form1.Height + 8
Wend
While Form1.Width < frmWidth
Form1.Width = Form1.Width + 8
Wend
Timer1.Enabled = False
End Sub
```

