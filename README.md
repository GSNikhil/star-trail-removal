<div align="center">

# <span>ECE 285: Computational Imaging Systems - Final Project 

## Turning Back Time: Computational Techniques for Star Trail Removal ​from Long-Exposure Astrophotography ​</span>

![Example](https://github.com/GSNikhil/star-trail-removal/blob/main/Data/example.png)
![Synthetic examples](https://github.com/GSNikhil/star-trail-removal/blob/main/Data/comp.png)
Deconvolution Results. A - Original Image, B - Wiener Deconvolution, C - Richardson-Lucy Deconvolution, D - Vanilla Gradient Descent, E - FISTA, F - FISTA + TV, G - ADMM, H - ADMM + TV

</div>

## <div align="center"><span style="color: #e67e22;">Team Members</span></div>
- **<span style="color: #e74c3c;">Nikhil Gandudi Suresh</span>**
- **<span style="color: #e74c3c;">Avanti Bhandarkar</span>**

## <div align="center"><span style="color: #e67e22;">Documents</span></div>

[Presentation Slides](https://github.com/GSNikhil/star-trail-removal/blob/main/Documents/ECE285_Slides.pdf) <br>
[Project Proposal](https://github.com/GSNikhil/star-trail-removal/blob/main/Documents/ECE285_Proposal.pdf) <br>

## <div align="center"><span style="color: #e67e22;">File Structure</span></div>
* `Data` stores all the images we used for this project (real and synthetic).
  * `binary_timed` - clustered version of timed
  * `real` - unused images (except star3.jpg)
  * `synthetic` - randomly generated pixel image
  * `timed` - all images with time of exposure metadata available

* `Documents` - stores all our submitted documents
  * `Proposal` 
  * `Report` - TO ADD
  * `Slides`

* `Notebooks` - stores our Jupyter Notebooks
  * `image_recovery` - recover the real image with star trails removed + replaced with reconstruction
  * `main` - contains all the utils functions, preprocessing pipeline, deconvolution manager and some outputs (real and synthetic)
  * `star_clustering` - K Means binary clustering and user center selection code


