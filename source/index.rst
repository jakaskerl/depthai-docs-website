DepthAI's Documentation
=======================

.. raw:: html

   <h5>Just received a device? Select the device you have below to get started:</h5>
   <div class="items-container">
      <div class="items-row">
         <div class="items-col">
            <div class="item" style="border-right-style: solid;border-right-width: 1px;">
               <div class="item-body">
                  <h3 class="item-title" style="text-align: center;">OAK Camera</h3>
               </div>
               <div class="item-img-wrapper">
                  <a href='pages/tutorials/first_steps/#first-steps-with-depthai'>
                     <img class="item-img" src="https://github.com/luxonis/depthai-docs-website/assets/18037362/becb32f5-0a91-48de-b786-7cefd1a18ec1"
                        alt="OAK Camera" />
                  </a>
               </div>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-body">
                  <h3 class="item-title" style="text-align: center;">RAE Robot</h3>
               </div>
               <div class="item-img-wrapper">
                  <a href='https://docs-beta.luxonis.com/hardware/rae/get-started'>
                        <img class="item-img" src="https://github.com/luxonis/depthai-docs-website/assets/18037362/149c65dc-99eb-4b3a-920b-1412e2aaf9cf"
                              alt="RAE Robot" />
                  </a>
               </div>
            </div>
         </div>
      </div>
   </div>

DepthAI is a :ref:`Spatial AI <spatialai>` **platform** that is used for communication with and development of our devices; OAK cameras and RAE robots.

It allows you to develop projects and products that require:

#. :ref:`Artificial Intelligence <AI / ML / NN>`
#. :ref:`Computer Vision`
#. :ref:`Depth perception` (`Stereo <https://docs.luxonis.com/projects/api/en/latest/components/nodes/stereo_depth/#internal-block-diagram-of-stereodepth-node>`__, `ToF <https://docs.luxonis.com/projects/hardware/en/latest/pages/DM0256/>`__)
#. Performant (high resolution and FPS, `multiple sensors <https://docs.luxonis.com/projects/hardware/en/latest/pages/articles/supported_sensors.html>`__)
#. Embedded, low power solution

Best of all, it is modular and you can **integrate** this technology `into your products <https://docs.luxonis.com/projects/hardware/en/latest/pages/guides/integrating_depthai_into_products.html>`__.

DepthAI Viewer
--------------

.. image:: /_static/images/tutorials/viewer_demo.png
  :alt: DepthAI Viewer demo

`DepthAI Viewer <https://github.com/luxonis/depthai-viewer#depthai-viewer-the-visualization-tool-for-depthai>`__ is the
visualization tool for DepthAI and OAK cameras. It's a GUI application that will run a demo app by default, which
will visualize all streams and run inference on the device. It also allows you to change the configuration of the device.
DepthAI viewer works for USB and POE cameras.

To install and run the DepthAI Viewer, run the following commands in the terminal:

.. code-block:: bash

   python3 -m pip install depthai-viewer
   # Run the DepthAI Viewer
   python3 -m depthai_viewer

We have also prepared a **step by step guide** :ref:`here <First steps with DepthAI>` with detailed instructions how to set up your DepthAI and run this script.

Example Use Cases
-----------------

In this section, you'll find an inspiration what can you build right away with DepthAI.

