# dotnet-console


Install the SDK

wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb

sudo apt-get update
sudo apt-get install -y apt-transport-https
sudo apt-get update
sudo apt-get install -y dotnet-sdk-6.0

Install Mudblazor

dotnet new --install MudBlazor.Templates
dotnet new mudblazor --host wasm --name MyApplication

public Politiker[]? 


var client = new RestClient("https://search.dip.bundestag.de/api/v1/") {
    //Authenticator = new HttpBasicAuthenticator("username", "password")
};


var request = new RestRequest("person");
request.AddHeader("Authorization", "Apikey N64VhW8.yChkBUIJeosGojQ7CSR2xwLf3Qy7Apw464");