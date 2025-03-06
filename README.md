# camera-calibrations
store camera calibrations here and vision config files 


Creating a dir structure based on year the files were created.

Majority may be for photonvision API use unless otherwise specified



Cameras used in 2025

Microsoft_LifeCam_HD-3000 - old usb

AlphacamW - usb newer 

Logitech C525 - usb logitech old 

rpiCamer3Wide  rasp pi camera 3 wide

USBOV9281spinel - usb Global shutter Spinel Manuf

limelight2-intcam - limelight 2 internal camera 



# HOW to import a camera calibration json file for a given camera.

I think you have to plug in that camera. Activate it if it's not activated.

Go to Camera tab, and in the Camera Calibration area, notice the 'i' Info column. 

Click on the 'i' for a given resolution. You will there find import and export options for that resolution.

Note some cameras of same model might still have different calibrations, so use at own risk and verify distances it tells you about. 

If you use the Dashboard tab of a camera resolution that is calibrated, the 3d processing mode will give you distance and angles only if calibrated.. so get calibrated.

I attempted to save off the entire settings file as a zip, which ends up being 80MB but upon import, it essentially bricks the installation of Photonvision so don't try to import settings .zip files unless you know how to do that. (may not work).

thank you photonvision which is at: https://github.com/PhotonVision/photonvision/tree/main



