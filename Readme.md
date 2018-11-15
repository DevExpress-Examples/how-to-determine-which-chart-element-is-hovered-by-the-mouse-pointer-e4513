<!-- default file list -->
*Files to look at*:

* [MainPage.xaml](./CS/DetermineHoveredElements/MainPage.xaml) (VB: [MainPage.xaml.vb](./VB/DetermineHoveredElements/MainPage.xaml.vb))
* [MainPage.xaml.cs](./CS/DetermineHoveredElements/MainPage.xaml.cs) (VB: [MainPage.xaml.vb](./VB/DetermineHoveredElements/MainPage.xaml.vb))
<!-- default file list end -->
# How to determine which chart element is hovered by the mouse pointer


<p>This example demonstrates how to calculate the hit information for the chart element over which the mouse pointer is hovering. </p><br />
<p>To accomplish this, handle the <strong>ChartControl.MouseMove</strong> event, obtain the current chart element via the <a href="http://documentation.devexpress.com/#Silverlight/DevExpressXpfChartsChartControl_CalcHitInfotopic"><u>ChartControl.CalcHitInfo</u></a> method, and if the element is not <strong>null</strong> (<strong>Nothing</strong> in Visual Basic), display its information.</p><br />


<br/>


