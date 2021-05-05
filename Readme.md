<!-- default file list -->
*Files to look at*:

* [ExtraLayoutControl.cs](./CS/LayoutControl/DXSample/ExtraLayoutControl.cs) (VB: [ExtraLayoutControl.vb](./VB/LayoutControl/DXSample/ExtraLayoutControl.vb))
* [ExtraLayoutGroup.cs](./CS/LayoutControl/DXSample/ExtraLayoutGroup.cs) (VB: [ExtraLayoutGroup.vb](./VB/LayoutControl/DXSample/ExtraLayoutGroup.vb))
* [MainWindow.xaml](./CS/LayoutControl/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LayoutControl/MainWindow.xaml))
<!-- default file list end -->
# How to change the LayoutGroup's size proportionally


This example demonstrates how to extend [LayoutControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutControl) and [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutGroup) to support proportional resizing. Please note that this custom solution may not support all possible usage scenarios/configurations. If proportional resizing is required, we recommend that you use controls that support this functionality out of the box ([DockLayoutManager](https://docs.devexpress.com/WPF/6820/controls-and-libraries/layout-management/dock-windows/getting-started/dock-layout-manager) with [layout groups](https://docs.devexpress.com/WPF/6824/controls-and-libraries/layout-management/dock-windows/docking-functionality/layout-groups) and [items](https://docs.devexpress.com/WPF/7223/controls-and-libraries/layout-management/dock-windows/layout-items) or a standard [Grid](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.grid)).

