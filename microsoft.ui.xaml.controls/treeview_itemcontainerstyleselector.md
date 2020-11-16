---
-api-id: P:Microsoft.UI.Xaml.Controls.TreeView.ItemContainerStyleSelector
-api-type: winrt property
---
<!-- Property syntax.
public StyleSelector ItemContainerStyleSelector { get;  set; }
-->

# Microsoft.UI.Xaml.Controls.TreeView.ItemContainerStyleSelector



## -description

Gets or sets a reference to a custom [StyleSelector](/uwp/api/windows.ui.xaml.controls.styleselector) logic class. The [StyleSelector](/uwp/api/windows.ui.xaml.controls.styleselector) returns different [Style](/uwp/api/windows.ui.xaml.style) values to use for the item container based on characteristics of the object being displayed.



## -property-value

A custom [StyleSelector](/uwp/api/windows.ui.xaml.controls.styleselector) logic class.



## -remarks



## -see-also



## -examples



## -xaml-syntax

```xaml
<TreeView ItemContainerStyleSelector="styleSelectorReference" />
```



## -xaml-values

<dl><dt>styleSelectorReference</dt><dd>styleSelectorReferenceA reference to an existing StyleSelector. Typically this is a keyed resource, which you reference through a {StaticResource} markup extension usage.</dd>
</dl>



