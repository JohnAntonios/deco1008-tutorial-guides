---
layout: post
title: Mid semester practical
subtitle: An optional prac that will teach you about 3D file types and 3D printing.
---

Mid-sem break - Mini Prac
This is an optional practical to help you learn more about 3D modelling file types and creating a 3D-print ready object to be 3D printed!
File Types for 3D printing.
.blend - this is your Blender file. It is NOT what you import into a slicing program like Cura. This stores data about your Blender scene (models, modifiers, hierarchy etc) and what you edit to produce your model.
.stl - this is the file needed to be exported for each model from Blender. STL stands for Standard Triangle language, it describes the surface geometry of a 3D object without any representation of colour, materials, animations or textures. This format has two variants - ASCII and Binary. Binary is the most common and what we will be exporting in as they are more compact. Slicing programs work best with STL files.
File types for other 3D modelling use cases.
Beyond 3D printing, there are many other applications of 3D modelling. Typically in video game development!
.obj - exports the model’s surface geometry along with its materials and textures. Use this if you only need the materials and textures and nothing else, good for high quality static renders.
.fbx - exports everything. This includes the scene’s information such as lights, cameras and animations applied to objects. You can optionally export selected objects which retrieves that model’s information only. This file is typically used in game engines such as Unity!
Objective 
Your objective is to model this Jack-O-Lantern Pumpkin! Please note, you do not need to 3D print this from Cura, it is just an exercise.
It consists of two parts:
The lid

The body with the face cut out.

Assembled:

Note the walkthrough will show a different pumpkin design!

## Step 1 - Extending the number of Undos
From observations, we have discovered that Blender has a default limit of 50 undos. We can increase this to 256 undos by:
Going to Edit -> Preferences
Going to the System Tab.
Changing the Undo Steps to 256 which is the limit.

## Step 2 - Pumpkin Body
Create a UV Sphere

You can optionally check Face Orientation in the Viewport Overlays.
Go to Top View

5. Go into Edit Mode

6. We want to select the edges that run down the sphere and are opposite of each other. We can do so by selecting Edges and while holding ALT, clicking an edge. This selects an “Edge Loop”

7. We want to select the edge loop that is opposite of this. To do this we need to add on to our current selection, we do this by holding SHIFT + ALT then selecting the edge.

Repeat this until you get a pattern you desire, this is an example:


8. Scale in the selected edges, but not so much they intersect each other.




9. Switch to vertex mode and select the bottom vertex.

We want to make this vertex on the same level as its outer ring vertices so it becomes flat for a better 3D print.
10. With the bottom vertex selected go into the Front View. Move the vertex down until it is flush with the other vertices. 

11. For less support material to be created during the 3D print process, you can repeat the last two steps but for any other vertices that are not flush with its sibling vertices.

12. Select the top vertex.

13. With the top vertex selected go into the Font View. Move the vertex up until it is flush with the other vertices. You can perform step 11 on this top’s vertex outer ring of vertices.


## Step 3 - Pumpkin Lid
1. Go into Top View and ensure faces are selected. Box select all the top faces.

2. Extrude upwards and scale inwards.

3. Complete the stem! It is up to you how you want to rotate and position it.

4. Go into Front View, Edit Mode, Toggle X-Ray mode on and ensure faces are selected. Now box select the top of the pumpkin including the stem created.

5. Separate the lid from the pumpkin by right clicking -> Separate -> Selection.

6. Rename the separated objects now to “Lid” and “Pumpkin” respectively.


7. Select the lid and move it upwards. We now need to create a cylinder to support the closing and opening of the lid as the lid on itself with the step can be weak and not hold in place. You can also scale down the lid slightly to make it a snug fit, ensuring that the scale is between 0.990 to 1




## Step 4 - Pumpkin Lid Support
1. Add a cylinder.

2. Move the cylinder up to the lid, so that it is slightly intersecting it.

3. Solidify the lid with a thickness of 1.8mm. NOT the cylinder.


