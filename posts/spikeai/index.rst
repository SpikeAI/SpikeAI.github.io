.. title: SpikeAI: laureat du Défi Biomimétisme 2019
.. slug: spikeai
.. date: 2019-04-01 23:00:00 UTC-03:00
.. tags: nikola, python, demo, blog
.. author: Laurent Perrinet
.. link: https://laurentperrinet.github.io/project/spikeai
.. description:
.. category: spikeAI

.. figure:: https://farm1.staticflickr.com/138/352972944_4f9d568680.jpg
   :target: https://farm1.staticflickr.com/138/352972944_4f9d568680_z.jpg?zz=1
   :class: thumbnail
   :alt: Nikola Tesla Corner by nicwest, on Flickr


Algorithmes événementiels d’Intelligence Artificielle / Event-Based Artificial Inteligence
------------------------------------------------------------------------------------------

The SpikeAI project targets analog computing for artificial intelligence in the form of Spiking Neural Networks (SNNs). Computer vision systems widely rely on artificial intelligence and especially neural network based machine learning, which recently gained huge visibility. The training stage for deep convolutional neural networks is time-consuming and yields enormous energy consumption. In contrast, the human brain has the ability to perform visual tasks with unrivaled computational and energy efficiency. It is believed that one major factor of this efficiency is the fact that information is vastly represented by short pulses (spikes) at analog –not discrete– times. However, computer vision algorithms using such representation still lack in practice, and its high potential is largely underexploited. Inspired from biology, the project addresses the scientific question of developing a low-power, end-to-end analog sensing and processing architecture. This will be applied on the particular context of a field programmable analog array (FPAA) applied to a stereovision system dedicated to coastal surveillance using an aerial robot of 3D visual scenes, running on analog devices, without a central clock and to validate them in real-life situations. The ambitious long-term vision of the project is to develop the next generation AI paradigm that will at term compete with deep learning. We believe that neuromorphic computing, mainly studied in EU countries, will be a key technology in the next decade. It is therefore both a scientific and strategic challenge for France and EU to foster this technological breakthrough. *This call will help kickstart collaboration within this European consortium to help leverage the chance to successfully apply to future large-scale grant proposals (e.g. ANR, CHIST-ERA, ERC).*

State-of-the-art
----------------

One important characteristic of today's computer vision systems is that most of them are frame-based. Conventional video sensors record the entire image with a given rate and resolution. The original rationale for sensing a scene in this way is that the transmission or recording is intended to be viewed by a human observer who may be looking closely at any part of the moving image. Frame-based video contains a huge amount of redundant data and requires enormous computational power to process. As stated in [Hopkins et. al 2018], biological vision sensors, however, are quite different from frame-based cameras. They do not sample images at a uniform rate, nor at a uniform resolution. The human eye has a small high-resolution region (the fovea) in the centre of the field of vision, and a much larger vision periphery, which has much lower resolution, combined with an increased sensitivity to movement. In this way, limited resources are deployed to extract the most salient information from the scene without wasting energy capturing the entire scene at the highest resolution. Furthermore, the human eye is primarily sensitive to changes in the luminance falling on its individual sensors. These changes are processed by layers of neurons in the retina through to the retinal ganglion cells that generate action potentials, or ‘spikes’ whenever a significant change is detected [IMSE2]. Then, these spikes propagate through the optic nerve to the brain [INT1]. This approach focuses resources on the areas of the image that convey maximum useful information such as edges and other details. Given the core objective of computer vision systems, it seems natural to sense the world with bio-inspired sensors. Moreover, primates and other mammals are given the ability to compute depth information from views acquired simultaneously from different points in space with stereopsis, which is a fundamental feature in environment 3D sensing [IMSE1, IMSE3].

Objectives
----------

Computer vision systems widely rely on artificial intelligence and especially neural network based machine learning (ML), which recently gained huge visibility. The training stage for deep convolutional neural networks is time-consuming (it requires up to several weeks with GPU servers) and yields enormous energy consumption, despite most recent advances in parallel digital architectures. In contrast, the human brain has the ability to perform visual tasks with unrivaled computational and energy efficiency. It is believed that one major factor of this efficiency is the fact that information is vastly represented by spikes at analog –not discrete– times. However, computer vision algorithms using such representation still lack in practice, and its high potential is largely underexploited. A major scientific deadlock is the lack of real-world, end-to-end analog algorithms based on SNNs.

