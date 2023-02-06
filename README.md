# MAUI: Model-driven Development Tool for Advanced Web User Interfaces

## Web GUI Dataset

[Download_Here](https://drive.google.com/file/d/1REUj9r0cOBUEhoGSpCjWJQyGpb80A_us/view?usp=sharing)

We build dataset to train the object detection model that extracts sections, important regions in a web page, from page screenshot. High-quality annotations of the bounding boxes covering the whole area of ground-truth sections effectively increase the accu-racy of the trained network. To this end, we implemented a tool for labeling the exact bounding boxes of sections by selecting associated DOM elements directly on a page. As a Chrome extension program, the tool supports an intuitive selection mechanism for DOM elements by hovering and clicking via the mouse to label their bounding boxes on a page screenshot. As most pages have overlapping elements on a single point, the tool provides a method for hovering the hierarchical path of the current element (e.g., click-and-wheelup). When the user selects an element, the tool displays a pop-up to decide its GUI type. The tool automatically stores a screenshot and an annotation file after the user has finished the labeling process on a page. 

We manually constructed a high-quality dataset using the tool and double-checked the collected and annotated data. The dataset consists of 3,452 annotated screenshots captured from web pages. Along with each image file, corresponding XML file for annotations is also included. 

* Our annotation tool is implemented as a browser extension and can be easily used in any Chromium-based browsers by simply loading it on a browser.
