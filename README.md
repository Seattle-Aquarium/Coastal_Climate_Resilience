# Coastal Climate Resilience at the Seattle Aquarium 

## Overview 
This is a public repository to organize information and resources regarding the Seattle Aquarium's **Coastal Climate Resilience** (CCR) program. 
Specifically, we have developed and implemented standardized methods to use small remotely operated vehicles (ROVs) to conduct video/photo surveys along relatively shallow coastal areas (5-40m depth), especially along canopy-forming and understory kelp forest locations. 
We envision fully integrating ROVs as another tool in the coastal ecologists' toolkit that can (among other missions) complement and enhance existing long-term subtidal monitoring programs. 

<div align="center">
  <img src="https://github.com/zhrandell/Seattle_Aquarium_Coastal_Climate_Resilience/blob/main/photos/ROV_GIF_1.gif" alt="Description of GIF">
</div>

**Our objectives:** 
* **1.** Expand the spatial extent (seafloor area) across which we gather high-resolution photo/video imagery.
  
* **2.** Use open-source AI methods of image analysis to efficiently extract large amounts of data from our imagery. 
  
* **3.** Conduct data analysis to better understand the patterns of population health and ecological resilience for kelp, invertebrates, and fishes. 
  
* **4.** Integrate these ROV-derived data with other sources of information such as data from scuba divers, fixed sensors, autonomous surface vessels (ASVs), drones, and satellite imagery, in order to maximize our inferences about benthic community structure, stability, and resilience.
  
* **5.** We commit to pursue **1.** - **4.** in an open-source, open-access manner such that our partners, collaborators, and the public can replicate what we've started in order to advance their own coastal monitoring, conservation, restoration, and management objectives. We likewise commit to actively support our partners in the development of their own ROV programs. Similar to the broad geographic reach of the standardized protocols set down by scientific diving programs such as Reef Check and PISCO, we envision a network of collaborators using standardized ROV survey protocols to enhance our collective data collection, analysis, and coordination capacity.

The purpose of this repo is to make general and introductory information about the CCR program accessible to our partners, collaborators, and the public. 
All information and documentation associated with the repo is freely available to download and share. 
We welcome collaborators and partners, as well as feedback, comments, and questions. Please direct contact to z.randell@seattleaquarium.org

<p float="center">
  <img src="photos/2024_1.jpg" width="400" height="350" />
  <img src="photos/2024_2.jpg" width="400" height="350" />
 </p>
 
 
 <p float="center">
  <img src="photos/2024_4.jpg" width="400" height="350" />
  <img src="photos/site_1.jpg" width="400" height="350" /> 
</p>

## General information; workflows ready to implement
The following repos contain general information about our work, and specialized repos for ROV telemetry analyses, processing and analyses of ROV-derived benthic abundance and distribution data, and simulating benthic data.  

```mermaid
graph TD

A["<a href='https://github.com/Seattle-Aquarium/Coastal_Climate_Resilience' target='_blank' style='font-size: 16px; font-weight: bold;'>Coastal_Climate_Resilience</a><br><font color='darkgray'>the main landing pad for the CCR research program</font>"]

A --> E["<a href='https://github.com/Seattle-Aquarium/CCR_analytical_resources' target='_blank' style='font-size: 16px; font-weight: bold;'>CCR_ROV_telemetry_processing</a><br><font color='darkgray'>analytical tools for working with ROV telemetry data</font>"]

A --> F["<a href='https://github.com/Seattle-Aquarium/CCR_benthic_analyses' target='_blank' style='font-size: 16px; font-weight: bold;'>CCR_benthic_analyses</a><br><font color='darkgray'>code to work with ROV-derived benthic community data</font>"]

A --> G["<a href='https://github.com/Seattle-Aquarium/CCR_benthic_taxa_simulation' target='_blank' style='font-size: 16px; font-weight: bold;'>CCR_benthic_taxa_simulation</a><br><font color='darkgray'>code to simulate ROV-derived benthic community</font>"]
```

## Help wanted! 
The following repos involve active areas of open-source software development, AI/ML implementation, and computer vision challenges; areas where we could use assistance are 🔶 highlighted in orange 🔶

```mermaid
graph TD

B["<a href='https://github.com/Seattle-Aquarium/CCR_development' target='_blank' style='font-size: 16px; font-weight: bold;'>CCR_development</a><br><font color='darkgray'>main hub for organizing active Issues under development </font>"]

B --> C["<a href='https://github.com/Seattle-Aquarium/CCR_image_processing' target='_blank' style='font-size: 16px; font-weight: bold;'>CCR_image_processing</a><br><font color='darkgray'>help wanted to implement AI/ML solution to expendite image processing</font>"]

B --> D["<a href='https://github.com/Seattle-Aquarium/CCR_kelp_feature_detection' target='_blank' style='font-size: 16px; font-weight: bold;'>CCR_kelp_feature_detection</a><br><font color='darkgray'>active research re: photogrammetry in kelp forests</font>"]

style B stroke:#FF8600,stroke-width:4px
style C stroke:#FF8600,stroke-width:4px
```

