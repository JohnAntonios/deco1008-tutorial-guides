---
layout: post
title: Week 7 Tutorial - (Assessment 1C) Animation in Blender
subtitle: Assessment 1C - Learning about animations in Blender!
---

This is Week 7's tutorial where you will learn about animation in Blender with your 1B PokeBall and stand.

## Objective

Your objective is to animate your Assessment 1B PokeBall! You will be **required** to produce two animations:

**Turntable**

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/d949bebf-3b9b-4c3b-a59b-3ecac273da99" frameborder="0"></iframe>

<br />

**Bounce, Roll and Open**

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/09ed1746-b544-439d-b239-6d77c714a956" frameborder="0"></iframe>

<br />

**You may go an extra step and apply two principles of animation to one of the above!**.

---

## Step 1 - Setting up the Blender file

### Video

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/87702c33-c8b3-4f1c-9faf-b88260c8d74c" frameborder="0" class="media">
</iframe>

### Walkthrough written steps

<details markdown="1">
  
  <summary style="color: #E64626;">Click here to see the steps.</summary>

<br />

<p markdown="1">

1. Locate your A1B Blender File.

<br />

![Step 1 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step1-image1.png)`

<br />

2. Duplicate this file (copy + paste) and rename it to **DECO2018_A1C_YourUnikey**.

<br />

![Step 1 - Image 2]({{site.baseurl}}/assets/images/wk7-tutorial/step1-image2.png)

<br />

3. Open this new Blender file.

<br />

![Step 1 - Image 3]({{site.baseurl}}/assets/images/wk7-tutorial/step1-image3.png)

</p>

</details>

<br />

---

## Step 2 - Introducing the Animation workspace

### Video

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/ed8bdba6-1529-4e0c-9f62-19f93e3b19a2" frameborder="0"></iframe>

### Walkthrough written steps

<details markdown="1">
  
  <summary style="color: #E64626;">Click here to see the steps.</summary>

<br />

Congratulations! You have made it past the modelling workspace in Blender! 😃

1. If you previously had **face orientation** on, turn this **off**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step2-image1.png)

2. Press the **Animation** tab in the workspaces ribbon.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step2-image2.png)

   You will notice that quite a bit has changed. Let's break down the new workspace.

3. We now see there are two viewports instead of one viewport. The viewport on the left is where you would preview your animation and the viewport on the right is where you would work on your animation.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step2-image3.png)

4. Below the viewports is a timeline. We will be in this area the most as it is where we can create our animations! If you have used a software like Adobe Animate or Adobe After Effects, it is quite similar in its workflow. It consists of:

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step2-image4.png)

- The **playhead** denoted by the blue vertical bar. This is like the handle you see in a video player on platforms like YouTube.
- The **sheet** which is the area in the centre. This is where your keyframes will be.
- The **player controls** at the bottom-centre. This is a series of buttons to play, pause, rewind, record and jump to certain points, in the animation.

</details>

<br />

---

## Step 3 - Introducing the Camera

### Video

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/065a237c-8d9c-46d7-9976-a2a3a1171330" frameborder="0"></iframe>

### Walkthrough written steps

<details markdown="1">
  
  <summary style="color: #E64626;">Click here to see the steps.</summary>

  <br />

1.  We have previously stated to not worry about the Camera, well now its time to focus on the Camera in Blender!
    The camera is a second pair of eyes, the first pair of eyes is the viewport which is what we as the user see in Blender.
    The camera acts as an internal camera that can be set up for rendering and animations.

    In the **left** viewport, click on the Hamburger menu near the top, then go to View -> Viewpoint -> Camera. You will notice this rectangular box, this is what the Camera is currently seeing.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image1.png)

2.  Try moving the camera around in the **right** viewport, you will notice that it is moving as well in the **left** viewport.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image2.png)

    Our objective for the first animation, the turntable, is to position the camera to have it slightly above the Pokeball + stand as we want the top shell to move up.

    You will notice that is quite difficult to do so, with just manually adjusting the camera in the right viewport.

3.  In the **left** viewport, press **N** on your keyboard or go to View -> Sidebar to open the Sidebar.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image3.png)

4.  Press the **view** tab in the sidebar.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image4.png)

5.  Under the **View Lock** section, check the **Camera to View** checkbox. What this will do is instead of adjusting the viewport when you are using your mouse to move around, it will adjust the camera's view.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image5.png)

6.  Still in the **left** viewport, try to move around with just your mouse. You will now notice that you are updating the camera's position and rotation as well! Much easier 😃

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image6.png)

7.  There is one issue! You will notice that as we zoom out, the Pokeball begins to clip. We need to update the clipping start and end, as the camera has different values for clipping compared to the viewport's.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image7.png)

8.  With the **Camera** Selected, go to the **Object Data Properties** tab. It is denoted by the camera icon.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image8.png)

9.  Change **Clip Start** to 0.01mm and **Clip End** to 1000mm.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image9.png)

</details>

<br />

---

## Step 4 - Turntable animation

### Video

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/aaa502d3-74f6-49c6-89b6-a4de3b38cc97" frameborder="0">
</iframe>

### Walkthrough written steps

<details markdown="1">
  
  <summary style="color: #E64626;">Click here to see the steps.</summary>

  <br />

Now we are going to create our first animation! The turntable animation.

1. Adjust the camera's view to something as shown below, with space at the top and the stand slightly cut-off.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image1.png)

2. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

3. In the **Object Properties** tab, press the circular dot near the **Location Z** value.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image3.png)

   This will create a keyframe in the timeline.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image4.png)

4. You will notice that if you de-select the Top_Shell, its keyframes disappear from the timeline. To still show these keyframes, you will need to toggle off the selected keyframes mode found on the top-right side of the timeline.

   When nothing is selected and selected keyframes mode is **on**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image5.png)

   When nothing is selected and selected keyframes mode is **off**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image6.png)

5. We now want to move the Top_Shell up, this will create the **explosion**. Ensure that the **Top_Shell** is selected. Now press the **record** button located at the bottom of the timeline.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image7.png)

6. Move the playhead to frame **50**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image8.png)

7. Move the **Top_Shell** up on the **Z-axis**, to where it touches the top edge of the rectangle in the **left** viewport.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image9.png)

8. You will now notice that Blender has automatically created the keyframe for us! But it has also annoyingly created a keyframe for every single other property 🙃, but that's okay because they are the same and have not changed.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image10.png)

   You can now turn off **record** mode.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image13.png)

9. Move the playhead to frame **1** and play the animation! You can do this by either pressing **Spacebar** on your keyboard or pressing the right arrow at the bottom of the timeline.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image12.png)
   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image11.png)

   Great work! You have created your first animation in Blender!

10. We can clean up the timeline by removing the redundant keyframes, box select everything but the **Z Location** keyframe.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image14.png)

    Right-click and press **Delete keyframes**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image15.png)

11. Move the playhead to frame **100** and select the keyframe at frame **50**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image16.png)

12. Right-click and press **Duplicate**, this will automatically grab the duplicated keyframe for you to move to a new location.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image17.png)

    Move the duplicated keyframe to frame **100** and left-click to confirm.
    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image18.png)

    This will hold the lifted position of the lid for 50 frames.

    You can re-adjust this length by selecting the duplicated keyframe and pressing **G** to move it to a new location, left-click to confirm.
    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image19.png)

13. Move the playhead to frame **130** and select the keyframe at frame **1**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image20.png)

    Just like the previous step, duplicate the keyframe and move it to frame **130**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image21.png)

    You can move the keyframes and adjust the timings however you like!

14. In the top-left of the timeline area, press the **Editor Type** and select **Graph Editor**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image22.png)

    You will notice that there is nothing but a single line!

15. Zoom out and pan upwards (the controls are exactly like moving the viewport), you will see your keyframes!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image24.png)

16. The graph editor allows us to adjust the **easing** of each keyframe, while still being able to move the keyframes.
    It works exactly like a spline curve!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image25.png)

17. The transition between two keyframes can be adjusted by changing the **Handle Type**. Select a keyframe, right-click -> Handle Type.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image26.png)

    - **Free** - gives you control over both control nodes independently, i.e. moving one won't affect the other.
    - **Aligned** - the standard control, i.e. a bezier curve between the two control nodes.
    - **Vector** - the opposite of **Aligned**, a linear curve between the two control nodes.

18. The type of easing between at least **two** keyframes can be changed by **interpolation**. Select two keyframes and right-click -> Interpolation Mode -> Choose an interpolation and preview to get a different result. Experiment with these and choose the one that feels best to you. Do this for both sides of the animation (opening the lid and closing the lid).

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image27.png)
    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image28.png)

19. Rename the animation by pressing the arrow icon near **Top_Shell** in the scene hierarchy, then pressing the arrow icon near **Animation**. Click on the animation itself, in this case it is called **Top_ShellAction.001** and rename it to "Explode".

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image29.png)

20. We now want to rotate the camera around the exploding Pokeball model. Go to Add -> Empty -> Plain Axes (make sure your 3D cursor is at world origin).

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image30.png)
    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image31.png)

    Rename this to **Camera_Rotator**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image32.png)

21. With the **Camera_Rotator** selected, go into its **Object Properties** and press the circle near the **Rotation Z** value.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image33.png)

22. Press the **record** button and move the playhead to the **end keyframe, (frame 250)**. A quick way to do this is by pressing the right arrow with a bar icon at the bottom-centre.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image34.png)

23. Change the **Rotation Z** value to 360.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image35.png)

    Play the animation and you will see the axes spin seamlessly. Press the **record** button to stop recording.

24. Select the **Camera_Rotator**, then select the **Camera**. It is important to select these in this order. A way to know that you have selected these correctly is by the **Camera** being highlighted in a darker shade of orange and blue, compared to the **Camera_Rotator**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image36.png)

25. Right-click -> Parent -> Object. This will parent the **Camera** to the **Camera_Rotator**. Meaning that the **Camera** will inherit the **Camera_Rotator's** animation!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image37.png)

    Play the animation and you will see the camera spin seamlessly. You will notice that something is a bit weird, the camera slows down towards the end and at the beginning.

26. Switch to **Graph Editor** and select both keyframes (you can do this by either box selecting, or pressing **A** on your keyboard)

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image38.png)

27. Right-click -> Interpolation Mode -> Linear. This will apply a constant rotation to the camera, with no easing mimicking a turntable.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image39.png)

28. The last thing to do is move the **Explode** animation from the beginning of the animation to somewhere in the middle. Select the **Top_Shell** and go into the **Dope Sheet**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image40.png)

29. Select all the keyframes and move these towards the centre.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image41.png)

30. Great! The turntable animation is finished, now we can render it. In the inspector toolbar, click on **Output Properties**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image42.png)

    Ensure:

    - **Resolution %** is 100%.
    - **Aspect X and Y** are both 1.000.
    - **Frame Start** is 1, **Frame End** is 250 and **Frame Step** is 1.
    - **Frame Rate** is either **24** or **23.98**.

31. Press the file button below **Output** and specify a file name for the animation. Use the convention: **DECO2018_A1C_yourUniKey_turntable**. Then press **Accept**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image43.png)

32. Change the file format from **PNG** to **FFmpeg Video**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image44.png)

33. Press on the **Encoding** tab and change the **Container** from **Matroska** to **MPEG-4**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image45.png)

34. In the **Encoding / Video** section, change the **Output Quality** to **High quality**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image46.png)

35. In the **left** viewport, press the hamburger menu -> **View** -> **Viewport Render Animation**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image47.png)

36. The animation will now begin the render. You can see the progress by the cursor updating to the current frame number, it will be complete once it reaches the **end frame** which is **250**. This will take some time depending on your computer's performance.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image48.png)

37. The animation will have saved into the location you specified earlier. Remove the **0001-0250** at the end of the file name, now play!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image49.png)

Great job, you have completed your first animation! Take a break before tackling the next animation.

</details>

<br />

---

## Step 5 - NLA

### Video

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/b467cebe-435a-4bf4-ab83-75705f3e9315" frameborder="0"></iframe>

### Walkthrough written steps

<details markdown="1">
  
  <summary style="color: #E64626;">Click here to see the steps.</summary>

<br />

**NLA** stands for **N**on**l**inear **A**nimation. They are Blender's way of composing multiple animations in one Blender scene without having to create a Blender file for each animation because that would be inefficient!

If you have ever used a video-editing software like Adobe Premiere Pro or Final Cut Pro, it works in a similar way. There is a **track** for each animation that is tied to an object. You can move these **tracks** around which adjusts when they get played, **mute** tracks that do not need to be edited or used and add new **empty tracks** for another animation applied to an object.

<p markdown="1">

1. Change the **Editor Type** to **Nonlinear Animation**.

<br />

![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step5-image1.png)

<br />On the left are the tracks. They are grouped by the 3D Object. Within these groups are the animation tracks.
<br />The orange bars represent the animation itself and its duration. You have the ability to **move** these around adjusting when they start / finish.</li>
<br />

<br />

![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step5-image2.png)

<br />

2. Press the **Push Down Action** button that is located near the **Camera_RotatorAction** animation track.

<br />

![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step5-image3.png)

<br />

You will see that under **Camera_Rotator** there is an **NlaTrack** which is the camera rotation animation and above it is an empty track called **No Action** - Blender is now able to edit the empty track for the **Camera_Rotator** object as it is the top-most one.

<br />

![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step5-image4.png)

<br />

3. Repeat the above step, but for the **Top_Shell - Explode** animation track.

<br />

![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step5-image6.png)

<br />

</p>

We can now begin working on our second animation!

**Note**

We will be changing a lot of the Pokeball's structure and properties and the camera in the scene hierarchy. If you want to keep the current state of the Pokeball and camera, **copy and paste** these into a **New Collection** and hide it.

</details>

<br />

---

## Step 6 - Bounce, Roll and Open animation

### Video

<iframe width="100%" height="320px" allowfullscreen="true" src="https://sydney.instructuremedia.com/embed/70f283b6-1067-407e-902e-9a99431840f4" frameborder="0"></iframe>

### Walkthrough written steps

<details markdown="1">
  
  <summary style="color: #E64626;">Click here to see the steps.</summary>

<br />

1. **Hide** your **Stand** object.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image1.png)

2. Currently the PokeBall is separated into two parts - the **Top_Shell** and the **Bottom_Shell**. We want to move the PokeBall as a whole, rather than selecting them individually and moving them. Select the **Top_Shell**, in the **right** viewport, go to **Object** -> **Snap** -> **Cursor to Active**

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image2.png)

3. Go to **Add** -> **Empty** -> **Sphere**. We want to create a silhouette of the Pokeball, and the shape that resembles it the most is a Sphere. We have created the sphere in the centre of the PokeBall so when we increase its size, it increases from the centre and not from the bottom.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image3.png)

4. Change the **radius** to **35.2**mm.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image4.png)

5. Rename the **Empty** sphere to **PokeBall**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image5.png)

6. Select the **Top_Shell** and **Bottom_Shell** first, then select the **PokeBall**. This order is important.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image6.png)

7. Right-click -> **Parent** -> **Object**. This will parent the **Top_Shell** and **Bottom_Shell** to the **PokeBall**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image7.png)

   Try to move the **PokeBall** object, you will see that the entire shell is moving in one piece!

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image8.png)

8. We need a ground for our PokeBall to land on. Go to **Add** -> **Mesh** -> **Plane** (Ensure the 3D cursor is at world origin).

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image9.png)

   Set its size to **2000**mm.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image10.png)

9. In the **left** viewport, adjust the camera to something like this. Where the PokeBall is on an angle and there is more space on the left, than on the right.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image11.png)

10. Go to **Add** -> **Curve** -> **Bezier**. We want to create a path for the PokeBall object to follow, this will make more sense as we progress.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image12.png)

    Set its radius to **50**mm.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image13.png)

    Rename to **PokeBall_Path**

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image14.png)

11. Switch to **Front** view and hide everything but the **PokeBall_Path**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image15.png)

12. Search the Internet for a bouncing ball animation reference, ideally one where it does not show the ball. **Note:** a PokeBall does not adhere to a 'bouncy' ball in the Physics world, meaning Squash and Stretch won't be applied here.

    Here's one you can use.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/Ball_Animation_Reference.png)

13. Add the downloaded reference image into your scene. Here's a quick refresher:

    Create a new collection - call it **References**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image17.png)

    **Add** -> **Image** -> **Reference**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image18.png)

    Select the downloaded file and **uncheck** align to view.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image19.png)

    Rotate the reference image so that it is facing the **front view**, **90** on the **X-axis**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image20.png)

    Increase its size to **670mm**, centre the reference image (by resetting its position and ensuring the **X Offset** and **Y Offset** are **-0.50**) and enable transparency, reducing the opacity to **0.3**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image21.png)

    Rename the reference image to **Ball_Path** and lock it.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image22.png)

14. Trace your Bezier Curve over the reference image. Remember it is **E** to extrude out a new point.

    - Change the **Handle Type** to **Free** for better control for each point.
    - Change the **Handle Type** to **Aligned** for each bottom point.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image23.png)

15. Select the last point in the path and extrude a new point. Ensure that it is extruding only on the **X-axis**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image24.png)

    Change its **Handle Type** to **Vector** so it becomes a straight line. This is the rolling line of the Ball.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image25.png)

16. Hide the **References** collection.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image26.png)

17. Select the **PokeBall_Path**, go to **Object** -> **Set Origin** -> **Origin to Geometry**

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image27.png)

18. Unhide the objects, and clean the path drawn (i.e. ensuring the Y values for each point are near / at 0, this is especially for the control points).

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image28.png)

19. Zero-out the position of the **PokeBall_Path** and move it slightly above the PokeBall itself. Adjust its scale to around **0.4 - 0.5**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image29.png)

20. Select the **PokeBall**, go to the **Object Constraints** tab in the Inspector.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image30.png)

21. **Add Object Constraint** -> **Follow Path**. We are going to have the **PokeBall** follow the path of the **PokeBall_Path**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image31.png)

22. Select the **Target** as the **PokeBall Path**, press **Animate Path** then check **Fixed Position**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image32.png)

23. Move the playhead to frame **0** (Or 1, no idea why I put it at 0 🤦‍♂️), then press the circle icon near **Offset Factor**.

    **Note**: If you are using an older version of Blender (<= 2.8), then you would need to right-click on the offset factor and press **Insert Keyframe**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image33.png)

24. Press record at the bottom of the timeline, move the playhead to the end frame **250** and change the **Offset Factor** value to **1**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image34.png)

    Don't forget to stop recording! Play the animation.

25. The animation is quite slow, we can speed this up by moving the keyframe at frame **250** closer, for a faster animation.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image35.png)

26. You'll notice that the PokeBall is inside the plane, we will need to fix this. Find a bottom point as reference, and move the **PokeBall_Path** down until the PokeBall is sitting on the Plane.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image37.png)

27. Continue to refine the path and animation until you are satisfied.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image38.png)

28. We now want to have the PokeBall rotating as it bounces and rolls to its final position. Move to the **first** frame and adjust the **Rotation Y** value of the **PokeBall** to **-121**, then press the circle icon to create the keyframe.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image39.png)

29. Go into **record** mode, move the playhead to when the **PokeBall** is no longer bouncing (mine is at frame **103**, yours may be different) and adjust the **Rotation Y** value to **229**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image40.png)

    Great! We now have the PokeBall bouncing and rolling, now all that is left is to open the lid.

30. Move the playhead to the **last keyframe** (where the Pokeball stops all together), and adjust the **Rotation Y** value to **360**, then turn off **record mode**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image41.png)

31. Move the playhead **10 frames after** the Pokeball has stopped rolling and is at rest.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image42.png)

32. We want to rotate the **Top_Shell** to show the Pokeball lid opening, however if we try to rotate it it's rotating around its centre point which intersects with the bottom shell. Select the **Top_Shell**, go to **Object** -> **Snap** -> **Cursor to Active**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image43.png)

33. Go to **Add** -> **Empty** -> **Cube**. We want to create a pivot point for the **Top_Shell**, so it rotates relative to that object and not to its centre.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image44.png)

34. Turn on **X-Ray Mode** and reduce the **radius** of the **Empty Cube** to **1.6mm**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image45.png)

35. Move the **Empty Cube** up so that it is touching the base of the **Top_Shell**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image46.png)

    Then to the back of the **Top_Shell**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image47.png)

36. Rename the **Empty Cube** to **Lid_Opener**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image48.png)

37. We first want to make the **Lid_Opener** a _child_ of the **PokeBall**. Select the **Lid_Opener** first, then select the **PokeBall**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image49.png)

    Right-click -> **Parent** -> **Object**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image50.png)

38. Now the **Top_Shell** needs to be a _child_ of the **Lid_Opener**. Select the **Top_Shell** first, then select the **Lid_Opener**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image51.png)

    Right-click -> **Parent** -> **Object**. **Ensure that you have ticked KEEP TRANSFORM**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image53.png)

39. Select the **Lid_Opener** and press the icon near **Rotation Y**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image54.png)

40. Turn on **record** mode, move the playhead **20 frames after** (For me this is frame **150**), then adjust the **Rotation Y** value to **-110**. Turn off **record** mode.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image55.png)

41. Refine the opening of the lid however you like!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image56.png)

42. Rename the animations to **Bounce_and_Roll** and **Lid_Open** respectively.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image57.png)

43. Press the file button below **Output** and specify a file name for the animation. Use the convention: **DECO2018_A1C_yourUniKey_roll_bounce_open**. Then press **Accept**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image58.png)

44. Change the file format from **PNG** to **FFmpeg Video**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image44.png)

45. Press on the **Encoding** tab and change the **Container** from **Matroska** to **MPEG-4**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image45.png)

46. In the **Encoding / Video** section, change the **Output Quality** to **High quality**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image46.png)

47. In the **left** viewport, press the hamburger menu -> **View** -> **Viewport Render Animation**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step6-image59.png)

Great job, you have completed your second required animation! Well done!

The next step is an optional animation, all the best.

</details>

<br />

---

## Extra Step - 2 Principles of Animation

Using **either** animation, add two **distinct** principles of animation to it.

## Submission

You will need to submit a **.ZIP** file, containing:

- DECO2018_A1C_yourUnikey_turntable.mp4 (or .mov)
- DECO2018_A1C_yourUnikey_bounce_roll_open.mp4 (or .mov)

Add a comment in the Canvas submission that states your two principles, for example:
- Principle of Animation 1: _Principle Name_
- Principle of Animation 2: _Principle Name_

---

That's all for this week!

![Surprised Pikachu Gif](https://media.tenor.com/images/7c355668e41f8cf511fe30c8483379d0/tenor.gif)