To achieve such a program, we need a novel way to collaborate in an inter-disciplinary network. We propose a consortium from four EU countries has a unique combination of expertise necessary for this ambitious project. Spiking Neural Networks (SNNs) specialists from the field of visual sensors [IMSE4, IMSE5] (IMSE, Spain), neural network architecture [UL1, UL2] and computer vision [UL3, UL4] (Uni. Lille, France) and computational neuroscience (INT, France) will team up with robotics and automatic control specialists [NTUA1-4]  (NTUA, Greece), and low power integrated systems designers (ETHZ, Switzerland) to help geoinformatics researchers [UNIWA1-5] (UNIWA, Greece) build a demonstrator UAV (TRL5) for coastal surveillance. All the members of the consortium share a common interest in analog based computing and computer vision with complementary points of view and expertise. The ambitious long-term vision of the project is to develop the next generation AI paradigm that will at term compete with deep learning. We believe that neuromorphic computing, mainly studied in EU countries, will be a key technology in the next decade. It is therefore both a scientific and strategic challenge for France and EU to foster this technological breakthrough. The BIOMIMETISME2019 call will help kickstart collaboration within this european consortium to help leverage the chance to successfully apply to future large-scale grant proposals (e.g. ANR, CHIST-ERA, ERC).

Methodology
-----------

Our proposal is that we will be able to define a novel Biologically inspired machine learning for vision based on the properties of SNNs. It will consist in the general definition of an information-processing unit, inspired by the organization of the cortex surface into highly interconnected elementary microcircuits. In parallel, we will develop bio-inspired algorithms targeted for analog event-based representations. In particular, we will learn to detect prototypical temporal patterns, which could be implemented using heterosynaptic delays, that is, differential delay lines tuning the temporal precision of the flow of analog events. We expect more efficient processing for low-level vision tasks (e.g. optical flow characterization), but also to reach higher information fidelity, without the noise induced by conventional capture and pre-processing processes. To our knowledge, this approach is completely innovative.

Standing out from the main stream of frame-based vision with deep learning, the project targets event-based vision using SNNs. We will develop new paradigms for low-power biologically-inspired end-to-end analog vision, from sensing to processing, in order to help machines (namely UAVs, but also autonomous vehicles and robots) gain 3D representation of real world visual scenes. A central aspect is the preservation of an analog chain between sensing and processing, maintaining the benefits and consistency of analog representations.

Outcomes
--------

Key challenges of this project will be end-to-end analog system design (from sensing to AI-based control of the UAV and 3D coastal volumetric reconstruction), energy efficiency, and practical usability in real conditions. We aim to show that such a bioinspired analog design will bring large benefits in terms of power efficiency, adaptability and efficiency needed to make coastal surveillance with UAVs practical and more efficient than digital approaches.

As stated, we aim at building in the longer term a technological demonstrator that will demonstrate the feasibility of the approach. The key challenges of this project will be end-to-end analog system design (from sensing to AI-based control of the UAV and 3D coastal image reconstruction), energy efficiency, and practical usability in real conditions.

Some of our explicit goals with this project are to strengthen the EU Spiking Neural Networks interdisciplinary research community by bringing researchers from different expertise and domains to work on a common concrete objective, to share with the scientific community our findings and the data we will gather to enable further research, and demonstrate the possibilities offered by analog computing for artificial intelligence. In particular, we aim at organizing a workshop on the subject in Marseille.

To realize this project, the coordinator organization will devote 3 person.months, including coordination of the project, and supervision of the master student. Each other participant will devote 1 person.month, mainly for the definition of the algorithm and the participation to the workshop.

References
----------

* [Hopkins et. al 2018] Hopkins M, Pineda-Garcıa G, Bogdan PA, Furber SB. 2018 Spiking neural networks for computer vision. Interface Focus8: 20180007. Link.

* [IMSE1] L. A. Camuñas-Mesa, T. Serrano-Gotarredona, S. Ieng, R. Benosman and B. Linares-Barranco, "Event-driven Stereo Visual Tracking Algorithm to Solve Object Occlusion," IEEE Trans. on Neural Networks and Learning Systems, vol. 29, no. 9, pp. 4223-4237, Sept. 2018.

* [IMSE2] C. Posch, T. Serrano-Gotarredona, B. Linares-Barranco, and T. Delbrück, "Retinomorphic Event-Based Vision Sensors: Bioinspired Cameras with Spiking Output," Proceedings of the IEEE, vol. 102, No. 10, pp. 1470-1484, October 2014.

* [IMSE3] L. A. Camuñas-Mesa, T. Serrano-Gotarredona, S. H. Ieng, R. B. Benosman, and B. Linares-Barranco, "On the Use of Orientation Filters for 3D Reconstruction in Event-Driven Stereo Vision," Frontiers in Neuromorphic Engineering, Front. Neurosci. 8:48. doi: 10.3389/fnins.2014.00048.

