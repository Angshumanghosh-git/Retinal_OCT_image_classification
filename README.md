# Retinal_OCT_image_classification


OCT Retinal Analysis Platform
Welcome to the Retinal OCT Analysis Platform
Optical Coherence Tomography (OCT) is a powerful imaging technique that provides high-resolution cross-sectional images of the retina, allowing for early detection and monitoring of various retinal diseases. Each year, over 30 million OCT scans are performed, aiding in the diagnosis and management of eye conditions that can lead to vision loss, such as choroidal neovascularization (CNV), diabetic macular edema (DME), and age-related macular degeneration (AMD).

Why OCT Matters
OCT is a crucial tool in ophthalmology, offering non-invasive imaging to detect retinal abnormalities. On this platform, we aim to streamline the analysis and interpretation of these scans, reducing the time burden on medical professionals and increasing diagnostic accuracy through advanced automated analysis.

Key Features of the Platform
Automated Image Analysis: Our platform uses state-of-the-art machine learning models to classify OCT images into distinct categories: Normal, CNV, DME, and Drusen.
Cross-Sectional Retinal Imaging: Examine high-quality images showcasing both normal retinas and various pathologies, helping doctors make informed clinical decisions.
Streamlined Workflow: Upload, analyze, and review OCT scans in a few easy steps.
Understanding Retinal Diseases through OCT
Choroidal Neovascularization (CNV)

Neovascular membrane with subretinal fluid
Diabetic Macular Edema (DME)

Retinal thickening with intraretinal fluid
Drusen (Early AMD)

Presence of multiple drusen deposits
Normal Retina

Preserved foveal contour, absence of fluid or edema
About the Dataset
Our dataset consists of 84,495 high-resolution OCT images (JPEG format) organized into train, test, and validation sets, split into four primary categories:

Normal
CNV
DME
Drusen
Each image has undergone multiple layers of expert verification to ensure accuracy in disease classification. The images were obtained from various renowned medical centers worldwide and span across a diverse patient population, ensuring comprehensive coverage of different retinal conditions.

Get Started
Upload OCT Images: Begin by uploading your OCT scans for analysis.
Explore Results: View categorized scans and detailed diagnostic insights.
Learn More: Dive deeper into the different retinal diseases and how OCT helps diagnose them.OCT Retinal Analysis Platform
Welcome to the Retinal OCT Analysis Platform
Optical Coherence Tomography (OCT) is a powerful imaging technique that provides high-resolution cross-sectional images of the retina, allowing for early detection and monitoring of various retinal diseases. Each year, over 30 million OCT scans are performed, aiding in the diagnosis and management of eye conditions that can lead to vision loss, such as choroidal neovascularization (CNV), diabetic macular edema (DME), and age-related macular degeneration (AMD).

Why OCT Matters
OCT is a crucial tool in ophthalmology, offering non-invasive imaging to detect retinal abnormalities. On this platform, we aim to streamline the analysis and interpretation of these scans, reducing the time burden on medical professionals and increasing diagnostic accuracy through advanced automated analysis.

Key Features of the Platform
Automated Image Analysis: Our platform uses state-of-the-art machine learning models to classify OCT images into distinct categories: Normal, CNV, DME, and Drusen.
Cross-Sectional Retinal Imaging: Examine high-quality images showcasing both normal retinas and various pathologies, helping doctors make informed clinical decisions.
Streamlined Workflow: Upload, analyze, and review OCT scans in a few easy steps.
Understanding Retinal Diseases through OCT
Choroidal Neovascularization (CNV)

Neovascular membrane with subretinal fluid
Diabetic Macular Edema (DME)

Retinal thickening with intraretinal fluid
Drusen (Early AMD)

Presence of multiple drusen deposits
Normal Retina

Preserved foveal contour, absence of fluid or edema
About the Dataset
Our dataset consists of 84,495 high-resolution OCT images (JPEG format) organized into train, test, and validation sets, split into four primary categories:

Normal
CNV
DME
Drusen
Each image has undergone multiple layers of expert verification to ensure accuracy in disease classification. The images were obtained from various renowned medical centers worldwide and span across a diverse patient population, ensuring comprehensive coverage of different retinal conditions.

Get Started
Upload OCT Images: Begin by uploading your OCT scans for analysis.
Explore Results: View categorized scans and detailed diagnostic insights.
Learn More: Dive deeper into the different retinal diseases and how OCT helps diagnose them.



About
About Dataset
Retinal optical coherence tomography (OCT) is an imaging technique used to capture high-resolution cross sections of the retinas of living patients. Approximately 30 million OCT scans are performed each year, and the analysis and interpretation of these images takes up a significant amount of time. (A) (Far left) choroidal neovascularization (CNV) with neovascular membrane (white arrowheads) and associated subretinal fluid (arrows). (Middle left) Diabetic macular edema (DME) with retinal-thickening-associated intraretinal fluid (arrows). (Middle right) Multiple drusen (arrowheads) present in early AMD. (Far right) Normal retina with preserved foveal contour and absence of any retinal fluid/edema.

Content
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (NORMAL,CNV,DME,DRUSEN). There are 84,495 X-Ray images (JPEG) and 4 categories (NORMAL,CNV,DME,DRUSEN).

Images are labeled as (disease)-(randomized patient ID)-(image number by this patient) and split into 4 directories: CNV, DME, DRUSEN, and NORMAL.

Optical coherence tomography (OCT) images (Spectralis OCT, Heidelberg Engineering, Germany) were selected from retrospective cohorts of adult patients from the Shiley Eye Institute of the University of California San Diego, the California Retinal Research Foundation, Medical Center Ophthalmology Associates, the Shanghai First People’s Hospital, and Beijing Tongren Eye Center between July 1, 2013 and March 1, 2017.

Before training, each image went through a tiered grading system consisting of multiple layers of trained graders of increasing exper- tise for verification and correction of image labels. Each image imported into the database started with a label matching the most recent diagnosis of the patient. The first tier of graders consisted of undergraduate and medical students who had taken and passed an OCT interpretation course review. This first tier of graders conducted initial quality control and excluded OCT images containing severe artifacts or significant image resolution reductions. The second tier of graders consisted of four ophthalmologists who independently graded each image that had passed the first tier. The presence or absence of choroidal neovascularization (active or in the form of subretinal fibrosis), macular edema, drusen, and other pathologies visible on the OCT scan were recorded. Finally, a third tier of two senior independent retinal specialists, each with over 20 years of clinical retina experience, verified the true labels for each image. The dataset selection and stratification process is displayed in a CONSORT-style diagram in Figure 2B. To account for human error in grading, a validation subset of 993 scans was graded separately by two ophthalmologist graders, with disagreement in clinical labels arbitrated by a senior retinal specialist.

Created by Angshuman Ghosh
