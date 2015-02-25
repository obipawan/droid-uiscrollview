# Droid-UIScrollView
**Note:** Still WIP!

An attempt at a ScrollView that scrolls both vertically and horizontally. A UI widget that is readily available for iOS, aptly named [UIScrollView]

##Gradle Dependency

Add this in your project app's ```build.gradle```

```sh
dependencies{
    compile 'com.greycellofp:DroidUIScrollView:1.0.0-SNAPSHOT'
}
```
###Build Caveat
This is not published to a central repo yet, but you could build it locally and install to your local Maven repository

```sh
$ gradle installArchives
```
You'd have to first comment out the gradle dependency in the demo(app) module before you ```installArchives```
### Version
1.0.0

### Development

PRs highly appreciated

### Todo's

 - Write Unit Tests
 - Publish to a central Maven Repository
 - Mimic iOS's Api for [UIScrollView] (or maybe not)
 - Add/Clean Code Comments
 - Implement Nested Scrolling support for [Lollipop]
 - Flags to switch On/Off Vertical/Horizontal scrolling
 - Cleanup code

License
----

Public License

[UIScrollView]:https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIScrollView_Class/index.html
[Lollipop]:http://www.android.com/versions/lollipop-5-0/
