# How to Add the Blazor Chips Component to a Blazor WebAssembly App

## Overview

This sample demonstrates how to add and configure the Syncfusion [Blazor Chips](https://www.syncfusion.com/blazor-components/blazor-chips) component in a Blazor WebAssembly application. The application displays a collection of chips with multiple selection, deletion, images, leading text, and a built-in outline style. It also handles chip click events and displays a message when a user interacts with a chip.

## Key Features

- Uses the Syncfusion Blazor `SfChip` component to display a collection of interactive chips.
- Supports selecting multiple chips and removing them using `SelectionType.Multiple` and `EnableDelete`.
- Defines the displayed chip collection through `ChipItems` and individual `ChipItem` components.
- Customizes individual chips with images, leading text, and CSS classes using `LeadingIconUrl`, `LeadingText`, and `CssClass`.
- Handles the `OnClick` event with `DisplayChipText` to update the message displayed below the component.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

### Visual Studio 2022

1. Clone or download this repository.
2. Open the solution file:

   `GettingStarted.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `GettingStarted.Server`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Verify that the configured Syncfusion Blazor Chips are displayed in the application.

### Visual Studio Code

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the executable server project directory:

```bash
cd Server
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal after the application starts.
8. Verify that the configured Syncfusion Blazor Chips are displayed in the application.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Chips getting started documentation](https://blazor.syncfusion.com/documentation/chip/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.