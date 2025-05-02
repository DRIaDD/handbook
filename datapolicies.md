---
layout: default
title: Data policies
subtitle: 
---

## Data policies

Make sure your data is backed up, either to a cloud server or a hard drive or both. Options to backup your laptop include:
For Mac users, Time-machine: [https://support.apple.com/en-gb/HT201250](https://support.apple.com/en-gb/HT201250).

Make sure you find out and follow any restrictions on how your data is used and stored. As a lot of our research is using secondary data, you should defer to the data owner. In many cases, data may need to be stored on a specific server which you will need to access remotely.

If you are collecting data, write a data management plan prior to collection (and adhere to it!) This will include things like where the data is stored, the format it will be stored in how it can be shared, how it will be analysed, and any other relevant information.  

If you are able to, in the spirit of open science, it is good to share as much of your data as possible, either via a GitHub, Zenodo, or another repository. This may also be a requirement of the journal in which you are publishing. But always check that you are allowed to share the data and / or that it has been suitably anonymized before doing so. Similar principles apply to sharing of code - see the Rigour / reproducibility section for help and information on sharing code, including the use of repositories such as GitHub.

Be aware of different open-access data depositories for different type of data, for instance, for instance, the "[GenBank](https://www.ncbi.nlm.nih.gov/genbank/)" (NIH genetic sequence database) for genomic data, and make sure they are aligning with funder's requirements and policies.

If you are not able to share your data due to restrictions on how it is shared, a good alternative in some cases is to create a synthetic dataset (i.e., fabricated data, but with some of the same features as the real data-set like age- and sex-structure). This will allow people to run your model code. IBM provides some useful information about synthetic data sets [here](https://www.ibm.com/topics/synthetic-data). The Julia package [SyntheticDatasets.jl](https://juliapackages.com/p/syntheticdatasets) and the R package [synthpop](https://cran.r-project.org/web/packages/synthpop/) can help you to make synthetic datasets.

Data dictionaries: It is good practice to create a data dictionary, especially for complex datasets, which describes the meaning of the data and each field, its relationship to other datasets, how it can be used, and any other relevant information. [Useful resource about creating data dictionaries](https://help.osf.io/article/217-how-to-make-a-data-dictionary)/

Data anonymization. It may be necessary to anonymize your data before sharing it or storing it. One approach could be to remove any personal identifiable information from the dataset. Fully "anonymised data" means individuals are no longer identifiable (for details please refer to [https://www.dataprotection.ie/en/dpc-guidance/anonymisation-pseudonymisation](https://www.dataprotection.ie/en/dpc-guidance/anonymisation-pseudonymisation)). A similar approach is pseudonymization, which instead replaces identifiable data with fake identifiers, thereby making the data anonymous, but potentially allowing it to be de-anonymized later. Another approach is to create a synthetic dataset, described above, which retains the properties of the dataset but none of the actual data. The university provides some useful resources relating to data anonymization [here](https://researchdata.ox.ac.uk/uk-anonymisation-network). 

Hard-drive encryption. The university strongly recommends you set up disk encryption on your devices, and has some resources and recommended programmes for doing so [here](https://www.infosec.ox.ac.uk/encryption). In addition to the university-recommended resources, a highly-regarded cross-platform disk encryption program is [VeraCrypt](https://www.veracrypt.fr/en/Home.html). 

Computer clusters. The university has two high-performance clusters: [Advanced Research Computing](http://arc.ox.ac.uk/) (ARC) and B[iomedical Research Computing](https://www.medsci.ox.ac.uk/for-staff/resources/bmrc) (BMRC). We currently have a basic account with ARC (account name is trop-driadd), and are in the process of setting up an account with the BMRC. Though their main benefit is running very large or parallel programs, these clusters are also secure places to store large datasets. Speak to Sean or Ben if you want to get a personal account on one of these clusters. 

University training course on information security. Please note that to retain access to NHS data, NDM needs to meet a completion rate threshold of the "Information Security" training each year. We are obligated to complete the course. The course only takes 10 minutes to complete and the department will get weekly reports of who has and has not completed the training. Please visit [www.infosec.ox.ac.uk/module](www.infosec.ox.ac.uk/module) to "Book the online Course" and follow through the instructions on the website to register. You will receive an email with details on how to complete the course. 

### Some useful links

* The website [www.privacyguides.org](http://www.privacyguides.org) provides a set of recommendations for device and software privacy and security. The advice does tend to be quite severe, but is useful if you have very sensitive data or are very privacy-conscious.

* The University's data protection policy is detailed [here](https://compliance.admin.ox.ac.uk/data-protection-policy). This is described in more detail in the Good practice / GDPR section.
