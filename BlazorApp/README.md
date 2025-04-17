# Building a Web App w/ ASP.NET Core using Blazor

## Getting Started
### Prerequisites:
- macOS 12.0 or later versions

### Necessary Downloads:
- .NET Software Development Kit
Download .NET 9 SDK Arm64 (Apple Silicon)

- Visual Studio Code (VS Code)
- - extension needed: ***C# Dev Kit*** (by microsoft )

### Run the Configure file
open a new terminal and type:
```bash
dotnet
```

Upon successful installation, you should see a helpful output for dotnet options.

## Creating the App
Open the command pallet in VS Code (`Cmd` + `Shift` + `P`) and type **.NET:** to see commands you can run w/ C# Dev Kit.

Find and Select: `.NET: New Project`.

Scroll down and select `Blazor Web App`. You will need to choose a location and a name for this project when prompted.

You may need to sign in at the bottom of VS Code by clicking on the C# icon in a the hexagonal shaped shield.

At this point you now have the scaffolding needed to create a simple Blazor App that is ready to run. See notes.md for further info regarding certain files.

## Running and Debugging the App
Click the `Run and Debug` button, while in the Program.cs file. You may need to select an option from a menu of launch configs. Select ***C#: BlazorAppName [Default]***

Utilize the Debug Panel to stop the web app from running. While viewing the Program.cs file, you may click the `Run` icon dropdown menu and select `Run project associated with this file`.