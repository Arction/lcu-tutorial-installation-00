# Installation

##### 1. Create a new Visual Studio project and select either Windows Forms or WPF Application.

##### 2. Set References to LightningChart DLLs choosing the most suitable method for you:

   1. LightningChart trial package is downloaded and unzipped

      * In Solution Explorer, right-click the project node and click Add Reference.

      * In the Add Reference dialog box or \(Reference Manager\), use search field and start typing “LightningChartUltimate”.

      * Move mouse over a component to see a short description.

      * Select the component you want to reference, and then click OK.

      Navigate to the install directory and select the DLLs from there. If you are not able to find them, the default installer directory is

      ```
      C:\Program Files (x86)\Arction\LightningChart Ultimate SDK v.8\LibNET4
      ```

   2. Manage NuGet Packages for Solution

   3. Package Manager Console

      * Check available Arction’s packages on NuGet profile page at the following link [https://www.nuget.org/profiles/Arction](https://www.nuget.org/profiles/Arction)
      * Open Package Manager Console by clicking Tools –
        NuGet
        Package Manager – Package Manager Console.
      * To install the latest LightningChart build for your project, run one the following command in the Package Manager  Console and press Enter.  
        For WindowsForms project:

        ```
        Install-Package LightningChartUltimateWinForms8
        ```

        For Windows Presentation Foundation:

        ```
        Install-Package LightningChartUltimateWPF8
        ```

##### 3. At this point, the solution should build and run, ready to use LightningChart for visualisation.



