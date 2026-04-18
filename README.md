# pyActionmapper
pyActionmapper is a Python-based keybind editor designed for [MechWarrior: Living Legends](https://mechlivinglegends.net/)

Made with the [dearpygui](https://github.com/hoffstadt/DearPyGui) framework, [screeninfo](https://pypi.org/project/screeninfo/), [lxml](https://pypi.org/project/lxml/), and [xmltodict](https://pypi.org/project/xmltodict/).

### TODO:
* **TASK_1**: Implement ``Reset to default`` - resetting to default actionmaps xml
	- **TASK_1_BUG**: Fix issue of tempfile not being reset when resetting edits
* **TASK_2**: Implement ``Help``, a guide to using pyAM
* **TASK_3**: ``Save As`` should immediately open the newly-saved file on successful save, instead of keeping open the temp file.
* **TASK_4**: Implement ``Invert Control`` option for ASF pitch/yaw/roll, VTOL pitch/yaw/roll, and tank autoboost(?)

* `Switch Profile` menu to bring up initial profile selection, can change "don't ask again dialogue" too.
* `Save As` window should open up in the actual Profile folder to make saving the actionmapper.xml easier. Also, `Save` button would be nice.
* `toggle_free_reticle` and `center_free_reticle` seem to have inconsistent behavior. Both key1 and key2 need to be bound (or just non-null?) for it to function. Also might need to be like this between Vehicle and Mech sections, even if just using a mech.

### QoL IDEAS:
* **IDEA_1**: Have the action name in the bind edit popup window be displayed in a distinguishably different color and/or bold
* **IDEA_2**: May need to up scaling of some elements/text

* Section headers to seperate categories of actions like old Actionmapper. Like `Targeting` or `HUD`

### IDEAS FOR WAAAAAAYYYYYY LATER:
* **IDEA_1**: Actual joystick/controller support (might not even need it)
* **IDEA_2**: Custom command maker: for perhaps being able to add stuff like custom paint selections on buy menu open (not sure what else this would be used for, though)
* **IDEA_3**: Graphical, dynamic keybind map a la [UserControlMap.png](https://wiki.mechlivinglegends.net/index.php?title=File:UserControlMap.png) on wiki