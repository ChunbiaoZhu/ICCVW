## An Innovative Salient Object Detection Using Center-Dark Channel Prior




|  ![ICCV 2017 logo][logo-iccv] | Paper accepted at [2017 IEEE International Conference on Computer Vision (ICCV) Workshop](http://iccv2017.thecvf.com/)   |
|:-:|---|

[logo-iccv]: https://github.com/ChunbiaoZhu/ACVR2017/blob/master/logo/ICCVLogo.png "ICCV 2017 logo"



## Journal Version (ACM Intelligent Systems and Technology)

Extended verision is published on ACM Intelligent Systems and Technology (Exploiting the Value of the Center-dark Channel Prior for Salient Object Detection), which can be downloaded at [here](https://dl.acm.org/citation.cfm?id=3319368).

## Abstract

 	
Saliency detection aims to detect the most attractive objects in images, which has been widely used as a foundation for various multimedia applications. In this paper, we propose a novel salient object detection algorithm for RGB-D images using center-dark channel prior. First, we generate an initial saliency map based on color saliency map and depth saliency map of a given RGB-D image. Then, we generate a center-dark channel map based on centre saliency prior and dark channel prior. Finally, we fuse the initial saliency map with centre dark channel map to generate the final saliency map. The proposed algorithm is evaluated on two public RGB-D datasets, and the experimental results show that our method outperforms the state-of-the-art methods. 


## Framework
![QFramework saliency detection](https://github.com/ChunbiaoZhu/ACVR2017/blob/master/images/fig1.png)




## Web Page
https://chunbiaozhu.github.io/ACVR2017/

## Code & Results

Source code is released! You can download in [here](https://github.com/ChunbiaoZhu/ACVR2017/blob/master/CDCP_iccv17.zip)

You can download our Results on RGBD2 Dataset in [here](https://github.com/ChunbiaoZhu/ACVR2017/blob/master/ICCV_RGBD2.zip)

Reference

    @INPROCEEDINGS{8265388, 
    author={C. Zhu and G. Li and W. Wang and R. Wang}, 
    booktitle={2017 IEEE International Conference on Computer Vision Workshops (ICCVW)}, 
    title={An Innovative Salient Object Detection Using Center-Dark Channel Prior}, 
    year={2017}, 
    volume={}, 
    number={}, 
    pages={1509-1515}, 
    keywords={image colour analysis;object detection;RGB-D image;center-dark channel map;color saliency map;saliency detection;salient object detection algorithm;Euclidean distance;Feature extraction;Fuses;Image color analysis;Object detection;Visualization}, 
    doi={10.1109/ICCVW.2017.178}, 
    ISSN={}, 
    month={Oct},}
    
    @article{Zhu:2019:EVC:3325195.3319368,
    author = {Zhu, Chunbiao and Zhang, Wenhao and Li, Thomas H. and Liu, Shan and Li, Ge},
    title = {Exploiting the Value of the Center-dark Channel Prior for Salient Object Detection},
    journal = {ACM Trans. Intell. Syst. Technol.},
    issue_date = {May 2019},
    volume = {10},
    number = {3},
    month = may,
    year = {2019},
    issn = {2157-6904},
    pages = {32:1--32:20},
    articleno = {32},
    numpages = {20},
    url = {http://doi.acm.org/10.1145/3319368},
    doi = {10.1145/3319368},
    acmid = {3319368},
    publisher = {ACM},
    address = {New York, NY, USA},
    keywords = {Salient object detection, center-dark channel prior},
    } 

## Previous work

If you were interested in this work, you may want to also check our previous work, [CAIP2017](https://chunbiaozhu.github.io/CAIP2017/), which offers a whole new idea.

If you were interested in this work, you may want to also check our previous work, [MM2017](https://chunbiaozhu.github.io/MM2017/), which offers a whole new application.

## Acknowledgements

This work was supported by the grant of National Natural Science Foundation of China (No.U1611461), Shenzhen Peacock Plan (20130408-183003656), and Science and Technology Planning Project of Guangdong Province, China (No. 2014B090910001).


## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/ChunbiaoZhu/ACVR2017/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:zhuchunbiao@pku.edu.cn>.

<!---
Javascript code to enable Google Analytics
-->

<!---
<script>
-->
<!---
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
-->
<!---
ga('create', 'UA-7678045-3', 'auto');
ga('send', 'pageview');
-->
<!---
</script>
-->
