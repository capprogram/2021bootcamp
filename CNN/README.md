We will be using [John Wu's github demo of convolutional neural networks](https://github.com/jwuphysics/convnet-demo) for this tutorial. CNN is a powerful machine learning tool that is often used to classify objects based on images. First, skim over [this long document](https://cs231n.github.io/convolutional-networks/#overview) from a Stanford CS class that explains what CNN are and how they work. I would suggest having this document handy while going over the actual tutorial. John Wu wrote a paper based off what is being done in the CNN demo, so please feel free to read over the abstract of the paper listed on his github. Check out the wikipedia page for Metallicity to better understand what is being determined in this demo. 

To download the tutorial:
* We will be using a version of the tutorial that I had on my harddrive. First, download the .zip file in this repository and then upload it to your google drive.
* Then, extract it in Google Drive using the "Zip Extractor" app. This step may take 10+ minutes. (you must do it this way as google drive doesn't like when you upload more than 100 files at once, and there are a lot of images)
* Once the extraction is done, go into google drive and rename the folder `convnet-demo-20210605T163933Z-001` to just `convnet-demo`
* Go into the folder you just uploaded and then into the notebooks folder and right-click on the file called "Metallicity prediction demo.py" and open it with google colaboratory. 
* Google Colaboratory is very similarly to JupyterLab, so run each cell by pressing shift+enter. 
* In the third cell, you may have to change the code from `PATH = os.path.abspath('/content/drive/My Drive/convnet-demo')` to `PATH = os.path.abspath('/content/drive/My Drive/convnet-demo/convnet-demo')` to represent the slightly different path.  


