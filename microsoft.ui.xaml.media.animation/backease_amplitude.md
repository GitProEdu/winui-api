---
-api-id: P:Microsoft.UI.Xaml.Media.Animation.BackEase.Amplitude
-api-type: winrt property
---

<!-- Property syntax
public double Amplitude { get;  set; }
-->

# Microsoft.UI.Xaml.Media.Animation.BackEase.Amplitude

## -description
Gets or sets the amplitude of retraction associated with a [BackEase](backease.md) animation.

## -xaml-syntax
```xaml
<BackEase Amplitude="double" .../>
```


## -property-value
The amplitude of retraction associated with a [BackEase](backease.md) animation. This value must be greater than or equal to 0. The default is 1.

## -remarks

## -examples
The following example applies a [BackEase](backease.md) easing function to a [DoubleAnimation](doubleanimation.md) to create an animation that retracts slightly at the beginning and end of the animation.


<!--  
      <p xml:space="preserve">
            <TRANSLATE_MANUALLY>
              <externalLink xmlns="http://ddue.schemas.microsoft.com/authoring/2003/5">
                <linkText>Run this sample</linkText>
                <linkUri>http://go.microsoft.com/fwlink/p/?linkid=139798&amp;sref=BackEase_scale</linkUri>
              </externalLink>
            </TRANSLATE_MANUALLY>
          </p>-->



[!code-xaml[BackEase_scale](../microsoft.ui.xaml.media.animation/code/BackEase_scale/csharp/Page.xaml#SnippetBackEase_scale)]

[!code-csharp[BackEase_scale_code](../microsoft.ui.xaml.media.animation/code/BackEase_scale/csharp/Page.xaml.cs#SnippetBackEase_scale_code)]

[!code-vb[BackEase_scale_code](../microsoft.ui.xaml.media.animation/code/BackEase_scale/vbnet/MainPage.xaml.vb#SnippetBackEase_scale_code)]

## -see-also