* [IMSE4] T. Serrano-Gotarredona and B. Linares-Barranco, "A 128x128 1.5% Contrast Sensitivity 0.9% FPN 3us Latency 4mW Asynchronous Frame-Free Dynamic Vision Sensor Using Transimpedance Amplifiers," IEEE J. Solid-State Circuits, vol.48, No. 3, pp. 827-838, March 2013.

* [IMSE5] J. A. Leñero-Bardallo, T. Serrano-Gotarredona, B. Linares-Barranco, "A 3.6us Asynchronous Frame-Free Event-Driven Dynamic-Vision-Sensor," IEEE J. of Solid-State Circuits 46(6), 2011

* [UL1] Pierre Falez, Pierre Tirilly, Ioan Marius Bilasco, Philippe Devienne, Pierre Boulet. Mastering the Output Frequency in Spiking Neural Networks, International Joint Conference on Neural Networks (IJCNN), Jul 2018, Rio de Janeiro, Brazil. HAL link.

* [UL2] Pierre Falez, Philippe Devienne, Pierre Tirilly, Marius Bilasco, Christophe Loyez, Ilias Sourikopoulos, Pierre Boulet, Flexible Simulation for Neuromorphic Circuit Design: Motion Detection Case Study, COMPAS 2017. HAL link.

* [UL3] Veïs Oudjail, Jean Martinet. Bio-inspired event-based motion analysis with spiking neural networks, Accepted to the International Conference on Computer Vision Theory and Applications (VISAPP'19), Feb 25-27 2019,  Prague, Czech Republic. HAL link.

* [UL4] Amel Aissaoui, Jean Martinet, Chabane Djeraba. Rapid and accurate face depth estimation in passive stereo systems. Multimedia Tools Appl. 72(3): 2413-2438 (2014)

* [UNIWA1]  Hloupis, G., Pagounis, V., Tsakiri, M., Doxastakis, G., Zacharis, V. 2017. Low-cost warning system for the monitoring of the Corinth Canal. Applied Geomatics (Springer, 2017) , pp. 1–15

* [UNIWA2] Panagou, Th., Hasiotis, T., Velegrakis, A.F. and E. Oikonomou. 2016. Coastal cliff erosion monitoring applying terrestrial laser scanner in Zakytnos Isl. Greece, Fourth International Conference on Remote Sensing and Geoinformation of the Environment 2016, 4-8 April, 2016, Cyprus

* [UNIWA3] C. Stentoumis, L. Grammatikopoulos, I. Kalisperakis, G. Karras. 2014. On accurate dense stereo-matching using a local adaptive multi-cost approach. ISPRS Journal of Photogrammetry and Remote Sensing, Volume 91, May 2014, Pages 29-49, ISSN 0924-2716

* [UNIWA4] Krassanakis V., Da Silva M. P., & Ricordel V. (2018), Monitoring Human Visual Behavior during the Observation of Unmanned Aerial Vehicles (UAVs) Videos, Drones, 2(4), 36.

* [UNIWA5] Krassanakis V., & Vassilopoulou V. (2018), Introducing a data-driven approach towards the identification of grid cell size threshold (CST) for spatial data visualization: an application on Marine Spatial Planning (MSP), Journal of Urban and Environmental Engineering, 12 (1).

* [NTUA1] P. Marantos, Y. Koveos, and Kostas J. Kyriakopoulos “UAV State Estimation using Adaptive Complementary Filters”, IEEE Trans. on Control Systems Technology, issue:99, Oct. 2015, pp 1-13.

* [NTUA2] P. Marantos, C. P. Bechlioulis and Kostas J. Kyriakopoulos “Robust Trajectory Tracking Control for Small-scale Unmanned Helicopters with Model Uncertainties”, IEEE Transactions on Control Systems Technology, DOI: 10.1109 / TCST.2016.2642160, Dec 2016.

* [NTUA3] Panos Marantos,  George C. Karras, Panagiotis Vlantis and Kostas J. Kyriakopoulos, “Vision-based Autonomous Landing Control for Unmanned Helicopters”, Journal of Intelligent & Robotic Systems, Springer, October 2017,  Link.

* [NTUA4] Panagiotis Vlantis, Panos Marantos, Charalampos Bechlioulis and Kostas Kyriakopoulos “Quadrotor Landing on an Inclined Platform of a Moving Ground Vehicle” 2015 IEEE International Conference on Robotics and Automation, May 26-30, 2015, Washington State Convention Center, Seattle, Washington, USA
