# How-to-Customize-the-Scroll-Button-in-.NET-MAUI-TabView-
TThis repository contains a sample explaining how to Customize the Scroll Button in .NET MAUI TabView.

### ContentSpacing support in .NET MAUI RadioButton

The `ScrollButtonColor` and `ScrollButtonBackground` support features enable seamless customization of scroll button appearance in the TabView control, enhancing visual consistency and user experience.

The following code example illustrate how to Customize ScrollButton in SfTabView.

### XAML

```
    <tabView:SfTabView ScrollButtonBackground="Violet" ScrollButtonColor="Red">
        <!--tab items can be add here >
    </tabView:SfTabView> 
```

### C#

```
    StackLayout stackLayout = new StackLayout();
    var tabView = new SfTabView();
    tabView.ScrollButtonBackground = SolidColorBrush.Violet;
    tabView.ScrollButtonColor = Colors.Red;
    stackLayout.Children.Add(tabView);
    this.Content = stackLayout; 
```


