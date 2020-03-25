<div class="clearfix" style="padding: 0px; padding-left: 100px; display: flex; flex-wrap: nowrap; justify-content: space-evenly; align-items:center">
<a href="http://bimcv.cipf.es/"><img src="https://github.com/BIMCV-CSUSP/BIMCV-COVID-19/blob/master/chestRx/logoinst.png?raw=true"</a><a href="http://ceib.san.gva.es"></a></div>

# Data Sources. [BIMCV-PadChest](http://ceib.bioinfo.cipf.es/covid19/padchest_neumonia.zip)
You can download the Raw images from this link --> http://ceib.bioinfo.cipf.es/covid19/padchest_neumonia.zip

You can download the resize images from  --> http://ceib.bioinfo.cipf.es/covid19/resized_padchest_neumo.tar.gz

You can download other resize images --> http://ceib.bioinfo.cipf.es/covid19/resized_padchest_neumo_32.tar.gz

**New updates 24/03/2020**

Following Roberto Paredes's suggestions we have resized the dataset 

**New updates 23/03/2020**

Following Roberto's suggestions we will leave a single partition, it will be easier.

**New updates 25/03/2020**

Some duplicates has been detected in per-file items, also some records does not follow the convention and may be corrupted.

Merging files this combination is found for these records:
```
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	dev	2	5194	2587
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	dev	2	5234	2633
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	te	2	5199	2611
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15598	7788
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15604	7801
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15610	7794
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15612	7808
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15623	7831
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15624	7807
23331	88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M		L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C	tr	2	15639	7797
88548371810148165870493436976020259913_mau2we.png	20150210	88548371810148165870493436976020259913	58566507537828054601015075993000320573	1955.0	M	nan	L	Manual review of DICOM fields	No	CR	PhilipsMedicalSystems	MONOCHROME2	0	['1', '1']	0.2000000029802	12	2047.0	4095.0	2140	1760	None	None	None	None	1806	['descendent aortic elongation', 'COPD signs']	C

```


**---**

## One example for helping to test
The tables that will be used to carry out the required model training are stored in one folder that contain the images. There are a total of 10 tables called "pneumo_dataset_balanced_x.tsv" where x takes values from 0 to 9. 
These files contain different partitions of the images and can be used individually or together if a "10-fold cross validation" is required. 

The most important data to take into account for the training phase are:

**Image ID:** name of the image file.

**StudyID:** study identifier.

**Patient ID:** patient identifier.

**Projection:** patient’s position when taking the radiography.

**Tags:** radiological findings found in the image.

**Group:** label of the class to which the image belongs. These labels can be:

* C - Control
* N - Pneumonia
* I - Infiltration
* NI - Pneumonia and infiltration

Partition: partition to which the image belongs. These values are:
* tr - Training
* dev - Development
* te - Test
## Run the code

To train the model example, you need to execute the following instruction:

python3 pneumo_cnn_classifier_training.py «FILE_TSV_BALANCED»


## RESULTS

|  Participant | Model name  | Dev Accuracy | Test Acuracy  | Comments  |
|---|---|---|---|---|
| rparedes  | first_model | xx  | xx  | using balanced-one-partition 200x200  |
|   |   |   |   |   |
|   |   |   |   |   |
