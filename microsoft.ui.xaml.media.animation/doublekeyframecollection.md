---
-api-id: T:Microsoft.UI.Xaml.Media.Animation.DoubleKeyFrameCollection
-api-type: winrt class
---

<!-- Class syntax.
public class DoubleKeyFrameCollection : Windows.Foundation.Collections.IIterable<Windows.UI.Xaml.Media.Animation.DoubleKeyFrame>, Windows.Foundation.Collections.IVector<Windows.UI.Xaml.Media.Animation.DoubleKeyFrame>
-->

# Microsoft.UI.Xaml.Media.Animation.DoubleKeyFrameCollection

## -description
Represents a collection of [DoubleKeyFrame](doublekeyframe.md) objects that can be individually accessed by index. DoubleKeyFrameCollection is the value of the [DoubleAnimationUsingKeyFrames.KeyFrames](doubleanimationusingkeyframes_keyframes.md) property.

## -remarks
<!--Begin NET note for IEnumerable support-->
### Enumerating the collection in C# or Microsoft Visual Basic

A DoubleKeyFrameCollection is enumerable, so you can use language-specific syntax such as **foreach** in C# to enumerate the items in the collection. The compiler does the type-casting for you and you won't need to cast to `IEnumerable<DoubleKeyFrame>` explicitly. If you do need to cast explicitly, for example if you want to call [GetEnumerator](/dotnet/api/system.collections.ienumerable.getenumerator), cast to [IEnumerable<T>](/dotnet/api/system.collections.generic.ienumerable-1) with a [DoubleKeyFrame](doublekeyframe.md) constraint.


<!--End NET note for IEnumerable support-->

## -examples

## -see-also
[DoubleAnimationUsingKeyFrames.KeyFrames](doubleanimationusingkeyframes_keyframes.md), [IVector&lt;T&gt;](/uwp/api/windows.foundation.collections.ivector`1), [IIterable&lt;T&gt;](/uwp/api/windows.foundation.collections.iiterable`1), [IList<T>](/dotnet/api/system.collections.generic.ilist-1)
