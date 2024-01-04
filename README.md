To connect to Azure Key Vault using C# code, you can use the Azure.Identity library and the Azure.Security.KeyVault.Secrets library. Here's an example of how you can achieve this using the latest Azure SDK:

Make sure to install the required NuGet packages:

bash
dotnet add package Azure.Identity
dotnet add package Azure.Security.KeyVault.Secrets


This example uses the `DefaultAzureCredential`, which tries various authentication methods such as environment variables, managed identity, or interactive login, depending on the context it's running in. Adjust the authentication method based on your application's requirements.
