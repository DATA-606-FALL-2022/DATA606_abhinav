<h1>ALZHEIMERS PREDICTION USING MRI IMAGES</h1>

Abhinav Reddy Mandadi
 

<h3>INTRODUCTION</h3>

<p align = "justify">The degenerative neurologic illness Alzheimer's disease results in the death of brain cells and brain tissue shrinkage. The most frequent cause of dementia, which is characterized by a steady deterioration in thinking, acting, and social abilities and impairs a person's capacity for independent functioning, is Alzheimer's disease. In the United States, 5.8 million persons aged 65 and older have Alzheimer's disease. Eighty per cent of them are 75 or older. Between 60% and 70% of the estimated 50 million dementia sufferers globally are thought to have Alzheimer's disease. Alzheimer's disease causes significant memory loss, which makes it difficult for a patient to do daily duties.</p>

What is your issue of interest (provide sufficient background information)? 

<p align = "justify">I find myself drawn to medical issues that data science can help solve. The topic "Alzheimer's prediction using MRI images" caught my attention as I searched through many issue statements such as breast cancer detection and skin cancer detection, among others.</p>

Why is this issue important to you and/or to others? 

<p align = "justify">Cost-effectiveness is one of the primary factors that led me to choose this project. The process of Alzheimer's diagnosis is drawn out and laborious. The patient must go through testing, which may be time-consuming and expensive. However, it will undoubtedly save money and time if an algorithm is developed that only uses the patient's medical data to forecast their likelihood of getting Alzheimer's.</p>

<h3>DATA</h3>

<p align = "justify">The Oasis website is where the dataset comes from. Data from 416 subjects and 434 MRI sessions were gathered. Each MRI session's data is stored in a directory with a subject ID label.</p>

<p align = "justify">An XML file, a text (TXT) file, and three subdirectories—RAW, PROCESSED, and FSL_SEG—are all included in each session directory. The XML file contains anatomic measurements generated from the scan pictures as well as acquisition information. Individual scan pictures are included in the RAW directory. SUBJ_111 and T88_111 are two new subdirectories found in the PROCESSED directory. The averaged, co-registered picture of each individual scan image in the original acquisition space, resampled to 1mm isotropic voxels, is included in SUBJ_111. T88_111 consists of an image that has been brain-masked and resampled to 1mm isotropic voxels together with an image that has been atlas-registered gain field-corrected. It also contains the matrices explaining the conversion into atlas space in a subfolder named t4_files. The grey/white/CSF segmentation picture created from the masked atlas image is contained in the FSL_SEG subfolder.</p>

There is also a dataset containing demographic, clinical, and derived anatomic measures.
Features of the dataset are:
<ol>
<li>Gender: M(Male)/F(Female).</li>
<li>Age: Age of the patient.</li>
<li>SES (Socio-Economic Status): It ranges from 1 to 5.</li>
<li>nWBV: Normalized Whole Brain Volume.</li>
<li>Educ: This feature corresponds to the levels of education ranging from 1 to 5.</li>
<li>MMSE: Mini-Mental State Examination.</li>
<li>CDR (Clinical Dementia Rating): Typically, a CDR value above 0 can be diagnosed with Alzheimer's.</li>
<li>eTIV: Estimated total intracranial volume (mm3).</li>
<li>ASF: Atlas scaling factor.</li>
</ol>
I plan to implement Sequential model on the data.

<h3>OUTCOMES</h3>

What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?

<p align = "justify">The goal of this project is to identify the best algorithm for quickly and cheaply diagnosing Alzheimer's. Although the concept appears straightforward, really putting it into practice is rather challenging. The procedure of diagnosing Alzheimer's in the real world will entail a number of additional variables. Therefore, even if this initiative probably won't be able to completely transform the sector, it will undoubtedly serve as a springboard for further advancements.</p>

<h3>REFERENCES</h3>
<ol>
<li>Alzheimer’s disease - Symptoms and causes. (2022, February 19). Mayo Clinic. Retrieved September 11, 2022, from https://www.mayoclinic.org/diseases-conditions/alzheimers-disease/symptoms-causes/syc-20350447</li>
</ol>

	 
