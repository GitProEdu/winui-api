---
-api-id: T:Microsoft.UI.Xaml.Input.Pointer
-api-type: winrt class
---

<!-- Class syntax.
public class Pointer : Windows.UI.Xaml.Input.IPointer
-->

# Microsoft.UI.Xaml.Input.Pointer

## -description

Provides basic properties for the input pointer associated with a single mouse, pen/stylus, or touch contact.

## -remarks

In most cases, we recommend that you get pointer info through the event argument of the pointer event handlers in your chosen language framework (Windows app using JavaScript, UWP app using C++, C#, or Visual Basic, or UWP app using DirectX with C++).

If the event argument doesn't intrinsically expose the pointer details required by your app, you can get access to extended pointer data through the [GetCurrentPoint](pointerroutedeventargs_getcurrentpoint_293890010.md) and [GetIntermediatePoints](pointerroutedeventargs_getintermediatepoints_516826524.md) methods of [PointerRoutedEventArgs](pointerroutedeventargs.md). We recommend using these methods as you can specify the context of the pointer data.

The static [PointerPoint](/uwp/api/windows.ui.input.pointerpoint) methods, [GetCurrentPoint](/uwp/api/windows.ui.input.pointerpoint.getcurrentpoint(system.uint32)) and [GetIntermediatePoints](/uwp/api/windows.ui.input.pointerpoint.getintermediatepoints(system.uint32)), always use the context of the app.
Pointer is an abstract class that is used to describe an input device. This class identifies the input device (such as stylus, finger, or mouse) for each pointer event that occurs.

## -examples

The following code example shows the usage of Pointer class to find the unique [PointerId](pointer_pointerid.md) of each input contact in an app, use the [PointerDeviceType](pointer_pointerdevicetype.md) to ignore specific forms of input (for example, mouse input) and store the Pointer positions. For additional code that uses the Pointer class, see the [Input sample](https://github.com/microsoftarchive/msdn-code-gallery-microsoft/tree/411c271e537727d737a53fa2cbe99eaecac00cc0/Official%20Windows%20Platform%20Sample/Input%20XAML%20user%20input%20events%20sample).


[!code-csharp[Code](../microsoft.ui.xaml.input/code/PointerExample/csharp/BlankPage.xaml.cs#SnippetCode)]

## -see-also
[Input sample](https://github.com/microsoftarchive/msdn-code-gallery-microsoft/tree/411c271e537727d737a53fa2cbe99eaecac00cc0/Official%20Windows%20Platform%20Sample/Input%20XAML%20user%20input%20events%20sample)
