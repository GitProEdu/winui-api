---
-api-id: T:Microsoft.UI.Xaml.Media.Animation.PointKeyFrameCollection
-api-type: winrt class
---

<!-- Class syntax.
public class PointKeyFrameCollection : Windows.Foundation.Collections.IIterable<Windows.UI.Xaml.Media.Animation.PointKeyFrame>, Windows.Foundation.Collections.IVector<Windows.UI.Xaml.Media.Animation.PointKeyFrame>
-->

# Microsoft.UI.Xaml.Media.Animation.PointKeyFrameCollection

## -description
Represents a collection of [PointKeyFrame](pointkeyframe.md) objects that can be individually accessed by index. PointKeyFrameCollection is the value of the [PointAnimation.KeyFrames](pointanimationusingkeyframes_keyframes.md) property.

## -remarks
<!--Begin NET note for IEnumerable support-->
### Enumerating the collection in C# or Microsoft Visual Basic

A PointKeyFrameCollection is enumerable, so you can use language-specific syntax such as **foreach** in C# to enumerate the items in the collection. The compiler does the type-casting for you and you won't need to cast to `IEnumerable<PointKeyFrame>` explicitly. If you do need to cast explicitly, for example if you want to call [GetEnumerator](/dotnet/api/system.collections.ienumerable.getenumerator), cast to [IEnumerable<T>](/dotnet/api/system.collections.generic.ienumerable-1) with a [PointKeyFrame](pointkeyframe.md) constraint.


<!--End NET note for IEnumerable support-->

## -examples

## -see-also
[PointAnimation.KeyFrames](pointanimationusingkeyframes_keyframes.md), [IVector&lt;T&gt;](/uwp/api/windows.foundation.collections.ivector`1), [IIterable&lt;T&gt;](/uwp/api/windows.foundation.collections.iiterable`1), [IList<T>](/dotnet/api/system.collections.generic.ilist-1)
