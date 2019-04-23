


# About me

I am aspriting data scientist with board range of technical experience in data science and material science. I am interestedin applications of machine learning (ML) in data inference, pattern identification, data driven decision-making, and deploying ML model. 

I was the Principal Investigator of a scanning probe microscopy group at Suranaree University of Technology, Thailand. My group focused on how nanoscale material properties give rise to the rich phenomena observed in mixed phase systems. We made extensive use of automated image and data processing techniques to analyze the large data sets generated, and to reveal the underlying physical mechanisms of the phenomena that we study. Some topics my group have investigated include - the ferroelectric and diode behavior in Sm-doped BiFeO3, resistive switching behavior in ZnO nanowires, and the structure and biomechanics of Spirulina and avian sperm. We also collaborated with Western Digital, Thailand on the development of novel materials for the memory storage industry.

My PhD research focused on the development and applications of a scanning near-field microwave impedance microscope, a novel scanning probe technique capable of measuring the local dielectric constant and conductivity of materials. This technique allows us to study low temperature physics involving metal-to-insulator transitions such as colossal magnetoresistance and the quantum hall edge state. Applications at room temperature have also been shown in semiconductor materials, nanowires, and graphene. This research lies at the intersection of microwave engineering, image analysis, microfabrication, MEMS technology, material sciences, and condensed matter physics. I was involved with the commercialization process of this microscopy technique, through a spin-off company PrimeNano Inc.

Data science [resume](https://github.com/worasom/worasom.github.io/blob/master/WK-resume/Worasom_Kundhikanjana-data_science_resume.pdf)| 
Hardware and data science [resume](https://github.com/worasom/worasom.github.io/blob/master/WK-resume/Worasom_Kundhikanjana-hardware_data_science_resume.pdf)|
LinkedIn [page](https://www.linkedin.com/in/worasom/)

# Machine Learning Projects
## Analysis of Air Pollution Data [git repository](https://github.com/worasom/aqi_thailand) 
    - Enabled effective environmental policy change by identifying main air pollutant sources.
    - Scraped weather and Bangkok air pollution data - NASA’s fire map, Berkeley’s Earth air pollution, and traffic data (Requests, wget, selenium, BeautifulSoup libraries) 
    - Created visualization of how the air pollution relates to geographical locations, agricultural burning, weather patterns (matplot.pyplotlib, Bokeh libraries)
    - Made extensive use of feature engineering and cleaning: included influence of neighboring provinces with time lag, distance weighed fire map data, extracted feature from weather patterns, and date-time feature engineering. Remove redundant feature using hierarchical clustering (scipy library)
    - Built a machine learning pipeline to identify the major contributors to PM2.5 air pollution: Used autoML the best models and hyper parameters (TPOT library), identify the feature of importance, and thus the pollution sources.
    - Obtain 0.78 R-square on the validation set 
    - Try other ML models: Use neural network (fast.ai), and VAR models(statmodels)
    - Blog: Scraping Air Pollution Data from Thailand EPA in [Medium.com](https://medium.com/@worasom/scraping-air-pollution-data-from-thailand-epa-a866f291c06)  
    - Blog: Identifying the Sources of Winter Air Pollution in Bangkok Part I[Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-i-d4392ea608dc)
    - Blog: Identifying the Sources of Winter Air Pollution in Bangkok Part II[Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-ii-72539f9b767a)

## Health Data 
    - Automatic liver patients identification from their blood test data [git repository](https://github.com/worasom/indian_liver_patients)
    - Exploratory data analysis and feature engineering using Python (pandas, numpy, matplot. pyplotlib)
    - Feature selection from feature of importance. Remove redundant feature using hierarchical clustering (scipy library)
    - Applied different classification models.  Compare performance of [random forest](https://github.com/worasom/indian_liver_patients/blob/master/Indian_liver_patients_random_forest.ipynb), [logistic regression](https://github.com/worasom/indian_liver_patients/blob/master/Indian_liver_logistic.ipynb), and [neural network](https://github.com/worasom/indian_liver_patients/blob/master/Indian_liver_patients-NN.ipynb)
    - Achieve 78% accuracy on the validation set(baseline = 72%) , loss =  0.47(baseline 0.69)

## Image Classifications 

###  Identified oil palm plantations from satellite images [git repository](https://github.com/worasom/WiDS_Datathon_2019)
    - Predicted how likely a satellite image contains oil palm plantations 
    -  Libraries: fastai, pytorch libraries, opencv 
    - Worked with Imbalance class: only 6% of the images belong to a second class (with oil palm). Solve by creating augmented images from the training set (OpenCV library)
    - Use transferred learning from pretrained models 
    - Explored different CNN architectures: resnet34, resnext201, dn201 
    - Achieved 99.4% accuracy for the Kaggle hold out dataset (approximately #113 on the leaderboard)

###  EiffelTower vs WatArun [git repository](https://github.com/worasom/EiffelTower_vs_WatArun)
    - Mined images from Google Images 
    - Performed dataloader and image augmentation in GPU (fastai, pytorch libraries)
    - Transferred learning using pretrained resnet weight 
    - Achieved 93% accuracy 

## Image Segmentation
    - Nuclei segmentation of stained tissue images of tumor patients in MICCAI2018 challenge[git repository](https://github.com/worasom/hist_images) 
    - Trained Unet architecture to perform image segmentation (fast.ai library). Use various image processing libraries (OpenCV, PIL, imageio, skimage)
    - Worked with small dataset. There were only 30 training images. Each has 1000 x 1000 pixels. Augmented training set by generating 125x125 images crop images and mask files
    - Achieved 90% accuracy on the validation set  

# Courses
    - Python for Data Scientist by DataCamp.com: supervise learning, unsupervised learning, deep learning, convolution neutral network, importing and cleaning data in Python, pandas, database, SQL, PySpark, MongoDB, interactive data visualization with Bokeh and geopandas, statistical thinking in Python
    - Machine learning by fast.ai: random forest, feature importance, partial dependence, gradient descent, logistic regression, feature engineering, natural language processing, embedding 
    - Deep Learning by fast.ai: Image classification, SGD, multi-label, Segmentation, NLP, backprob, CNN, Resnet, U-net, GANs
    - Convolutional Neural Networks for Visual Recognition by Stanford University: image classification, localization and detection
    - CS109 Data Science by Harvard University: Web Scraping, Pandas, Exploratory Data Analysis, SQL, Statistical Models, Bias and Regression, machine learning models, clustering 
    - Class notes in [git repository]]https://github.com/worasom/class-projects