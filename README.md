# My Party Album (D2)

The deployed version of our application is linked [here](https://github.com/MyPartyAlbum/mpa/releases/tag/D2) and the demo to our partner is explained [here](#demo-to-our-partner).

## Description 

My Party Album is a one-stop photo sharing application where a user can either create an account for an event of their own, or join as a guest for someone else’s event using a unique code corresponding to the event. Users can then take pictures, edit them, and then share them with everyone using the event code. Originally, the application's photo editor allowed users to apply a single filter to an image. So, users could either adjust the brightness of an image or its saturation, but not both. Moreover, the app did not offer any other editing tools. These factors limited a user’s ability to edit their images the way that they may want to, which could push these users to resort to third-party apps to edit their photos instead. 

In order to address these issues, our application implements upgrades to the pre-existing photo editor in My Party Album. Where users could originally only apply a single filter at a time, we have added functionality to allow users to layer different filters on top of their images. Moreover, we have added a stickers tab where users can choose from a variety of stickers available and add them to their images. Additionally, we have added undo functionality to the editor to provide users with more flexibility in editing their photos. Our version of the photo editor for My Party Album offers more features to the users, thereby creating a better editing experience and eliminating the need for users to use third party applications to be able to edit images to their liking.

## Key Features

There are three main features that we have implemented in the current version of the application:

1. **Apply multiple filters to an image:** 

Originally, users were only able to apply one filter to an image. We have upgraded filter functionality in the photo editor so that users can now apply multiple filters to an image at the same time, allowing them to adjust the image to the state that they want. We have also made UI improvements to create a more intuitive layout, and provide a better user experience.

2. **Allow users to add stickers to an image:** 

We have added in a tab where users can choose from a selection of stickers, and add these stickers to their images. The stickers can be rotated, resized, and their location on the image can be changed. If a user does not like a sticker, they can also simply delete it.

3. **Allow users to undo changes made to an image:** 

We have added in an undo button to provide users with the ability to undo any changes they have made to the image that they now deem unsatisfying.

Jump [here](#editor-images) to see the various features that are now present in the editor.

## Instructions
### Installation

#### Requirements:
- An android device with Android 10 more higher.

#### Step 1: Download, Install and Launch the Application 
- Please download and install the .apk file from [here](https://github.com/MyPartyAlbum/mpa/releases/download/D2/mpa.apk). If you see a 404 page, please first log into GitHub on the browser, and then reopen the link.
- Alternatively, you can go to the ["Release" section on our partner's repository](https://github.com/MyPartyAlbum/mpa/releases/tag/D2) and download the apk there.

Next, to launch the application, there are three ways of doing so.

1. Use an Android device. **(Strongly Recommended)** | [A short video for this method](https://youtube.com/shorts/ujwzCyTI1-I?feature=share)
> _Note:_ If you have never installed an app outside of the Google Play, your device may prohibit you from installing. If that happens, please follow the instruction [here](https://www.maketecheasier.com/install-apps-from-unknown-sources-android/) to allow your phone to install from an unkown source. (We promise that our app does not contain any virus ;) )

2. Use any [Android Emulators](https://developer.android.com/studio/run/emulator) such as [BlueStacks](https://www.bluestacks.com) and [Nox](https://www.bignox.com). If you are using these emulators to run the app, just install the app as you install it on a physical Android device.

> _Note:_ If you are using an emulator, you might need to flip the camera to selfie mode in order to enter the photo editor. This has been a problem (with the emulator) experienced by several of our developers.

3. Use the chrome browser by using [this](https://chrome.google.com/webstore/detail/apkonline-apk-manager-for/lnhnebkkgjmlgomfkkmkoaefbknopmja/related) extension. However, this does not offer a good user experience and is not preferred.

#### Step 2: Login and Party Selection | [A short video for this step](https://youtube.com/shorts/3mMT_kP53HI?feature=share)
- Login or registration is required on the first time opening the app, please use the following account to access the app.
- Email: briansbrain@yopmail.com
- Password:Csc301group7!
- Please enter the credentials as shown in the first image below, then click the "LOG IN" button.

<p align="center">
<img src="https://github.com/csc301-fall-2022/team-project-7-mypartyalbum-m/blob/main/deliverable-2/images/login.jpg" width=200>
 &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;
<img src="https://github.com/csc301-fall-2022/team-project-7-mypartyalbum-m/blob/main/deliverable-2/images/party_select_1.jpg" width=205>
 &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;
<img src="https://github.com/csc301-fall-2022/team-project-7-mypartyalbum-m/blob/main/deliverable-2/images/party_select_2.jpg" width=200>
</p>

- Once logged in, you will see the home page. The app might ask for permissions for camera and storage, please allow them. 
- In order to access the image editor, a party needs to be selected. To do so, simply click on the "UofT Development Team" tab in the "Live Parties" section as shown in the images above.
>_Note_: If you do not see any parties in the "Live Parties" Section, please wait for 10 ~ 30 seconds for it to show up.

#### <a name="editor-images">Step 3: Take a Photo and Enjoy the Editor! | [A short Demo video!](https://youtu.be/UoL8tGGkKPQ)</a>

By clicking on the "CAMERA" tab at the bottom of the screen, you can go to the camera page.

After taking a picture, the app will automatically brings you to the image editor.

The Image Editor consists of 1 top action bar and 2 tabs, the filters tab and the stickers tab.

**Swiching between tabs**
- User can switch between the filters and stickers tabs by clicking on the corresponding button at the top of the screen.

**Applying Filters:** 
- Switch to the "Filters" tab. You can see annotate layouts in the images below.
- As annotated in the first image, horizontally scroll the bar located at the bottom of the screen to find the filter you want to apply. 
- Select the filter by clicking it.
- Once the filter is selected, a new tab will show up.
- Slide the slider for choosing the intensity of the filer
- Clicking on the "CANCEL" and "DONE" buttons to discard or confirm the changes. (As shown in the second iamge.)
- Repeat the above steps to apply multple filters.

<p align="center">
<img src="https://github.com/csc301-fall-2022/team-project-7-mypartyalbum-m/blob/main/deliverable-2/images/filters.jpg" width=900>
</p>
 
**Adding Stickers:** 
- Switch to the "Stickers" tab. You can see annotate layouts in the images below.
- Horizontally scroll the bar located at the bottom of the screen to find the sticker you want to add.
- Add the sticker to the center of the screen by clicking it.
- Move the sticker by druging it.
- Rotate, resize, and delete the sticker by using related buttons. (As shown in the second image.)
- Repeat the above steps to apply multiple stickers.
- click a sticker to move it to the top layer.

<p align="center">
<img src="https://github.com/csc301-fall-2022/team-project-7-mypartyalbum-m/blob/main/deliverable-2/images/stickers.jpg" width=900>
</p>

 **Undo Changes:**
- User can undo their changes by clicking on the backarrow at the top-right-corner of the screen, as annotated in the images above.
 

## Development requirements

- The prefered IDE of developing Android apps is [Android Studio](https://developer.android.com) since it has full support of build tools, emulators and language syntax that are used in this project. Here is the instruction to set up Android Studio

  1. Download and install Android Studio from [this link](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwiHweLo65f7AhXSyJQJHSDeDHMYABAAGgJ5bQ&ohost=www.google.com&cid=CAESauD2Dj7GVa4snHGOeo8J7q-xxvwPgUGUW3B5yRrtc2N8xnZ4k9I3Z0SYvmdzOuX0MgeKn2AAfuwT0Nq_EIYkqpbvdnS9vPBbMYPRnW1S82TjuMjNaA8mxBal0vGbhpo2HIhJiFUAZZbVnQc&sig=AOD64_3MnTWwbhBFh3JS16qh4A3q0Xx6oA&q&adurl&ved=2ahUKEwi22dno65f7AhX2jokEHQF_A5oQ0Qx6BAgGEAE&nis=8)
  2. Clone the repository to your machine by typing the following command in the command line. Then open the project in Android Studio. 
  ```
  git clone https://github.com/MyPartyAlbum/mpa.git
  ```
  Or you can use "Get from VCS" in Android Studio. Here is a [tutorial](https://www.geeksforgeeks.org/how-to-clone-android-project-from-github-in-android-studio/) for doing this.
  
  3. After loading the project in Android Studio, set up an emulator by selecting the "Device Manager" tab on the right side of the IDE, then click "create device" and select the type, API level and the allocated memory of the device. Remember to select an API which has an API level of 26 or above. Here is a more detailed [tutorial](https://developer.android.com/studio/run/emulator?gclid=Cj0KCQjwk5ibBhDqARIsACzmgLTb7zjeDOOpyHge8b_yPG5mSKSksXlGZV2Wh6k4fISVNq-Kmed7k74aAh0oEALw_wcB&gclsrc=aw.ds) for setting up the emulator
  
  4. All things are set! Now you can run the app on the emulator!
 
 - Technical requirements for the project:
   - Langugae: Java Version 11
   - Build tool: Gradle JDK 11
   - Android OS:
     - Target compile SDK version: API 33
     - Minimum compile SDK version: API 26
   - 3rd party libraries:
     - Glide 4.13.2
     - Retrofit 2.9.0
     - Stripe 18.2.9
     - PhotoView 2.3.0
     - GPUImage 2.0.1

 >_Note:_ All technical requirements and libraries will be installed on the first gradle build.

## Deployment and Github Workflow
 
 ### Pull-requests
 - Since we are building on an existing software, we put all of our work (which is the entire image editor feature) in the ["UofTBranch"](https://github.com/MyPartyAlbum/mpa/tree/UofTBranch) so that we would not change the build of the original software.
 
 - For seperate sub-features, we work on new branches that branches off from UofTBranch and submit [pull requests](https://github.com/MyPartyAlbum/mpa/pulls?q=is%3Apr+is%3Aclosed)(PR) from those new branches to UofTBranch. The developer who puts the PR will request for one or more reviewers to review it depending on the size of the PR. After the PR is approved, the reviewer or the developer will merge it to UofTBranch.
 
 - If a bug is caught, we will set up a [github issue](https://github.com/MyPartyAlbum/mpa/issues) and assign it to the developer who is responsible for that particular feature so we could keep track of every issue. Fixes and patches will also be merged to the UofTBranch with pull requests with the same process mentioned above.
 
 - The reason why we chose this workflow is that we could ensure the code quality during the review and spot any conflicts in the code before merging new changes into the codebase by using pull request. Moreover, since we merged all the changes related to the image editor in a seperate branch from the main branch, our partner could review and test our feature individually.    
 
 ### Naming conventions
 In our code, we follow the naming conventions suggested by [Oracle](https://www.oracle.com/java/technologies/javase/codeconventions-namingconventions.html). It is the standard naming convention for Java.

As for the naming of our branches, we named them with "UofT", followed by the branch name in pascal case, such as "UofTBranch" and "UofTUndo". This is to separate the branches created by us and by the partner, since we are working in their code base.
 
### Deployment
The main deployment tool used is Github Actions to automated the process of releasing versions of our code. We have set up two workflows - one for creating a tag when we merge into the main branch, another for creating a release based on the tag that was created. We seperated these two actions into two workflows because we want more control over how we can release a version of our application.

>_Note:_ These Github workflow files are not found in the partner's repository that we are working on because we are working with an existing codebase from our partner, and they did not consent with us using Github Actions in their repository since they have a different deployment process. However, in order to demonstrate that we are able to set the automation up, we have included these files in the ["workflows"](https://github.com/csc301-fall-2022/team-project-7-mypartyalbum-m/tree/main/workflows) folder in this repository instead and also set them up in a [testing repository](https://github.com/valyippee/android-deployment-test) with an Android application to show that the tags and releases are correctly setup as part of an automated release process. The links provided below are linked to the testing repository.

By default, when we push to main, a tag will be created with [this](https://github.com/valyippee/android-deployment-test/blob/main/.github/workflows/tag.yml) workflow. This immediately triggers [this](https://github.com/valyippee/android-deployment-test/blob/main/.github/workflows/release.yml) workflow which creates an .apk file for release. It then create a release named as "My Party Album" with the tag name of the tag created.

Another way to create a release automatically is to create and push a tag to the remote repository, which triggers the "release" workflow only. Thus, we have finer control over how tags are named. As part of D2, we used the latter to create a tag named "D2" and a [release](https://github.com/valyippee/android-deployment-test/releases/tag/D2) called "My Party Album D2", using [this](https://github.com/valyippee/android-deployment-test/actions/runs/3402159386) Github workflow. Note that the .apk file in this release is just for testing, and is not related to our project.

>_Note:_ Since the above automation process could only be done in the testing repository, the .apk file linked in the release [here](https://github.com/MyPartyAlbum/mpa/releases/tag/D2) is done manually.


## Licenses 

MyPartyAlbum does not license the use of their code by third parties.

Our partner made this choice because they are a business, and they want to keep the code proprietory.

## Others
### Demo to our partner
A demo was done on 4 November 2022. However, our group did not know that we had to record the session down as the instructions were not clear enough regarding this, and we were only given a reply on [piazza](https://piazza.com/class/l6uha1gwhmw5zl/post/98) after the demo.

However, the videos posted in the section on [Instructions](#instructions) are exactly what we have demoed to our partner, and with [these](https://docs.google.com/document/d/1vFcy-O6XyqCT1VI6c5Coww-IqR00_mS44ziKs-jb6e0/edit?usp=sharing) meeting minutes taken down, we hope that what we have provided is sufficient as a replacement of the recording!
