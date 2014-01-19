# SwipePad Theme Example

From version 0.9.16, SwipePad becomes themeable. To demonstrate how to make your own theme, we made this example theme for you.

[![Play](http://developer.android.com/images/brand/en_generic_rgb_wo_60.png)](https://play.google.com/store/apps/details?id=com.calciumion.swipepad.theme.example)

# How to make a custom theme

## Prerequisites 

At the end of the day, your theme would be distributed as an Android app. If you have developed an icon pack before, you'll find most parts familiar. 

* [How to make an Android app](http://developer.android.com/training/basics/firstapp/index.html)
* Knowledge about [Android app resources](http://developer.android.com/guide/topics/resources/providing-resources.html) (drawables, dimensions, etc.)
* [How to distribute an Android app](http://developer.android.com/distribute/googleplay/publish/register.html)

 
## Customizable Elements

SwipePad will try to read following resources from your app, if they are not presented, the corresponding elements in the default theme will be used.

### Drawables (res/drawables-\*/\*)

* swipepad\_icon\_allapps

* swipepad\_icon\_contextpanel

* swipepad\_icon\_home

* swipepad\_icon\_quickpost

* swipepad\_group\_background

* swipepad\_group\_icon\_add

* swipepad\_pad\_background

* swipepad\_pad\_cursor

* swipepad\_pad\_grid\_background

* swipepad\_portal\_rect

* swipepad\_portal\_rect\_empty

* swipepad\_portal\_rect\_hold

* swipepad\_portal\_rect\_hover

* swipepad\_portal\_rect\_selector

* swipepad\_portal\_rect\_empty\_selector

* swipepad\_portal\_ring

* swipepad\_portal\_ring\_empty

* swipepad\_portal\_ring\_hold

* swipepad\_portal\_ring\_hover

* swipepad\_portal\_ring\_selector

* swipepad\_portal\_ring\_empty\_selector

### Colors (res/values/colors.xml)

* swipepad\_group\_item\_text\_color

* swipepad\_group\_title\_color

* swipepad\_pad\_empty\_item\_text\_color

* swipepad\_pad\_item\_text\_color

* swipepad\_pad\_title\_color

### Dimensions (res/values/dimens.xml)

* swipepad\_pad\_cursor\_radius

* swipepad\_pad\_grid\_spacing

* swipepad\_portal\_rect\_padding\_top

* swipepad\_portal\_rect\_padding\_bottom

### Integers (res/values/integers.xml)

* swipepad\_pad\_cursor\_period

### Boolean

* swipepad\_pad\_cursor\_rotate\_clockwise

## Preview

To be recognized as a theme by SwipePad, you need to provide a drawable called **swipepad\_theme\_preview**. This drawable will be presented to users as how your theme would finally look like.
