---
layout: project
title:  "Noise Robust Depth from Focus using a Ring Difference Filter"
oral:	"Spotlight"
auth:	"<em>Jaeheung Surh</em>, Hae-Gon Jeon, Yunwon Park, Sunghoon Im, Hyowon Ha, and In So Kweon"
pub:	"IEEE Conference on Computer Vision and Pattern Recognition (CVPR)"
date:   2017-07-01 00:00:00 +0900
impath:	"../assets/images/thumb_RDF.png"
pdf:	"../assets/pdf/CVPR2017_RDF.pdf"
bib:	true
imalt:	"RDF"
---

Depth from focus (DfF) is a method of estimating depth of a scene by using the information acquired through the change of the focus of a camera. Within the framework of DfF, the focus measure (FM) forms the foundation on which the accuracy of the output is determined. With the result from the FM, the role of a DfF pipeline is to determine and recalculate unreliable measurements while enhancing those that are reliable. In this paper, we propose a new FM that more accurately and robustly measures focus, which we call the "ring difference filter'' (RDF). FMs can usually be categorized as confident local methods or noise robust non-local methods. RDF's unique ring-and-disk structure allows it to have the advantageous sides of both local and non-local FMs. We then describe an efficient pipeline that utilizes the properties that the RDF brings. Our method is able to reproduce results that are on par with or even better than those of the state-of-the-art, while spending less time in computation. 

Bibtex:
```bib
@inproceedings{surh:cvpr17,
    AUTHOR = {Surh, Jaeheung and Jeon, Hae-Gon and Park, Yunwon and Im, Sunghoon and Ha, Hyowon and Kweon, In So},
    TITLE = {Noise Robust Depth from Focus using a Ring Difference Filter},
    BOOKTITLE = {Proceedings of International Conference on Computer Vision and Pattern Recognition (CVPR)},
    YEAR = {2017}
}
```