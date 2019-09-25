# Installing Plugins for Xi-cam for developement
Similar to installing Xi-cam itself, in order to install plugins you should first activate your virtual enivronment (```venv_Xi-cam```).
Use ```source venv_Xi-cam/bin/actviate``` for Linux or MacOs and use ```venv_Xi-cam\Scripts\activate``` for Windows.

Afterwards you clone the plugin repository and install it with ```pip```. The following uses the LOG-Plugin as an example.
```
git clone https://github.com/synchrotrons/Xi-cam.plugins.Log
cd Xi-cam.plugins.Log 
pip install -e .
```