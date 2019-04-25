# Welcome to Worasom Kundhikanjana's GitHub page

In this page, you will find my machine learning projects, blogs, class notes, and previous publications. If you have any suggestion, please leave me a message! 

## About me

I am an aspiring data scientist with a board range of technical experience in data science and material science. I am interested in applications of machine learning (ML) in data inference, pattern identification, data driven decision-making, and model deployment. 

I was the Principal Investigator of a scanning probe microscopy group at Suranaree University of Technology, Thailand. My group focused on how nanoscale material properties give rise to the rich phenomena observed in mixed phase systems. We made extensive use of automated image and data processing techniques to analyze our large data sets, and to reveal the underlying physical mechanisms of the phenomena. Some topics investigated by my group include - the ferroelectric and diode behavior in Sm-doped BiFeO3, resistive switching behavior in ZnO nanowires, and the structure and biomechanics of Spirulina and avian sperm. We also collaborated with Western Digital Thailand on the development of novel materials for the memory storage industry.

My PhD research focused on the development and applications of a scanning near-field microwave impedance microscope, a novel scanning probe technique capable of measuring the local dielectric constant and conductivity of materials. This technique allows us to study low temperature physics involving metal-to-insulator transitions such as colossal magnetoresistance and the quantum hall edge state. Applications at room temperature have also been shown in semiconductor materials, nanowires, and graphene. This research lies at the intersection of microwave engineering, image analysis, microfabrication, MEMS technology, material sciences, and condensed matter physics. I was involved with the commercialization process of this microscopy technique, through a spin-off company PrimeNano Inc.

