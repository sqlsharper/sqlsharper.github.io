---
layout: page
title: Download
header: Get SQL Sharper
group: navigation
weight: 3
---
{% include JB/setup %}

### SQL Sharper 20
<p>
Environment:
    <ul>
        <li>Windows 10+ (X64)</li>
        <li>.NET Framework 4.7.2+</li>
        <li>SQL Server Management Studio 20/19/18</li>
    </ul>
</p>

[![Download](/images/download.png)](/files/sqlsharper20/SqlSharper20.msi)

### Previous Versions
* [SQL Sharper 2014 (SSMS 2014/2012)](/files/sqlsharper2014/sqlsharper2014_setup.exe)
<!-- 
* [SQL Sharp 2008](http://www.cnsharp.com/files/sqlsharp_2008_2.0.zip)
* [SQL Sharp 2005 (SSMS 2005 SP1+ required)](http://www.cnsharp.com/files/sqlsharp_2005_1.0.zip)  
-->

### Release Notes
*SQL Sharper 20*
- **20.0.0 : 2025.5.15 **
    - New Feature: SSMS 20/19/18 support.
    - Improve: Optimize query history function and persistence strategy.
    - BugFix: Fix the issues in the pervious version.

*SQL Sharper 2014*

- **2.0.0 : 2015.3.22**

    - New Feature: SSMS 2014 support.

*SQL Sharper 2012*

- **1.2.0 : 2014.12.01**

    - New Feature: 'SELECT TOP 100 ROW DESC' in Table ContextMenuStrip.
    - Improve:Implement 'Script Data as INSERT' by row constructor.

- **1.1.3 : 2014.03.27**

    - Improve:Query History popup window no longer always active after command executed,replaced by a ToolStripButton.
    - Improve:Compatibility for SSMS Express.

- **1.1.2 : 2014.01.24**

    - New Feature:Add stored procedure search in Object Explorer.

- **1.1.1 : 2013.12.06**

    - BugFix:Format Char Values for SELECT-IN statement.

- **1.1.0 : 2013.12.03**

    - New Feature:Query history view

- **1.0.0 : 2013.09.10**

    - New Feature:View SQL project files in Windows Explorer by ContextMenuStrip.
    - New Feature:Add DB objects cache which full table schema exporting is depended on it.
    - Improve:Export Results Grid data without query DB once again.
    - Improve:DB object searcher can locate selected object in DB object explorer.
    - Improve:Format SELECT-IN statements judge numeric values&nbsp;intelligently.
    - BugFix:a few bugs in Code Generator.