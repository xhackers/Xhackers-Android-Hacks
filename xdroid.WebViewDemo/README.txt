Simple things you always wanted to do but never knew how?

You don't want Title bar ? 
Add Theme = "@android:style/Theme.NoTitleBar" as shown below
[Activity (Label = "YourActivityName",Theme = "@android:style/Theme.NoTitleBar")]

You want to go fullscreen?
Add Theme = "@android:style/Theme.NoTitleBar.Fullscreen" as shown below
[Activity (Label = "YourActivityName",Theme = "@android:style/Theme.NoTitleBar.Fullscreen")]

Check more about what do you can do with Theme styles at 
https://android.googlesource.com/platform/frameworks/base/+/refs/heads/master/core/res/res/values/themes.xml

Things to look for are 
Theme.Dialog
Theme.Dialog.Alert
Theme.SearchBar
Theme.Wallpaper




ss