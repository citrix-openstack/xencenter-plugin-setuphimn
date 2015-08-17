xencenter-himn-plugin
=====================

xencenter-himn-plugin is a XenCenter Plugin to setup Host Internal Management Network (HIMN) on a guest VM. Please be noted that you DONOT need to install Visual Studio or run the make file from a Visual Sutdio Command Prompt.

Prerequisites
-------------

+ PowerShell version 2.0
+ WiX 3.7

Compile
-------

	xencenter-himn-plugin\SetupHIMN\make.cmd

Install
-------

	xencenter-himn-plugin\SetupHIMN\output\SetupHIMN.msi


How to Use
----------

+ Restart XenCenter
+ Right-click on the target VM, and click on the menu item of "Setup HIMN"
+ Input root password of the XenServer in the command prompt that popped up
