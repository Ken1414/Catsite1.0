*This source code is a proofreading and extension of the program ''copycat'', which analyzes synthesizer's screen recording video (mp4 file) and extracts the audio played in alphabetical notation, so that it runs on a browser.

*I'm not very good at using github, so I don't know how to contact the poster of ''copycat'', so I'm making changes on my own, so if I receive a request for deletion, I'll respond immediately.




## **Introduction**

Since it is created using Django and python, you need to activate the server to start the browser.<br>
Once activated, you will probably be able to access it from the default port 8000.<br>

<img width="995" alt="スクリーンショット 2023-12-02 15 58 55" src="https://github.com/Ken1414/Catsite1.0/assets/116622288/738c73d1-6916-49f6-ab38-f0b5bda93f2b">
After preparing a video record of synthesia like the image above,<br>

Currently, we only have Japanese available, so we apologize for the inconvenience, but please follow the steps and

① Specify the video path in files<br>

② (from top to bottom)<br>
 * File name (including .mp4)<br>
 * First note (A0 to C9 on the leftmost keyboard)<br>
 * Song tempo (3-digit BPM)<br>
 * Start time (time to cut until notes touch)<br>
 * Keyboard color (from RGB)<br>
 <br>
 <img width="467" alt="スクリーンショット 2023-12-02 16 13 33" src="https://github.com/Ken1414/Catsite1.0/assets/116622288/cf1be3c8-91aa-4f3a-b387-1dfd3094bcd0">
 <br>
 Enter and click the "Run" button on the left.<br>
 
 <br>
 At this time, the button on the right resets the input value. Be careful not to operate incorrectly.

③After a few seconds, the results will be displayed within the frame.<br>

<img width="718" alt="スクリーンショット 2023-12-02 16 15 28" src="https://github.com/Ken1414/Catsite1.0/assets/116622288/abde212b-7acf-4c72-834f-49b568afc2bb"><br>
<br>
 The button at the bottom outside the frame returns the page to its initial state. Be careful not to operate incorrectly.
 <br>

## **Development environments**

【Master】 copycat by SoloSteve

https://github.com/SoloSteve/copycat
<br>

【Editor】 Visual Studio Code w/python3.11.1 64-bit

[https://replit.com/~](https://code.visualstudio.com/)https://code.visualstudio.com/



