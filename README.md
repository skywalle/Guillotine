Guillotine
==========

A .NET headless browser, written in C#


### Introduction

The project is a test-driven headless browser, that implements the following features:

* [TODO] Synchronous HTML downloader
* [TODO] Custom header support (user-agent)
* [TODO] Form POST and GET support, including fields
* [TODO] Link support (clicking)
* [TODO] Cookie support
* [TODO] Selector support (jQuery/Sizzler style .class,#id,td etc.)
* [TODO] IWebDriver support
* [TODO] Support automatic batch runs
* [TODO] Some kind of XML format for the batch runs (and webinject XML format support)
 
It's currently work in progress.

### Ideas

* RestSharp for the HTTP library, and not HttpClient. This gives us POST, GET support along with querystring/header support.
* Testable-Turtles-all-the-way-down architecture: composition over inheritence
* StructureMap for dependencies
* HtmlAgility Pack with Sizzler for selector support or...
* CSQuery for HTML parsing
