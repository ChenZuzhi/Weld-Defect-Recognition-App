# Weld-Defect-Recognition-App

## 0.About this app
Project name: Weld defect recognition
Version: Beta 1.0

This app can be run on 

## 1.Installation

No need to install anything. All you have to do is to place the folder "App_beta_v1_0" in your computer. 

Noticing: The path that you place the app should not contain any Chinese characters. Also, for windows user, it's better not put this folder in the C:drive(otherwise may cause some operating system permission issues).


## 2.Get start

The entrance of this app is located at:

```
the path you place the folder\App_beta_v1_0\beta1_0.exe
```

Just double click the beta1_0.exe, then the program get start.

Noticing: The anti-virus software like 360 may report a virus, **ignore it**. The app will not do any harm to your computer, don't worry about it.


## 3.How to use the app

If the users open the app successfully, you shall see something like this:

########################Here's an image

Then the users can click the 'select an image' button to open an image(Noticing that *.jpg, *.jpeg, *.png, *.bmp image format are supported):

########################Image2

If the image is opened successfully, the users shall see something like this:

########################Image3

Now the image is ready, the users can click the 'run' button to run the recognition code.

It may take some time to finish the entire progress. Usually, the app will only use the CPU to do the computing, so it will be kind of a slow. 

If the users want to use the GPU computing for this app. Firstly, please make sure your GPU can support GPU computing. Secondly, you need to install the corresponding version of Cuda and Cudnn to your computer.####################More info

The running processing looks like this, the blud rectangle marks the block that the app is working on at the moment.

##########################Image4

When the progress is done. The users will see the final image in the dialog window.

The users can export the image to anywhere that makes them happy.

The finished dialog looks like this:

##########################Image5

Clicking the 'export' button then the users can export the finished image:

###########################Image6

That's it. After that, the users can choose to open another image or exit the app.
