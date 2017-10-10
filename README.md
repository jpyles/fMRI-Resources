# fMRI-Resources
A page of information and resources on functional MRI.

Suggestions welcome!
Either submit an issue or contact me (jpyles at cmu dot edu).

[Useful Websites](#useful-websites)  
[Software](#software)  
[Brain Anatomy](#brain-anatomy)  


---


## Useful Websites


* **[fMRI 4 Newbies](http://culhamlab.ssc.uwo.ca/fmri4newbies/)** - Jody Culham's excellent site for intro fMRI info
* **[Berkeley 3T Training Guide](http://bic.berkeley.edu/sites/default/files/3T_user_training_FAQ_08Mar2012.doc)** - This is by far the most useful single document I have found for understanding MRI parameters and Siemens scanners. Written by Berkeley's MR physicist Ben Inglis (who also writes practiCal fMRI) it is *a must read*.
* **[practiCal fMRI](https://practicalfmri.blogspot.com/)** - Ben Inglis' blog on everything related to MRI physics (especially Siemens magnets) and lots on fMRI practice and other issues. An excellent resource.
* **[NIH MRI Summer Course](https://fmrif.nimh.nih.gov/public/fmri-course)** - A great collection of lecture videos and slides covering many aspects of functional and structural imaging.
* **[MIT Imaging Mindhive](http://mindhive.mit.edu/imaging)** - A wiki of very good information on various aspects of fMRI.
* **[Harvard Center for Brain Science FAQ](http://cbs.fas.harvard.edu/science/core-facilities/neuroimaging/information-investigators/MRphysicsfaq)** - Very good MRI FAQ.
* **[Beauchamp Lab Wiki](http://www.openwetware.org/wiki/Beauchamp:Lab_Notebook)** - Michael Beauchamp has an excellent lab wiki with lots of useful info.
* **[Aguirre Lab](https://cfn.upenn.edu/aguirre/wiki/public:methods)** - Useful resources from Geoff Aguirre's lab website at Univ. of Pennsylvania.

***Other Useful General Research Sites***
* **[Data Analysis Tips I Wish I'd Known Sooner](http://deevybee.blogspot.com/2014/04/data-analysis-ten-tips-i-wish-id-known.html)** - A good set of tips.
* **[Lab Hacks](https://github.com/pbeukema/LabHacks)** - Good general advice on research for grad students and others from Patrick Beukema at CMU.
* **[Jody's Advice to Young Scientists](http://www.culhamlab.com/academic-advice/)** - Another excellent collection of general research advice from Jody Culham at Western University.


## Software

***Main fMRI Software Packages***

* **[SPM](http://www.fil.ion.ucl.ac.uk/spm/)** - The most widely used fMRI analysis software. Based in Matlab it is powerful and versatile, but has poor visualization capabilities. (From: FIL at Univ. College London)

* **[AFNI](https://afni.nimh.nih.gov/)** - An excellent and fast Linux/Unix compiled analysis package with scripting capability and good visualization, especially when combined with the SUMA surface analysis package. (From: Medical College of Wisconsin and now based at NIH)

* **[FSL](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki)** - Another excellent Linux/Unix compiled package with good visualization and powerful analysis and scripting capabilities. FSL also is also home to one of the standard diffusion MRI packages. (From: FMRIB, Univ. of Oxford)

* **[BrainVoyager](http://www.brainvoyager.com/)** - A powerful cross platform compiled package with excellent visualization and surface analysis capabilities and an easy to use GUI. Requires a paid license. (From: Rainer Goebel and Brain Innovations, Maastricht, The Netherlands)

* **[FreeSurfer](https://surfer.nmr.mgh.harvard.edu/)** - An analysis package rooted in surface reconstruction. `recon-all` is the standard automatic segmentation routine for many researchers, even if they analyze their data in other packages. (From: The Laboratory for Computational Neuroimaging and the Martinos Center at MGH)

* **[MrVista](https://github.com/vistalab/vistasoft)** - The analysis package developed by Brain Wandell's Vista Lab based in Matlab (with compiled portions) and optimized for surface analysis and vision science experiments. (From: VISTA Lab, Stanford)

***Other Useful MRI Software***

* **[NeuroDebian](http://neuro.debian.net/)** - A repository for lots of neuroimaging software and an easy way to install many useful packages such as AFNI, FSL, etc.
* **[MriCron](http://people.cas.sc.edu/rorden/mricron/index.html)** - Probably the standard cross-platform NIfTI viewer. Also includes the dcm2nii converter.
* **[NeuroElf](http://neuroelf.net/)** - Excellent and powerful set of tools, functions, and a GUI interface that allows many formats of fMRI data to be imported and exported from Matlab. There are also tools for pre-processing and analysis. (Written and maintained by Jochen Weber at Columbia University.)
* **[NIPY](http://nipy.org/)** - Python tools for neuroimaging.
* **[Nipype](http://nipype.readthedocs.io/en/latest/#)** - Python project to integrate different neuroimaging software packages. (Primary developer Chris Gorgolewski at Stanford.)
* **[Pycortex](https://gallantlab.github.io/)** - Python tools for surface visualization. (Primarly developed by James Gao in the Gallant Lab at Berkeley)
* **[3DSlicer](https://www.slicer.org/)** - Open source medical imaging file processing and visualization tool.
* **[MRIConvert](http://lcni.uoregon.edu/downloads/mriconvert)** - Powerful file format converter.
* **[Horos (Mac)](https://www.horosproject.org/)** - Excellent DICOM visualization and sorting tool based off the commercial OsiriX viewer.
* **[Mango](http://ric.uthscsa.edu/mango/)** - Medical image viewer with analysis tools.
* **[FSL View](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslView)** - The viewer part of the FSL package that can also be used as a general viewer.
* **[BROCCOLI](https://github.com/wanderine/BROCCOLI)** - A set of pre-processing and analysis routines that are optimized for GPUs.
* **[Human Connectome Project Workbench](http://www.humanconnectome.org/software/connectome-workbench)** - A new and powerful set of visualization and data exploration tools from the HCP. (Although installation of the package is reportedly currently difficult.)
* **[GLM Denoise](http://kendrickkay.net/GLMdenoise/)** - A package for denoising task based fMRI data from [Kendrick Kay](http://cvnlab.net/).
* **[preprocessfmri](https://github.com/kendrickkay/preprocessfmri)** - Kendrick Kay's powerful fMRI preprocessing script. Particularly useful if fieldmap corrections are being performed.
* **[Yeatman Lab Tools](https://github.com/yeatmanlab)** - [Jason Yeatman](http://www.jasonyeatman.com/)'s lab at the Univ. of Washington has a number of useful tools for MRI.
* **[CoAxLab Tools](https://github.com/CoAxLab)** - Software and tools from the Cognitive Axon Lab at Carnegie Mellon.

***Other Useful General Software***

* **[Cyberduck (Mac)](https://cyberduck.io/?l=en)** - Good SFTP GUI.
* **[Atom](https://atom.io/)** - Excellent text editor that is well integrated with GitHub.
* **[Git/GitHub](https://github.com/git)** - The standard for version tracking code (and other stuff) and making it publicly available.
* **[Slack](https://slack.com/)** - Very userful lab/workgroup message system.
* **[PathFinder (Mac)](https://cocoatech.com/)** - Excellent Finder replacement for OSX (because Finder is terrible). It allows sorting by extension, tabs, two pane file browsers, all the things you need to efficiently do science.


***For MVPA***

* **[libsvm](https://www.csie.ntu.edu.tw/~cjlin/libsvm/)** - The most popular support vector machine classifier.
* **[Surfing](http://surfing.sourceforge.net/Welcome.html)** - A toolbox for surface based voxel selection.
* **[PyMVPA](http://www.pymvpa.org/)** - Python package for MVPA.
* **[Neural Decoding Toolbox](http://www.readout.info/)** - Matlab toolbox for MVPA.
* **[SearchMight](http://www.franciscopereira.org/searchmight/)** - Searchlight toolbox from [Francisco Pereira](http://www.franciscopereira.org/).
* **[Princeton MVPA Toolbox](https://github.com/princetonuniversity/princeton-mvpa-toolbox)** - MVPA toolbox from Princeton.
* **[MVPA Meanderings](http://mvpa.blogspot.com/)** - Very good blog on issues in MVPA.
* **[Some tutorials from Rochester](http://www2.bcs.rochester.edu/sites/raizada/fmri-matlab.html)**



## Brain Anatomy

* **[Caspers 2017 OHBM Slides](https://www.humanbrainmapping.org/files/2017/ED%20Courses/Course%20Materials/Anatomy_Caspers_Julian.pdf)** - Julian Caspers, a neuroradiologist, provided a great set of guidelines at the 2017 Organization for Human Brain Mapping conference.
* **[Atlas of the Human Brain](http://www.amazon.com/Atlas-Human-Brain-Third-Edition/dp/012373603X)** -- Mai, Paxinos, & Voss
* **[Talairach Atlas online](http://www.talairach.org/)**
* **[Brain Explorer from Allen Brain Institute](http://human.brain-map.org/static/brainexplorer)**
* **[Whole Brain Atlas](http://www.med.harvard.edu/aanlib/home.html)** - Harvard MGH
* **[Brainmaps.org](brainmaps.org)**
* **[Digital Anatomist](http://www9.biostr.washington.edu/da.html)** - Univ. of Washington
* **[BrainVoyager Brain Tutor](http://www.brainvoyager.com/products/braintutor.html)**
* **[Video of Unfixed Brain](https://youtu.be/jHxyP-nUhUY)** - A rare and important look at a post-mortem brain that has not yet been fixed, thus showing the compressibility of the brain and details of vasculature.
* **[Marian Diamond's full anatomy course](https://www.youtube.com/watch?v=S9WtBRNydso&list=PLYaP1u75QsCDt6gTE29X758sD7-by7U_T)** - The legendary Berkeley anatomy course.
