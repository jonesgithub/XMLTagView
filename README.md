# XMLTagView

A tagView for displaying tags, tag with multiple lines supported, using PureLayout 

XMLTagView is a subClass of UIview to show tag buttons with mutipule lines, it is just like a tableView and all you have to do 
is to implement it's delegate method. It will look like this:

![screenShot1](https://raw.githubusercontent.com/Phelthas/XMLTagView/master/ScreenShots/XMLTagViewDemoScreenShot1.png)

I am inspired by [SKTagView](https://github.com/zsk425/SKTagView) by @zsk425 <br>
and it is based on [PureLayout](https://github.com/smileyborg/PureLayout) by @smileyborg <br>

Actually I think it is better to do this With UICollectionView, but if there are not so many tags XMLTagView is also a good choice.

## How to use
add XMLTagView.h and XMLTagView.m to your project <br>
The rest is just like a UITableView and you could see it in the demo <br>
in order to run the demo you need to run "pod install" first

## Requirements
targeting either iOS 6.0 and above, ARC-enabled.


## LICENSE
XMLTagView is available under the MIT license. See the LICENSE file for more info.
