# Driver-Drowsiness-Detection-System
<h1>DRIVER DROWSINESS DETECTION SYSTEM</h1>
<img src="C:\Users\Admin\Downloads\drowsi.jpg" alt="drowsiness pic" width=500 height= 400><br><br>
<U>INTRODUCTION:</U>
<p>Our project is  for detecting drowsiness in drivers is developed by using a camera that point directly towards the drivers face and capture for the real time video. Once the video is captured, monitoring the face region and eyes in order to detect drowsy. The system able to monitoring eyes and determines whether the eyes are in an open position or closed state. In such a case when drowsiness is detected, a warning signal is issued to alert the driver. It can determine a time interval of eye closure as the proportion of a time interval that the eye is in the closed position. If the drivers eyes are closed cumulatively more than a standard value, the system draws the conclusion that the driver is falling asleep, and then it will activate an alarm sound to alert the driver.</P>
<u>WORKING:</u><br>
<P>In this Python project, we will be using OpenCV for gathering the images from webcam will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :
<pre>
Step 1 – Take image as input from a camera.
Step 2 – Detect the face in the image and create a Region of Interest (ROI).
Step 3 – Detect the eyes from ROI and feed it to the classifier.
Step 4 – Classifier will categorize whether eyes are open or closed.
Step 5 – Calculate score to check whether the person is drowsy.</pre></P>
<u>REQUIREMENTS:</U><br>
<ul>
<li>jupyter notebook</li>
<li>open cv</li>
<li> keras</li>
<li> pygame</li>
<li> tensorflow</li>
<li>numpy</li></ul>

<u>Conclusion:</u><br>
              <P>  Information about the eyes position is obtained through self-developed image processing algorithm. During the monitoring, the system is able to decide if the eyes are opened or closed. When the eyes have been closed for too long, a warning signal is issued. In addition, during monitoring, the system is able to automatically detect any eye localizing error that might have occurred. In case of this type of error, the system is able to recover and properly localize the eyes.</p>

