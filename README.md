# Applying Big Data Solutions to Big Tomographic Problems

The presentation for the Workshop on Large-Scale Tomography in Szeged, Hungary in January 2016.
- The [slides](https://rawgit.com/4Quant/WLST-2016/master/Slides.html) can be seen here
- A Demo of our [Quantitative Image Search Engine](https://kmader.shinyapps.io/SearchMachineDemo)

## Abstract
With every more efficient detectors, higher flux, and stable beamlines, comes the ability to probe 

time and length-scales previously unachievable. Of particular interest are the massive scale 

projects like the Human Brain Project, adult Zebra fish imaging, and dynamic imaging. All 

involve thousands to millions of measurements at the highest possible resolutions to cover mm 

to nanometer length scales. The task of processing and analyzing such large collections of 

measurements is exceptionally difficult. We show how the commodity hardware-based ‘Big 

Data’ solutions can be adapted to the scientific domain to  address the processing terabytes 

worth of measurements in a parallel, distributed manner. Building on the distributed frameworks 

of Apache Spark and Spark Imaging Layer, we have extended the common tomographic and 

image processing tools to work on these images enabling the use of many machines in parallel 

and drastically accelerating the speed and ease with which these large datasets can be stitched 

and analyzed. Our most recent developments enable the data to be analyzed and processed in 

real-time using the latest streaming and micro-batch processing techniques. Unique such an 

approach allows for fault-tolerant, distributed analytics to process complicated datasets and 

eventually provide feedback to both experimentalists and their equipment to allow for adaptation 

of measurements.

## Relevant Links

- [Quantitative Big Imaging Course](http://kmader.github.io/Quantitative-Big-Imaging-2015/)
- [X-Ray Imaging Group at ETH Zurich](http://www.biomed.ee.ethz.ch/research/x-ray_imaging)
- [Presentation at Spark Summit 2014](http://4quant.com/spark-summit-2014-presentation)
- [Spark Introduction](http://4quant.com/spark-introduction/)

## Bio
Kevin Mader is the founder and CTO of 4Quant and a lecturer in Image Analysis at ETH Zurich. He focuses on turning big hairy 3D images into simple, robust, reproducible numbers without resorting to black boxes or magic. In particular, as part of several collaborations, he is currently working on automatically segmenting full animal zebrafish images, characterizing rheology in 3D flows, and measuring viral infection dynamics in cell lines.


