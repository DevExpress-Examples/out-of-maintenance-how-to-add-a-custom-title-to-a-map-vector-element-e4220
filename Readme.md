<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571099/15.2.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4220)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/DXMap_UseTitleOptions/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXMap_UseTitleOptions/MainWindow.xaml))
<!-- default file list end -->
# How to add a custom title to a map vector element

This example illustrates how to add a title to a map's dot.  

To accomplish this, create a [ShapeTitleOptions](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ShapeTitleOptions?p=netframework) object and  assign it to the [MapShape.TitleOptions](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.MapShapeBase.TitleOptions?p=netframework) property. Then, specify the title's text via the [ShapeTitleOptions.Pattern](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ShapeTitleOptions.Pattern?p=netframework) property. 

Note that the title's text can be invisible on a map. So make sure the [ShapeTitleOptions.Visible](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ShapeTitleOptions.Visible?p=netframework) property is set to **true**.


