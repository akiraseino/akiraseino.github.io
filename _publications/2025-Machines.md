---
title: "Fabric Flattening with Dual-Arm Manipulator via Hybrid Imitation and Reinforcement Learning"
collection: publications
permalink: /publications/2025-Machines
date: 2025-10-6
journal: "Machines"
issue: "10"
number: "13"
year: "2025"
page: ""
paperurl: 'https://www.mdpi.com/2075-1702/13/10/923'
url: 'https://www.mdpi.com/2075-1702/13/10/923'
authors: "Y. Ma<sup>1</sup>, F. Tokuda<sup>2, 3</sup>, A. Seino<sup>2, 3</sup>, A. Kobayashi<sup>2, 3</sup>, M. Hayashibe<sup>1</sup>, B. Jin<sup>2, 4</sup>, K. Kosuge<sup>2, 3, 4</sup>"
affiliations: "1. School of Engineering, Tohoku University, 6-6-01 Aobra Aramaki, Aoba-ku, Sendai, Miyagi, 980-8579, Japan <br> 2. Centre for Transformative Garment Production, Unites 1215 to 1220, 12/F, Building 19W, SPX1, Hong Kong Schience Park, Pak Shek Kok, N. T., Hong Kong SAR <br> 3. Department of Electrical and Electronic Engineering, The University of Hong Kong, Hong Kong SAR <br> 4. Director of the JC STEM Lab of Robotics forSoft Materials, Department of Electrical and Electronic Engineering, Faculty of Engineering, The University of Hong Kong, Hong Kong SAR <br>"
doi: 10.3390/machines131
---
Abstract
:	Fabric flattening is a critical pre-processing step for automated garment manufacturing. Most existing approaches employ single-arm robotic systems that act at a single contact point. Due to the nonlinear and deformable dynamics of fabric, such systems often require multiple actions to achieve a fully flattened state. This study introduces a dual-arm fabric-flattening method based on a cascaded Proposal–Action network with a hybrid training framework. The PA network is first trained through imitation learning from human demonstrations and is subsequently refined through reinforcement learning with real-world flattening feedback. Experimental results demonstrate that the hybrid training framework substantially improves the overall flattening success rate compared with a policy trained only on human demonstrations. The success rate for a single flattening operation increases from 74% to 94%, while the overall success rate improves from 82% to 100% after two rounds of training. Furthermore, the learned policy, trained exclusively on baseline fabric, generalizes effectively to fabrics with varying thicknesses and stiffnesses. The approach reduces the number of required flattening actions while maintaining a high success rate, thereby enhancing both efficiency and practicality in automated garment manufacturing.