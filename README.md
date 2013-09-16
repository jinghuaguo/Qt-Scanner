Qt-Scanner
==========

This is an experimental 3D-Scanner tool built using Canon ED-SDK and Qt.

This utility will use the Canon ED-SDK to capture the images of the object that is being scanned. The image will be processed to extract points where the line laser hits the object and convert it into a 3D point cloud.

The point cloud will be converted into a mesh and rendered using Qt-OpenGL. 

For the mesh to be used for 3D Printing, the mesh will be further processed into a STL file that can be loaded into the printer.

The modules that will be built are:
1. Image Capture Utility
2. Image Processing Utility
3. Point Cloud Extraction Utility
4. 3D Mesh Generation Utility
5. 3D Mesh Renderer Utility
6. STL Export Utility

Note: Since Canon ED-SDK cannot be distributed due to copyright issues, I cannot upload any binaries for the same. I will be creating placeholder folders where you will need to put your own binaries for the SDK. Rest of the code will be uploaded here to be used by everyone interested.

If you are interested in helping me with this project, feel free to contact me @ info@siddharthv.com



