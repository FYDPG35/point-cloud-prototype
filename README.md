# Point Cloud Generation

First, install OpenDroneMap. Start by cloning the following directory.
```sh
git clone https://github.com/OpenDroneMap/OpenDroneMap.git`
```
Then, create a `projects` directory, and clone this inside of it.
```sh
git clone https://github.com/OpenDroneMap/odm_data_aukerman.git
```
Now, inside the `OpenDroneMap` directory:
```sh
./configure.sh install
## Edit settings.yaml to include the abolute path to the projects folder.
./run.sh odm_data_aukerman
```
Results can be found inside the `projects` directory.

Folder structure:
```
/
    OpenDroneMap/
        configure.sh
        run.sh
    projects/
        odm_data_aukerman/
            images/
```
