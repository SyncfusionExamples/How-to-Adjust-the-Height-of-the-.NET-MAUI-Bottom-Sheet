# How-to-Adjust-the-Height-of-the-.NET-MAUI-Bottom-Sheet
This repository contains a sample explaining how to adjust the height of the .NET MAUI Bottom Sheet

**Adjust the Height of the .NET MAUI Bottom Sheet**

You can adjust the height of the .NET MAUI Bottom Sheet using various configuration properties such as:

1.FullExpandedRatio

2.HalfExpandedRatio

3.CollapsedHeight

Below are code examples that illustrate how to configure these properties in XAML.

**Example 1: Full Expanded Height:**

**XAML**

```
<bottomSheet:SfBottomSheet x:Name="bottomSheet" FullExpandedRatio="0.8" ContentPadding="10" State="FullExpanded">
    <bottomSheet:SfBottomSheet.BottomSheetContent>
     .   .   .
    </bottomSheet:SfBottomSheet.BottomSheetContent>
</bottomSheet:SfBottomSheet>
```

**Example 2: Half Expanded Height:**

**XAML**

```
<bottomSheet:SfBottomSheet x:Name="bottomSheet" HalfExpandedRatio="0.4" ContentPadding="10" State="HalfExpanded">
    <bottomSheet:SfBottomSheet.BottomSheetContent>
     .   .   .
    </bottomSheet:SfBottomSheet.BottomSheetContent>
</bottomSheet:SfBottomSheet>
```

**Example 3: Collapsed Height**

**XAML**

```
<bottomSheet:SfBottomSheet x:Name="bottomSheet" State="Collapsed" CollapsedHeight="150" ContentPadding="10">
    <bottomSheet:SfBottomSheet.BottomSheetContent>
     .   .   .
    </bottomSheet:SfBottomSheet.BottomSheetContent>
</bottomSheet:SfBottomSheet>

```
