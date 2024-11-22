

# Welcome to Organometallics Chemical Space!

Coded by Galymzhan Moldagulov (Grad student @ IBS-CARS & UNIST, KR)

## [Organometallic Space (Click to Open)](https://moldagulovg.github.io/organometallic-space/umap_plot.html)

You can easily:
- explore chemical space in the interactive Faerun map;
- search complexes by their CSD code;
- switch between color schemes in the plot legend;
- look at 3D structures of individual complexes (e.g. [WAXGAG](https://moldagulovg.github.io/organometallic-space/saved_htmls/WAXGAG.html), [KIPBAP](https://moldagulovg.github.io/organometallic-space/saved_htmls/KIPBAP.html) and [AGUZAD](https://moldagulovg.github.io/organometallic-space/saved_htmls/AGUZAD.html)).


![](https://github.com/moldagulovg/organometallic-space/blob/main/3d-example.png)

![](https://github.com/moldagulovg/organometallic-space/blob/main/om-space.png)

## Methods:
- Sampled 1k mononuclear organometallic complexes from tmQM dataset and CSD <sup>[1, 2]</sup>;
- Vectorized molecules were embedded/projected into 2D UMAP representation <sup>[3]</sup>;
- Molecules were vectorized by ECFP6 (Morgan Fingerprint) and distance matrix for the entire set was calculated by Tanimoto Similarity <sup>[4, 5]</sup>;
- Chemical space was visualized with interactive Faerun module <sup>[6]</sup>;
- Visualization of individual molecules in various 3D representations was impleted using 3Dmol.js <sup>[7]</sup>.

## References:
1) *J. Chem. Inf. Model*. **2020**, 60, *12*, 6135–6146;
2) *Acta Cryst.* **2016**, B72, 171-179;
3) arXiv:1802.03426;
4) *J. Chem. Inf. Model.* **2010**, 50, *5*, 742–754;
5) *J. Cheminform.* **2015**, 7, *20*;
6) *Bioinformatics*, **2018**, 34, *8*, 1433–1435;
7) *Bioinformatics*, **2015**, 31, *8*, 1322–1324.

## Acknowledgements:
Big shoutout to Ph.D. Yaroslav Sobolev (IBS-CARS, KR) for teaching me how embeddings of multi-dimensional space work, Junren Li (PKU, CN) for his guidance on UMAP and Faerun, as well as Sanzhar Nurgaliyev (NU, KZ), and Assanali Salem (UNIST, KR) for their help!