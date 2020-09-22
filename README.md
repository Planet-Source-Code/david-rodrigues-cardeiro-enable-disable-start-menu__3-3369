<div align="center">

## Enable / Disable Start Menu


</div>

### Description

Enable or disable the start menu in one line of code.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[David Rodrigues Cardeiro](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/david-rodrigues-cardeiro.md)
**Level**          |Intermediate
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |Microsoft Visual C\+\+
**Category**       |[Security](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/security__3-14.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/david-rodrigues-cardeiro-enable-disable-start-menu__3-3369/archive/master.zip)





### Source Code

```
//Disable Start Button
EnableWindow(FindWindowEx(FindWindow("Shell_TrayWnd", NULL), 0, "Button", NULL), false);
//Enable Start Button
EnableWindow(FindWindowEx(FindWindow("Shell_TrayWnd", NULL), 0, "Button", NULL), true);
```

