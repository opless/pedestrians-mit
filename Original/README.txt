FROM:
https://web.archive.org/web/20041118152354/http://cbcl.mit.edu/cbcl/software-datasets/PedestrianData.html

People
------

The training database of people was generated from color images and
video sequences taken in Boston and Cambridge in a variety of seasons
using several different digital cameras and video recorders. The data
was initially used in [1] and was later used in [2]-[8]. The pose
of the people in this dataset is limited to frontal and rear views.

Each image was extracted from raw data and was scaled to the size
64x128 and aligned so that the person's body was in the center of the
image; the height of these people is such that the distance from the
shoulders to the feet is approximately 80 pixels.

The data is presented without any normalization; for details on how
these images were processed, see the publications below.


[1]
@INPROCEEDINGS{OrePap97,
AUTHOR = {M. Oren and C.P. Papageorgiou and P. Sinha and E. Osuna and T. Poggio},
TITLE = {Pedestrian Detection Using Wavelet Templates},
BOOKTITLE = cvpr,
YEAR = {1997},
PAGES = {193-99}
}

[2]
@INPROCEEDINGS{PapOre98,
AUTHOR = {C.P. Papageorgiou and M. Oren and T. Poggio},
TITLE = {A General Framework for Object Detection},
BOOKTITLE = {Proceedings of 6th International Conference on Computer Vision},
YEAR = {1998}
}

[3]
@TECHREPORT{PapGirPog98,
AUTHOR = {C.P. Papageorgiou and F. Girosi and T. Poggio},
TITLE = {{Sparse Correlation Kernel Analysis and Reconstruction}},
INSTITUTION = mitai,
YEAR = {1998},
TYPE = aimemo,
NUMBER = {1635},
NOTE = {(CBCL Memo 162)}
}

[4]
@InProceedings{PapEvg98,
author = {C. Papageorgiou and T. Evgeniou and T. Poggio},
title = {A Trainable Pedestrian Detection System},
booktitle = {Proceeding of Intelligent Vehicles},
year = 1998,
month = {October},
pages = {241-246}
}

[5]
@MastersThesis{Mohan99,
author = {A. Mohan},
title = {{Robust Object Detection in Images by Components}},
school = mit,
year = 1999,
month = {May}
}

[6]
@Article{MohPap99,
author = {A. Mohan and C. Papageorgiou and T. Poggio},
title = {Example Based Object Detection in Images by Components},
journal = ieeepami,
year = 1999,
note = {in preparation}
}

[7]
@Article{PapPog00,
author = {C. Papageorgiou and T. Poggio},
title = {A Trainable System for Object Detection},
journal = ijcv,
year = 2000,
note = {In press}
}

[8]
@TechReport{Pap00,
author = {C. Papageorgiou},
title = {A Trainable System for Object Detection in Images and Video Sequences},
institution = mitai,
year = 2000,
type = {Technical Report},
number = 1685
}

 

Copyright 2000
Center for Biological and Computational Learning at MIT and MIT
All rights reserved.
Permission to copy and modify this data, software, and its documentation only for internal research use in your organization is hereby granted, provided that this notice is retained thereon and on all copies. This data and software should not be distributed to anyone outside of your organization without explicit written authorization by the author(s) and MIT. It should not be used for commercial purposes without specific permission from the authors and MIT. MIT also requires written authorization by the author(s) to publish results obtained with the data or software and possibly citation of relevant CBCL reference papers.
We make no representation as to the suitability and operability of this data or software for any purpose. It is provided "as is" without express or implied warranty.
