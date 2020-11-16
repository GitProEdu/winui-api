---
-api-id: T:Microsoft.UI.Xaml.Core.Direct.IXamlDirectObject
-api-type: winrt interface
---

<!-- Interface syntax.
public interface IXamlDirectObject 
-->

# Microsoft.UI.Xaml.Core.Direct.IXamlDirectObject

## -description

Represents the primary object type that participates in the [XamlDirect](xamldirect.md) set of APIs.

## -remarks

The [XamlDirect](xamldirect.md) APIs allows middleware authors to access most of Xaml at a more primitive level, achieving better CPU and working set performance.  
IXamlDirectObject is the minimal handle to Xaml's internal object instances. It is used only by [XamlDirect](xamldirect.md) APIs.

## -see-also

[Windows.UI.Xaml.Core.Direct namespace](windows_ui_xaml_core_direct.md), [XamlDirect class](xamldirect.md)

## -examples

The following example shows how to create an instance of an internal Xaml object of type Border.

```C#
IXamlDirectObject border = XamlDirect.CreateInstance(XamlTypeIndex.Border);
```
