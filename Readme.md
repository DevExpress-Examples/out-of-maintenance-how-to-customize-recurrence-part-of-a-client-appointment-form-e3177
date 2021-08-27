<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128546224/15.2.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3177)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [CustomEvents.cs](./CS/WebSite/App_Code/CustomEvents.cs) (VB: [CustomEvents.vb](./VB/WebSite/App_Code/CustomEvents.vb))
* [CustomResources.cs](./CS/WebSite/App_Code/CustomResources.cs) (VB: [CustomResources.vb](./VB/WebSite/App_Code/CustomResources.vb))
* [DataHelper.cs](./CS/WebSite/App_Code/DataHelper.cs) (VB: [DataHelper.vb](./VB/WebSite/App_Code/DataHelper.vb))
* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
* [DefaultObjectDataSource.ascx](./CS/WebSite/DefaultObjectDataSource.ascx) (VB: [DefaultObjectDataSource.ascx](./VB/WebSite/DefaultObjectDataSource.ascx))
* [DefaultObjectDataSource.ascx.cs](./CS/WebSite/DefaultObjectDataSource.ascx.cs) (VB: [DefaultObjectDataSource.ascx.vb](./VB/WebSite/DefaultObjectDataSource.ascx.vb))
* [ScriptAppointmentForm.ascx](./CS/WebSite/UserForms/ScriptAppointmentForm.ascx) (VB: [ScriptAppointmentForm.ascx](./VB/WebSite/UserForms/ScriptAppointmentForm.ascx))
* [ScriptAppointmentForm.ascx.cs](./CS/WebSite/UserForms/ScriptAppointmentForm.ascx.cs) (VB: [ScriptAppointmentForm.ascx.vb](./VB/WebSite/UserForms/ScriptAppointmentForm.ascx.vb))
* [ScriptRecurrenceForm.ascx](./CS/WebSite/UserForms/ScriptRecurrenceForm.ascx) (VB: [ScriptRecurrenceForm.ascx](./VB/WebSite/UserForms/ScriptRecurrenceForm.ascx))
* [ScriptRecurrenceForm.ascx.cs](./CS/WebSite/UserForms/ScriptRecurrenceForm.ascx.cs) (VB: [ScriptRecurrenceForm.ascx.vb](./VB/WebSite/UserForms/ScriptRecurrenceForm.ascx.vb))
<!-- default file list end -->
# How to customize recurrence part of a client appointment form 


<p>This example illustrates how to customize some recurrence elements of a client recurrence form:</p><p>- The default selection in the WeeklyRecurrenceControl is made only for specific days. Weekends are hidden.<br />
- The "No end date" option is removed.<br />
- The Max value of Days and Occurrences spin edits is limited.</p><p>Refer to the "~/UserForms/ScriptRecurrenceForm.ascx" and "~/Default.aspx" markup files to learn more (see the corresponding comments in the JS code).</p><p>Note that this example is based on the <a href="https://www.devexpress.com/Support/Center/p/E1547">How to implement a client-side appointment editing form with custom fields</a> example.</p><p>Also, we are going to implement the capability to customize the server recurrence form controls in the context of the <a href="https://www.devexpress.com/Support/Center/p/S31460">Appointment Recurrence Form - Provide the capability to customize the form</a> suggestion.</p>

<br/>


