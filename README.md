# Altium Designer Schematic Templates

<p align="center">
	<img src="images/example1.png?raw=true" width=440>
	&nbsp;
	<img src="images/example2.png?raw=true" width=210>
</p>

This repository contains a collection of schematic templates for Altium Designer, available in A2, A3, A4, and A5 sizes, in both landscape and portrait orientations. These templates are designed to help you create professional-looking schematics for your electronic designs.

The templates are available in the following sizes:

* A2 (420x594mm)
	- Landscape
	- Portrait
* A3 (297x420mm)
	- Landscape
	- Portrait
* A4 (210x297mm)
	- Landscape
	- Portrait
* A5 (148x210mm)
	- Landscape
	- Portrait

# How to Use

### Apply to a new project

1. Copy and paste the template files to Altium template path. (Default: `C:\Users\Public\Public Documents\Altium\AD24\Templates`)
2. In the "New Project" window, you have to define three new parameters:
	- `Prj`: The full project name
	- `Des`: Designer Name
	-  `PN`: Product number

<div align="center">
    <p>
        <img src="images/project_parameters.png?raw=true "add new"" width="700">
    </p>
</div>

3. Create the project.
4. After adding each schematic document to the project, apply the appropriate template depending on the required size and orientation.
5. On the "Parameters" section of each schematic file, change the value of these two parameters:
	- `Title`: The title of each schematic doc. Like Power, MCU, etc.
	- `Revision`: The schematic version.

6. If the designer of the page is different from the designer of other pages, or if you used a previously designed schematic that has another designer, it is necessary to overwrite the designer name. For this, in the Parameters section of that page, add a variable called `Des` and write the name of the designer in it. Now the name of the designer of this document will be different from other schematics.

### Apply to an existing project

1. Copy and paste the template files to Altium template path. (Default: `C:\Users\Public\Public Documents\Altium\AD24\Templates`)
2. Navigate to the "Parameters" tab in the "Project/Project Options" menu.
3. Define three new parameters:
	- `Prj`: The full project name
	- `Des`: Designer Name
	-  `PN`: Product number

<div align="center">
    <p>
        <img src="images/project_options_parameters.png?raw=true "add new"">
    </p>
</div>

4. After adding each schematic document to the project, apply the appropriate template depending on the required size and orientation.
5. On the "Parameters" section of each schematic file, change the value of these two parameters:
	- `Title`: The title of each schematic doc. Like Power, MCU, etc.
	- `Revision`: The schematic version.

6. If the designer of the page is different from the designer of other pages, or if you used a previously designed schematic that has another designer, it is necessary to overwrite the designer name. For this, in the Parameters section of that page, add a variable called `Des` and write the name of the designer in it. Now the name of the designer of this document will be different from other schematics.

