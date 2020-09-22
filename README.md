<div align="center">

## How to remove the selected item in a listview


</div>

### Description

Shows how to delete an the selected item out of a listview control.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Bill Tarlton](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bill-tarlton.md)
**Level**          |Beginner
**User Rating**    |4.9 (49 globes from 10 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bill-tarlton-how-to-remove-the-selected-item-in-a-listview__10-1578/archive/master.zip)





### Source Code

```
This is pretty simple peice of code but took me a good hour to figure out because there are no examples. I hope this saves you some time.
VOTE if you find it usefull!
If lvw.SelectedItems.Count <> 0 Then
   lvw.Items.RemoveAt(lvw.SelectedItems(0).Index())
  Else ' no items are selected
   MsgBox("No item has been selected.", MsgBoxStyle.Information, "No selection")
  End If
```

