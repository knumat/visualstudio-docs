---
title: "What's happening to Visual Studio for Mac"
description: "Learn about Visual Studio for Mac retirement and the new Mac development options."
author: j-martens 
ms.author: jmartens
manager: jmartens
ms.date: 09/01/2023
ms.topic: overview
---
# What's happening to Visual Studio for Mac?

Visual Studio for Mac is scheduled for retirement by August 31, 2024 in accordance with Microsoft’s [Modern Lifecycle Policy](/lifecycle/policies/modern).  Visual Studio for Mac 17.6 will continue to be supported until August 31, 2024, with servicing updates for security issues and updated platforms from Apple. 

While the decision has been made to retire Visual Studio for Mac, **we remain committed to our developers on Mac and .NET MAUI** with alternatives like the [C# Dev Kit for Visual Studio Code](https://code.visualstudio.com/docs/csharp/get-started) and other extensions you can use to take advantage of our ongoing investments in .NET development. 

## Support timeline

The following notes outline the timeline for support. 

:::row::: 
    :::column span="1"::: 
        **On or before Aug 31, 2024**
    :::column-end::: 
    :::column span="3"::: 
        Users can still:
        + Create and maintain Mono, .NET 6, and .NET 7 applications. You can also continue to develop, maintain, and publish your apps to app stores.  
        + Access Microsoft Customer Service and Support for Visual Studio for Mac. If you have any support agreements, you can continue to have access to technical support during this period.  
        + Install product updates we release so you can reliably maintain and publish your mobile applications using the latest Xcode, iOS, and Android versions. Microsoft also releases security updates for Visual Studio for Mac.
        Microsoft doesn't plan to add support for [.NET 8](/dotnet/core/whats-new/dotnet-8/) or [C#12](/dotnet/csharp/whats-new/csharp-12/) to Visual Studio for Mac.  We won't extend to any other workloads before retirement either.
    :::column-end::: 
:::row-end:::
:::row::: 
    :::column span="1"::: 
        **After Aug 31, 2024**
    :::column-end::: 
    :::column span="3":::
        Visual Studio for Mac is no longer be supported or maintained starting August 31st, 2024. Starting that date, Visual Studio for Mac remains available as a legacy installation only via my.visualstudio.com for users with Visual Studio subscriptions. 
    :::column-end::: 
:::row-end:::


## Alternative options for developing on the Mac

[Visual Studio Code](https://code.visualstudio.com/docs/editor/whyvscode) is a great place for cloud-native .NET development on the Mac with things like Azure Functions, and more.  As of 2023, premier support is available in Visual Studio Code for .NET cloud, [.NET MAUI](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-maui), and Mobile C# development through the [C# Dev Kit for Visual Studio Code](https://code.visualstudio.com/docs/csharp/get-started). Additionally, [Unity for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=visualstudiotoolsforunity.vstuc) offers support for designing, editing, and debugging Unity scripts as well. These extensions operate natively across all supported platforms, including macOS, and the experience using these are continuously improved as they move from preview to General Availability and beyond.  We are continuing to invest in making these a great experience for C#, .NET MAUI and Unity development on Visual Studio Code. We encourage you submit suggestions and report issues for these extensions in the [Visual Studio Code GitHub project repository](https://github.com/microsoft/vscode-dotnettools/issues).

Visual Studio continues to be the premier tool of choice for .NET/C# development. If you prefer to use a full-fledged IDE, you can use the same license for Visual Studio for Mac on **Visual Studio on Windows** in a VM either on a Mac or in the cloud. You can use VM hosts like Parallels to set up Windows and work in Visual Studio (Windows).  A [cloud-hosted VM from Microsoft Dev Box](/azure/dev-box/overview-what-is-microsoft-dev-box) provides access to the full power of Visual Studio through your Web or native RDP client from a Mac without the overhead of running a virtual machine on your local machine.  

## Get support 

Visual Studio for Mac is licensed under Microsoft’s [Modern Lifecycle Policy](/lifecycle/policies/modern).  Microsoft Customer Service and Support remains available through Visual Studio for Mac’s end-of-life date. You’ll also receive security updates to ensure you can continue to build and publish your existing applications with Visual Studio for Mac.
 

You can continue to submit [Developer Community tickets](/visualstudio/ide/developer-community-guidelines) to report bugs with Visual Studio for Mac before May 2024, but note that Microsoft won't consider suggestions for new features and extended workload support. Additionally, Microsoft might not respond to every ticket, your input is used to help steer investments to ensure Visual Studio for Mac is a quality, performant, and reliable IDE through its end-of-life date. We want to encourage folks to upvote relevant tickets as that increases visibility on our end. 

## Next steps

Try the [C# Dev Kit for Visual Studio Code](https://code.visualstudio.com/docs/csharp/get-started) for premier support for .NET cloud, [.NET MAUI](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-maui), and Mobile C# development.  
