## Cura plugin for Machinekit and the Turnigy Fabrikator Mini
This plugin enables to use Cura with Machinekit and velocity
extrusion. Furthermore, it also adds a machine configuration for the
[Fabrikator Mini / TinyBoy 3D printer](https://github.com/HKCOTA/TinyBoy).
For more details please take a look at [my blog post](http://machinekoder.com/?p=9).

### Install
Use following command to install the files to your Cura installation.
The make argument `CURA_PATH` specifies the path of your cura installation.

``` bash
sudo make install CURA_PATH=/opt/cura
```

On **Windows** please copy the corresponding files to your Cura
installation:

```
fabrikator_mini.def.json -> <cura_path>/resources/definitions/
fabrikator_mini_platform.stl <cura_path>/resources/meshes/
NGCWriter -> <cura_path>/plugins/
```

On Linux you can optionally install the Machinekit MIME type by running:

``` bash
sudo make mime
```
