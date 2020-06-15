# Histopathological_Cancer_Detection
 
 - Kranthi Kumar
 
<p style='text-align: justify;'><b>Cancer</b> is the name given to a Collection of Related Diseases. In all types of Cancer's, some of the Body’s cells <b>Begin to Divide Without Stopping and Spread into Surrounding Tissues</b>.</p>

<p style='text-align: justify;'>When a surgeon operates to remove a <b>Primary Cancer</b>, one or more of the nearby (regional) <b>Lymph Nodes</b> may be removed as well. Removal of one lymph node is called a Biopsy. When many lymph nodes are removed, it’s called Lymph Node Sampling or Lymph Node Dissection. When cancer has spread to Lymph Nodes i.e known as <b>Metastatasis</b>, then there’s a <b>Higher Risk that the Cancer might come back after Surgery</b>.The tissue that’s removed is looked at under the microscope by a Pathologist for the Presence of Cancer Cells.<p>
    
<br>
<b>Lymph Nodes :</b>

<p style='text-align: justify;'>Lymph vessels route lymph fluid through nodes throughout the body. Lymph nodes are small structures that work as filters for harmful substances. They contain immune cells that can help fight infection by attacking and destroying germs that are carried in through the lymph fluid.</p>


<b>Metastatasis :</b>

<p style='text-align: justify;'> Metastasis is the spread of cancer cells to new areas of the body, often by way of the lymph system or bloodstream. A metastatic cancer, or metastatic tumor, is one that has spread from the primary site of origin, or where it started, into different areas of the body.</p>

<b>Histopathology</b>
<p style='text-align: justify;'> <b>Histology</b> is the study of <b>Tissues</b>, and <b>Pathology</b> is the study of <b>Disease</b>. So taken together, <b>Histopathology</b> literally means the <b>Study of Tissues as relates to Disease</b>. A histopathology report describes the tissue that has been sent for examination and the features of what the cancer looks like under the microscope. A histopathology report is sometimes called a biopsy report or a pathology report.</p>

<b>Digital Pathological Scans</b>

<p style='text-align: justify;'> Digital pathology is a sub-field of pathology that focuses on data management based on information generated from digitized specimen slides. Through the use of computer-based technology, digital pathology utilizes virtual microscopy. Glass slides are converted into digital slides that can be viewed, managed, shared and analyzed on a computer monitor. With the practice of Whole-Slide Imaging (WSI), which is another name for virtual microscopy, the field of digital pathology is growing and has applications in diagnostic medicine, with the goal of achieving efficient and cheaper diagnoses, prognosis, and prediction of diseases. </p>

### Data

<p style='text-align: justify;'>The Data here is from the Histopathological Scans. A positive label indicates that the center 32x32 px region of a patch contains at least one pixel of Tumor Tissue. Tumor tissue in the outer region of the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a Whole Slide Image(WSI).</p>

 - This Dataset was prepared on PCam (Patch Camelyon) which was prepared on Camelyon16 Data.
 - It is Smaller version of Camelyon16 Data. 
 - The Original PCam dataset contains duplicate images due to its Probabilistic Sampling, however, the version presented on Kaggle does not contain duplicates. 
 - The Data can be downloaded from https://www.kaggle.com/c/histopathologic-cancer-detection/data
 - <b>Files:</b>
     - Train : 5.87 GB
     - Test : 1.53 GB
     - Train_Labels: 9.02 MB
 - Train and Test Data consists only Images.
