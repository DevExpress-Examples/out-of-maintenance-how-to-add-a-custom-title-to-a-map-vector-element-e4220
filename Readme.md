<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571099/13.1.6%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4220)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/DXMap_UseTitleOptions/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXMap_UseTitleOptions/MainWindow.xaml))
<!-- default file list end -->
# How to add a custom title to a map vector element


<p>This example illustrates how to add a title to a map's dot.  </p><p>To accomplish this,  create a  <a href="http://documentation.devexpress.com/#WPF/clsDevExpressXpfMapShapeTitleOptionstopic"><u>ShapeTitleOptions</u></a> object and  assign it to  the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapShape_TitleOptionstopic"><u>MapShape.TitleOptions</u></a> property. Then,  specify the title's text via the <a href="ShapeTitleOptions.Pattern"><u>ShapeTitleOptions.Pattern</u></a> property.  </p><p>Note that the title's text can be invisible on a map. So make sure the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapShapeTitleOptions_Visibletopic"><u>ShapeTitleOptions.Visible</u></a> property is set to<strong> true</strong>.</p>

<br/>


