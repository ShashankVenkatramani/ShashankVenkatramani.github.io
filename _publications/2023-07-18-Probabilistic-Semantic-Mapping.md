---
title: "Probabilistic Semantic Mapping for Autonomous Driving in Urban Environments"
collection: publications
category: manuscripts
permalink: 'https://www.mdpi.com/1424-8220/23/14/6504'
excerpt: 'Semantic Segmentation projected onto pointclouds, and then into 2D as a prior for downstream Autonomous Vehicle tasks'
date: 2023-07-18
venue: 'MDPI Sensors 2023'
paperurl: 'https://www.mdpi.com/1424-8220/23/14/6504'
citation: '
@Article{s23146504,
  AUTHOR =       {Zhang, Hengyuan and Venkatramani, Shashank and Paz, David and
                  Li, Qinru and Xiang, Hao and Christensen, Henrik I.},
  TITLE =        {Probabilistic Semantic Mapping for Autonomous Driving in Urban
                  Environments},
  JOURNAL =      {Sensors},
  VOLUME =       {23},
  YEAR =         {2023},
  NUMBER =       {14},
  ARTICLE-NUMBER ={6504},
  URL =          {https://www.mdpi.com/1424-8220/23/14/6504},
  ISSN =         {1424-8220},
  ABSTRACT =     {Statistical learning techniques and increased computational
                  power have facilitated the development of self-driving car
                  technology. However, a limiting factor has been the high
                  expense of scaling and maintaining high-definition (HD) maps.
                  These maps are a crucial backbone for many approaches to
                  self-driving technology. In response to this challenge, we
                  present an approach that fuses pre-built point cloud map data
                  with images to automatically and accurately identify static
                  landmarks such as roads, sidewalks, and crosswalks. Our
                  pipeline utilizes semantic segmentation of 2D images,
                  associates semantic labels with points in point cloud maps to
                  pinpoint locations in the physical world, and employs a
                  confusion matrix formulation to generate a probabilistic
                  bird’s-eye view semantic map from semantic point clouds.
                  The approach has been tested in an urban area with different
                  segmentation networks to generate a semantic map with road
                  features. The resulting map provides a rich context of the
                  environment that is valuable for downstream tasks such as
                  trajectory generation and intent prediction. Moreover, it has
                  the potential to be extended to the automatic generation of HD
                  maps for semantic features. The entire software pipeline is
                  implemented in the robot operating system (ROS), a widely used
                  robotics framework, and made available.},
  DOI =          {10.3390/s23146504}
}
'
---