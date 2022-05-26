# Revit hospital beds occupancy in real time  
  
This project was developed during COVID-19 pandemic between 2020 and 2021.  
  
Check out main code [here!](./PySensor.extension/PySensor.tab/Sensores.panel/leitos.pushbutton/script.py)
  
  
This program is a [PyRevit](https://github.com/eirannejad/pyRevit) Extension that integrates a [BIM](https://en.wikipedia.org/wiki/Building_information_modeling) model and sensors in order to gather hospital beds occupancy data. The main motivation was explore possible solution for the health system collapse through quicker hospital bed occupancy data.  
  
First, the [Autodesk Revit](https://en.wikipedia.org/wiki/Autodesk_Revit) software was used to build a simplified model of a hospital and with the use of a PyRevit add-in, the information collected by the sensors was processed and presented in a simple and intuitive way, facilitating the monitoring of bed occupancy.   
  
Therefore, it was possible to centralize the access to all static information, such as materials, suppliers, schedules and number of beds occupied, as dynamic information, in a quick and visual way.  
   
  
### Technologies used  
- [PyRevit](https://github.com/eirannejad/pyRevit)
- [pyFirmata](https://github.com/tino/pyFirmata)
- [Autodesk Revit](https://www.autodesk.com/products/revit/)
- Python
- XAML for UI
- Arduino UNO
- Infrared sensors

  
### Screenshots  
![User Interface](./PySensor.extension/PySensor.tab/Sensores.panel/leitos.pushbutton/img/ui.png)  
<img src="./PySensor.extension/PySensor.tab/Sensores.panel/leitos.pushbutton/img/eletronic-scheme.png" height="500" width="500"/>  

https://user-images.githubusercontent.com/58222697/170397284-80e7c9d4-884f-402f-9d34-613a057f6232.mp4

















