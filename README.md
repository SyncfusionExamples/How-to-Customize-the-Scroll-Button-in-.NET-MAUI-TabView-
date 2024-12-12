# How-to-Customize-the-Scroll-Button-in-.NET-MAUI-TabView-
TThis repository contains a sample explaining how to Customize the Scroll Button in .NET MAUI TabView.

### ScrollButton customization support in .NET MAUI TabView

The `ScrollButtonColor` and `ScrollButtonBackground` properties let you customize the color and background of scroll buttons in the TabView control, making it visually appealing and consistent.

The following code example illustrate how to Customize ScrollButton in SfTabView.

### XAML

```
    <tabView:SfTabView ScrollButtonBackground="Violet" ScrollButtonColor="Red">
        <!--tab items can be add here >
    </tabView:SfTabView> 
```

### C#

```
    var tabView = new SfTabView();
    tabView.ScrollButtonBackground = SolidColorBrush.Violet;
    tabView.ScrollButtonColor = Colors.Red; 
```


