# Things you should know

## What is a Semantic Object?
**WorldObjects** represents Entities Objects such as a Customer, Invoice or Citizen Card, in a semantic way.

Using **WorldObjects**, you can bundle applications that reflect a specific scenario. They allow you to refer to objects in a standardized way, abstracting from concrete implementations of these Objects. 

## WorldObjects in DocDigitizer
**DocDigitizer** offers a framework and a scalable platform, **DocDigitizer WorldObjects**,  where you can create your Entities using semantic language provided by this framework, accessing and managing this Entities using functionalities provided by the platform.

**DocDigitizer WorldObjects** provides semantic language to help create and define your Business Objects, adding properties that define each object and index mechanisms which can be helpful to support semantic query processing.

You can also use semantic objects shipped by with **DocDigitizer WorldObjects**.

## Catalogs in DocDigitizer WorldObjects
 **DocDigitizer WorldObjects** you can choose what information you want to work with, then let the system retrieve the data from the appropriate systems without you knowing what the source systems are.

**DocDigitizer WorldObjects** provide functionalities where you can associate the "data domain" related to each object, this is, associate list of values like "list of countries", which we refer as Catalogs 

This Catalogs can be "managed":
* **Local Catalogs** managed "client-side", where the data can be stored “in code". 
* **Remote Catalogs** managed "server-side", where the data can be store in Database or can be obtained invoking Services/API.

You can also use Catalogs (and their related semantic objects) shipped by with **DocDigitizer WorldObjects**.

For more information, please consult our website where you can find guidelines, tutorials, among other information that can help you get started.
[Guidelines](https://developers.docdigitizer.com/v2.0/docs/getting-started-with-docdigitizer-worldobjects)

# Pre-requiremets

The following software should be installed on &quot;client-side&quot;:

| **Name** | **Company** | **Version** |
| --- | --- | --- |
| [.NET Core](https://dotnet.microsoft.com/download/dotnet/5.0) | Microsoft | 5 |
| [Visual Studio Code](https://code.visualstudio.com/download) | Microsoft | 1.61+ |

# Setup

## Login
Login using a Google account or Custom:

<img src="resources/Login.png" width="25%" height="25%">

If login successfully, source folders should appear:

<img src="resources/SourceView.png" width="25%" height="25%">

# DocDigitizer
For more information about DocDigitizer and other produts and services provided, please consult our website:
[DocDigitizer](https://www.docdigitizer.com/)
[DocDigitizer - Developers Portal](https://developers.docdigitizer.com)