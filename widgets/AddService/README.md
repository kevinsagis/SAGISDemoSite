# AddService
1.0 - Initial Creation
1.1 - Enhancements made by Stan McShinsky to settings folder, enabling web app builder integration 
1.1.1 - Fixed Layer name bug. Layer list widget will pull in the json.mapName object for dynamic and tiled map services. Not necessary for image services.
1.1.2 - Fixed image service bug. Now checks for the allowRasterFunction in JSON object to infer image service type, and attributes a new variable called imageServiceBool depending on outcome. If the allowRasterFunction object exists in the JSON then imageServiceBool = true, else imageServiceBool = false.
1.1.3 - Fixed image service bug. Added additional code for error handling. 

#Instructions
Drop the unzipped widget folder into your web app builder "Widgets" folder.
AddService widget should be automatically picked up in the header controller widget pool. 
