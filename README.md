# dmenuzathura.
Basic dmenu script for open pdfs with zathura.

> Requires **xdg-open**.

# Install.
Just change a path in script and put him there **/usr/bin/**

Add this line in **config** dwm.

```c
static const char *zatpdf[] = {"/usr/bin/openpdf", NULL};
```
Create a keybind for use the script.
```c
{ MODKEY|ShiftMask,   XK_o, spawn,  {.v=zatpdf}},
```
