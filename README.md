<!-- default badges list -->
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Blazor Grid - Disable Selection Checkboxes in Specific Rows

You can display a Selection Column to allow users select data rows. However, you may want to disable selection for specific rows.

![Grid with Disabled Selection Checkbox](result.png)

Use the **DxGridSelectionColumn**'s **CellDisplayTemplate** to put the CheckBox. Specify the lambda expression that defines whether the CheckBox is disabled for the [Enabled](https://docs.devexpress.com/Blazor/DevExpress.Blazor.Base.DxDataEditorBase-2.Enabled) property. Use the template context's [Selected](https://docs.devexpress.com/Blazor/DevExpress.Blazor.GridSelectionColumnCellDisplayTemplateContext.Selected) property to bind the CheckBox's [Checked](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxCheckBox-1.Checked) value.

## Files to Look At

- [Index.razor](./CS/GridDisabledCheckboxes/Pages/Index.razor)

## Documentation

- [Selection Column](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGridSelectionColumn)
- [CellDisplayTemplate](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGridSelectionColumn.CellDisplayTemplate)

## More Examples

- [Show Detail Information in DxFormLayout](https://github.com/DevExpress-Examples/blazor-DxDataGrid-Detail-Information-DxFormLayout)
- [Implement an External Search Panel](https://github.com/DevExpress-Examples/blazor-datagrid-external-search-panel)
