---
author: joshbax-msft
title: Test Members
description: Test Members
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 2725dd47-755b-45a9-b125-94f18f684eba
---

# Test Members


The following table lists the members exposed by the **Machine** type.

## Protected Constructors


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Test</strong></p></td>
<td><p>Overloaded.</p></td>
</tr>
</tbody>
</table>

 

## Public Properties


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>ContentLevels</strong></p></td>
<td><p>This property represents a collection of ContentLevelType values that describe the content level for the test.</p></td>
</tr>
<tr class="even">
<td><p><strong>Description</strong></p></td>
<td><p>This property represents the certification test description.</p></td>
</tr>
<tr class="odd">
<td><p><strong>EstimatedRuntime</strong></p></td>
<td><p>This property represents the time (in seconds) estimated to complete the certification test.</p></td>
</tr>
<tr class="even">
<td><p><strong>ExecutionState</strong></p></td>
<td><p>This property indicates whether there is an instance of this test that is queued, waiting to be run, or not running.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Id</strong></p></td>
<td><p>This property represents the ID value for the certification test. The test ID value is a unique identifier that distinguishes this certification test among other tests and is consistent across all installations.</p></td>
</tr>
<tr class="even">
<td><p><strong>InstanceId</strong></p></td>
<td><p>This property represents the instance ID for this certification test. A job may be needed for every test target in a target family. This instance ID allows the caller to know which unique test this is, even if many tests use the same job.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p>This property represents the name of the certification test.</p></td>
</tr>
<tr class="even">
<td><p><strong>ScheduleOptions</strong></p></td>
<td><p>This property represents the schedule options available for this test.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Status</strong></p></td>
<td><p>This property represents the pass or fail status of this test.</p></td>
</tr>
<tr class="even">
<td><p><strong>TestType</strong></p></td>
<td><p>This property represents the certification test type.</p></td>
</tr>
</tbody>
</table>

 

## Protected Properties


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>LockObject</strong></p></td>
<td><p>(Inherited from <strong>NotificationBase</strong>)</p></td>
</tr>
</tbody>
</table>

 

## Public Methods


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Equals</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="even">
<td><p><strong>GetHashCode</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetMachineRole</strong></p></td>
<td><p>This method retrieves a logical machine set. If there is no machine set associated with this job, this will return <strong>null</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetParameters</strong></p></td>
<td><p>This method retrieves a dictionary collection of test parameters, sorted by parameter name.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetRequirements</strong></p></td>
<td><p>This method retrieves the enumerable list of certification requirements that this test verifies.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetSupportedPlatforms</strong></p></td>
<td><p>This method returns a enumerable list of the architectures supported by this certification test.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetTestResults</strong></p></td>
<td><p>This method retrieves the list of the test results generated during runs of this certification test.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetTests</strong></p></td>
<td><p>This method retrieves all tests needed for this node.</p></td>
</tr>
<tr class="odd">
<td><p><strong>GetTestTargets</strong></p></td>
<td><p>This method retrieves a list of possible test targets for this test.</p></td>
</tr>
<tr class="even">
<td><p><strong>GetType</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="odd">
<td><p><strong>QueueTest</strong></p></td>
<td><p>Overloaded.</p></td>
</tr>
<tr class="even">
<td><p><strong>SetParameter</strong></p></td>
<td><p>Overloaded.</p></td>
</tr>
<tr class="odd">
<td><p><strong>ToString</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
</tbody>
</table>

 

## Protected Methods


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Finalize</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
<tr class="even">
<td><p><strong>MemberwiseClone</strong></p></td>
<td><p>(Inherited from <strong>Object</strong>)</p></td>
</tr>
</tbody>
</table>

 

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20Test%20Members%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