Data science [resume](https://github.com/worasom/worasom.github.io/blob/master/WK-resume/Worasom_Kundhikanjana-data_science_resume.pdf)| 
Hardware and data science [resume](https://github.com/worasom/worasom.github.io/blob/master/WK-resume/Worasom_Kundhikanjana-hardware_data_science_resume.pdf)|
LinkedIn [page](https://www.linkedin.com/in/worasom/)

# Machine Learning Projects

## Analysis of Air Pollution Data [git repository](https://github.com/worasom/aqi_thailand) 
- Enabled effective environmental policy change by identifying main air pollutant sources.
- Scraped weather and Bangkok air pollution data from NASA’s fire map, Berkeley Earth air pollution, and traffic data (Requests, wget, selenium, BeautifulSoup libraries) 
- Created visualization of how the air pollution relates to geographical locations, agricultural burning, weather patterns (matplot.pyplotlib, Bokeh libraries)
- Made extensive use of feature engineering and cleaning: included influence of neighboring provinces with time lag, distance weighed fire map data, extracted features from weather patterns, and date-time feature engineering. Removed redundant features using hierarchical clustering (scipy library)
- Built a machine learning pipeline to identify the major contributors to PM2.5 air pollution: Used autoML to identify the best models and hyper parameters (TPOT library), identified contributions of different pollution sources through feature of importance.
- Obtained 0.78 R-square on the validation set 
- Applied other ML models: Used neural network (fast.ai), and VAR models(statmodels)
- Blog: Scraping Air Pollution Data from Thailand EPA. Published in [Medium.com](https://medium.com/@worasom/scraping-air-pollution-data-from-thailand-epa-a866f291c06)  
- Blog: Identifying the Sources of Winter Air Pollution in Bangkok Part I. Published in [Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-i-d4392ea608dc)
- Blog: Identifying the Sources of Winter Air Pollution in Bangkok Part II. Published in [Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-ii-72539f9b767a)

## Health Data 

**Automatic liver patients identification from their blood test data [git repository](https://github.com/worasom/indian_liver_patients)**
- Exploratory data analysis and feature engineering using Python (pandas, numpy, matplot. pyplotlib)
- Feature selection from feature of importance. Removed redundant features using hierarchical clustering (scipy library)
- Applied different classification models.  Compared performance of [random forest](https://github.com/worasom/indian_liver_patients/blob/master/Indian_liver_patients_random_forest.ipynb), [logistic regression](https://github.com/worasom/indian_liver_patients/blob/master/Indian_liver_logistic.ipynb), and [neural network](https://github.com/worasom/indian_liver_patients/blob/master/Indian_liver_patients-NN.ipynb)
- Achieved 78% accuracy on the validation set(baseline = 72%) , loss =  0.47(baseline 0.69)

## Image Classifications 

**Identified oil palm plantations from satellite images [git repository](https://github.com/worasom/WiDS_Datathon_2019)**
- Predicted how likely a satellite image contains oil palm plantations 
- Libraries: fastai, pytorch libraries, opencv 
- Worked with Imbalance class: only 6% of the images belong to a second class (with oil palm). Resolved by creating augmented images from the training set (OpenCV library)
- Used transferred learning from pretrained models 
- Explored different CNN architectures: resnet34, resnext201, dn201 
- Achieved 99.4% accuracy for the Kaggle hold out dataset (approximately #113 on the leaderboard)

**EiffelTower vs WatArun [git repository](https://github.com/worasom/EiffelTower_vs_WatArun)**
- Mined images from Google Images 
- Performed dataloader and image augmentation in GPU (fastai, pytorch libraries)
- Transferred learning using pretrained resnet weight 
- Achieved 93% accuracy 

## Image Segmentation

**Nuclei segmentation of stained tissue images of tumor patients in MICCAI2018 challenge[git repository](https://github.com/worasom/hist_images)**
- Trained Unet architecture to perform image segmentation (fast.ai library). Used various image processing libraries (OpenCV, PIL, imageio, skimage)
- Worked with small dataset. There were only 30 training images. Each has 1000 x 1000 pixels. Augmented training set by generating 125x125 cropped images and mask files
- Achieved 90% accuracy on the validation set  

## Database: 

- **MongoDB [notebook](https://github.com/worasom/database_projects/blob/master/MongoDB.ipynb)**: Query documents and subdocuments, Counting Documents, Survey Distinct Values with filters, element match operator, Filter with Regular Expressions, Indexes in MongoDB, aggregation 
- **SQLite [notebook](https://github.com/worasom/database_projects/blob/master/SQL_datascience.ipynb)**: How to setup an SQLite server and populate tables, Insert, delete colums from the tables, Query the table and output as dataframe, Filter query using WHERE, AND, OR, IS NULL, LIKE, Aggregation using GROUP BY, ORDER BY, Create index, Joins


# Blogs

Scraping Air Pollution Data from Thailand EPA. Published in [Medium.com](https://medium.com/@worasom/scraping-air-pollution-data-from-thailand-epa-a866f291c06)  

Identifying the Sources of Winter Air Pollution in Bangkok Part I. Published in [Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-i-d4392ea608dc)

Identifying the Sources of Winter Air Pollution in Bangkok Part II. Published in [Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-ii-72539f9b767a)


# Class Projects/Notes [repository](https://github.com/worasom/class-projects)

- Data Visualization [notebook](https://github.com/worasom/class-projects/blob/master/data_vis.ipynb)
- Interactive Visualization with Bokeh [notebook](https://github.com/worasom/class-projects/blob/master/bokeh_note.ipynb)
- Time Series Analysis [notebook](https://github.com/worasom/class-projects/blob/master/time-series-anlysis.ipynb)
- Machine Learning for Time Series Data in Python [notebook](https://github.com/worasom/class-projects/blob/master/ml4time_series.ipynb)

# Courses Work 

- Machine Learning 
    - Data Scientist [Certificate](https://github.com/worasom/wora  som.github.io/blob/master/WK-certificates/Data%20Scientist%20with%20Python%20Track.pdf) from DataCamp.com: supervise learning, unsupervised learning
    - Machine learning by fast.ai: random forest, feature of importance, partial dependence, gradient descent, logistic regression, feature engineering, natural language processing, embedding
    - CS109 Data Science by Harvard University: Web Scraping, Pandas, Exploratory Data Analysis, SQL, Statistical Models, Bias and Regression, machine learning models, clustering 
  
- Deep Learning
    - Deep Learning by fast.ai: Image classification, SGD, multi-label, Segmentation, NLP, backprob, CNN, Resnet, U-net, GANs
    - Convolutional Neural Networks for Visual Recognition by Stanford University: image classification, localization and detection

- Database: database from DataCamp.com [certificate](https://github.com/worasom/worasom.github.io/blob/master/WK-certificates/SQL%20Fundamentals%20Track.pdf), SQLite, Postgre, MongoDB

- Other topics: pyspark, importing and cleaning data in Python, pandas, interactive data visualization with Bokeh and geopandas, statistical thinking in Python from DataCamp.com

# Publications and Conferences 

- **Memory Device**: Identified defect-dominated conduction behavior in resistive switching ZnO nanowire devices that can improve the growth process. Used non-linear fitting in MATLAB.  O. Srikimkaew, **W. Kundhikanjana (Leader)**, et al., Journal of Electronics material (2019) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Size-Independent%20Unipolar%20and%20Bipolar%20Resistive%20Switching%20Behaviors%20in%20ZnO%20Nanowires.pdf) 

- **Ferroelectric Material**: Studied effectiveness of Sm substitution in improving ferroelectric property, and reducing conductivity in bismuth ferrite ceramics. Identified an optimal doping level for ferroelectic device applications. Used image cross-correlation, curve fitting(python). P. Sriboriboon, **W. Kundhikanjana (Leader)**, et al., Physics Letter A, (2019)[pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Effects%20of%20Sm%20Substitution%20on%20Ferroelectric%20Domains%20and%20Conductivity%20in%20Bismuth%20Ferrite%20Ceramics%20-2019.pdf). J. Nonkumwong,  **W. Kundhikanjana (CO-Leader)**, et al., Integrated Ferroelectrics (2018) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Ferroelectric%20domain%20evolution%20in%20gold%20nanoparticle-modified%20perovskite%20barium%20titanate%20ceramics%20by%20piezoresponse%20force%20microscopy2018.pdf)

- **Biological study**
    - Studied survival strategy of Arthrospira platensis (Spirulina) by shape transformation from spiral to rod shapes for effective food production.  A. Chaiyasitdhi, **W. Kundhikanjana (CO-Leader)**, et al., PLoS ONE, (2018) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/The%20biomechanical%20role%20of%20overall-shape%20transformation%20in%20a%20primitive%20multicellular%20organism%20A%20case%20study%20of%20dimorphism%20in%20the%20filamentous%20cyanobacterium%20Arthrospira%20platensis-2018.pdf)
    - Investiage effect of storage mediums on ultrastructure of spermatozoa. C. Riou, **W. Kundhikanjana (CO-Leader)**, Avian Model Sytems Conference, (2018) 

- **Strongly Correlated Oxides**: Designed and conducted imaging experiments to capture microscopic glassy behavior of a metallic phase in a perovskite manganite film. Cross-correlation analysis to register large sets of images (MATLAB). Image segmentation to calculate areal fraction of the metallic phase. **W. Kundhikanjana (main author)**, et al, Physical Review Letters, (2015) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Direct%20Imaging%20of%20Dynamic%20Glassy%20Behavior%20in%20a%20Strained%20Manganite%20Film-2015.pdf)

- **Semiconductor Material**: Failure analysis of a RAM device. Identified the cause of an unexpected surface implanted layer. Figure selected for Journal cover page.  **W. Kundhikanjana (main author)**, et al, Semiconductor Science and Technology (2013)  

- **Image Analysis**
     - Investigated nanoscale electronic properties in novel materials. Image analysis to understand statistical inference of the data. **W. Kundhikanjana (main author)**, Nano Letters, (2009) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Hierarchy%20of%20Electronic%20Properties%20of%20Chemically%20Derived%20and%20Pristine%20Graphene%20Probed%20by%20Microwave%20Imaging%202009.pdf)
     - Image segmentation and edge detection in (MATLAB). K. Lai, **W. Kundhikanjana (co-author)**, Physical Review Letters, (2011) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Imaging%20of%20Coulomb-Driven%20Quantum%20Hall%20Edge%20States-2011.pdf)
     - Used image autocorrelation to calculate correlation length (MATLAB).  K. Lai, **W. Kundhikanjana (co-author)**, Science, (2010) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Mesoscopic%20Percolating%20Resistance%20Network%20in%20a%20Strained%20Manganitethinfilm%20Science-2010-Lai-190-3.pdf) and [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Ultrathin%20Topological%20Insulator%20Bi2Se3%20Nanoribbons%20Exfoliated%20by%20Atomic%20Force%20Microscopy_2010.pdf)

- **Microfabrication**: Failure analysis to help optimize microfabrication process of cantilever probes for commercial purpose. Resulted in a spin-off company (PrimeNano Inc). Y. Yang, **W. Kundhikanjana (co-author)**, et al, Journal of Micromechanics and Microengineering (2012) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Batch-fabricated%20cantilever%20probes%20with%20electrical%20shielding%20for%20nanoscale%20dielectric%20and%20conductivity%20imaging-2012.pdf), Y. Yang, **W. Kundhikanjana (co-author)**, Journal of Micromechanics and Microengineering (2014)[pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Shielded%20piezoresistive%20cantilever%20probes%20fornanoscaletopography%20and%20electrical%20imaging.pdf), and Y. Yang, **W. Kundhikanjana (co-author)**, MEMS  (2011)[pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/A%20SHIELDED%20CANTILEVER-TIP%20MICROWAVE%20PROBE%20FOR%20MICRO_NANO%20SURFACE%20IMAGING%20OF%20CONDUCTIVE%20PROPERTIES%202011.pdf)

- **Software**: Designed automatic control and data acquisition software in LabVIEW for high-vacuum and low temperature scanning probe microscopy platform. Resulted in many follow up publication in high-impact journals. **W. Kundhikanjana (main author)**, et al, Review of Scientific Instruments, (2011) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Cryogenic%20microwave%20imaging%20of%20metal%E2%80%93insulator%20transition%20in%20doped%20silicon_2011.pdf) 

- **Hardware**
     - Designed and implemented calibration procedure for quantitative dielectric measurement with microwave microscopy technique.  K. Lai, **W. Kundhikanjana (co-author)**, et al, Review of Scientific Instruments, (2009) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Calibration%20of%20shielded%20microwave%20probes%20using%20bulk%20dielectrics-2008.pdf) and K. Lai, **W. Kundhikanjana (co-author)**, et al, Review of Scientific Instruments, (2009) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Tapping%20mode%20microwave%20impedance%20microscopy-2009.pdf)
     - Explored applications and provided show cases for the invented microscopy technique. K. Lai, **W. Kundhikanjana (co-author)**, Nano Letter, (2009) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Nanoscale%20Electronic%20Inhomogeneity%20in%20In2Se3%20Nanoribbons%20Revealed%20by%20Microwave%20Impedance%20Microscopy-2009.pdf), S.-S.Hong, **W. Kundhikanjana (co-author)**, Nano Letter, (2010)[pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Ultrathin%20Topological%20Insulator%20Bi2Se3%20Nanoribbons%20Exfoliated%20by%20Atomic%20Force%20Microscopy_2010.pdf), E.Y. Ma, **W. Kundhikanjana (co-author)**, Nature Communication, (2015)[pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Unexpected%20edge%20conduction%20in%20mercury%20telluride%20quantum%20wells%20under%20broken%20time-reversal%20symmetry-2015.pdf)

- **Simulation**: Developed microwave impedence microscopy technique. Finite element modeling of tip-sample interaction (COMSOL) to understand the contrast mechanism of nanoscale microwave microscopy technique, which provides hard-to-obtain information for material development. K. Lai, **W. Kundhikanjana (co-author)**, et al, Review of Scientific Instruments, (2008) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Calibration%20of%20shielded%20microwave%20probes%20using%20bulk%20dielectrics-2008.pdf), K. Lai, **W. Kundhikanjana (co-author)**, Applied Nanoscience, (2011) [pdf](https://github.com/worasom/worasom.github.io/blob/master/WK-publications/Nanoscale%20microwave%20microscopy%20using%20shielded%20cantilever%20probes-2011.pdf)