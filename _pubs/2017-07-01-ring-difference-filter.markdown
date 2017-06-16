---
layout: project
title:  "Noise Robust Depth from Focus using a Ring Difference Filter"
oral:	"Spotlight"
auth:	"<em>Jaeheung Surh</em>, Hae-Gon Jeon, Yunwon Park, Sunghoon Im, Hyowon Ha, and In So Kweon"
pub:	"IEEE Conference on Computer Vision and Pattern Recognition (CVPR)"
date:   2017-07-01 00:00:00 +0900
thumb:	"/assets/images/thumb_RDF.jpg"
pdf:	"/assets/pdf/CVPR2017_RDF.pdf"
code:	true
src:	false
bib:	true
---

<div align="center">
	<iframe width="900" height="510" src="https://www.youtube.com/embed/9arP_plSUEI" frameborder="0" allowfullscreen></iframe>
</div>
<br>

<h1 class="post-title" itemprop="name headline">Abstract</h1>

Depth from focus (DfF) is a method of estimating depth of a scene by using the information acquired through the change of the focus of a camera. Within the framework of DfF, the focus measure (FM) forms the foundation on which the accuracy of the output is determined. With the result from the FM, the role of a DfF pipeline is to determine and recalculate unreliable measurements while enhancing those that are reliable. In this paper, we propose a new FM that more accurately and robustly measures focus, which we call the "ring difference filter'' (RDF). FMs can usually be categorized as confident local methods or noise robust non-local methods. RDF's unique ring-and-disk structure allows it to have the advantageous sides of both local and non-local FMs. We then describe an efficient pipeline that utilizes the properties that the RDF brings. Our method is able to reproduce results that are on par with or even better than those of the state-of-the-art, while spending less time in computation.

<br><br>

<a name="bib"></a>
Bibtex:
```
@inproceedings{surh2017rdf,
    author = {Surh, Jaeheung and Jeon, Hae-Gon and Park, Yunwon and Im, Sunghoon and Ha, Hyowon and Kweon, In So},
    title = {Noise Robust Depth from Focus using a Ring Difference Filter},
    booktitle = {Proceedings of International Conference on Computer Vision and Pattern Recognition (CVPR)},
    year = {2017}
}
```