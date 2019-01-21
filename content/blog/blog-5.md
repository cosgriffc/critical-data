+++
title = "PLAGH-MIT Datathon"
date = "2019-01-09"
tags = ["datathon","MIT","PLAGH"]
categories = ["blog"]
banner = "img/blog/plagh.jpg"
+++

## A Deep Dive into an International Data Hackathon Collaboration – MIT Critical Data

_Generously contributed by Joel Park MD, FACEP_

With the implementation of Meaningful Use and electronic health record mandate, an unprecedented amount of patient data is being collected at high velocity, ranging from patient demographics to physician documentation and laboratory values. Similar to many other industries, many hospitals and organizations have been attempting to decipher and gain insight from their information. However, because of the complex and unstructured nature of healthcare data, deriving meaningful insight has been challenging and met with varying success. One group from MIT’s Laboratory of Computational Physiology, the MIT Critical Data team, have taken upon themselves to face this challenge.

For data science, machine learning, deep learning, and artificial intelligence to be successfully executed, a repository of “big medical data” is required. Unfortunately, for a multitude of reasons, having sufficient curated healthcare data is difficult to obtain and many healthcare organizations are hesitant to share data. Concerns for Patient Health Information (PHI) breach and HIPAA violations are legitimate as prior offenses have led to several million-dollar fines. Even if institutions are willing to share the data, the technical barriers can be significant and financially costly. It is not surprising that EHR interoperability continues to remain a persistent issue.

However, under the guidance of Drs. Roger Mark and Leo A. Celi, these physician-scientists and healthcare data scientists have successfully created an incredibly in-depth and sophisticated ICU database known as "Medical Information Mart for Intensive Care" or MIMIC-III. Utilizing the Harvard Beth Israel Deaconess Hospital electronic healthcare record system, over sixty thousand unique ICU admissions and their corresponding data values were successfully deidentified, wrangled, and deployed onto a cloud database. The database contains extensive information including continuous vital signs, laboratory values, radiology dictation reports, EKGs, physician progress notes, nursing notes, active medications, and so forth.

![](img/blog/joel-pic1.jpg)

Furthermore, the team is expected to release over 600 chest radiographs in their next iteration of MIMIC (being released in January 2019). Inspired by MIT LCP’s spirit of open data, Phillips had also contributed their private healthcare database, known as eICU, to supplement MIMIC. This impressive database contains over 200 hospitals including ICU, floor, and emergency room visits. The level of detail, attention, and depth of healthcare data is sure to be prime ground for a wealth of medical insight.

Currently, several thousand academic and industry researchers around the globe are accessing the database and have been executing an extensive amount of machine learning and deep learning research, which has ranged from real-time mortality risk prediction for sepsis, packed red blood cell transfusion prediction for anemic patients, and identification of factors leading to post-stroke complications. With the new addition of the radiographs, researchers will be given an exciting opportunity to trial deep learning and computer vision. For medical researchers who are interested in venturing into MIMIC, a request can be submitted to the [MIT LCP’s website](https://mimic.physionet.org). Information regarding SQL querying and boilerplate templates can be accessed via their [Github repository](https://github.com/MIT-LCP/mimic-code).

Though the MIMIC database is undeniably extraordinary, the more notable concept is how MIT Critical Data disseminates their database. The MIT Critical Data hosts these events called “Datathons,” or Data Hackathons, where clinicians are partnered with data scientists and engineers to collaborate on a medical research project. The clinician develops a pertinent and medically relevant research question and provides domain expertise to the data scientists. In turn, the data scientists will apply their extensive statistical and programming background to answer the question. The event typically takes over two to three days and usually has the spirit of a regular hackathon, i.e., late nights and a great deal of food and snacks. The datathon then concludes ceremoniously with the presentations of the teams’ findings. Because many of the teams accomplish a remarkable quantity of work, MIT Critical Data encourages the participants to continue working on their projects and submit them for publications (as many are often published).

![](/pic2.jpg)

Datathons are held typically monthly in different places around the world, including England, France, Mexico, Italy, South Korea, Thailand, Australia, Brazil, and the Philippines. The most recent datathon was at the beginning of this month (December 2018) at the People’s Liberation Army General Hospital (PLAGH) in Beijing, China. The organizers, Drs. Zhengbo Zhang and Peiyao Li had organized over 500 participants from numerous universities around China including many key leaders in their respective fields in medicine, statistics, and computer science. Ultimately, the event was wildly successful and well appreciated by the attendees.

![](/pic3.jpg)

Medicine should follow the same suit as the technology community and embrace the open-source concept. Serious research with data science, machine learning and deep learning require a significant amount of “big data.” I hope that healthcare organizations will one day soon realize the importance of big healthcare data research.

I also like to take time to thank the core contributors to the MIMIC Database for all of their hard work: Dr. Alistair Johnson, Lu Shen, and Chen Xie.