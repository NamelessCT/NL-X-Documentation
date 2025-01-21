# Another thing used in C++ that is included in NL-X is ANSI message boxes (MessageBoxA).


MessageBoxA has four parameters:
```
MessageBoxA(
  HWND    hWnd,        // Handle to the owner window
  LPCSTR  lpText,      // Pointer to the message to be displayed
  LPCSTR  lpCaption,   // Pointer to the message box title
  UINT    uType        // Message box style (e.g., OK button, yes/no buttons)
);
```
lpText and lpCaption are just strings ("").

hWnd unsupported, so it needs to be nullptr or 0.

Types of uTypes for MessageBoxA:
```
MB_TOPMOST: Specifies the message box should be displayed as the topmost window.
MB_DEFAULT_DESKTOP_ONLY: Specifies the message box should be displayed on the desktop only.
MB_APPLMODAL: Specifies the message box is an application modal dialog box. This is the default.
MB_SYSTEMMODAL: Specifies the message box is system modal and will block input to all windows except the system.
MB_TASKMODAL: Specifies the message box is task modal and will block input to all windows in the same thread.
MB_DEFBUTTON1: Specifies the first button is the default button.
MB_DEFBUTTON2: Specifies the second button is the default button.
MB_DEFBUTTON3: Specifies the third button is the default button.
MB_ICONERROR (or MB_ICONHAND): Displays an error icon (red X).
MB_ICONQUESTION: Displays a question mark icon.
MB_ICONEXCLAMATION (or MB_ICONWARNING): Displays a warning icon (yellow exclamation).
MB_ICONINFORMATION (or MB_ICONASTERISK): Displays an information icon (blue "i").
MB_OK: Displays an "OK" button.
MB_OKCANCEL: Displays "OK" and "Cancel" buttons.
MB_ABORTRETRYIGNORE: Displays "Abort", "Retry", and "Ignore" buttons.
MB_YESNO: Displays "Yes" and "No" buttons.
MB_YESNOCANCEL: Displays "Yes", "No", and "Cancel" buttons.
MB_RETRYCANCEL: Displays "Retry" and "Cancel" buttons.
```
In NL-X, for the first parameter, you want to have NULL as we can't fully handle it.
An example in a complete script would be:
```
void Main()
{
  FOV(120.0f)
  MessageBoxA(NULL, "You set your FOV to 120", "You set your FOV to 120", MB_OK);
}
```
