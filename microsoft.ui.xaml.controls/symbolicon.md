---
-api-id: T:Microsoft.UI.Xaml.Controls.SymbolIcon
-api-type: winrt class
---

<!-- Class syntax.
public class SymbolIcon : Windows.UI.Xaml.Controls.IconElement, Windows.UI.Xaml.Controls.ISymbolIcon
-->

# Microsoft.UI.Xaml.Controls.SymbolIcon

## -description

Represents an icon that uses a glyph from the `SymbolThemeFontFamily` resource as its content.

## -xaml-syntax

```xaml
<SymbolIcon .../>
```

## -remarks

The most common way to specify the icon for an app bar button is to use one of the standard glyphs provided by the `SymbolThemeFontFamily` theme resource, as specified in the [Symbol](symbol.md) enumeration. You can use a `SymbolIcon` by setting the [Icon](appbarbutton_icon.md) property of an [AppBarButton](appbarbutton.md) directly to a value of the [Symbol](symbol.md) enumeration.

The `SymbolIcon` uses the font family defined by the `SymbolThemeFontFamily` theme resource. By default, Windows uses the [**Segoe Fluent Icon**](/windows/uwp/design/style/segoe-ui-symbol-font) font family. If your app is run on Windows 10, version 20H2 or earlier, the Segoe Fluent Icon font family is not available and the `SymbolThemeFontFamily` resource falls back to the [**Segoe MDL2 Asset**](/windows/uwp/design/style/segoe-ui-symbol-font) font family instead.

> [!TIP]
> If the glyph you want is not available in the [Symbol](symbol.md) enumeration, you can use a [FontIcon](fonticon.md) with the default font family anywhere you would use a `SymbolIcon`.

### Foreground

If you use a `SymbolIcon` in an [AppBarButton](appbarbutton.md), you can set the `Foreground` property on the `AppBarButton` or on the `SymbolIcon`. If you set the [Foreground](control_foreground.md) on the `AppBarButton`, it's applied only to the default visual state. It's not applied to the other visual states defined in the `AppBarButton` template, like `MouseOver`. If you set the [Foreground](iconelement_foreground.md) on the `SymbolIcon`, the color is applied to all visual states.

## -examples

> [!TIP]
> For more info, design guidance, and code examples, see [Command bar](/windows/uwp/controls-and-patterns/app-bars).
>
> If you have the **XAML Controls Gallery** app installed, click here to [open the app and see the SymbolIcon in action](xamlcontrolsgallery:/item/AppBarButton).
> + [Get the XAML Controls Gallery app (Microsoft Store)](https://www.microsoft.com/store/productId/9MSVH128X2ZT)
> + [Get the source code (GitHub)](https://github.com/Microsoft/Xaml-Controls-Gallery)

This example shows two ways to use a `SymbolIcon` an [AppBarButton](appbarbutton.md). The second button icon has its [Foreground](iconelement_foreground.md) set to "Green".

```xaml

<AppBarButton Icon="Like" Label="Like"/>

<AppBarButton Label="Accept">
    <AppBarButton.Icon>
        <SymbolIcon Symbol="Accept" Foreground="Green"/>
    </AppBarButton.Icon>
</AppBarButton>
```

## -see-also
[IconElement](iconelement.md), [Symbol enumeration](symbol.md), [Quickstart: Adding app bar buttons](/previous-versions/windows/apps/jj662743(v=win.10)), [AppBarButton](appbarbutton.md), [AppBarToggleButton](appbartogglebutton.md), [BitmapIcon](bitmapicon.md), [FontIcon](fonticon.md), [PathIcon](pathicon.md), [Controls list](/windows/uwp/design/controls-and-patterns/), [Controls by function](/windows/uwp/controls-and-patterns/controls-by-function)
