# Azure Bot Framework Demo

Here's a demo of setting up an easy setup of Not Framework through Azure portal. 

# Prerequisites 
For this demo there're some things should be done before makeing the steps of the demo. Basicalyl, you should have 
* Basic **C#** knowledge and asynchronous programming
* Visual Studio on Windows/Mac with ASP.NET components installed
* Active Azure Suscription. All offers of Azure described [here](https://habr.com/ru/company/microsoft/blog/352786/ "Как получить подписку Microsoft Azure?") (in Russian).


# Step 1. Create Azure Bot
You should first create a resource for this bot using Azure Portal. The full maunal is [here](https://docs.microsoft.com/en-us/azure/bot-service/abs-quickstart?view=azure-bot-service-4.0 "Create Bot resource using Azure portal").

# Step 2. Download source code on your machine
After you've created a Bot resource in Azure, you can download a source code from the portal ![alt text](https://github.com/ilia2108/BotFrameworkDemo/blob/master/Photos/download.png "Portal").

# Spep 3. Open project using Visual Studio
Then you should unzip and open the folder of your project. By clicking on .sln file Visual Studio would prepare everything for you.

Also, there's another option. You can open Visual Studio and choose "Open a project" option. And also select .sln file.

# Step 4. Run the project
Afer you've opened Visual Studio you can easily run your project by clicking button "Run" or pressing F5. In case of any errors you can:
* restore NuGet packages,
* clean and build solution.

# Step 5. Test using Bot Framework emulator
In the Azure portal (see [step 2](https://github.com/ilia2108/BotFrameworkDemo/master/readme.md#download-source-code-on-your-machine)) you can also install Bot Framework emulator. After installation you need to test your bot. You can find innstructions [here](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0#start-the-emulator-and-connect-to-your-bot).

# Step 6. Deploy your bot to Azure
After your bot is tested we can deploy it to Azure. The full insctructions are [here](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0#start-the-emulator-and-connect-to-your-bot).


# Conclusion
To sum it all up, this demo shows the basic chat-bot with serverless backend in Azure Logic App that can be deployed to Azure. In case of any issues, suggestions or questions don't hesitate to email ilia.ryabukhin@studentpartner.com or write me in Telegram (@ilia_2108).
