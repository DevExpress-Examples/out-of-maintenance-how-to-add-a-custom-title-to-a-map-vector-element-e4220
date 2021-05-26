<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/DXMap_UseTitleOptions/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXMap_UseTitleOptions/MainWindow.xaml))
<!-- default file list end -->
# How to add a custom title to a map vector element

This example illustrates how to add a title to a map's dot.  

To accomplish this, create a [ShapeTitleOptions](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ShapeTitleOptions?p=netframework) object and  assign it to the [MapShape.TitleOptions](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.MapShapeBase.TitleOptions?p=netframework) property. Then, specify the title's text via the [ShapeTitleOptions.Pattern](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ShapeTitleOptions.Pattern?p=netframework) property. 

Note that the title's text can be invisible on a map. So make sure the [ShapeTitleOptions.Visible](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ShapeTitleOptions.Visible?p=netframework) property is set to **true**.


