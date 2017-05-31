# KaggleTheRainForest
We save the world by analyzing the amazon deforestation from sattelite images

# and win the money

Problem fixes:
1. Requirement: Install pip https://pip.pypa.io/en/stable/installing/
2. pip install module will output to a different site-packages, maybe needs to be added to project interpreter path (not sure if that works yet) or modulues copied over (not optimal)
3. numpy, plotly, tensorflow, kaggle_data can be imported using pycharm
4. Everything that doesn't work throught he pycharm installer should be tryed using pip install
5. cv2 is part of opencv that needs to be installed by hand or copied from this location (https://drive.google.com/open?id=0B5ogfg3UfTlvalllNmFBcGFjLTA) and pasted into python36/lib/site-packages (not optimal)
6. If this error occurs: "No module named _pywrap_tensorflow" (https://stackoverflow.com/questions/42011070/on-windows-running-import-tensorflow-generates-no-module-named-pywrap-tenso) Tensorflow maybe needs visual studio https://www.microsoft.com/en-us/download/confirmation.aspx?id=48145 and an Nvida tool kit for Deep Learning https://developer.nvidia.com/cuda-downloads
