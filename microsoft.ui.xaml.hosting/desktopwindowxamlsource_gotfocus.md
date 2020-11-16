---
-api-id: E:Microsoft.UI.Xaml.Hosting.DesktopWindowXamlSource.GotFocus
-api-type: winrt event
---

<!-- Event syntax.
public event TypedEventHandler GotFocus<DesktopWindowXamlSource, DesktopWindowXamlSourceGotFocusEventArgs>
-->

# Microsoft.UI.Xaml.Hosting.DesktopWindowXamlSource.GotFocus

## -description
Occurs when the [DesktopWindowXamlSource](desktopwindowxamlsource.md) gets focus in the desktop application (for example, the user presses the **Tab** key while focus is on the element just before the **DesktopWindowXamlSource**).

## -remarks
When you add a **DesktopWindowXamlSource** to your desktop application, by default the **DesktopWindowXamlSource** does not automatically handle focus navigation via keyboard events such as the **Tab** or arrow keys. Call the [NavigateFocus](desktopwindowxamlsource_navigatefocus_935751221.md) method to programmatically give focus when the user navigates to the **DesktopWindowXamlSource**.

Handle **GotFocus** event to be notified when user enters the **DesktopWindowXamlSource** via some non-keyboard event, such as a mouse click, and you want to keep the state of the UI in the host desktop application up to date.

## -see-also

## -examples
