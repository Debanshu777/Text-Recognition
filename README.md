# Text-Recognition 📷
Text recognition is the process of detecting text in images and video streams and recognizing the text contained therein. Once detected, the recognizer then determines the actual text in each block and segments it into lines and words. The Text API detects text in Latin based languages (French, German, English, etc.), in real-time, on device.

## Dependencies
- <a href="https://github.com/ArthurHub/Android-Image-Cropper">Image Cropper</a>
  Powerful (Zoom, Rotation, Multi-Source), customizable (Shape, Limits, Style), optimized (Async, Sampling, Matrix) and simple image cropping library for Android.
  ```
    implementation 'com.theartofdev.edmodo:android-image-cropper:2.8.+'
  ```
- <a href="https://developers.google.com/vision/android/text-overview">Vision-Api</a>
  ```
    implementation 'com.google.android.gms:play-services-vision:20.1.0'
  ```
## Screenshots
<table>
  <tr>
    <td>Opening Screen</td>
     <td>Choose the source of image</td>
     <td>Crop the required Part</td>
     <td>Output</td>
  </tr>
  <tr>
    <td><img src="https://github.com/Debanshu777/Text-Recognition/blob/master/app/Screenshots/Screenshot_1593878899.png" width=240 height=420/></td>
    <td><img src="https://github.com/Debanshu777/Text-Recognition/blob/master/app/Screenshots/Screenshot_1593878912.png" width=240 height=420/></td>
    <td><img src="https://github.com/Debanshu777/Text-Recognition/blob/master/app/Screenshots/WhatsApp%20Image%202020-07-04%20at%2010.48.57%20PM.jpeg" width=240 height=420/></td>
    <td><img src="https://github.com/Debanshu777/Text-Recognition/blob/master/app/Screenshots/WhatsApp%20Image%202020-07-04%20at%2010.48.57%20PM%20(1).jpeg" width=240 height=420/></td>
  </tr>
</table>
  
## Text Structure
The Text Recognizer segments text into blocks, lines, and words. Roughly speaking:

- a Block is a contiguous set of text lines, such as a paragraph or column,

- a Line is a contiguous set of words on the same vertical axis, and

- a Word is a contiguous set of alphanumeric characters on the same vertical axis.

The image below highlights examples of each of these in descending order. The first highlighted block, in cyan, is a Block of text. The second set of highlighted blocks, in blue, are Lines of text. Finally, the third set of highlighted blocks, in dark blue, are Words.
<br><br>
![](https://developers.google.com/vision/images/text-structure.png)

## How To Run This
<> Open your terminal (NOTE: git bash prefered/ Terminal on Android Studio/Any Other Editor)</br>
<> Run the git clone command and clone this repo.</br>
<> Navigate to the project folder where you have cloned the repo.</br>
<> Sync the project.</br>
<> Open an emulator or plug in a real device</br>
<> Run the App</br>

## Contributing
#### Feel Free To Contribute
Pull request are most welcomed, Add proper documentation to the part you contribute, Give me some time to review pull request Thank you.
#### Developed And Maintained by
😎<a href="https://github.com/Debanshu777">Debanshu777</a>

## License
This project is licensed under the MIT License - see the <a href="https://github.com/Debanshu777/Text-Recognition/blob/master/LICENSE">LICENSE.md</a> file for details

## Getting Started
To get started read the Android developers <a href="https://developer.android.com/">documentation</a>
