---
-api-id: T:Microsoft.UI.Xaml.Controls.InfoBar
-api-type: winrt class
---

# Microsoft.UI.Xaml.Controls.InfoBar

<!--
public class InfoBar : Windows.UI.Xaml.Controls.Control
-->


## -description

An `InfoBar` is an inline notification for essential app-wide messages. The `InfoBar` will take up space in a layout and will not cover up other content or float on top of it. It supports rich content (including titles, messages, icons, and buttons) and can be configured to be user-dismissable or persistent.

## -remarks

Use an `InfoBar` control when a user should be informed of, acknowledge, or take action on a changed application state. The changed state should impact app perception or experience for the user.  

### Control style and template

You can modify the default [Style](../microsoft.ui.xaml/style.md) and [ControlTemplate](controltemplate.md) to give the control a unique appearance. For information about modifying a control's style and template, see [Styling controls](/windows/uwp/controls-and-patterns/styling-controls). The default style, template, and resources that define the look of the control are included in the generic.xaml file. For design purposes, generic.xaml is available in the \(Program Files)\Windows Kits\10\DesignTime\CommonConfiguration\Neutral\UAP\ &lt;SDK version&gt;\Generic folder from a Windows Software Development Kit (SDK) installation. Styles and resources from different versions of the SDK might have different values.

Starting in Windows 10, version 1607 (SDK 14393), generic.xaml includes resources that you can use to modify the colors of a control in different visual states without modifying the control template. In apps that target this software development kit (SDK) or later, modifying these resources is preferred to setting properties such as [Background](control_background.md) and [Foreground](control_foreground.md). For more info, see the [Light-weight styling](/windows/uwp/controls-and-patterns/styling-controls) section of the [Styling controls](/windows/uwp/controls-and-patterns/styling-controls) article.

This table shows the resources used by the InfoBar control.

### All Theme Resources
| Resource Key | Description |
|:-:|:--|
| InfoBarErrorSeverityBackgroundBrush | Error Severity background color 
| InfoBarWarningSeverityBackgroundBrush | Warning Severity background color 
| InfoBarSuccessSeverityBackgroundBrush | Success Severity background color 
| InfoBarInformationalSeverityBackgroundBrush | Informational Severity background color
| InfoBarErrorSeverityIconForeground | Error Severity icon color
| InfoBarWarningSeverityIconForeground | Warning Severity icon color
| InfoBarSuccessSeverityIconForeground | Success Severity icon color
| InfoBarInformationalSeverityIconForeground | Informational Severity icon color
| InfoBarTitleForeground | Title text color
| InfoBarMessageForeground | Message text color 
| InfoBarHyperlinkButtonForeground | Hyperlink button text color
| InfoBarBorderBrush | Border color
| InfoBarBorderThickness | Border thickness
| InfoBarTitleFontSize | Title text font size 
| InfoBarTitleFontWeight | Title text font weight
| InfoBarMessageFontSize | Message text font size
| InfoBarMessageFontWeight | Message text font weight
| InfoBarMinHeight | Minimum height of InfoBar
| InfoBarCloseButtonSize | Close button size
| InfoBarCloseButtonGlyphSize | Close button glyph size
| InfoBarInformationalIconGlyph | Informational Severity icon glyph
| InfoBarErrorIconGlyph | Error Severity icon glyph
| InfoBarWarningIconGlyph | Warning Severity icon glyph
| InfoBarSuccessIconGlyph | Success Severity icon glyph
| InfoBarContentRootPadding | Padding thickness for Content property
| InfoBarIconMargin | Icon margin thickness
| InfoBarIconFontSize | Icon font size
| InfoBarPanelMargin | Panel margin thickness
| InfoBarPanelHorizontalOrientationPadding | Panel padding in horizontal, single-line layout
| InfoBarPanelVerticalOrientationPadding | Panel padding in vertical, multiline layout
| InfoBarTitleHorizontalOrientationMargin | Title margin thickness in the horizontal, single-line layout
| InfoBarTitleVerticalOrientationMargin | Title margin thickness in the vertical, multiline layout
| InfoBarMessageHorizontalOrientationMargin | Message margin thickness in the horizontal, single-line layout
| InfoBarMessageVerticalOrientationMargin | Message margin thickness in the vertical, multiline layout
| InfoBarActionHorizontalOrientationMargin | Action content margin thickness in the horizontal, single-line layout
| InfoBarActionVerticalOrientationMargin | Action content margin thickness in the vertical, multiline layout
| InfoBarActionButtonMinWidth | Action button minimum width
| InfoBarActionButtonHeight | Action button height
| InfoBarActionButtonPadding | Action button padding thickness
| InfoBarActionButtonCornerRadius | Action button corner radius
| InfoBarHyperlinkButtonFontSize | Hyperlink button font size
| InfoBarHyperlinkButtonHeight | Hyperlink button height
| InfoBarHyperlinkButtonPadding | Hyperlink button padding thickness
| InfoBarCloseButtonSymbol | Close button symbol glyph
| InfoBarCloseButtonStyle | Close button style

## -see-also

[InfoBar overview](/windows/uwp/design/controls-and-patterns/infobar)

## -examples

See the **XAML Controls Gallery** sample app for examples of WinUI features and controls.

If you have the **XAML Controls Gallery** app installed, see the [InfoBar](xamlcontrolsgallery:/item/InfoBar) in action.

If you don't have the XAML Controls Gallery app installed, get the WinUI 2.x version from the [Microsoft Store](https://www.microsoft.com/p/xaml-controls-gallery/9msvh128x2zt).

You can also view, clone, and build the XAML Controls Gallery source code from [GitHub](https://github.com/Microsoft/Xaml-Controls-Gallery) (switch to the [WinUI 3 Preview branch](https://github.com/microsoft/Xaml-Controls-Gallery/tree/winui3preview) for WinUI 3 Preview controls and features).

