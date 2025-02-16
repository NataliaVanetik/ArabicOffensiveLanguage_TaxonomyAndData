# ArabicOffensiveLanguage_TaxonomyAndData
This repository contains existing offensive language datasets in Arabic re-annotated in accordance with a new taxonomy of Arabic offensive language.
This is a collaborative effort of N. Vanetik, A. Al-Afawi, M. Litvak, and C. Liebeskind.

DISCLAIMER: It is our purpose to advance the research in the area of detecting offensive language in Arabic. The datasets may contain ome examples of offensive content that may target specific individuals or groups.
This is strictly for the purposes of enabling this research, and we have sought to minimize the number of examples where possible. Please be aware that this content could be offensive and cause you distress.

There are total of 14 existing datasets that are contained in this repository.
We supply here the list of files and their origin (papers that describe and introduce them). All of the datasets were made publically available by their respective authors at the time of their publication.
Note that dataset IDs do not contain 1 and 13, and this is intentional. 

| Dataset | Paper |
|-----------------------------------:|---------------|
|arabic_off_lang_dataset_ID2.xlsx    |  Ousidhoum, Nedjma, Zizheng Lin, Hongming Zhang, Yangqiu Song & Dit-Yan Yeung. 2019. Multilingual and multi-aspect hate speech analysis. arXiv preprint arXiv:1908.11049.  |
| arabic_off_lang_dataset_ID3.xlsx   | Mulki, Hala, Hatem Haddad, Chedi Bechikh Ali & Halima Alshabani. 2019. L-HSAB: a Levantine Twitter dataset for hate speech and abusive language. In Proceedings of the third workshop on abusive language online, 111–118. Alakrot, Azalden, Liam Murray & Nikola S Nikolov. 2018. Dataset construction for the detection of anti-social behaviour in online communication in arabic. Procedia Computer Science 142. 174–181. |
| arabic_off_lang_dataset_ID4.xlsx   |  Alakrot, Azalden, Liam Murray & Nikola S Nikolov. 2018. Dataset construction for the detection of anti-social behaviour in online communication in Arabic. Procedia Computer Science 142. 174–181. |
| arabic_off_lang_dataset_ID5.xlsx   | Zampieri, Marcos, Preslav Nakov, Sara Rosenthal, Pepa Atanasova, Georgi Karadzhov, Hamdy Mubarak, Leon Derczynski, Zeses Pitenis & Ça˘ grı Çöltekin. 2020. Semeva-2020 task 12: multilingual offensive language identification in social media (offenseval 2020). arXiv preprint arXiv:2006.07235.              |
| arabic_off_lang_dataset_ID6.xlsx   | Mubarak, Hamdy, Kareem Darwish & Walid Magdy. 2017. Abusive language detection on Arabic social media. In Proceedings of the first workshop on abusive language online, 52–56. |
| arabic_off_lang_dataset_ID7.xlsx   |  Mubarak, Hamdy, Kareem Darwish & Walid Magdy. 2017. Abusive language detection on Arabic social media. In Proceedings of the first workshop on abusive language online, 52–56. |
| arabic_off_lang_dataset_ID8.xlsx   |  Haddad, Hatem, Hala Mulki & Asma Oueslati. 2019. T-HSAB: a Tunisian hate speech and abusive dataset. In International conference on Arabic language processing, 251–263. |
| arabic_off_lang_dataset_ID9.xlsx   |  Chowdhury, Shammur Absar, Hamdy Mubarak, Ahmed Abdelali, Soon-gyo Jung, Bernard J Jansen & Joni Salminen. 2020. A multi-platform Arabic news comment dataset for offensive language detection. In Proceedings of the twelfth language resources and evaluation conference, 6203–6212.            |
| arabic_off_lang_dataset_ID10.xlsx   | Abdelhakim, Mohamed, Bingquan Liu & Chengie Sun. 2023. Ar-pufi: a short-text dataset to identify the offensive messages towards public figures in the Arabian community. Expert Systems with Applications. 120888. |
| arabic_off_lang_dataset_ID11.xlsx   |  Essefar, Kabil, Hassan Ait Baha, Abdelkader El Mahdaouy, Abdellah El Mekki & Ismail Berrada. 2023. OMCD: offensive Moroccan comments dataset. Language Resources and Evaluation. 1–21. |
| arabic_off_lang_dataset_ID12.xlsx   | Aref, Abdullah, Rana Husni Al Mahmoud, Khaled Taha, Mahmoud Al-Sharif, et al. 2020. Hate speech detection of Arabic shorttext. In CS IT Conf. proc, vol. 10, 81–94. |
| arabic_off_lang_dataset_ID14.xlsx   | Mulki, Hala & Bilal Ghanem. 2021. Let-Mi: an Arabic Levantine Twitter dataset for misogynistic language. arXiv preprint arXiv:2103.10195.  |
| arabic_off_lang_dataset_ID15.xlsx   | Litvak, Marina, Natalia Vanetik, Yaser Nimer, Abdulrhman Skout. 2021. Offensive language detection in semitic languages. In Multimodal hate speech workshop, vol. 2021, 7–12. |
| arabic_off_lang_dataset_ID16.xlsx   |  Alhazmi, Ali. 2023. Hate Speech Dataset for the Saudi Dialect. Mendeley Data. Version V1. https://doi.org/10.17632/c2jpnv9yk6.1. |


All the datasets have been re-organized in accordance to our new Arabic Offensive Language Taxonomy (published in [1]). Because not all of the data has existing annotations for all of the taxonomy level, in these cases 'null' indicates 'no annotation'.
We also specify dialect of every dataset, if it could be determined; if no specific dialect can be identified or the texts are in Modern Standard Arabic (MSA), the corresponding column contains 'null'.
We did not modify the data in any way, and did not clean it - the data may contain non-Arabic characters, emojis, or even full texts in languages other than Arabic.

[1] Liebeskind, C., Afawi, A., Litvak, M. and Vanetik, N., 2024. Classifying offensive language in Arabic: a novel taxonomy and dataset. Lodz Papers in Pragmatics, (0).

To evaluate the datasets further, we unified datasets that are written in MSA (datasets with IDs 2,4,7,9,12) and excluded those that contain a specific dialect or mix of dialects. 
The data is contained in the joint-MSA-dataset-level-1.xlsx file.
