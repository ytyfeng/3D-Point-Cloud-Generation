# 3D-Point-Cloud-Generation
A web app to generate a 3D Point Cloud from a set of 2D images of an item using Structure from Motion 
## Author: Ty Feng

## Inspiration
Traditionally 3D model acquisition was not widely accessible to everyone due to the complexity of hardware required. Typically the user would need specialized cameras with depth or time-of-flight sensors in order to create 3D models. However, with Structure from Motion (SfM) techniques it is possible to create 3D models without complex hardware and cameras. Our web app allows users to upload images of an object and create a 3D point cloud of the object with the result rendered on the frontend in real-time. It democratizes technologies and algorithmic techniques to everyone. 

## What it does
The web page takes in multiple 2D images of an item and using structure from motion (a photogrammetric range imaging technique for estimating three-dimensional structures from two-dimensional image sequences that may be coupled with local motion signals) from the openMVG library to generate a 3D Point Cloud the item. This 3D Point Cloud is visualized using Three.js.

## How we built it
We have used html5 with bootstrap on the front-end and python with Flask framework on the back-end. The home page built using HTML5 and bootstrap, is the interface for the user to upload the 2D Image Sequences (with multiple file format support). The whole project is based on the google cloud compute engine, with the Flask framework used for communicating the resources from the gcloud and Python. We have used the openMVG and its structure from motion capabilities to generate a 3D point cloud and finally for viewing the output we have used Three.js. 

## Challenges we ran into
For some of the group members it was the first time using Google Cloud Platform. Most of the challenges stemmed from unfamiliarity with certain technology used which was supplemented with tutorials and teaching one another.

## Accomplishments that we're proud of
We were able to successfully render a 3D point cloud model and complete the project despite concerns that our idea was too ambitious to complete within the time frame given. 

## What we learned
Our team consisted of members with different skill levels and knowledge. For some it our first time using some of the technology employed in the project, such as GCP and Flask. We learned to work better as a team and teach one another different skills in order to contribute to the project. Over all, it was a steep learning curve, but a fun and exciting challenge for all. 

## What's next for 3D Point Cloud Generation Tool
The next steps for the project would be generate a 3D Model with the 3D Point cloud generated, with future use in an AR/VR application to be able to play with the model real-time.

## Built With
`Python`, `Flask`, `Three.js`, `Google Cloud Compute Engine`, `openMVG`, `html5`, `bootstrap`
