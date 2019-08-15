# pyDirectInputKeySend
Send keystrokes to Windows

Intended to be in its own folder and imported like this:
```
from pyDirectInputKeySend.directInputKeySend import DirectInputKeyCodeTable, PressKey, 
from pyDirectInputKeySend.directInputKeySend import ReleaseKey, PressReleaseKey, KeycodeToDIK

# Simulate pressing the "1" key
PressReleaseKey('DIK_1')

# Or the more general version, using the tkinter scan code
# for the key (which happens to be the same as the ASCII
# in this case, it won't always be)
PressReleaseKey(KeycodeToDIK('1')
```
