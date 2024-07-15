

### Ensure High DPI awareness on Windows

```py
# Ensure High DPI awareness on Windows
try:
    from ctypes import windll
    windll.shcore.SetProcessDpiAwareness(1)
except:
    pass
```





### Title & Dimension

```py
# -----------------  Title & Dimensions  -----------------------


window.title("Digital Clock")
window.geometry("500x300")
window.resizable(0, 0)
window.configure(bg="white")

# --------------------------------------------------------------
```
