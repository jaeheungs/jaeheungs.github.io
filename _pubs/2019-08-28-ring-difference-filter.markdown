---
layout: project
title:  "Ring Difference Filter for Fast and Noise Robust Depth From Focus"
oral:	false
auth:	"Hae-Gon Jeon*, <em>Jaeheung Surh*</em>, Sunghoon Im, and In So Kweon"
pub:	"IEEE Transactions on Image Processing (TIP)"
date:   2019-08-28 00:00:00 +0900
thumb:	"/assets/images/RDF_TIP.png"
pdf:	"https://ieeexplore.ieee.org/document/8818667"
code:	true
src:	"https://github.com/jaeheungs/rdf_depth_from_focus"
bib:	true
---

<div align="center">
	<img src="/assets/images/RDF_pipeline.png">
</div>
<br>

<h1 class="post-title" itemprop="name headline">Abstract</h1>

Depth from focus (DfF) is a method of estimating the depth of a scene by using information acquired through changes in the focus of a camera. Within the DfF framework of, the focus measure (FM) forms the foundation which determines the accuracy of the output. With the results from the FM, the role of a DfF pipeline is to determine and recalculate unreliable measurements while enhancing those that are reliable. In this paper, we propose a new FM, which we call the “ring difference filter” (RDF), that can more accurately and robustly measure focus. FMs can usually be categorized as confident local methods or noise robust non-local methods. The RDF's unique ring-and-disk structure allows it to have the advantages of both local and non-local FMs. We then describe an efficient pipeline that utilizes the RDF's properties. Part of this pipeline is our proposed RDF-based cost aggregation method, which is able to robustly refine the initial results in the presence of image noise. Our method is able to reproduce results that are on par with or even better than those of state-of-the-art methods, while spending less time in computation.

<br><br>

<a name="bib"></a>
Bibtex:
```
@article{jeon2019ring,
  title={Ring Difference Filter for Fast and Noise Robust Depth From Focus},
  author={Jeon, Hae-Gon and Surh, Jaeheung and Im, Sunghoon and Kweon, In So},
  journal={IEEE Transactions on Image Processing},
  year={2019}
}
```