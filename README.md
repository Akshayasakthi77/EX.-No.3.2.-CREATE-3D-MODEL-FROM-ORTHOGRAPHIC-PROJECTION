# EX No.3.2. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:02/11/2026
Name:THANISHKA S
Reference No: 26014076
## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

Step 1: Create the Base Flange
1.Start a New Sketch on the XY (Top) Plane.

2.Draw a Center-to-Center Slot (under Create > Slot) along the horizontal axis:
       1.Set the center-to-center distance to 300 mm.
       2.Set the slot width to 120 mm (this creates the R60 mm rounded ends and 420 mm overall length).

3.Draw two circles of diameter 40 mm concentric with the left and right R60 mm arcs.

4.Click Finish Sketch and select Extrude (E):
        1.Select the slot profile (excluding the two 40 mm holes).
        2.Extrude Upward by 30 mm as a New Body.
![image](https://user-images.githubusercontent.com/113594316/198823371-bacc7928-28aa-45dd-a652-8833f95e3ea9.png)

Step 2: Create the Central Arch

1.Start a New Sketch on the XZ (Front) Plane (the vertical plane running lengthwise down the center of the part).

2.Draw a Center Point Arc (under Create > Arc) with its center at the origin on the bottom face:
      1.Set the radius to 110 mm (R110 mm).
      2.Snap both endpoints to the bottom horizontal axis so it forms a half-circle (220 mm wide at the base and 110 mm tall).

3.Draw a horizontal Line connecting the two endpoints of the arc along the bottom edge to close the profile.

4.Click Finish Sketch and select Extrude (E):
        1.Select the semicircle profile.
        2.Set Direction to Symmetric and Measurement to Whole Length.
        3.Enter a total width of 150 mm (75 mm per side).
        4.Set Operation to Join and click OK.


![image](https://user-images.githubusercontent.com/113594316/198823390-0832a221-257e-439f-99b4-1a8beca74b56.png)

Step 3: Cut the Bottom Rectangular Tunnel

1.Start a New Sketch on the XZ (Front) Plane again.

2.Draw a 2-Point Rectangle centered horizontally on the bottom edge:
       1.Set the width to 120 mm (60 mm to the left and 60 mm to the right of the center axis).
       2.Set the height to 60 mm measured from the bottom face.

3.Click Finish Sketch and select Extrude (E):
        1.Select the 120 mm × 60 mm rectangle.
        2.Set Direction to Symmetric and Extent Type to All.
        3.Set Operation to Cut to clear the tunnel completely through the base and arch.

![image](https://user-images.githubusercontent.com/113594316/198823408-d3d678f1-2247-41a2-abdd-b9a8918daef8.png)

Step 4: Add the Top Center Hole

1.Start a New Sketch on the XY (Top) Plane (or create an Offset Plane 110 mm above the bottom face).

2.Draw a Center Diameter Circle at the exact center point of the part (150 mm from each end hole center) with a diameter of 20 mm.

3.Click Finish Sketch and select Extrude (E):
        1.Select the 20 mm circle.
        2.Extrude Downward (or To Object selecting the inner ceiling of the 60 mm cutout) with Operation set to Cut.


![image](https://user-images.githubusercontent.com/113594316/198823415-9d0a9454-b197-44bf-b90f-179c75602500.png)

## INPUT:
<img width="947" height="552" alt="sf" src="https://github.com/user-attachments/assets/636054b5-9d38-49a9-acf7-33997a356983" />

## OUTPUT:
<img width="1600" height="900" alt="WhatsApp Image 2026-11-17 at 9 27 03 PM" src="https://github.com/user-attachments/assets/608f7af0-7639-4004-afe7-e934a9e7a158" />



## RESULT:
Thus, 3D model is created from orthographic projection.



