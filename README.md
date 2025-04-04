# Uppgift dokumentation

<h2>Steg 1 - Förbered repository</h2>
- git fork av https://github.com/Degendeg/cua24s_gamestore (Via Github UI)<br/>
- git clone https://github.com/JohnFlorinus/GameShop<br/>
- Publish Project via Visual Studio (För produktionsmiljö)<br/>

<h2>Steg 2 - App Service Setup</h2>
- Web App väljs<br/>
- Läggs i resource group "GameShop"<br/>
- Aktivera Continous Deployment och länka GameShop GitHub repository<br/>
- Aktivera Application Insights<br/>
<h4>App Service Specs</h4>
* Publish: Code<br/>
* Runtime stack: .NET 8.0<br/>
* OS: Windows<br/>
* Pricing Plan: Free F1<br/>
