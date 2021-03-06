---
layout: post
title: Project Conversion | ASP.NET MVC (Essential JS 2) | Syncfusion
description: Project Conversion is a add-in that converts an existing ASP.NET MVC project into a Syncfusion ASP.NET MVC project by adding required Essential JS 2 components
platform: extension
control: Syncfusion Extensions
documentation: ug
---

# Syncfusion Project Conversion

Syncfusion ASP.NET MVC conversion is a Visual Studio add-in that converts an existing ASP.NET MVC application into a Syncfusion ASP.NET MVC (Essential JS 2) Web application by adding the required assemblies and resource files.

I> The Syncfusion ASP.NET MVC (Essential JS 2) Web Application Project Conversion utility is available from v16.3.0.17. 

## Convert into Syncfusion ASP.NET MVC (Essential JS 2) Web Application 

The steps below help you to convert the ASP.NET MVC application to the Syncfusion ASP.NET MVC application via the Visual Studio 2019:

> Before use, the Syncfusion ASP.NET MVC Project Conversion, check whether the **ASP.NET MVC Extensions - Syncfusion** installed or not in Visual Studio Extension Manager by clicking on the Tools -> Extensions and Updates -> Installed for Visual Studio 2017 or lower and for Visual Studio 2019 by clicking on the Extensions -> Manage Extensions -> Installed. Also, check whether the corresponding Essential Studio version build installed or not. If the Essential Studio version is not same for both the Extension and build, then the Project Conversion will not be shown.

1. Open an existing Microsoft ASP.NET MVC Web Application or create a new Microsoft ASP.NET MVC Web Application. 

2. To open Project Conversion Wizard, follow either one of the options below:

   **Option 1:**  

    Click **Syncfusion Menu** and choose **Essential Studio for ASP.NET MVC > Convert to Syncfusion ASP.NET MVC Application…** in **Visual Studio Menu**.

   ![Syncfusion Essential JS 2 ASP.NET MVC Project Conversion via Syncfusion Menu](Project-Conversion_images/Syncfusion_Menu_ProjectConversion.png)

   N> In Visual Studio 2019, Syncfusion menu available under **Extensions** in Visual Studio menu.

   **Option 2:**  

   Right-click the **Project** from Solution Explorer, select **Syncfusion Web**, and choose the **Convert to Syncfusion ASP.NET MVC Application...** Refer to the following screenshot for more information.

   ![Syncfusion Essential JS 2 ASP.NET MVC Project Conversion add-in](Project-Conversion_images/Project-Conversion-img1.png)

3. The Syncfusion ASP.NET MVC Project Conversion window will appear. You can choose the required version of Syncfusion ASP.NET MVC, Assets from, and Themes to convert the application.

   ![Syncfusion Essential JS 2 ASP.NET MVC Project Conversion wizard](Project-Conversion_images/Project-Conversion-img2.png)

   > The versions are loaded from the Syncfusion ASP.NET MVC NuGet packages which published in [NuGet.org](https://www.nuget.org/packages?q=Tags%3A%22aspnetmvc%22syncfusion) and it requires internet connectivity.
   
   The following configurations are used in the Project Conversion Wizard.

   **Assets From:** Load the Syncfusion Essential JS 2 assets to ASP.NET MVC Project, from either NuGet, CDN, or Installed Location.  

   N> *Installed location option will be available only when the Syncfusion Essential JavaScript 2 setup has been installed*.   
   
   **Choose the Theme:** Choose the required theme.
   
4. Check the **“Enable a backup before converting”** checkbox if you want to take the project backup and choose the location.   

5. The required Syncfusion NuGet packages, Scripts and CSS are included in the ASP.NET MVC Web Application. Refer to the following screenshots for more information.

   ![Required reference assemblies included to the Syncfusion Essential JS 2 ASP.NET MVC project](Project-Conversion_images/Project-Conversion-img4.jpg)

   ![Required Scripts and Themes references added in _Layout.cshtml file of the Syncfusion Essential JS 2 ASP.NET MVC project](Project-Conversion_images/Project-Conversion-img5.jpg)
   
   ![Configured required assemblies and namespaces entry in Web.config file of the Syncfusion Essential JS 2 ASP.NET MVC project](Project-Conversion_images/Project-Conversion-img6.jpg)

   if you enabled project backup before converting, the old project was saved in the specified backup path location, as shown below once the conversion process completed.

    ![BackupLocation](Project-Conversion_images/BackupLocation.png)

6. If you installed the trial setup or NuGet packages from nuget.org you must register the Syncfusion license key to your project since Syncfusion introduced the licensing system from 2018 Volume 2 (v16.2.0.41) Essential Studio release. Navigate to the [help topic](https://help.syncfusion.com/common/essential-studio/licensing/license-key#how-to-generate-syncfusion-license-key) to generate and register the Syncfusion license key to your project. Refer to this [blog](https://blog.syncfusion.com/post/Whats-New-in-2018-Volume-2-Licensing-Changes-in-the-1620x-Version-of-Essential-Studio.aspx?_ga=2.11237684.1233358434.1587355730-230058891.1567654773) post for understanding the licensing changes introduced in Essential Studio.
   
## Rendering Control after Syncfusion ASP.NET MVC Conversion

Once you convert your ASP.NET MVC Application to Syncfusion ASP.NET MVC (Essential JS 2) Application using Syncfusion Visual Studio Extension, perform the following steps to render the Syncfusion controls to your project.

1. The CSS, Scripts, Syncfusion References and required Web.config file entries are added to your project by Syncfusion ASP.NET MVC Conversion.

2. Add the required Script and CSS files references in the master page (_Layout.cshtml file). Please refer to below screenshot for more information.

   ![Scripts and Themes references in _Layout.cshtml file of the Syncfusion Essential JS 2 ASP.NET MVC project](Project-Conversion_images\Project-Conversion-img7.jpg)

3. Now, include the Syncfusion controls to your project. Refer to the following screenshot for more information.

   ![Syncfusion Essential JS 2 ASP.NET MVC calendar control code snippet](Project-Conversion_images\Project-Conversion-img8.jpg)
   
4. Run the project and the following output is displayed.

   ![Syncfusion Essential JS 2 ASP.NET MVC calendar control output](Project-Conversion_images\Project-Conversion-img9.jpg)
   
   
   