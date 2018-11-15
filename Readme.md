<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Q205071/Form1.cs) (VB: [Form1.vb](./VB/Q205071/Form1.vb))
* [Program.cs](./CS/Q205071/Program.cs) (VB: [Program.vb](./VB/Q205071/Program.vb))
<!-- default file list end -->
# How to automatically expand the detail view when new master row is added


<p>To accomplish this task, enable the GridView.OptionsDetail.AllowExpandEmptyDetails option for the master grid view and use the GridView.SetMasterRowExpanded method to expand an appropriate master row within the GridView.RowCountChanged event handler. Please note, this scenario won't work with sorted or filtered data source.</p>

<br/>