.. raw:: html

   <div class="items-container">
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://user-images.githubusercontent.com/5244214/127147829-0b12b913-85ee-484f-92a0-3ab2bac00ec4.gif" alt="Blazepose Demo"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Pose Estimation</h5>
                  <span class="item-descr">
                      <p>This example shows how to run Google Mediapipe single body pose tracking models</p>
                      <p>Created by our contributor - <a href="https://github.com/geaxgx" target="_blank">Geaxgx</a></p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/geaxgx/depthai_blazepose" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://user-images.githubusercontent.com/5244214/127148741-7f1e0279-5cbc-41a2-95f6-b2d3990131a8.gif" alt="Hand tracker Demo"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Hand Tracking</h5>
                  <span class="item-descr">
                      <p>This example shows how to run Google Mediapipe hand tracking models</p>
                      <p>Created by our contributor - <a href="https://github.com/geaxgx" target="_blank">Geaxgx</a></p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/geaxgx/depthai_hand_tracker" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://youtu.be/BcjZLaCYGi4" target="_blank">
                     <img class="item-img" src="https://user-images.githubusercontent.com/5244214/127150740-b9e8dcd7-3188-4a83-93a8-d1211219ebdb.gif" alt="Human Machine Safety Demo"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Human-Machine Safety</h5>
                  <span class="item-descr">
                      <p>This example shows how to use the DepthAI to detect dangerous interactions between humans and other objects.</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-human-machine-safety" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://youtu.be/tB_-mVVNIro" target="_blank">
                    <img class="item-img" src="https://user-images.githubusercontent.com/5244214/111202991-c62f3980-85c4-11eb-8bce-a3c517abeca1.gif" alt="License plates detection demo"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">License Plates & Car Attributes Recognition</h5>
                  <p class="item-descr">
                      <p>This experiment allows you to run multiple neural networks at once to collect car attributes and license plates (only Chinese)</p>
                  </p>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-license-plate-recognition" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://user-images.githubusercontent.com/18037362/172148301-45adb7ce-3aab-478f-8cad-0c05f349ce50.gif" alt="Head posture detection"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Head posture detection</h5>
                  <span class="item-descr">
                      <p>This example demonstrates 2-stage pipeline with depthai - face detection NN and head pose estimation NN</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-head-posture-detection" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://user-images.githubusercontent.com/5244214/115357410-e900cf00-a1bc-11eb-97d7-baac5d052572.gif" alt="Sign Language Recognition"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Sign Language Recognition</h5>
                  <span class="item-descr">
                      <p>This example demonstrates how to recognize American Sign Language (ASL) on DepthAI using hand landmarks </p>
                      <p>Example by <a href="https://www.cortic.ca/post/classifying-american-sign-language-alphabets-on-the-oak-d" target="_blank">Cortic Technology</a></p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/cortictechnology/hand_asl_recognition" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://user-images.githubusercontent.com/5244214/106155520-0f483d00-6181-11eb-8b95-a2cb73cc4bac.mp4" target="_blank">
                    <img class="item-img" src="https://user-images.githubusercontent.com/5244214/106155937-4fa7bb00-6181-11eb-8c23-21abe12f7fe4.gif" alt="Gaze estimation"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Gaze Estimation</h5>
                  <span class="item-descr">
                      <p>This example demonstrates how to run 3 stage inference (3-series, 2-parallel) on DepthAI using Gen2 Pipeline Builder.</p>
                      <p>Original OpenVINO demo, on which this example was made, is <a target="_blank" href="https://docs.openvinotoolkit.org/2021.1/omz_demos_gaze_estimation_demo_README.html">here</a>.</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-gaze-estimation" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://github.com/luxonis/depthai-experiments/raw/master/gen2-fatigue-detection/media/fatigue.gif" alt="Fatigue Detection"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Fatigue Detection</h5>
                  <span class="item-descr">
                      <p>This example demonstrates the Gen2 Pipeline Builder running face detection network and head detection network</p>
                      <p>This example was created by our partner - <a href="https://www.arducam.com/oak-opencv-ai-kit-camera/" target="_blank">ArduCam</a></p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-fatigue-detection" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://www.youtube.com/watch?v=PwnVrPaF-vs" target="_blank">
                    <img class="item-img" src="https://user-images.githubusercontent.com/5244214/106005496-954a8200-60b4-11eb-923e-b84df9de9fff.gif" alt="Age Gender Recognition"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Age Gender Recognition</h5>
                  <span class="item-descr">
                      <p>This example demonstrates how to run 2 stage inference on DepthAI using Gen2 Pipeline Builder.</p>
                      <p>First, a face is detected on the image and then the cropped face frame is sent to age gender recognition network, which produces the estimated results</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-age-gender" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://user-images.githubusercontent.com/18037362/134054837-eed40899-7c1d-4160-aaf0-1d7c405bb7f4.gif" alt="Face Recognition"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Face Recognition</h5>
                  <span class="item-descr">
                    <p>This example demonstrates the Gen2 Pipeline Builder running face detection network, head posture estimation network and face recognition network</p>
                    <p>This example was created by our partner - <a href="https://www.arducam.com/oak-opencv-ai-kit-camera/" target="_blank">ArduCam</a></p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-face-recognition" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://youtu.be/c4KEFG2eR3M" target="_blank">
                    <img class="item-img" src="https://user-images.githubusercontent.com/5244214/112673778-6a3a9f80-8e65-11eb-9b7b-e352beffe67a.gif" alt="COVID-19 mask detection"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">COVID-19 mask detection</h5>
                  <p class="item-descr">
                      <p>This experiment allows you to run the COVID-19 mask/no-mask object detector which was trained via</p>
                      <p>the Google Colab tutorial <a href="https://github.com/luxonis/depthai-ml-training/tree/master/colab-notebooks#covid-19-maskno-mask-training" target="_blank">here</a>.</p>
                  </p>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/edit/master/gen2-coronamask" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://www.youtube.com/watch?v=QlXGtMWVV18" target="_blank">
                    <img class="item-img" src="https://user-images.githubusercontent.com/32992551/108567421-71e6b180-72c5-11eb-8af0-c6e5c3382874.png" alt="Deeplabv3"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Pedestrian reidentification</h5>
                  <p class="item-descr">
                      <p>This example demonstrates how to run 2 stage inference on DepthAI using Gen2 Pipeline Builder.</p>
                      <p>Original OpenVINO demo, on which this example was made, is <a target="_blank" href="https://docs.openvinotoolkit.org/2020.1/_demos_pedestrian_tracker_demo_README.html">here</a>.</p>
                  </p>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-pedestrian-reidentification" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://user-images.githubusercontent.com/32992551/99454609-e59eaa00-28e3-11eb-8858-e82fd8e6eaac.png" alt="Camera Demo"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Camera Demo</h5>
                  <span class="item-descr">
                      <p>This example shows how to use the DepthAI/megaAI/OAK cameras in the Gen2 Pipeline Builder over USB.</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-camera-demo" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://www.youtube.com/watch?v=M1LTqGy-De4" target="_blank">
                    <img class="item-img" src="https://user-images.githubusercontent.com/18037362/134072030-102f4567-2071-491e-b97f-049d558dd812.gif" alt="Deeplabv3"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Deeplabv3 (Segmentation)</h5>
                  <span class="item-descr">
                      <p>This example shows how to run Deeplabv3+ and crop the depth image based on the models output.</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-deeplabv3_depth" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
      <div class="items-row">

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <img class="item-img" src="https://github.com/luxonis/depthai-experiments/raw/master/gen2-fire-detection/images/fire_demo.gif" alt="Fire detection"/>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Fire detection</h5>
                  <span class="item-descr">
                      <p>This example demonstrates the Gen2 Pipeline Builder running fire detection network</p>
                      <p>This example was created by our partner - <a href="https://www.arducam.com/oak-opencv-ai-kit-camera/" target="_blank">ArduCam</a></p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-fire-detection" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

         <div class="items-col">
            <div class="item">
               <div class="item-img-wrapper">
                  <a href="https://www.youtube.com/watch?v=Bv-p76A3YMk" target="_blank">
                     <img class="item-img" src="https://user-images.githubusercontent.com/5244214/115358042-8d831100-a1bd-11eb-8782-415392c71a87.png" alt="Gen2 OCR"/>
                  </a>
               </div>
               <div class="item-body">
                  <h5 class="item-title">Text Detection + OCR</h5>
                  <span class="item-descr">
                    <p>This example demonstrates the Gen2 Pipeline Builder running text detection (EAST) followed by optical character recognition of the detected text</p>
                  </span>
               </div>
               <footer class="item-footer">
                  <a href="https://github.com/luxonis/depthai-experiments/tree/master/gen2-ocr" class="btn item-cta">Try now ›</a>
               </footer>
            </div>
         </div>

      </div>
   </div>

