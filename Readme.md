<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128654150/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4618)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# WPF LayoutControl - Change the LayoutGroup's Size Proportionally

This example demonstrates how to extend the [LayoutControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutControl) and [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutGroup) behavior to support proportional resizing. The created `LayoutItemSize` property allows you to specify relative (star `*`) values.

> **Note**
>
> This custom solution may not support all possible usage scenarios and configurations. If proportional resizing is required, we recommend that you use controls that support this functionality out of the box ([DockLayoutManager](https://docs.devexpress.com/WPF/6820/controls-and-libraries/layout-management/dock-windows/getting-started/dock-layout-manager) with [layout groups](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutGroup) and [items](https://docs.devexpress.com/WPF/7223/controls-and-libraries/layout-management/dock-windows/layout-items) or a standard [Grid](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.grid)).

## Files to Review

* [ExtraLayoutControl.cs](./CS/LayoutControl/DXSample/ExtraLayoutControl.cs) (VB: [ExtraLayoutControl.vb](./VB/LayoutControl/DXSample/ExtraLayoutControl.vb))
* [ExtraLayoutGroup.cs](./CS/LayoutControl/DXSample/ExtraLayoutGroup.cs) (VB: [ExtraLayoutGroup.vb](./VB/LayoutControl/DXSample/ExtraLayoutGroup.vb))
* [MainWindow.xaml](./CS/LayoutControl/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LayoutControl/MainWindow.xaml))

## Documentation

* [LayoutControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutControl)
* [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.LayoutControl.LayoutGroup)
* [DockLayoutManager](https://docs.devexpress.com/WPF/6820/controls-and-libraries/layout-management/dock-windows/getting-started/dock-layout-manager)
