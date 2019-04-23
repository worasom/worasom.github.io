


# About me

I am aspriting data scientist with board range of technical experience in data science and material science. I am interestedin applications of machine learning (ML) in data inference, pattern identification, data driven decision-making, and deploying ML model. 

I was the Principal Investigator of a scanning probe microscopy group at Suranaree University of Technology, Thailand. My group focused on how nanoscale material properties give rise to the rich phenomena observed in mixed phase systems. We made extensive use of automated image and data processing techniques to analyze the large data sets generated, and to reveal the underlying physical mechanisms of the phenomena that we study. Some topics my group have investigated include - the ferroelectric and diode behavior in Sm-doped BiFeO3, resistive switching behavior in ZnO nanowires, and the structure and biomechanics of Spirulina and avian sperm. We also collaborated with Western Digital, Thailand on the development of novel materials for the memory storage industry.

My PhD research focused on the development and applications of a scanning near-field microwave impedance microscope, a novel scanning probe technique capable of measuring the local dielectric constant and conductivity of materials. This technique allows us to study low temperature physics involving metal-to-insulator transitions such as colossal magnetoresistance and the quantum hall edge state. Applications at room temperature have also been shown in semiconductor materials, nanowires, and graphene. This research lies at the intersection of microwave engineering, image analysis, microfabrication, MEMS technology, material sciences, and condensed matter physics. I was involved with the commercialization process of this microscopy technique, through a spin-off company PrimeNano Inc.

Data science [resume](https://github.com/worasom/worasom.github.io/blob/master/WK-resume/Worasom_Kundhikanjana-data_science_resume.pdf)| 
Hardware and data science [resume](https://github.com/worasom/worasom.github.io/blob/master/WK-resume/Worasom_Kundhikanjana-hardware_data_science_resume.pdf)|
LinkedIn [page](https://www.linkedin.com/in/worasom/)

# Machine Learning Projects
## Analysis of Air Pollution Data [page](https://github.com/worasom/aqi_thailand): 
- Enabled effective environmental policy change by identifying main air pollutant sources
Mined publicly available weather and air pollution data - NASA’s fire map, Berkeley’s Earth air pollution, and traffic data (Requests, wget, selenium, BeautifulSoup libraries) 
- Created visualization of how the air pollution relates to geographical locations, agricultural burning, weather patterns (matplot.pyplotlib, Bokeh libraries)
- Made extensive use of feature engineering and cleaning: included influence of neighboring provinces with time lag, distance weighed fire map data, extracted feature from weather patterns, and date-time feature engineering.
- Remove redundant feature using hierarchical clustering (scipy library)
- Build a random forest regression model to identify the feature of importance, and thus the pollution sources
- Built a machine learning pipeline to identify the major contributors to PM2.5 air pollution: used autoML the best models and hyper parameters (TPOT library)
- Try other models: neural network, and VAR models 
- Blog: Scraping Air Pollution Data from Thailand EPA in [Medium.com](https://medium.com/@worasom/scraping-air-pollution-data-from-thailand-epa-a866f291c06)  
- Blog: Identifying the Sources of Winter Air Pollution in Bangkok Part I[Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-i-d4392ea608dc)
Blog: Identifying the Sources of Winter Air Pollution in Bangkok Part II[Medium.com](https://towardsdatascience.com/identifying-the-sources-of-winter-air-pollution-in-bangkok-part-ii-72539f9b767a)