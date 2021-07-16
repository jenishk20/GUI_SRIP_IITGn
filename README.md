
# Computational Lithography

Development of Layout Editor,Viewer and GUI for Computational Lithography modules.



## Installation 

### Dependencies:

```bash 
 -> MarkDown Preview Plus Extension of Chrome  
 -> Python (2.0 or 3.0)
 -> Tkinter Package (For Layout Viewer)
 -> GDSPy Package (For Layout Viewer and Editing)
 -> Numpy Package (For Computations)
 -> Pya Package (For Loading GDS Files and Editing)
```
### Installation Code (Windows):
```bash
Markdown Package Download link:

https://chrome.google.com/webstore/detail/markdown-preview-plus/febilkbfcbhebfnokafefeacimjdckgl
```
```bash
Tkinter Package: pip install tk
```
```bash
GDSPy Package : pip install gdspy
```
```bash
Numpy Package : pip install numpy
```
```bash
PYA Package : pip install pya
```


# Module 1 
## Fragmentation Module
### Deployment


To deploy this project run

```bash
  python3 GUI.py
```
#### Guidelines
```bash
-> Enter Fragmentation Size or length in the textbox of GUI and then press "Do Fragmentation" button and output file path will be displayed on GUI.

-> Now Load the output File using Browse Files option and on the Viewer you will see the GDS file.
```

  
# Module 2 
## Boolean Operations on Layers
### Deployment


To deploy this project run

```bash
  python3 GUI.py
```
#### Guidelines
```bash
-> First of all, Load a Layout having atleast 2 Layers since Boolean
operations can be performed on 2 layers only.

-> Select the layername and datatype by entering values in the textbox
and then select boolean operation from DropDown Menu.

-> Press "Do Boolean Operation", if the details are correct, it will show the output file path. 

-> Load the output file to see the output.

```
