"# UNET-roofs" 
"Using MobileNetV2 for U-net architecture as encoder" 



ARTICLES OF PARTICULAR IMPORTANCE OR THEORETICAL INTEREST ARE MARKED WITH EXCLAMATION MARKS



An article describing an algorithm for restoring a 3D model from a point cloud using 3 stages
https://isprs-archives.copernicus.org/articles/XLII-2/1191/2018/isprs-archives-XLII-2-1191-2018.pdf

Automatic reconstruction algorithms based on the SURE algorithm(The article provides some mathematical 
                                                                part of the implementation      
                                                                + an illustration of the structure
                                                                of the algorithm as a whole)
https://www.researchgate.net/publication/276090364_SURE_Photogrammetric_Surface_Reconstruction_From_Imagery

Original of low quality 3D Reconstruction
https://github.com/SBCV/SatelliteSurfaceReconstruction

Another Unet roof-segmentation algorithm
https://github.com/MaedeRn/semantic-segmentation-of-building-roof/blob/master/roof_segmentation.py

A model for detecting tiles in a photograph of a roof (possibly, with proper configuration and retraining, 
                                                        it will be able to detect objects in a photograph of a roof)
https://universe.roboflow.com/roofdetection-fspvp/roof-tiles-detection

Model for detecting the edges and slopes of the roof (Perhaps later it will be needed at the stage of 
                                                      identifying clear boundaries of the roof)
https://universe.roboflow.com/proglint-asacd/roof_ridge-segmentation

3D SURFACE RECONSTRUCTION FROM MULTI-PROJECT AND MULTIDATE SATELLITE IMAGES
https://www.researchgate.net/publication/360957720_3D_SURFACE_RECONSTRUCTION_FROM_MULTI-VIEW_AND_MULTI-DATE_GOOGLE_EARTH_SATELLITE_IMAGES_WITH_3D_HOMOGRAPHY-BASED_PROJECTIVE_RECONSTRUCTION

Resolution enhancement of aerial images or satellite images
https://patents.google.com/patent/EP3796252A1/en

Systems and processes for building multiple equiprobable coherent geometrical models of the subsurface
https://patents.google.com/patent/US8600708B1/en

Modeling of 3D objects or surfaces by mesh constructions having optimal quality characteristics and dynamic resolution capabilities
https://patents.google.com/patent/US5886702A/en

Providing a 3d model
https://patents.google.com/patent/WO2014112908A1/en

!!Satellite image three-dimensional reconstruction method and device, electronic equipment and readable storage medium!!
https://patents.google.com/patent/CN116704139A/en

!!Method for 3D reconstruction from satellite imagery!!
https://patents.google.com/patent/US11600042B2/en

!!The polygonal approximation!!(Used to work with car cameras, but can also be used to detect polygon objects)
https://github.com/bperez77/thickedge-polygonal-approximation/tree/master?tab=readme-ov-file

Polygon approximation
https://www.cse.iitb.ac.in/~sharat/icvgip.org/icvgip2002/proceedings/336.pdf

!!!!!!!!The article is not based on clustering by primitives from LIDARa points,!!!!!!!!!!!
                                but on initial semantic segmentation and subsequent reconstruction
                                using a building height inference algorithm for retrieving the heights of the roof 
                                and base using the combination of adaptive filtering and buffer analysis.
https://www.sciencedirect.com/science/article/pii/S092427162030318X#s0055
Automatic 3D building reconstruction from multi-view aerial images with deep learning