3. If the cylinder is too long, you can go into Edit mode with faces selected, select the bottom face and move it up. Additionally if you want a more loose fit, you can scale down the cylinder.

4.  Move the cylinder so that it is intersecting within the lid itself, X-Ray will help with this.

5.  Select both the lid and cylinder. Union them!


6. Move the combined lid down and re-scale accordingly such that it is slightly larger than the pumpkin.

7. Ensure the object is renamed to “Lid” and hide. 

## Step 5 - Carving the Pumpkin
1. With the Pumpkin selected go into edit mode and ensure vertex mode is on, and go into Front View.

2. We are going to be using a new tool in Edit mode - the knife tool. This lets us cut new topology in the model.
 
3. Left click on a vertex point and you will see a yellow rectangle with a red line. Think of this as a pen tool.

4. To complete an empty selection press Spacebar.

5. Let’s cut out one of the eyes by making a triangular shape cut, then pressing spacebar to confirm the cut:

The red points indicate new vertices that will be created upon confirming the cut. Note that Blender automatically added these as we connected the vertices together.

You will also notice that a left-click cut is an opaque rectangular point and a cut that is a result of going beyond that vertex to the new selected cut point is a transparent circle.
6. Repeat the same steps but for the right eye.

7. Cut out the nose now, note that if you try to just connect the left corner to the right corner it won’t make the cut through the indented vertex point. In that case we need to select that point as well.


Spacebar to confirm the cut.

8. Now cut out the mouth of the Pumpkin! Using the two techniques shown above.

Now press spacebar to confirm.

9. You will notice that the cut faces have been selected. We can now deselect the faces that we do not need to remove. Change to the select tool (W) Hold SHIFT and left click these faces.


10. Now press Delete on your keyboard -> Faces. Tada!


We have cut out the faces without even needing to do any Boolean differences.
11. If you don’t like the shape of what has been cut, you can individually move these vertices in edit mode.

12. Once you are happy with the carved face, solidify the pumpkin with a thickness at least 1.8mm.

13. Reposition the lid back to the centre and adjust again if you want.

## Step 6 - Exporting parts for 3D printing
1. Select only the Lid. Go to File -> Export -> .STL.

2. Name the file “lid”, ensure Selection Only is ticked. Then press Export STL.

3. Repeat the steps for the Pumpkin, ensuring its name is “pumpkin” or “body”. Note that with Apply Modifiers checked, any modifier that hasn’t been applied yet will be applied in the export process.


## Step 7 - Importing into Cura
From the 3D printing induction, you would have gone through the process of installing and setting up Cura.
1. Double-click the exported Lid STL file and it will open in Cura. If you are on Mac, you will need to open Cura then drag and drop the Lid STL file.

2. Drag and drop in the body STL file.

3. You will now see both of your parts in Cura!

After modelling the Jack-O-Lantern Pumpkin’s parts, we would want to test out the slicing operation in Cura which you should have learned from the 3D printing induction.
Cura is a powerful, open-source slicing engine that is free and easy to use. A great choice by the DMaF Lab!
You would have learned how to import STL files into Cura as shown below.

What you might not have learned is how to arrange your models for efficient printing that is time-saving!
The space that each model occupies in the print bed is not just the model itself, but the brim that is printed around the model. This is shown by the shadow around an object. A brim is a form of base support that ensures your model is always stuck to the printing bed!

So you would need to accommodate for this as well when arranging your models.
A method to arrange models nicely is to use the Arrange All Models feature in Cura.
Simply right-click on the bed and press “Arrange All Models”


This gap would be the absolute maximum between each model, too close and the nozzle might be bumping into the models while it moves between the two.

This gap would be the absolute minimum between each model, too further out and the print would take a longer time and the chance of stringing is greater. Stringing occurs when small strings of plastic are left behind. This is typically due to plastic oozing out of the nozzle while the extruder is moving to a new location. They are also quite annoying to remove.


This would be the recommended distance between the models, roughly ½ of a square in Cura.
Don’t send these off to print, this was just an exercise to get you ready for when you 3D print your own devices!
