---
title: "Deep Learning Based Topography Aware Gas Source Localization with Mobile Robot"
collection: publications
category: published
priority: 1
permalink: /publication/Topography_aware_GSL
excerpt: "Our paper about spatial gas perception. We utilized an U-net to predict gas leakage source based on environmental spatial context. It's the first work presenting gas source localization in complex indoor environment<br/><img src='https://raw.githubusercontent.com/CHTiansweet/CHTian/master/images/GSLabstract.png'>"
# date: 2009-10-01
 venue: '2025 IEEE International Conference on Robotics & Automation'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://github.com/CHTiansweet/CHTian/blob/master/files/GSL_preprint.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Gas source localization in complex environments is critical for applications such as environmental monitoring, industrial safety, and disaster response. Traditional methods often struggle with the challenges posed by a lack of environmental topography integration, especially when interactions between wind and obstacles distort gas dispersion patterns. In this paper, we propose a deep learning-based approach, which leverages spatial context and environmental mapping to enhance gas source localization. By integrating Simultaneous Localization and Mapping (SLAM) with a U-Net-based model, our method predicts the likelihood of gas source locations by analyzing gas sensor data, wind flow, and topography of the environment represented by a 2D occupancy map. We demonstrate the efficacy of our approach using a wheeled robot equipped with a photoionization detector, a LIDAR, and an anemometer, in various scenarios with dynamic wind fields and multiple obstacles. The results show that our approach can robustly locate gas sources, even in challenging environments with fluctuating wind directions, outperforming conventional methods by utilizing topography contextual information. This study underscores the importance of topographical context in gas source localization and offers a flexible and robust solution for real-world applications.<br>

You can find a short demo video here https://youtu.be/hftQQQpgXKM
