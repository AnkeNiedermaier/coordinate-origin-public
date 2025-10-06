# PythonPart CoordinateOrigin
The PythonPart is a parametric coordinate cross that can be placed in the drawing file to fulfill two different use-cases:
- mark the internal program origin of ALLPLAN
- set and define a local coordinate system for views and sections

The latter is needed to create local views of objects that do not have an internal coordiate system themselfesves, like for example a 3D body

## Installation
The PythonPart **CoordinateObject** can be installed directly from the Plugin Manager in ALLPLAN.

Alternatively, the corresponding ***.allep** package can be downloaded from the [release page](url of the release).\
 ***.allep** files are ALLPLAN internal setups that can be installed via drag and drop into the program window.

At least the version 2026 is needed to install the PythonPart.

## Installed PythonPart Scripts
If the installation was successfull, the PythonPart **CoordinateOrigin.pyp** can be found
in the ALLPLAN Library:
`Office` → `Allplan GmbH` → `CoordinateOrigin`

Additionaly it is also added to the ActionBar in a new created task area **Coordinates** in the task **Plug-ins**.

## Workflow
The PythonPart is executed directly in ALLPLAN from the **Library palette**. In general, all PythonParts can be stated either with a **double-click** on the entry or per **Drag and Drop**. This shows the corresponding Properties palette and executes the skript.\
