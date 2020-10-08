---
layout: post
title: Week 7 Tutorial - (Assessment 1C) Animation in Blender
subtitle: Assessment 1C - Learning about animations in Blender!
---

This is Week 7's tutorial where you will learn about animation in Blender with your 1B PokeBall and stand.

## Objective

Your objective is to animate your Assessment 1B PokeBall! You will be **required** to produce two animations:

- Turntable

  !()[]

- Bounce, Roll and Open

  !()[]

You may go an extra step and animate:

- Catching a Pokemon based on Omega Ruby and Sapphire 3DS games.

_Refrence_:

!()[]

---

## Step 1 - Setting up the Blender file

1. Locate your A1B Blender File.

   ![Step 1 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step1-image1.png)

2. Duplicate this file (copy + paste) and rename it to **DECO1008_A1C_YourUnikey**.

   ![Step 1 - Image 2]({{site.baseurl}}/assets/images/wk7-tutorial/step1-image2.png)

3. Open this new Blender file.

   ![Step 1 - Image 3]({{site.baseurl}}/assets/images/wk7-tutorial/step1-image3.png)

## Step 2 - Introducing the Animation workspace

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

## Step 3 - Introducing the Camera

1.  We have previously stated to not worry about the Camera, well now its time to focus on the Camera in Blender!
    The camera is a second pair of eyes, the first pair of eyes is the viewport which is what we as the user see in Blender.
    The camera acts as an internal camera that can be set up for rendering and animations.

    In the **left** viewport, click on the Hamburger menu near the top, then go to View -> Viewpoint -> Camera. You will notice this rectangular box, this is what the Camera is currently seeing.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image1.png)

2.  Try moving the camera around in the **right** viewport, you will notice that it is moving as well in the **left** viewport.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image2.png)

    Our objective for the first animation, the turntable, is to position the camera to have it slightly above the pokeball + stand as we want the top shell to move up.

    You will notice that is quite difficult to do so, with just manually adjusting the camera in the right viewport.

3.  In the **left** viewport, press **N** on your keyboard or go to View -> Sidebar to open the Sidebar.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image3.png)

4.  Press the **view** tab in the sidebar.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image4.png)

5.  Under the **View Lock** section, check the **Camera to View** checkbox. What this will do is instead of adjusting the viewport when you are using your mouse to move around, it will adjust the camera's view.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image5.png)

6.  Still in the **left** viewport, try to move around with just your mouse. You will now notice that you are updating the camera's position and rotation as well! Much easier 😃

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image6.png)

7.  There is one issue! You will notice that as we zoom out, the pokeball begins to clip. We need to update the clipping start and end, as the camera has different values for clipping compared to the viewport's.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image7.png)

8.  With the **Camera** Selected, go to the **Object Data Properties** tab. It is denoted by the camera icon.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image8.png)

9.  Change **Clip Start** to 0.01mm and **Clip End** to 1000mm.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step3-image9.png)

## Step 4 - Turntable animation

Now we are going to create our first animation! The turntable animation.

1. Adjust the camera's view to something as shown below, with space at the top and the stand slightly cut-off.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image1.png)

2. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

3. In the **Object Properties** tab, press the circular dot near the **Location Z** value.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image3.png)

   This will create a keyframe in the timline.

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

15. Zoom out and pan upwards (the controls are exectly like moving the viewport), you will see your keyframes!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image24.png)

16. The graph editor allows us to adjust the **easing** of each keyframe, while still being able to move the keyframes.
    It works exactly like a spline curve!

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image25.png)

17. Select the **Top_Shell** and move the playhead to frame **1**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

18. Select the **Top_Shell** and move the playhead to frame **1**.

    ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

## Step 5 - NLE animations

6. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

7. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

8. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

## Step 6 - Bounce, Roll and Open animation

6. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

7. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

8. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

## Extra Step - Catching a Pokemon animation

6. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

7. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

8. Select the **Top_Shell** and move the playhead to frame **1**.

   ![Step 2 - Image 1]({{site.baseurl}}/assets/images/wk7-tutorial/step4-image2.png)

## Submission

You will need to submit a **.ZIP** file, containing:

- DECO1008_A1C_yourUnikey_turntable.mp4 (or .mov)
- DECO1008_A1C_yourUnikey_bounce_roll_open.mp4 (or .mov)

_Extra_

- DECO1008_A1C_yourUnikey_pokeball_catch.mp4 (or .mov)

---

That's all for this week!

![Surprised Pikachu Gif](https://media.tenor.com/images/7c355668e41f8cf511fe30c8483379d0/tenor.gif)
