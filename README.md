# tumor_demo

This contains the model (final version) for the `tumor_demo` that is built in the Supplemental document of the [PhysiCell Studio publication](https://www.biorxiv.org/content/10.1101/2023.10.24.563727v2).

Copy the .zip into your PhysiCell `/user_projects` folder and unzip it there, e.g.
```
~/dev/PhysiCell_V1.13.1/user_projects$ unzip tumor_demo.zip
```

then load it from the root directory and compile it:
```
~/dev/PhysiCell_V1.13.1$ make load PROJ=tumor_demo
~/dev/PhysiCell_V1.13.1$ make
... (should create the "project" executable)
```

then run the Studio with this model (by default, it will use `config/PhysiCell_settings.xml`):
```
~/dev/PhysiCell_V1.13.1$ python path-to-the-studio/bin/studio.py -e project
```
