# PyTorch Template


To install a specific environment use:

```conda create -n FAI python=3.9```

If you want to work on medical data make sure to install the dependencies in ```environments/medical_requirements.txt```


### Installation of Batch Viewer
To use use the inspectors you need to install the Batch Viewer Toolkit.


```
git clone https://github.com/FabianIsensee/BatchViewer.git
cd BatchViewer
pip install . 
pip install pyqtgraph pyqt5
```


## Visualize niftis using Fiji

It is also possible to inspect the images using Fiji. 

`https://imagej.net/software/fiji/`

Just install Fiji, then you can open the images easily by choosing File -> Open. If you want to open Dicom Images you have to open it as File -> Import -> Image Sequence.