## ROV videos, photos from deployments, and hardware/software 
* To view an example of ROV survey imagery, see [this folder](https://www.dropbox.com/scl/fo/c6bw7jn0akgdu0wrshwnm/AM96nKZ9ApqJCPLfCwaqYsE?rlkey=0boyf0f0r2vc469rdopfycejr&st=sue5tt55&dl=0) with imagery from offshore of Centennial Park, Seattle 
* To view videos from the ROV, see the _ROV_video_vignettes_ document ([here](https://github.com/zhrandell/Seattle_Aquarium_ROV_development/blob/main/ROV_videos.md))
* To view all hardware and software associated with this project, see the _hardware_software_ document ([here](https://github.com/zhrandell/Seattle_Aquarium_ROV_development/blob/main/documents/hardware_software.md))

## Public facing
* To view an Earth Day at the Seattle Aquarium with Xbox livestream, see [this link](https://www.twitch.tv/videos/2438923866)
* To view a August 2024 guest lecture at the Applied Physics Lab (APL), see [this link](https://www.youtube.com/watch?v=w-YeXgaE_F0)
* To view a Seattle Channel video detailing our partnership with Port of Seattle, see [this link](https://www.youtube.com/watch?app=desktop&v=WdsnsdwxIYs)
* To read a Seattle Times article about our partnership with the Port of Seattle, see [this link](https://www.seattletimes.com/sponsored/seattle-partnership-dives-into-the-mysteries-of-elliott-bays-bull-kelp/)
* To view a keynote talk at BlueTIDES 2023 hosted by Blue Robotics in Los Angeles, see [this link](https://www.dropbox.com/scl/fi/acp4qsdphob1a42kp7nxb/blueTIDES_2023.mp4?rlkey=k5dhch9pyj9pzha5qcgklf5l1&dl=0)
* To view an October 2023 talk at the Elakha Alliance Sea Otter Science Symposium, see [this link](https://www.youtube.com/watch?v=GUMnOl4OmFQ) 
* To view a live-streamed ROV dive facilitated by StreamYard and a Verizon MiFi unit, see [this link](https://www.youtube.com/watch?v=6dmY5qtlVhw&t=300s)
* To view a January 2023 talk at the Puget Sound Kelp Research and Monitoring Workgroup, see [this link](https://www.youtube.com/watch?v=weyHmOVaXjk&t=5935s)
* To view a Xbox Twitch Stream event, view [this link](https://www.twitch.tv/xbox/video/1800600515) starting at 22:00.  
* To read a post detailing our research on the BlueRobotics forums, see [this link](https://discuss.bluerobotics.com/t/new-research-using-customized-bluerov2-to-conduct-kelp-forest-surveys/13166)
* To read an article in the Wahkiakum County Eagle about our ROV outreach and engagement, see [this link](https://www.waheagle.com/story/2022/12/08/wahkiakum-people/seattle-aquarium-gives-career-talk-and-demo-at-town-pool/21681.html)

## Synopses
* To read the 2024 year-end report to the Port of Seattle, download the pdf found at [this link](https://www.dropbox.com/scl/fi/ve6ltn17ftkkub9pn5j1l/2024_YearEnd_Report_Urban-Kelp-Research-Project.pdf?rlkey=q05fyjaa1qtsep7znxzd6chy5&dl=0)
* To read the 2023 year-end report to the Port of Seattle, download the pdf found at [this link](https://www.dropbox.com/scl/fi/r9h8rwams3n2h39q5hpib/2023_YearEnd_Report_Urban-Kelp-Research-Project.pdf?rlkey=35ua56ufnezqcyuomed3wgnep&dl=0)
* To read a mid-year, July 2023 report to the Port of Seattle, download the pdf found at [this link](https://www.dropbox.com/scl/fi/jymeod2kwqhwbgq47lfhm/MidYear_PortReport_2023.pdf?rlkey=k64u9y5tuh62bwdg82b4ib299&dl=0)
* To read our 2022 year-end report to the Port of Seattle, download the pdf found at [this link](https://www.dropbox.com/scl/fi/dn9cxx2oxomhcs9weaacl/2022_YearEnd_PortReport.pdf?rlkey=ejarsnwtf20mwbphhestvzn3z&dl=0)
* To read our August 2022 mid-year report to the Port of Seattle, download the pdf found at [this link](https://www.dropbox.com/scl/fi/33j2agq8jknhb4i11maoh/Urban_Kelp_August_report.pdf?rlkey=20o1m6avd1r3yuhqs21kmzb7n&dl=0)

## Funding proposals
* To read a proposal funded by the North Pacific Coast Marine Resources Committee, see _North_Pacific_Coast_MRC_proposal_ document ([pdf](https://github.com/zhrandell/Seattle_Aquarium_ROV_development/blob/main/documents/North_Pacific_Coast_MRC_proposal/ROV_pilotStudy_NPC-MRC_proposal%2021-23.pdf)) 
* To read a proposal funded by Sea Otter Foundation and Trust, see the _SOFT_2022_SeattleAquarium_proposal_ document ([pdf](https://github.com/zhrandell/Seattle_Aquarium_ROV_development/blob/main/documents/SOFT_2022_SeattleAquarium_proposal.pdf))