Tools & API Examples
--------------------

In this section, you'll see examples of various API usage permutations, to show what the API is capable of or to solve
some meta problem, like how to stream the data, how to collect it and alike.

.. list-table::
  :widths: 10 90

  * - `OCR <https://github.com/luxonis/depthai-experiments/tree/master/gen2-ocr>`__
    - This pipeline implements text detection (EAST) followed by optical character recognition of the detected text
  * - `Multiple Devices <https://github.com/luxonis/depthai-experiments/tree/master/gen2-multiple-devices>`__
    - This example shows how you can use multiple DepthAI's on a single host. The demo will find all devices connected to the host and display an RGB preview from each of them
  * - `Face recognition <https://github.com/luxonis/depthai-experiments/tree/master/gen2-face-recognition>`__
    - Detects all faces in the frame, gets face feature vectors and compares it with database to perform face recognition
  * - `Message Syncing <https://github.com/luxonis/depthai-experiments/tree/master/gen2-syncing>`__
    - This example shows how to sync messages (eg. NN results with frames) with software, based on either timestamps or sequence numbers
  * - `License plate recognition <https://github.com/luxonis/depthai-experiments/tree/master/gen2-license-plate-recognition>`__
    - Detects license plates and performs license plate recognition operation on the camera itself
  * - `WLS Filtering <https://github.com/luxonis/depthai-experiments/tree/master/gen2-wls-filter>`__
    - This example demonstrates how to do host-side WLS filtering using the rectified_right and depth stream from DepthAI API
  * - `QR code scanner <https://github.com/luxonis/depthai-experiments/tree/master/gen2-qr-code-scanner>`__
    - QR Code detection model running on the device combined with on-host QR code decoder
  * - `Deploy Roboflow models <https://blog.roboflow.com/deploy-roboflow-model-luxonis-depth-sdk>`__
    - Deploy over 10,000 pre-trained AI models from Roboflow Universe and your own Roboflow custom models

