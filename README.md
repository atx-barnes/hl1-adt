# Azure Digital Twin Wind Turbine Demo for HoloLens (1st gen.)

This is a clone of https://github.com/MicrosoftDocs/mslearn-mr-adt-in-unity but has been modified to support the HoloLens (1st gen.)

All of the credential fields in the project have been left blank so you will need to fill those out with all of the required credentials for this demo to work.
For more info on building the entire project follow this tutorial https://docs.microsoft.com/en-us/learn/modules/connect-iot-hololens-azure-digital-twins-unity/

Credentials Setup in Main Scene Include:<br />
- Prefab: ADTConnection > Compenent: ADTDataHandler > Field: Url<br />
- Prefab: ADTTurbineAlertController > Compenent: ADTTurbineAlertController > Field: AdtConnectionInfo (ScriptableObject)<br />
- Prefab: Bing Maps Operate > Compenent: MapSession > Field: DeveloperKey
