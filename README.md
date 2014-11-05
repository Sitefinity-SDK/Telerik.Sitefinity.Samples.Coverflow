Telerik.Sitefinity.Samples.Coverflow
====================================
 
[![Build Status](http://sdk-jenkins-ci.cloudapp.net/buildStatus/icon?job=Telerik.Sitefinity.Samples.Coverflow.CI)](http://sdk-jenkins-ci.cloudapp.net/job/Telerik.Sitefinity.Samples.Coverflow.CI/)

## Coverflow widget sample

The CoverFlow widget is a Silverlight-based widget that displays all images uploaded in a selected album of Sitefinity Images library. The sample features a widget created with RadCoverFlow, part of RadControls for Silverlight suite that is delivered with the SDK. The RadCoverFlow is used to create a native Sitefinity widget. 

You can run the Coverflow widget sample with any type of license.

Using the Coverflow widget sample, you can:

* Create a RadCoverFlow widget 
* Register the widget in the Toolbox
* Upload all images necessary for the widget to function in a Sitefinity Images Library


### Requirements

* Sitefinity license
* .NET Framework 4
* Visual Studio 2012
* Microsoft SQL Server 2008R2 or later versions


### Prerequisites

Clear the NuGet cache files. To do this:

1. In Windows Explorer, open the **%localappdata%\NuGet\Cache** folder.
2. Select all files and delete them.

### Nuget package restoration
The solution in this repository relies on NuGet packages with automatic package restore while the build procedure takes place.   
For a full list of the referenced packages and their versions see the [packages.config](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.Coverflow/blob/master/SitefinityWebApp/packages.config) file.    
For a history and additional information related to package versions on different releases of this repository, see the [Releases page](https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.Coverflow/releases).    

### Installation instructions: SDK Samples from GitHub


1. In Solution Explorer, navigate to _SitefinityWebApp_ -> *App_Data* -> _Sitefinity_ -> _Configuration_ and select the **DataConfig.config** file. 
2. Modify the **connectionString** value to match your server address.
3. Build the solution.

For version-specific details about the required Sitefinity NuGet packages for this sample application, click on [Releases]
 (https://github.com/Sitefinity-SDK/Telerik.Sitefinity.Samples.Coverflow/releases).

### Login

To login to Sitefinity backend, use the following credentials: 

**Username:** admin
**Password:** password


### Additional resources

[Developers Guide](http://www.sitefinity.com/documentation/documentationarticles/developers-guide)

[Create a Book widget](http://www.sitefinity.com/documentation/documentationarticles/developers-guide/how-to/how-to-create-a-book-widget)
