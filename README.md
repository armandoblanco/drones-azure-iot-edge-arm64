We have found that one of the great areas of interest in many of the customers is to use Computer Vision's capabilities to solve problems, for example, process inspection to ensure quality in manufacturing, industrial inspection and to identify if a worker is on a prohibited area, an element it has been spilled or a worker has no use helmet, but a very interesting one is the visual inspection with drones.

Currently drones have become different industries in a key element to achieve more efficient processes, saving time and early problems's detection, for example in the agro industry the drones can help us to detect areas of low production, problems of undergrow or in other industries such as mining or manufacturing can help to detect early problems with railways, strauctures among others.

There are several mechanisms to implement AI models in the drones, for example with simple drone we can use a base station which can capture streaming video from a drone such as Mavik Air or in the same drone extend the capabilities through the use of a card and cpñpcar the edge compute in the drone.

In Microsoft we have the technology called Azure IoT Edge https://docs.microsoft.com/en-us/azure/iot-edge/ which allows us to compute devices such as a drone or cards, we have worked with Drones DJI Matrice which has DJI Manifold device https://www.dji.com/mx/manifold which have an arm64 architecture like a TX2 or Xavier, after much time invested to be able to implement the


The article will divide the following chapters.

1. Enable Azure IoT Edge in an ARM64 architecture (Actually, this is not officially supported by Microsoft) https://docs.microsoft.com/en-us/azure/iot-edge/support
2. How implement Docker containers multiarch
3. Enable GPUs and Cameras in the Docker Containers
3. Example to capture images of a USB camera, in a container with OpenCV, and process a model trained in Custom Vision, all running on Azure IoT Edge
