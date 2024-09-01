
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

!!!!!!!!!!!READY PROJECT THAT RESTORES THE LoD2 model FROM A PICTURE!!!!!!!!!
https://github.com/GDAOSU/LOD2BuildingModel

!Reconstruction from unstructured point clouds by taking advantage of the learned visibility of the 3D points 
            in the virtual views and traditional graph-cut based mesh generation.
https://github.com/GDAOSU/vis2mesh/blob/master/README.md

Reconstruction from Point Clouds with Visibility Information
https://github.com/raphaelsulzer/dsrv-data/blob/main/README.md

Example of comparing two meshes to reconstruct a 3D model from a point cloud (does include work with satellite images)
https://github.com/raphaelsulzer/dsr-benchmark

Another example of classic height restoration from satellite images
https://github.com/sherif-abdallah/satellite-data/tree/main

Detailed analysis of 3D shape restoration using images from a car camera, etc.
https://github.com/PJLab-ADG/neuralsim

!!!Shadow Neural Radiance (S-NeRF)!!!
https://github.com/fedesemeraro/surfnerf

!!!!A page containing a large number of repositories with information, algorithms, datasets, techniques 
        for processing satellite images, and even pre-trained models with weights!!!!!!!
https://github.com/satellite-image-deep-learning

!!!!Article about aproximation!!!
https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Approximating_shapes_in_images_with_low-complexity_polygons_CVPR_2020_paper.pdf

!!!Ready Classification!!!(On C)
https://github.com/CGAL/cgal/tree/master/Classification

!!!LOD Generation for Urban Scenes!!!
https://inria.hal.science/hal-01113078/file/manuscript.pdf

!!!Git with a GeometryLibrary!!!
https://github.com/chenzhaiyu/awesome-planar-reconstruction?tab=readme-ov-file

It doesn't solve our problem, but it builds LoD models based on already marked building contours and a point cloud.
https://github.com/tudelft3d/City3D?tab=readme-ov-file

