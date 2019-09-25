# SettingsPlugin
Plugins of this base class are used to load, change and store settings.
Each of them has a name, an icon and a widget.
## Important methods
The ```SettingsPlugin``` contains the three important methods ```fromState```, ```apply``` and ```toState```.
### fromState
This method  takes in the deserialized settings and repopulates the widget.
### apply
This method applies the settings.
### toState
This method prepares the settings in a way, that can be serialized by cloudpickle and returns them.
