<h1 align="center">Real Time Object Detection Web App with Audio Assistance : **VisionVerse** </h1>
The project **VisionVerse** is a web-based application that utilizes real-time object detection to identify and label objects within an image or video stream and give out the recognised object as audio output. It is built using Next.js, ONNXRuntime, and YOLOv7 model.

## :hourglass: Project Demo at [RTOD.vercel.app](https://real-time-object-detection-web-app-master.vercel.app/)
<div align="center" >
  <video autoplay loop muted
  src="https://user-images.githubusercontent.com/44163987/211734752-e354b590-0f55-465a-b783-504ed55d3ed3.mp4" alt="demo.mp4" >
  </video>
</div>

## :innocent::thought_balloon: Motivation
This research details the development of a Real-Time Object Detection system designed toenhance the spatial awareness of visually impaired individuals. 
- This Real-Time Object Detection system represents a significant step towards fosteringinclusivity for the visually impaired, providing a tangible solution to the challenges they facein their daily lives. By harnessing the power of modern technology, this project seeks tobridge the gap between the visually impaired and their environment, ultimately enhancingtheir autonomy and facilitating a more inclusive and accessible society.
- The primary objective is to empower the blind with the ability to perceive and navigate their surroundings moreeffectively. The proposed solution employs advanced computer vision techniques to detectand recognize objects in real time, subsequently relaying this information through an intuitiveaudio output interface.

## :computer: Working :abacus:
- The system utilizes a deep learning framework for object detection, allowing it to identify adiverse range of objects in the user's environment.
- A camera captures live visual data, whichis then processed in real time by the trained neural network.
- The identified objects aretranslated into meaningful auditory cues, providing the user with immediate and actionableinformation about their surroundings.
- This auditory feedback is crucial for enabling aseamless integration of the system into the user's daily life, promoting independent mobility,and fostering a sense of confidence and security.

## :dizzy: Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### :key: Prerequisites
In order to run this project, you will need to have the following software installed on your machine:

- Node.js
- A web browser 

### 🚀&nbsp; Installation
1. Clone the repository to your local machine:
```
https://github.com/juanjaho/real-time-object-detection-web-app.git
```

2. Navigate to the project directory:
```
cd real-time-object-detection-web-app
```

3. Install the necessary dependencies by running:
```
npm install
# or 
yarn install
```

4. Start the development server by running:
```
npm run dev
# or
yarn dev
```

5. Open your web browser and navigate to http://localhost:3000 to view the application.

### :nerd_face: Installation as PWA

This app can also be installed on your device (desktop or mobile) as a progressive web app (PWA). Here's how:

1. Visit the app's URL in a web browser that supports PWAs (such as Google Chrome or Firefox).
2. Look for the "Install" or "Add to Homescreen" button in the browser's interface. 
3. Click the button and follow the prompts to install the app.
4. The app will now be installed on your device and can be launched from the homescreen like any other app.

### :robot: Deployment
This project can be deployed to a web server for public access. For more information on deploying a Next.js application, please visit the official [documentation](https://nextjs.org/docs/deployment/)


## :warning: Built With
- [ONNXRuntime](https://onnxruntime.ai/) - An open-source project for running inferences using pre-trained models in a variety of formats.
- [YOLOv7](https://github.com/WongKinYiu/yolov7) - A Object detection model which is used in this project.
- [Next.js](https://nextjs.org/) - A JavaScript framework for building server-rendered React applications.
- [PWA](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) - A progressive web app that can be installed on a user's device and run offline, providing a native-like experience.

## :handshake: Contributing
If you want to contribute to this project, please feel free to submit a pull request. Any contributions, big or small, are greatly appreciated!

## :heart: Authors
Surya Choudhuri - Project Idea/Initiation - [@suryachoudhuri](https://github.com/Suryachoudhuri003)
Reedham Pujara - App Dev -  [@reedhampujara](https://github.com/Reedham20)

## :star: Acknowledgments
- Special thanks to [@WongKinYiu](https://github.com/WongKinYiu) for creating such an amazing [YOLOv7](https://github.com/WongKinYiu/yolov7) model.

- Hats off to the ONNXRuntime team for making such a powerful tool accessible to developers.

- Referenced [ONNXRuntime Web Demo](https://github.com/microsoft/onnxruntime-web-demo) for guidance on how to use ONNXRuntime in a web application.

- Thank you to all the contributors to the open-source libraries used in this project.

## :bookmark_tabs: Citation
### Paper Title
Real Time Oject Detection for Blind with Audio Assitance
###  Author List
- Surya Choudhuri (Bharath Institute of Higher Education and Research) <`suryachoudhuri03@gmail.com`>
- Baalaji K (Bharath Institute of Higher Education and Research) <`baalaji.cse@bharathuniv.ac.in`>
- SAGAR GHUGUSKAR (Bharath Institute of Higher education and research ) <`sagartheghuguskar@gmail.com`>
- Reedham Pujara (Bharath Institute of Higher education and Research) <`reedhamjpujara2092001@gmail.com`>
- Ravikant Yadav ( Bharath Institute of Higher education and Research) <`yadavravikant581@gmail.com`>
### Conference Name
International Conference on Intelligent Computing and Communication (ICICC 24)

## :scroll: License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE.md) file for details.