Ecosystem
---------

.. list-table:: Core Repositories
  :widths: 10 90

  * - `depthai-python <https://github.com/luxonis/depthai-python/>`__
    - Here you'll find Python bindings creating the Python API of DepthAI
  * - `depthai-core <https://github.com/luxonis/depthai-core/>`__
    - Our core API written in C++
  * - `depthai-ros <https://github.com/luxonis/depthai-ros/>`__
    - DepthAI ROS Wrapper. This is an attempt at basic DepthAI to ROS2
      interface. It's largely leveraging the existing depthai-python examples.
  * - `depthai-unity <https://github.com/luxonis/depthai-unity>`__
    - DepthAI Unity Wrapper projects and examples. Useful for synthetic dataset generation.
  * - `depthai-hardware <https://github.com/luxonis/depthai-hardware/>`__
    - This repository contains Luxonis open sourced baseboards, and contains
      Altium design files, documentation, and pictures to help you
      understand more about the embedded hardware that powers DepthAI.
  * - `depthai-ml-training <https://github.com/luxonis/depthai-ml-training/>`__
    - Here you can find repositories to help you connect your NN and create BLOBs.


.. list-table:: Demo Repositories
  :widths: 10 90

  * - `depthai-experiments <https://github.com/luxonis/depthai-experiments/>`__
    - In this repository, you'll find various experiments using DepthAI. You can use those examples as a basis or a reference in your application.
  * - `depthai <https://github.com/luxonis/depthai/>`__
    - This repo contains a demo application, which can load different networks, create pipelines, record video, etc. This program includes an example of depth & CNN inference and ready to use models.
  * - `depthai-core-example <https://github.com/luxonis/depthai-core-example/>`__
    - CMake example project which serves as a template on how to quickly get started with C++ and depthai library
  * - `depthai-tutorials <https://github.com/luxonis/depthai-tutorials/>`__
    - This repo contains source code for tutorials published on docs.luxonis.com.
  * - `depthai-docker <https://github.com/luxonis/depthai-docker/>`__
    - This repository contains a Dockerfile, that allows you to run OpenVINO on DepthAI inside a Docker container.

.. include::  /pages/includes/footer-short.rst

.. toctree::
   :hidden:
   :maxdepth: 0

   index


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Tutorials

   pages/tutorials/first_steps.rst
   pages/spatial-ai.rst
   pages/ai_ml_nn.rst
   pages/depth.rst
   pages/cv.rst
   pages/tutorials/on-device-programming.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Modules:

   C++/Python API <https://docs.luxonis.com/projects/api/en/latest/>
   DepthAI SDK <https://docs.luxonis.com/projects/sdk/en/latest/>
   Hardware Products <https://docs.luxonis.com/projects/hardware/en/latest/>


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Contents

   pages/faq.rst
   pages/oak_webcam.rst
   pages/troubleshooting.rst
   pages/slam_oak.rst
   pages/oak_on_drones.rst
   pages/education.rst
   pages/support.rst
