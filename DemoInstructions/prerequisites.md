# Pre-Requisites
aka.ms/VAReadyPreReq

## Download and Install
1. Download and install Visual Studio 2019 for PC or Mac.
1. Download and install the [Virtual Assistant and Skill Templates](https://marketplace.visualstudio.com/items?itemName=BotBuilder.VirtualAssistantTemplate). 
    > Note that Visual Studio on Mac doesn't support VSIX packages, instead clone the [Virtual Assistant Sample](https://github.com/microsoft/botframework-solutions/tree/master/samples/csharp/assistants/virtual-assistant/VirtualAssistantSample). from our repository
1. Download and install [.NET Core SDK](https://www.microsoft.com/net/download).  
1. Download and install [Node Package manager](https://nodejs.org/en/).
1. Download and install [PowerShell Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell?view=powershell-6).
1. Download and install the Bot Framework CLI tools:

   ```
   npm install -g @microsoft/botframework-cli botdispatch luis-apis
   ```
1. Install Botskills CLI tool:
   
   ```
   npm install -g botskills@latest
   ```

1. Download and install the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest) (Minimum version 2.0.64 required).
1. Download and install the [Bot Framework Emulator](https://aka.ms/botframework-emulator).

Note: You might need enable the running of unsigned powershell scripts.  Run the following command from an admin powershell:
   ```
   Set-ExecutionPolicy Unrestricted
   ```


[**Next, create a base Virtual Assistant.**](https://github.com/microsoft/VAReady2020/blob/master/DemoInstructions/createvirtualassistant.md)
