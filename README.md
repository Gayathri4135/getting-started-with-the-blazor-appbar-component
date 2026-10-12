# Getting Started with the Blazor AppBar Component

## Overview

This sample demonstrates how to integrate and customize the Syncfusion [Blazor AppBar](https://www.syncfusion.com/blazor-components/blazor-appbar) component in a Blazor WebAssembly application. The implementation showcases a navigation header with menu actions, embedded search functionality, external navigation links, layout spacing controls, and custom styling options. It also demonstrates how AppBar positioning, color themes, and button interactions can be configured to create a responsive application toolbar experience.

## Key Features

- Uses the `SfAppBar` component to create the application toolbar.
- Configures AppBar appearance with `ColorMode`and positions the AppBar using `Position`.
- Integrates Syncfusion buttons through the `SfButton` component.
- Displays a menu button using `IconCss="e-icons e-menu"`.
- Uses `AppBarSpacer` to align content within the AppBar.
- Uses `AppBarSeparator` to visually separate toolbar items.
- Implements event handling through the `OnClick` event.
- Uses Blazor `NavigationManager` for programmatic navigation.
- Navigates users to the Syncfusion download page from the Free Trial button.
- Includes external navigation links for Demos, Forums, and Upgrade Guide resources.
- Embeds a search input element inside the AppBar layout.
- Demonstrates custom styling through the `ralign` and `prominent-appbar` CSS classes.
- Includes optional prominent AppBar configuration through the commented `Mode="AppBarMode.Prominent` setting.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone the repository.
2. Open the `MyBlazorApp.sln` solution.
3. Restore all NuGet packages.
4. Set the startup project to `MyBlazorApp`.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.
```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/Index.razor` — Main sample page demonstrating the Syncfusion Blazor AppBar component, button interactions, navigation links, search input integration, layout elements, and custom styling.

- `MyBlazorApp.sln` — Solution file for the sample application.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/appbar/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.