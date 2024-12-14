# How-to-Customize-the-Scroll-Button-in-.NET-MAUI-TabView-
TThis repository contains a sample explaining how to Customize the Scroll Button in .NET MAUI TabView.

### ScrollButton customization support in .NET MAUI TabView

The `ScrollButtonColor` and `ScrollButtonBackground` properties let you customize the color and background of scroll buttons in the TabView control.

The following code example illustrate how to Customize ScrollButton in SfTabView.

### XAML

```
    <Grid VerticalOptions="Start">
    <tabView:SfTabView x:Name="tabView" ScrollButtonBackground="Violet" ScrollButtonColor="Red" IsScrollButtonEnabled="True">

        <tabView:SfTabItem Header="John">
            <StackLayout Padding="10">
                <Label Text="John is a software developer with 5 years of experience in building mobile apps." 
                   FontSize="16" 
                   HorizontalOptions="Center" 
                   VerticalOptions="Center" 
                   TextColor="Black" />
            </StackLayout>
        </tabView:SfTabItem>

        <tabView:SfTabItem Header="Emily">
            <StackLayout Padding="10">
                <Label Text="Emily is a graphic designer who specializes in creating stunning visuals and brand identities." 
                   FontSize="16" 
                   HorizontalOptions="Center" 
                   VerticalOptions="Center" 
                   TextColor="Black" />
            </StackLayout>
        </tabView:SfTabItem>
    </tabView:SfTabView>
    </Grid>

```

### C#

```
    var tabView = new SfTabView();
    tabView.ScrollButtonBackground = SolidColorBrush.Violet;
    tabView.ScrollButtonColor = Colors.Red; 
```


