# Analysis of the State of the Art

* [Analysis of the State of the Art](#analysis-of-the-state-of-the-art)
    * [Texturing Methods](#texturing-methods)
        * [Example-Based Control](#example-based-control)
            * [Stochastic Textures](#stochastic-textures)
            * [Unrestricted Texture Designs](#unrestricted-texture-designs)
            * [Element Arrangements](#element-arrangements)
        * [Grammar Generation](#grammar-generation)
    * [Shapes and Masts](#shapes-and-masts)
        * [Rule- and Grammar-Based Methods](#rule--and-grammar-based-methods)
            * [Probabilistic Interference](#probabilistic-interference)
        * [Data-Driven Fillings](#data-driven-fillings)
        * [Summary](#summary)
    * [Vector Fields](#vector-fields)
    * [Curves, Sketches and Painting](#curves-sketches-and-painting)
        * [Curves as Basis Elements](#curves-as-basis-elements)
        * [Curves As Control Mechanisms](#curves-as-control-mechanisms)
            * [Data-Driven Approaches](#data-driven-approaches)
            * [Feature Exploration](#feature-exploration)
    * [Element Placement](#element-placement)
    * [Machine Learning](#machine-learning)
    * [Semantic Attributes](#semantic-attributes)
    * [Add But Not Sure Where](#add-but-not-sure-where)
    * [Maybe Add](#maybe-add)
        * [Tile-based designs](#tile-based-designs)
        * [Hand-drawing](#hand-drawing)
        * [Fabrication](#fabrication)
        * [Coloring](#coloring)
        * [Creativity](#creativity)

## Texturing Methods

### Example-Based Control

#### Stochastic Textures

##### IN

* @inproceedings{lagae_2010_sap,
    author = {A. Lagae and S. Lefebvre and R. Cook and T. DeRose and G. Drettakis and D. S. Ebert and J. P. Lewis and K. Perlin and M. Zwicker},
    title = {State of the Art in Procedural Noise Functions},
    booktitle = {Proceedings of the Conference of the European Association for Computer Graphics},
    year = {2010},
    publisher = {The Eurographics Association},
}
* @article {galerne_2017_tno,
    author = {Galerne, B. and Leclaire, A. and Moisan, L.},
    title = {Texton Noise},
    journal = {Computer Graphics Forum},
    year = {2017},
}
* @article{lagae_2010_pis,
    author = {Lagae, Ares and Vangorp, Peter and Lenaerts, Toon and Dutr{\'e}, Philip},
    title = {Procedural Isotropic Stochastic Textures by Example},
    journal = {Computers and Graphics},
    volume = {34},
    number = {4},
    year = {2010},
    pages = {312--321},
    publisher = {Pergamon Press, Inc.},
} 
* @article{gilet_2012_mkn,
    author={Gilet, G. and Dischler, J-M. and Ghazanfarpour, D.},
    title={Multiple kernels noise for improved procedural texturing},
    journal={The Visual Computer},
    year={2012},
    volume={28},
    number={6},
    pages={679--689},
}
* @article{galerne_2012_gne,
    author = {Galerne, Bruno and Lagae, Ares and Lefebvre, Sylvain and Drettakis, George},
    title = {Gabor Noise by Example},
    journal = {{ACM} Transactions on Graphics},
    volume = {31},
    number = {4},
    year = {2012},
    pages = {73:1--73:9},
    publisher = {ACM},
} 
* @article{gilet_2014_lrn,
    author = {Gilet, Guillaume and Sauvage, Basile and Vanhoey, Kenneth and Dischler, Jean-Michel and Ghazanfarpour, Djamchid},
    title = {Local Random-phase Noise for Procedural Texturing},
    journal = {{ACM} Transactions on Graphics},
    volume = {33},
    number = {6},
    year = {2014},
    pages = {195:1--195:11},
    publisher = {ACM},
} 
* @inproceedings {pavie_2016_pts,
    author = {Pavie, Nicolas and Gilet, Guillaume and Dischler, Jean-Michel and Ghazanfarpour, Djamchid},
    title = {Procedural texture synthesis by locally controlled spot noise},
    booktitle = {Proceedings of International Conference in Central Europe on Computer Graphics, Visualization and Computer Vision},
    year = {2016},
}
* @article {guingo_2017_btm,
    author = {Guingo, Geoffrey and Sauvage, Basile and Dischler, Jean-Michel and Cani, Marie-Paule},
    title = {Bi-Layer textures: a Model for Synthesis and Deformation of Composite Textures},
    journal = {Computer Graphics Forum},
    volume = {36},
    number = {4},
    pages = {111--122},
    year = {2017},
}
* @article{kang_2017_fpt,
    author = {Kang, Hyeongyeop and Han, Junghyun},
    title = {Feature-preserving Procedural Texture},
    journal = {The Visual Computer},
    volume = {33},
    number = {6-8},
    year = {2017},
    pages = {761--768},
    publisher = {Springer},
} 
* @article {gilet_2010_ias,
    author = {Gilet, G. and Dischler, J-M.},
    title = {An Image-Based Approach for Stochastic Volumetric and Procedural Details},
    journal = {Computer Graphics Forum},
    volume = {29},
    number = {4},
    pages = {1411--1419},
    year = {2010},
}


#### Unrestricted Texture Designs

##### IN

* @inproceedings{lefebvre_2000_ass,
  author    = {Laurent Lefebvre and Pierre Poulin},
  title     = {Analysis and Synthesis of Structural Textures},
  booktitle = {Proceedings of the Graphics Interface Conference},
  year      = {2000},
  pages     = {77-86},
}
* @article {gilet_2012_map,
    author = {Gilet, G. and Dischler, J-M. and Ghazanfarpour, D.},
    title = {Multi-scale Assemblage for Procedural Texturing},
    journal = {Computer Graphics Forum},
    volume = {31},
    number = {7},
    publisher = {Blackwell Publishing Ltd},
    pages = {2117--2126},
    year = {2012},
}
* @article {bourque_2004_ptm,
    author = {Eric Bourque and Gregory Dudek},
    title = {Procedural Texture Matching and Transformation},
    journal = {Computer Graphics Forum},
    volume = {23},
    number = {3},
    publisher = {The Eurographics Association},
    pages = {461--468},
    year = {2004},
}

##### TO ADD

* @article {gieseke_2014_ipr,
    author = {Gieseke, L. and Koch, S. and Hahn, J.-U. and Fuchs, M.},
    title = {Interactive Parameter Retrieval for Two-Tone Procedural Textures},
    journal = {Computer Graphics Forum},
    volume = {33},
    number = {4},
    pages = {71--79},
    year = {2014},
}
* @article{tu_2020_cct,
    title = {Continuous Curve Textures},
    author = {Peihan Tu and Li-Yi Wei and Koji Yatani and Takeo Igarashi and Matthias Zwicker},
    journal = {{ACM} Transactions on Graphics},
    volume = {39},
    number = {6},
    year = 2020,
}

* @inproceedings {pauly_2009_sot,
booktitle = {Eurographics 2009 - State of the Art Reports},
editor = {M. Pauly and G. Greiner},
title = {{State of the Art in Example-based Texture Synthesis}},
author = {Wie, Li-Yi and Lefebvre, Sylvain and Kwatra, Vivek and Turk, Greg},
year = {2009},
publisher = {The Eurographics Association},
}
    * https://diglib.eg.org/bitstream/handle/10.2312/egst.20091063.093-117/093-117.pdf?sequence=1&isAllowed=y

#### Element Arrangements

##### IN

* @article{barla_2006_spa,
    author = {Barla, Pascal and Breslav, Simon and Thollot, Jo{\"e}lle and Sillion, Fran{\c c}ois and Markosian, Lee},
    title = {Stroke Pattern Analysis and Synthesis},
    journal = {Computer Graphics Forum},
    year = {2006},
    volume = {25},
    number = {3},
    pages = {663-671},
}
* @inproceedings{hurtut_2009_ags,
    title = {Appearance-guided Synthesis of Element Arrangements by Example},
    booktitle = {Proceedings of the International Symposium on Non-Photorealistic Animation and Rendering},
    publisher = {ACM},
    author = {Hurtut, T. and Landes, P.-E. and Thollot, J. and Gousseau, Y. and Drouillhet, R. and Coeurjolly, J.-F.},
    year = {2009},
    pages = {51--60}
}
* @article{ijiri_2008_aeb,
    author = {Ijiri, Takashi and M\v{e}ch, Radom{\'i}r and Igarashi, Takeo and Miller, Gavin},
    title = {An Example-based Procedural System for Element Arrangement},
    journal = {Computer {Graphics} {Forum}},
    volume = {27},
    year = {2008},
    number = {2},
    pages = {429-436},
}
* @article{ma_2011_det,
    author = {Ma, Chongyang and Wei, Li-Yi and Tong, Xin},
    title = {Discrete Element Textures},
    journal = {{ACM} Transactions on Graphics},
    volume = {30},
    number = {4},
    year = {2011},
    pages = {62:1--62:10},
    publisher = {ACM},
} 
* @article{ma_2013_det,
    author = {Ma, Chongyang and Wei, Li-Yi and Lefebvre, Sylvain and Tong, Xin},
    title = {Dynamic Element Textures},
    journal = {{ACM} Transactions on Graphics},
    volume = {32},
    number = {4},
    year = {2013},
    pages = {90:1--90:10},
    publisher = {ACM},
} 

##### TO ADD

* Mention here already, is currently introduced under vector fields: @inproceedings{saputra_2017_ffo,
    author = {Saputra, Reza Adhitya and Kaplan, Craig S. and Asente, Paul and M\v{e}ch, Radom\'{\i}r},
    title = {FLOWPAK: Flow-Based Ornamental Element Packing},
    year = {2017},
    publisher = {Canadian Human-Computer Communications Society},
    booktitle = {Proceedings of the 43rd Graphics Interface Conference},
    pages = {8–15},
    numpages = {8},
}

* @inproceedings{saputra_2018_rde,
    author = {Saputra, Reza Adhitya and Kaplan, Craig S. and Asente, Paul},
    title = {RepulsionPak: Deformation-Driven Element Packing with Repulsion Forces},
    year = {2018},
    publisher = {Canadian Human-Computer Communications Society},
    booktitle = {Proceedings of the 44th Graphics Interface Conference},
    pages = {10–17},
}

* @article{chen_2019_mpc,
    author = {Chen, Minghai and Xu, Fan and Lu, Lin},
    year = {2019},
    title = {Manufacturable pattern collage along a boundary},
    volume = {5},
    journal = {Computational Visual Media},
}
* @article{DAVISON201923,
    title = "Interactive example-palettes for discrete element texture synthesis",
    journal = "Computers & Graphics",
    volume = "78",
    pages = "23 - 36",
    year = "2019",
}
    * https://prism.ucalgary.ca/ds2/stream/?#/documents/90e293e8-1edd-4f9c-8891-c8d9bed7c894/page/3
* @inproceedings{hsu_2020_aef,
author = {Hsu, Chen-Yuan and Wei, Li-Yi and You, Lihua and Zhang, Jian Jun},
title = {Autocomplete Element Fields},
year = {2020},
publisher = {ACM},
booktitle = {Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems},
pages = {1–13},
numpages = {13},
}
    * https://dl.acm.org/doi/10.1145/3313831.3376248
* @inproceedings{hsu_2018_bef,
    author = {Hsu, Chen-Yuan and Wei, Li-Yi and You, Lihua and Zhang, Jian Jun},
    title = {Brushing Element Fields},
    year = {2018},
    publisher = {Association for Computing Machinery},
    booktitle = {SIGGRAPH Asia 2018 Technical Briefs},
    articleno = {6},
    numpages = {4},
}
    * https://dl.acm.org/doi/10.1145/3283254.3283274
* @inproceedings{10.1111/cgf.12152,
author = {Landes, Pierre-Edouard and Galerne, Bruno and Hurtut, Thomas},
title = {A Shape-Aware Model for Discrete Texture Synthesis},
year = {2013},
publisher = {Eurographics Association},
booktitle = {Proceedings of the Eurographics Symposium on Rendering},
pages = {67–76},
}
    * https://dl.acm.org/doi/10.1111/cgf.12152
    * https://hal.archives-ouvertes.fr/hal-00825735/document



### Grammar Generation

##### IN

* @article{stava_2010_ipm,
  title = {Inverse Procedural Modeling by Automatic Generation of L-systems},
  volume = {29},
  number = {2},
  journal =  {Computer {Graphics} {Forum}},
  author = {{\v S}t'ava, O. and Bene{\v s}, B. and M{\v e}ch, R. and Aliaga, D. G. and Kri{\v s}tof, P.},
  year = {2010},
  pages = {665--674}
}
* @inproceedings{talton_2012_ldp,
    author = {Talton, Jerry and Yang, Lingfeng and Kumar, Ranjitha and Lim, Maxine and Goodman, Noah and M\v{e}ch, Radom\'{\i}r},
    title = {Learning Design Patterns with Bayesian Grammar Induction},
    booktitle = {Proceedings of the ACM Symposium on User Interface Software and Technology},
    year = {2012},
    pages = {63--74},
    publisher = {ACM},
} 

##### ADD

* @article{guo_ipm,
author = {Guo, Jianwei and Jiang, Haiyong and Benes, Bedrich and Deussen, Oliver and Zhang, Xiaopeng and Lischinski, Dani and Huang, Hui},
title = {Inverse Procedural Modeling of Branching Structures by Inferring L-Systems},
year = {2020},
issue_date = {September 2020},
publisher = {ACM},
volume = {39},
number = {5},
journal = {{ACM} Transactions on Graphics},
articleno = {155},
}
    * https://dl.acm.org/doi/10.1145/3394105

## Shapes and Masts

### Rule- and Grammar-Based Methods

##### IN

* @inproceedings{wong_1998_cgf,
    title = {Computer-generated Floral Ornament},
    booktitle = {Proceedings of the Conference on Computer Graphics and Interactive Techniques},
    publisher = {ACM},
    author = {Wong, Michael T. and Zongker, Douglas E. and Salesin, David H.},
    year = {1998},
    pages = {423--434},
}
* @article{santoni_2016_ggp,
    author = {Santoni, Christian and Pellacini, Fabio},
    title = {gTangle: A Grammar for the Procedural Generation of Tangle Patterns},
    journal = {{ACM} Transactions on Graphics},
    volume = {35},
    number = {6},
    year = {2016},
    pages = {182:1--182:11},
    publisher = {ACM},
} 
* @article{loi_2017_pae,
    author = {Loi, Hugo and Hurtut, Thomas and Vergne, Romain and Thollot, Joelle},
    title = {Programmable 2D Arrangements for Element Texture Design},
    journal = {{ACM} Transactions on Graphics},
    volume = {36},
    number = {3},
    year = {2017},
    pages = {27:1--27:17},
    publisher = {ACM},
} 

##### TO ADD

* @inproceedings{gieseke_2017_ooo,
 author = {Gieseke, Lena and Asente, Paul and Lu, Jingwan and Fuchs, Martin},
 title = {Organized Order in Ornamentation},
 booktitle = {Proceedings of the Symposium on Computational Aesthetics},
 year = {2017},
 pages = {4:1--4:9},
 publisher = {ACM},
} 

#### Probabilistic Interference

##### IN

* @article{talton_2011_mpm,
    title = {Metropolis procedural modeling},
    volume = {30},
    number = {2},
    journal = {{ACM} Transactions on Graphics},
    author = {Talton, Jerry O. and Lou, Yu and Lesser, Steve and Duke, Jared and M{\v e}ch, Radom{\'\i}r and Koltun, Vladlen},
    year = {2011},
    pages = {1--14},
}
* @article{ritchie_2015_cpm,
    author = {Ritchie, Daniel and Mildenhall, Ben and Goodman, Noah D. and Hanrahan, Pat},
    title = {Controlling Procedural Modeling Programs with Stochastically-ordered Sequential Monte Carlo},
    journal = {{ACM} Transactions on Graphics},
    volume = {34},
    number = {4},
    year = {2015},
    pages = {105:1--105:11},
    publisher = {ACM}
} 


### Data-Driven Fillings

##### IN

* @article{chen_2016_sof,
    title={Synthesis of filigrees for digital fabrication},
    author={Chen, Weikai and Zhang, Xiaolong and Xin, Shiqing and Xia, Yang and Lefebvre, Sylvain and Wang, Wenping},
    journal={{ACM} Transactions on Graphics},
    volume={35},
    number={4},
    pages={98},
    year={2016},
    publisher={ACM}
}

### Summary

##### IN

* Discuss in detail?!: @article{benes_2011_gpm,
  title = {Guided Procedural Modeling},
  volume = {30},
  number = {2},
  journal = {Computer {Graphics} {Forum}},
  publisher = {Wiley Online Library},
  author = {Bene{\v s}, B. and {\v S}t'ava, O. and M{\v e}ch, R. and Miller, G.},
  year = {2011},
  pages = {325--334},
}


## Vector Fields

##### IN

* Also under element arrangements: @article{ijiri_2008_aeb,
    author = {Ijiri, Takashi and M\v{e}ch, Radom{\'i}r and Igarashi, Takeo and Miller, Gavin},
    title = {An Example-based Procedural System for Element Arrangement},
    journal = {Computer {Graphics} {Forum}},
    volume = {27},
    year = {2008},
    number = {2},
    pages = {429-436},
}
* @article{yuanyuan_2011_gso,
  title = {Geometry Synthesis on Surfaces Using Field-Guided Shape Grammars},
  volume = {17},
  number = {2},
  journal = {{IEEE} Transactions on Visualization and Computer Graphics},
  author = {Yuanyuan Li and Fan Bao and Zhang, Eugene and Kobayashi, Yoshihiro and Wonka, Peter},
  year = {2011},
  pages = {231--243}
}
* @article{chen_2008_ips,
    author    =  {Guoning Chen and Gregory Esch and Peter Wonka and Pascal Mueller and Eugene Zhang},
    title         =  {Interactive Procedural Street Modeling},
    journal = {{ACM} Transactions on Graphics},
    year        =  {2008},
    volume   =  {27},
    number  =  {3},
    pages  =  {103:1-103:10},
}
* @article{maharik_2011_dm,
    author = {Maharik, Ron and Bessmeltsev, Mikhail and Sheffer, Alla and Shamir, Ariel and Carr, Nathan},
    title = {Digital Micrography},
    journal = {{ACM} Transactions on Graphics},
    volume = {30},
    number = {4},
    year = {2011},
    pages = {100:1--100:12},
    publisher = {ACM},
} 
* @article {xu_2015_ptm,
    author = {Xu, Ling and Mould, David},
    title = {Procedural Tree Modeling with Guiding Vectors},
    journal = {Computer Graphics Forum},
    volume = {34},
    number = {7},
    pages = {47--56},
    year = {2015},
}

##### TO ADD

* Also add OOO here

## Curves, Sketches and Painting

### Curves as Basis Elements

##### IN

* @incollection{anderson_2008_udt,
    title = {User driven two-dimensional computer-generated ornamentation},
    booktitle = {Advances in Visual Computing},
    publisher = {Springer},
    author = {Anderson, Dustin and Wood, Zo\"{e}},
    year = {2008},
    pages = {604--613},
}
* @article{yu_2012_ans,
    author = {Yu-Sheng Chen and Jie Shie and Lieu-Hen Chen},
    title = {A NPR System for Generating Floral Patterns based on L-System},
    journal = {Bulletin of Networking, Computing, Systems, and Software},
    volume = {1},
    number = {1},
    year = {2012},
}
* @inproceedings {xu_2009_mcc,
    booktitle = {Proceedings of the Eurographics conference on Computational Aesthetics in Graphics, Visualization and Imaging},
    title = {Magnetic Curves: Curvature-Controlled Aesthetic Curves Using Magnetic Fields},
    author = {Xu, Ling and Mould, David},
    year = {2009},
    publisher = {The Eurographics Association},
}
* @article{merrell_2010_ecs,
    author = {Merrell, Paul and Manocha, Dinesh},
    title = {Example-based Curve Synthesis},
    journal = {Computers and Graphics},
    volume = {34},
    number = {4},
    year = {2010},
    pages = {304--311},
    publisher = {Pergamon Press, Inc.},
} 
* @article{zehnder_2016_dso,
    author = {Zehnder, Jonas and Coros, Stelian and Thomaszewski, Bernhard},
    title = {Designing Structurally-sound Ornamental Curve Networks},
    journal = {{ACM} Transactions on Graphics},
    volume = {35},
    number = {4},
    year = {2016},
    pages = {99:1--99:10},
    publisher = {ACM},
} 

##### ADD

@inproceedings{pedersen_2006_ola,
    author = {Pedersen, Hans and Singh, Karan},
    title = {Organic Labyrinths and Mazes},
    year = {2006},
    publisher = {Association for Computing Machinery},
    booktitle = {Proceedings of the 4th International Symposium on Non-Photorealistic Animation and Rendering},
    pages = {79–86},
}
    * https://dl.acm.org/doi/10.1145/1124728.1124742

### Curves As Control Mechanisms

##### IN

* @article{mech_2012_tdf,
    title = {The Deco framework for interactive procedural modeling},
    volume = {1},
    number = {1},
    urldate = {2015-12-03},
    journal = {Journal of Computer Graphics Techniques},
    author = {M\v{e}ch, Radom{\'\i}r and Miller, Gavin},
    year = {2012}, 
    pages = {43--99},
}
* @inproceedings{jacobs_2018_dbe,
    author = {Jacobs, Jennifer and Brandt, Joel R. and M\v{e}ch, Radom\'{\i}r and Resnick, Mitchel},
    title = {Dynamic Brushes: Extending Manual Drawing Practices with Artist-Centric Programming Tools},
    booktitle = {Extended Abstracts of the CHI Conference on Human Factors in Computing Systems},
    year = {2018},
    pages = {D316:1--D316:4},
    publisher = {ACM},
} 
* @inproceedings{anastacio_2008_spl,
    author = {Anastacio, F. and Prusinkiewicz, P. and Sousa, M. C.},
    title = {Sketch-based Parameterization of L-systems Using Illustration-inspired Construction Lines},
    booktitle = {Proceedings of the Eurographics Conference on Sketch-Based Interfaces and Modeling},
    year = {2008},
    pages = {119--126},
    url = {http://dx.doi.org/10.2312/SBM/SBM08/119-126},
    publisher = {Eurographics Association},
} 
* @article{chen_2008_stm,
    title = {Sketch-based {Tree} {Modeling} {Using} {Markov} {Random} {Field}},
    volume = {27},
    number = {5},
    journal = {{ACM} Transactions on Graphics},
    author = {Chen, Xuejin and Neubert, Boris and Xu, Ying-Qing and Deussen, Oliver and Kang, Sing Bing},
    year = {2008},
    pages = {109:1--109:9}
}
* @article{palubicki_2009_sot,
    title = {Self-organizing Tree Models for Image Synthesis},
    volume = {28},
    number = {3},
    journal = {{ACM} Transactions on Graphics},
    author = {Palubicki, Wojciech and Horel, Kipp and Longay, Steven and Runions, Adam and Lane, Brendan and M\v{e}ch, Radom{\'\i}r and Prusinkiewicz, Przemyslaw},
    year = {2009},
    pages = {58:1--58:10}
}
* @article{emilien_2015_wie,
    author = {Emilien, Arnaud and Vimont, Ulysse and Cani, Marie-Paule and Poulin, Pierre and Benes, Bedrich},
    title = {WorldBrush: Interactive Example-based Synthesis of Procedural Virtual Worlds},
    journal = {{ACM} Transactions on Graphics},
    volume = {34},
    number = {4},
    year = {2015},
    pages = {106:1--106:11},
    publisher = {ACM},
}
* @article{diverdi_2013_ppp,
    author = {S. DiVerdi and A. Krishnaswamy and R. M\v{e}ch and D. Ito},
    title = {Painting with Polygons: A Procedural Watercolor Engine},
    journal = {IEEE Transactions on Visualization and Computer Graphics},
    volume = {19},
    number = {5},
    year = {2013},
    pages = {723-735},
    publisher = {IEEE Computer Society}
}
* @inproceedings{xing_2016_eit,
    author = {Xing, Jun and Kazi, Rubaiat Habib and Grossman, Tovi and Wei, Li-Yi and Stam, Jos and Fitzmaurice, George},
    title = {Energy-Brushes: Interactive Tools for Illustrating Stylized Elemental Dynamics},
    booktitle = {Proceedings of the Symposium on User Interface Software and Technology},
    year = {2016},
    pages = {755--766},
    publisher = {ACM},
} 

#### Data-Driven Approaches

##### IN

* @article{lu_2014_dds,
    title = {{DecoBrush}: Drawing Structured Decorative Patterns by Example},
    volume = {33},
    number = {4},
    journal = {{ACM} Transactions on Graphics},
    author = {Lu, Jingwan and Barnes, Connelly and Wan, Connie and Asente, Paul and M\v{e}ch, Radom{\'\i}r and Finkelstein, Adam},
    year = {2014},
    pages = {90:1--90:9},
}
* @article{zhou_2014_tsv,
    author = {Zhou, Shizhe and Jiang, Changyun and Lefebvre, Sylvain},
    title = {Topology-constrained Synthesis of Vector Patterns},
    journal = {{ACM} Transactions on Graphics},
    volume = {33},
    number = {6},
    year = {2014},
    pages = {215:1--215:11},
    publisher = {ACM},
} 
* @inproceedings{kazi_2012_vit,
 author = {Kazi, Rubaiat Habib and Igarashi, Takeo and Zhao, Shengdong and Davis, Richard},
 title = {Vignette: Interactive Texture Design and Manipulation with Freeform Gestures for Pen-and-ink Illustration},
 booktitle = {Proceedings of the SIGCHI Conference on Human Factors in Computing Systems},
 year = {2012},
 pages = {1727--1736},
 publisher = {ACM},
} 
* @article{xing_2014_apr,
    author = {Xing, Jun and Chen, Hsiang-Ting and Wei, Li-Yi},
    title = {Autocomplete Painting Repetitions},
    journal = {{ACM} Transactions on Graphics},
    volume = {33},
    number = {6},
    year = {2014},
    pages = {172:1--172:11},
    publisher = {ACM},
} 

#### Feature Exploration

##### IN

* @inproceedings{todi_2016_sse,
    author = {Todi, Kashyap and Weir, Daryl and Oulasvirta, Antti},
    title = {Sketchplore: Sketch and Explore with a Layout Optimiser},
    booktitle = {Proceedings of the ACM Conference on Designing Interactive Systems},
    year = {2016},
    pages = {543--555},
    publisher = {ACM},
} 
* @inproceedings{chen_2016_msi,
 author = {Chen, Yilan and Fu, Hongbo and Au, Kin Chung},
 title = {A Multi-level Sketch-based Interface for Decorative Pattern Exploration},
 booktitle = {SIGGRAPH Asia Technical Briefs},
 year = {2016},
 pages = {26:1--26:4},
 publisher = {ACM},
} 

## Element Placement

##### IN

* Mentioned already in Curves As Control Mechanism: @article{mech_2012_tdf,
    title = {The Deco framework for interactive procedural modeling},
    volume = {1},
    number = {1},
    urldate = {2015-12-03},
    journal = {Journal of Computer Graphics Techniques},
    author = {M\v{e}ch, Radom{\'\i}r and Miller, Gavin},
    year = {2012}, 
    pages = {43--99},
}
* @article{yeh_2009_dsa,
    title = {Detecting Symmetries and Curvilinear Arrangements in Vector Art},
    volume = {28},
    number = {2},
    urldate = {2015-06-10},
    journal = {Computer Graphics Forum},
    author = {Yeh, Yi-Ting and M{\v e}ch, Radom{\'\i}r},
    year = {2009},
    pages = {707--716}
}
* @article{guerrero_2016_pep,
  title   = {{PATEX}: Exploring Pattern Variations}, 
  author  = {Paul Guerrero and Gilbert Bernstein and Wilmot Li and Niloy J. Mitra},
  year    = {2016},
  journal = {{ACM} Transactions on Graphics},
  volume = {35},
  number = {4},
  pages = {48:1--48:13},
}


## Machine Learning

##### IN

* @inproceedings{phan_2016_ple,
    author = {Phan, H. Q. and Lu, J. and Asente, P. and Chan, A. B. and Fu, H.},
    title = {Patternista: Learning Element Style Compatibility and Spatial Composition for Ring-based Layout Decoration},
    booktitle = {Proceedings of the Joint Symposium on Computational Aesthetics and Sketch Based Interfaces and Modeling and Non-Photorealistic Animation and Rendering},
    year = {2016},
    pages = {79--88},
    publisher = {Eurographics Association},
}
* @inproceedings{ritchie_2016_ngp,
 author = {Ritchie, Daniel and Thomas, Anna and Hanrahan, Pat and Goodman, Noah D.},
 title = {Neurally-guided Procedural Models: Amortized Inference for Procedural Graphics Programs Using Neural Networks},
 booktitle = {Proceedings of the International Conference on Neural Information Processing Systems},
 year = {2016},
 pages = {622--630},
 publisher = {Curran Associates Inc.},

} 
* @inproceedings{deterding_2017_mci,
    author = {Deterding, Sebastian and Hook, Jonathan and Fiebrink, Rebecca and Gillies, Marco and Gow, Jeremy and Akten, Memo and Smith, Gillian and Liapis, Antonios and Compton, Kate},
    title = {Mixed-Initiative Creative Interfaces},
    booktitle = {Proceedings of the CHI Conference Extended Abstracts on Human Factors in Computing Systems},
    year = {2017},
    pages = {628--635},
    publisher = {ACM},
}

##### Maybe Add

* @article{hu_2019_ssf,
author = {Hu, Zhongyuan and Xie, Haoran and Fukusato, Tsukasa and Sato, Takahiro and Igarashi, Takeo},
title = {Sketch2VF: Sketch-based flow design with conditional generative adversarial network},
journal = {Computer Animation and Virtual Worlds},
volume = {30},
number = {3-4},
pages = {e1889},
year = {2019}
}
    * http://www.jaist.ac.jp/~xie/sketch2vf.html

* @article {heer_2019_apa,
	author = {Heer, Jeffrey},
	title = {Agency plus automation: Designing artificial intelligence into interactive systems},
	volume = {116},
	number = {6},
	pages = {1844--1850},
	year = {2019},
	publisher = {National Academy of Sciences},
	journal = {Proceedings of the National Academy of Sciences}
}
    * https://www.pnas.org/content/116/6/1844
* @InProceedings{gatys_2017_cpf,
author = {Gatys, Leon A. and Ecker, Alexander S. and Bethge, Matthias and Hertzmann, Aaron and Shechtman, Eli},
title = {Controlling Perceptual Factors in Neural Style Transfer},
booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {July},
year = {2017}
}
    * https://openaccess.thecvf.com/content_cvpr_2017/html/Gatys_Controlling_Perceptual_Factors_CVPR_2017_paper.html

* Interactive example-based terrain authoring with conditional generative adversarial networks
    * https://dl.acm.org/doi/10.1145/3130800.3130804
* Interactive Modeling and Authoring of Climbing Plants
    * http://hpcg.purdue.edu/bbenes/papers/Haedrich2017EG.pdf


## Semantic Attributes

##### IN

* @article{yumer_2015_sse,
    author = {Yumer, Mehmet Ersin and Chaudhuri, Siddhartha and Hodgins, Jessica K. and Kara, Levent Burak},
    title = {Semantic Shape Editing Using Deformation Handles},
    journal = {{ACM} Transactions on Graphics},
    volume = {34},
    number = {4},
    year = {2015},
    pages = {86:1--86:12},
    publisher = {ACM},
} 
* @article{julesz_1981_tte,
  title={Textons, the elements of texture perception, and their interactions},
  author={B{\'e}la Julesz},
  journal={Nature},
  year={1981},
  volume={290},
  pages={91-97}
}
* @article{liu_2015_vpp,
  title={Visual Perception of Procedural Textures: Identifying Perceptual Dimensions and Predicting Generation Models},
  author={Jun Liu and Junyu Dong and Xiaoxu Cai and Lin Qi and Mike J. Chantler and Sliman J. Bensmaia},
  note={PLoS ONE 10(6): e0130335},
  year={2015},
}
* @inproceedings{matthews_2013_eta,
    author={T. Matthews and M. S. Nixon and M. Niranjan},
    booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
    title={Enriching Texture Analysis with Semantic Data},
    year={2013},
    pages={1248-1255},
}
* @article{liu_2018_ppt,
    title = {Perception-driven procedural texture generation from examples},
    journal = {Neurocomputing},
    volume = {291},
    pages = {21--34},
    year = {2018},
    author = {Jun Liu and Yanhai Gan and Junyu Dong and Lin Qi and Xin Sun and Muwei Jian and Lina Wang and Hui Yu}
}
* @article{dong_2017_ptg,
    author = {Dong, Junyu and Wang, Lina and Liu, Jun and Sun, Xin},
    year = {2017},
    title = {A Procedural Texture Generation Framework Based on Semantic Descriptions},
    note = {arXiv:1704.04141 [cs.CV]},
}
* @inproceedings{cimpoi_2014_dtw,
    author       = {Cimpoi, M. and Maji, S. and Kokkinos, I. and Mohamed, S. and Vedaldi, A.},
    title        = {Describing Textures in the Wild},
    booktitle    = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
    year         = {2014},
}

##### ADD

* @misc{godi_2019_tra,
      title={Texel-Att: Representing and Classifying Element-based Textures by Attributes}, 
      author={Marco Godi and Christian Joppi and Andrea Giachetti and Fabio Pellacini and Marco Cristani},
      year={2019},
      eprint={1908.11127},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
    * https://arxiv.org/abs/1908.11127

* @inproceedings{joppi_2019_tri,
    author={Joppi, Christian
    and Godi, Marco
    and Giachetti, Andrea
    and Pellacini, Fabio
    and Cristani, Marco",
    editor="Ricci, Elisa
    and Rota Bul\`o, Samuel
    and Snoek, Cees
    and Lanz, Oswald
    and Messelodi, Stefano
    and Sebe, Nicu},
    title={Texture Retrieval in the Wild Through Detection-Based Attributes},
    booktitle={Image Analysis and Processing -- ICIAP 2019},
    year={2019},
    publisher={Springer International Publishing},
    pages={522--533}
}
    * https://arxiv.org/pdf/1908.11111.pdf


## Add But Not Sure Where

* @inproceedings{talton_2009_emw,
  author = {Jerry O. Talton and Daniel Gibson and Lingfeng Yang and Pat Hanrahan and Vladlen Koltun},
  title = {Exploratory Modeling with Collaborative Design Spaces},
  booktitle = {Proceedings of the 2nd Annual ACM SIGGRAPH Conference and Exhibition in Asia},
  year = {2009},
  address = {New York, NY, USA},
  publisher = {ACM},
}
    * http://jerrytalton.net/research/tgyhk-emcds-09/paper.pdf

* @inproceedings{friske_2019_acs,
    author = {Friske, Mikhaila and Wu, Shanel and Devendorf, Laura},
    title = {AdaCAD: Crafting Software For Smart Textiles Design},
    year = {2019},
    publisher = {ACM},
    booktitle = {Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems},
    pages = {1–13},
}
    * https://dl.acm.org/doi/abs/10.1145/3290605.3300575

* @inproceedings{li_2020_sva,
    author = {Li, Jingyi and Brandt, Joel and Mech, Radom\'{\i}r and Agrawala, Maneesh and Jacobs, Jennifer},
    title = {Supporting Visual Artists in Programming through Direct Inspection and Control of Program Execution},
    year = {2020},
    publisher = {ACM},
    booktitle = {Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems},
    pages = {1–12},
}
    * https://dl.acm.org/doi/abs/10.1145/3313831.3376765
* @inproceedings{10.1145/3025453.3025927,
    author = {Jacobs, Jennifer and Gogia, Sumit and Mundefinedch, Radom\'{\i}r and Brandt, Joel R.},
    title = {Supporting Expressive Procedural Art Creation through Direct Manipulation},
    year = {2017},
    publisher = {ACM},
    booktitle = {Proceedings of the 2017 CHI Conference on Human Factors in Computing Systems},
    pages = {6330–6341},
}
    * https://dl.acm.org/doi/10.1145/3025453.3025927

* 
@article{alvarez_2019_ido,
    author = {Alvarez, Luis and MonzÃ³n, Nelson and Morel, Jean-Michel},
    title = {Interactive design of random aesthetic abstract textures by composition principles},
    journal = {Leonardo},
    volume = {0},
    pages = {1-11},
    year = {2019},
}
    * http://dev.ipol.im/~nmonzon/aat/Alvarez_msR1.pdf

* @article{galin_2019_aro,
author = {Galin, Eric and Guérin, Eric and Peytavie, Adrien and Cordonnier, Guillaume and Cani, Marie-Paule and Benes, Bedrich and Gain, James},
    title = {A Review of Digital Terrain Modeling},
    journal = {Computer Graphics Forum},
    volume = {38},
    number = {2},
    pages = {553-577},
    year = {2019}
}
* http://hpcg.purdue.edu/bbenes/papers/Galin19STAR.pdf

* @inproceedings{li_:_2019_aqp,
    author = {Li, Yifei and Breen, David E. and McCann, James and Hodgins, Jessica},
    title = {Algorithmic Quilting Pattern Generation for Pieced Quilts},
    booktitle = {Proceedings of Graphics Interface 2019},
    year = {2019},
    publisher = {Canadian Information Processing Society},
}
    * http://graphicsinterface.org/proceedings/gi2019/gi2019-13/
* @article{peihan_2019_pps,
    title = {Point Pattern Synthesis via Irregular Convolution},
    author = {Peihan Tu, Dani Lischinski and Hui Huang},
    journal = {Computer Graphics Forum (Proceedings of SGP 2019)},
    volume = {38},
    number = {5},
    pages = {109--122},
    year = {2019},
} 
    * https://vcc.tech/research/2019/PointSyn


## Maybe Add

* Mention recommendation systems?
    * http://pages.stern.nyu.edu/~atuzhili/pdf/TKDE-Paper-as-Printed.pdf
* Causality: a conceptual model of interaction history
    * https://dl.acm.org/doi/10.1145/2556288.2556990
* Patch-based geometric texture synthesis
    * https://dl.acm.org/doi/10.1145/2487276.2487278
* Towards effective evaluation of geometric texture synthesis algorithms
    * https://dl.acm.org/doi/10.1145/2486042.2486043
* Digital tools in collaborative creative work
    * https://dl.acm.org/doi/abs/10.1145/3240167.3240262
* A survey of the state-of-the-art in patch-based synthesis
    * https://link.springer.com/article/10.1007/s41095-016-0064-2#citeas
* Semi-Procedural Textures using Point Process Texture Basis Functions
    * http://pascal.guehl.pagesperso-orange.fr/index.html
* Authoring landscapes by combining ecosystem and terrain erosion simulation
    * https://dl.acm.org/doi/10.1145/3072959.3073667
* Example based repetitive structure synthesis
    * https://people.inf.ethz.ch/~sobarbar/papers/Rov15/Rov15.pdf


### Tile-based designs

* @article{bian_2018_tpd,
    author = {Bian, Xiaojun and Wei, Li-Yi and Lefebvre, Sylvain},
    title = {Tile-Based Pattern Design with Topology Control},
    year = {2018},
    publisher = {The Association for Computers in Mathematics and Science Teaching},
    volume = {1},
    number = {1},
    journal = {Proceedings of the ACM on Computer Graphics and Interactive Techniques},
    articleno = {23},
}
    * https://dl.acm.org/doi/10.1145/3203204
* @article{derouet_2019_gsw,
    author = {Derouet-Jourdan, Alexandre and Salvati, Marc and Jonchier, Théo},
    title = {Generating Stochastic Wall Patterns On-the-fly with Wang Tiles},
    journal = {Computer Graphics Forum},
    volume = {38},
    number = {2},
    pages = {255-264},
    year = {2019}
}
    * https://olm.co.jp/rd/wp-content/uploads/GeneratingStochasticWallPatternsOn-the-FlyWithWangTiles.pdf

### Hand-drawing

* @article{xing_2015_aha,
    author = {Xing, Jun and Wei, Li-Yi and Shiratori, Takaaki and Yatani, Koji},
    title = {Autocomplete Hand-Drawn Animations},
    year = {2015},
    publisher = {ACM},
    volume = {34},
    number = {6},
    journal = {{ACM} Transactions on Graphics},
    articleno = {169},
}
    * https://dl.acm.org/doi/abs/10.1145/2816795.2818079



### Fabrication

##### ADD

* @article{bickel_2018_sat,
  author       = {Bickel, Bernd and Cignoni, Paolo and Malomo, Luigi and Pietroni, Nico},
  title        = {State of the Art on Stylized Fabrication},
  journal      = {Computer Graphics Forum},
  volume       = {37},
  year         = {2018},
}
* @article{bermano_sot,
author = {Bermano, Amit H. and Funkhouser, Thomas and Rusinkiewicz, Szymon},
title = {State of the Art in Methods and Representations for Fabrication-Aware Design},
journal = {Computer Graphics Forum},
volume = {36},
number = {2},
pages = {509-535},
year = {2017}
}
* https://www.cs.tau.ac.il/~amberman/fabStar.pdf


* Fabricable Tile Decors
    * https://dl.acm.org/doi/10.1145/3130800.3130817
* Star-shaped metrics for mechanical metamaterial design
    * https://dl.acm.org/doi/abs/10.1145/3306346.3322989
* By-example synthesis of structurally sound patterns
    * https://dl.acm.org/doi/10.1145/2766984
* Fabricable Dihedral Escher Tessellations
    * http://irc.cs.sdu.edu.cn/Dihedral/index.html
* Interactive fabrication: new interfaces for digital fabrication
    * https://dl.acm.org/doi/10.1145/1935701.1935716
* Connected fermat spirals for layered fabrication
    * https://dl.acm.org/doi/10.1145/2897824.2925958


### Coloring

* http://www.shumash.com/research

### Creativity

##### ADD

* @inproceedings{frich_2018_tyo,
author = {Frich, Jonas and Mose Biskjaer, Michael and Dalsgaard, Peter},
title = {Twenty Years of Creativity Research in Human-Computer Interaction: Current State and Future Directions},
year = {2018},
publisher = {ACM},
booktitle = {Proceedings of the 2018 Designing Interactive Systems Conference},
pages = {1235–1257},
}
    * https://dl.acm.org/doi/abs/10.1145/3196709.3196732
* @inproceedings{10.1145/3290605.3300619,
author = {Frich, Jonas and MacDonald Vermeulen, Lindsay and Remy, Christian and Biskjaer, Michael Mose and Dalsgaard, Peter},
title = {Mapping the Landscape of Creativity Support Tools in HCI},
year = {2019},
publisher = {ACM},
booktitle = {Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems},
pages = {1–18},
}
    * https://dl.acm.org/doi/abs/10.1145/3290605.3300619
* @inproceedings{10.1145/3357236.3395474,
author = {Remy, Christian and MacDonald Vermeulen, Lindsay and Frich, Jonas and Biskjaer, Michael Mose and Dalsgaard, Peter},
title = {Evaluating Creativity Support Tools in HCI Research},
year = {2020},
publisher = {ACM},
booktitle = {Proceedings of the 2020 ACM Designing Interactive Systems Conference},
pages = {457–476},
}
    * https://dl.acm.org/doi/abs/10.1145/3357236.3395474
* @inproceedings{benedetti_2014_pwb,
author = {Benedetti, Luca and Winnem\"{o}ller, Holger and Corsini, Massimiliano and Scopigno, Roberto},
title = {Painting with Bob: Assisted Creativity for Novices},
year = {2014},
publisher = {ACM},
booktitle = {Proceedings of the 27th Annual ACM Symposium on User Interface Software and Technology},
pages = {419–428},
}
    *  https://dl.acm.org/doi/abs/10.1145/2642918.2647415

