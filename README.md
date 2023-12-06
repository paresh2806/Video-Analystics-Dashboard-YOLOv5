<h1 align="center">Video Analytics Tool using YoloV5 and Streamlit</h1>

## :innocent: Motivation
As AI engineers, we love data and we love to see graphs and numbers! So why not project the inference data on some platform to understand the inference better? When a model is deployed on the edge for some kind of monitoring, it takes up rigorous amount of frontend and backend developement apart from deep learning efforts — from getting the live data to displaying the correct output. So, I wanted to replicate a small scale video analytics tool and understand what all feature would be useful for such a tool and what could be the limitations?

## :framed_picture: Demo

https://user-images.githubusercontent.com/37156032/160282244-42f6bd8c-bfc8-47af-8973-d3d199140e44.mp4

## :key: Features



<ol>
    <li>Choose input source - Local, RTSP or Webcam</li>
    <li>Input class threshold</li>
    <li>Set FPS drop warning threshold</li>
    <li>Option to save inference video</li>
    <li>Input class confidence for drift detection</li>
    <li>Option to save poor performing frames</li>
    <li>Display objects in current frame</li>
    <li>Display total detected objects so far</li>
    <li>Display System stats - Ram, CPU and GPU usage</li>
    <li>Display poor performing class</li>
    <li>Display minimum and maximum FPS recorded during inference</li>
</ol> 

## :dizzy: How to use?
<ol>
    <li>Clone this repo</li>
    <li>Install all the dependencies</li>
    <li>Run -> streamlit run app.py</li>
</ol>

## :heart: Extras
Do checkout the Medium article and give this repo a :star:
# Streamlit
