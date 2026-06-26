---
title: Setup
---

Please download Fiji for your operating system as described in the Software Setup section below.  
Fiji is a powerful, "batteries-included" distribution of ImageJ2 software designed specifically for scientific image analysis. It is heavily favoured by researchers and biologists for its ability to handle complex, multi-dimensional data and automate workflows.

![](fig/fiji.svg){alt=""}

### Key Reasons to Use Fiji

* **Free and Open Source:** Driven by a community on GitHub, featuring an automatic updater that keeps all libraries fully maintained.
* **Pre-bundled Plugins:** Comes pre-configured with hundreds of curated plugins for tracking, segmentation, and 3D rendering.
* **Bio-Formats Integration:** Opens thousands of proprietary microscope and camera file formats (like .czi or .nd2) without extra conversions.
* **Multi-Dimensional Analysis:** Processes heavy 3D, 4D, and multi-channel image datasets with optimized memory management.
* **Automation & Scripting:** Automates repetitive tasks via built-in scripting languages (like Python, Java, or JavaScript) for reproducible research.

**Beware of Whole Slide Images:** Although it has optimized memory management, whole slide images are better analyzed with a "pyramid" aware software *e.g.* [QuPath](https://qupath.github.io/)



## Data Sets


Download the [data zip file](data/lesson-data.zip) and unzip it to your Desktop (or somewhere you can navigte to from within the ImageJ App).
This folder contains the images we will need for today's lesson.

## Software Setup

::::::::::::::::::::::::::::::::::::::: discussion

### Details

Visit the [Fiji download page](https://fiji.sc) and follow the instruction below to download and install the version for your specific operating system.
The downloads page will autodetect your system's operating system and hardware architecture and usually suggest the correct download for your system.
You can download either the Latest or the Stable version. 
:::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::: solution

### Windows

Click on the Big Green Download button at the top of the page. Once the zip file is downloaded, right click the zip folder to "extract all" somewhere.
This can be your Downloads folder, your Desktop, your Documents, etc. Just be sure that you *know* where you extracted the contents. Do not move it to the programs folder.
To install plugins, you must have write privileges to the folder that contains your imageJ executable file and the plugins folder. 


:::::::::::::::::::::::::

:::::::::::::::: solution

### MacOS

Click on the Big Green Download button at the top of the page. Once the zip file is downloaded, double-click on the zip file and it will automatically unzip into the Downloads folder.
You can run the app from the downloads folder or move it into the Applications folder and run it from there. 

:::::::::::::::::::::::::


:::::::::::::::: solution

### Linux

Some flavors of Linux make ImageJ available as a package that can be installed with your packaage manager. ***Do not install ImageJ this way***, as you will likely have problems installing additional plugins. Furthermore, ImageJ2 is not available from package managers. For the time being, it is recommended to download the Linux 64-bit distribution of Fiji from the link above.

:::::::::::::::::::::::::

