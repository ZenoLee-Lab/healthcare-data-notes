# **From Routinely Collected Healthcare Data to Big Data for Health Research**

## ***An Introduction to Korea’s Health Insurance Claims Data***

This article draws on published research and official guidance.

# **1\. How Can We Gather the Data Needed for Health Research?**

Among the medications and treatments used for the same condition, which are more effective? Does long-term use of a particular medication increase the risk of adverse effects or other diseases? How do these treatment benefits and risks vary according to patients’ physical characteristics, existing conditions, and treatment histories?

Launching a new clinical trial or long-term follow-up study to answer these questions presents several challenges. Participants must consent voluntarily and remain involved, and recruiting enough people can be difficult. Assigning medications requires participants’ consent, safeguards for their safety, and ethical justification; researchers cannot simply ask people to take a particular drug at will for a study. Observing long-term treatment effects or diseases that occur infrequently may also take considerable time. Gathering and verifying participants’ medical and treatment histories, use of other medications, lifestyle habits, and other factors that may influence outcomes also requires substantial time and effort.

Could records already accumulated through routine care offer another way to investigate these questions? Researchers could examine care that has already taken place and subsequent outcomes without assigning new treatments. Korea’s health insurance claims data offer one way to use such routine healthcare records for research.\[1\]

# **2\. How Korea’s Health Insurance System Generates Nationwide Data**

South Korea’s National Health Insurance (NHI) is a single public health insurance system. It is administered by the National Health Insurance Service (NHIS) and covers most of the population. Contributions vary according to income and other measures of ability to pay, while public assistance helps people with low incomes and other eligible groups afford medical care. Paying higher contributions does not entitle someone to a higher tier of insurance benefits. People covered by NHI can receive care under common benefit rules at participating healthcare facilities nationwide, beyond their area of residence.

When healthcare providers submit claims for covered services, the Health Insurance Review and Assessment Service (HIRA) reviews them, and the NHIS pays providers based on the review results. Through this process, data on healthcare use by most of the population accumulate nationwide, creating a foundation for research.\[1\]

# **3\. How Are Claims Data Structured and Linked?**

Research data are not necessarily provided as a single, complete table for each patient. A single claim may be divided across tables containing treatment details, diagnoses, and prescriptions. Researchers use a unique claim identifier to link the relevant tables. A separate research identifier allows multiple healthcare records belonging to the same person to be linked.\[1\]

Identifiers for the same claim and identifiers for the same person serve different purposes. Because a claim can contain multiple diagnoses and medications, simply joining tables can multiply rows and lead to double counting. Combining the tables correctly is therefore important.\[5\]

Data that support linking individual records over time allow researchers to examine healthcare histories before a medication was prescribed and subsequent hospitalizations or diagnoses. Accumulated claims records can support long-term follow-up without researchers contacting participants at every stage.\[1\]

Researchers also use these records to define study populations. For example, they may combine diagnosis codes and medication prescriptions to identify patients with a particular condition.\[1,2\]

Information missing from claims data can be supplemented by linking them with other health data. One example is data from the national health screening program administered by the NHIS. These screenings collect information such as body weight, blood pressure, blood test results, and responses to lifestyle questionnaires. Linking these data with the same individuals’ claims records allows researchers to examine associations between their health at screening and subsequent diagnoses, hospitalizations, and treatment.

Data from the Korea National Health and Nutrition Examination Survey (KNHANES), conducted by the Korea Disease Control and Prevention Agency (KDCA), can also be linked with claims records. KNHANES collects information on the health, health behaviors such as smoking and alcohol consumption, dietary habits, and nutrient intake of a sample of the population. For participants who consent to linkage and whose records can be linked, researchers can examine associations between the lifestyle or nutritional information collected in the survey and subsequent healthcare use. Such linkage is subject to the required application and review procedures.

Linking these sources allows researchers to consider health and lifestyle information that is difficult to capture through claims data alone. Because KNHANES is a sample survey, these analyses concern the participants whose records are linked; the linkage does not provide dietary information for the entire population.

The ability to link individuals’ healthcare records makes it important to consider who can access these data and under what conditions.

# **4\. How Is Personal Information Protected?**

The availability of patients’ healthcare records for research does not mean that anyone can access them. **To use HIRA’s customized research data, researchers must first submit an application describing their research purpose and the scope of data needed, undergo review, and obtain approval.**\[3,4\]

The data made available to researchers are processed so that direct identifiers, such as names and resident registration numbers, are not visible. Instead, research identifiers allow records belonging to the same person to be linked without directly revealing that person’s identity.

Approved researchers analyze the data using designated computers at an analysis center or a remote analysis system. Taking analysis results out of this environment requires **a separate export application and review**.\[3,4\]

These safeguards allow the data to be used for research while protecting personal information.

# **5\. Long-Term Follow-up and Health Information: Research Applications**

**Examining Weight Changes and Subsequent Dementia**

Are substantial weight changes in later life associated with the likelihood of a subsequent dementia diagnosis? One study explored this question using records from approximately 67,000 adults aged 60–79 in the NHIS Health Screening Cohort.

The researchers assessed changes in body mass index between two national health screenings conducted during 2002–2005 and followed dementia occurrence through healthcare records from 2008 to 2013\. Their analysis accounted for age, income, smoking, alcohol consumption, physical activity, and conditions including hypertension, diabetes, and heart disease. In other words, they statistically adjusted for factors other than weight change that could be associated with dementia occurrence.\[6\]

This example shows how linking health information collected at screening with subsequent healthcare records can support research on health changes over time without recruiting new participants.

**Examining Smoking History and Cardiovascular Disease After Quitting**

How does cardiovascular disease risk among former smokers vary with their past smoking exposure and the time since they quit? A study published in 2024 investigated this question using health screening and healthcare records from approximately 5.39 million people in the NHIS database.

The researchers used national health screening questionnaires to assess smoking exposure and time since quitting, then followed the occurrence of conditions including myocardial infarction, stroke, and heart failure. They excluded people with pre-existing cardiovascular disease and adjusted their analysis for age, sex, income, body mass index, underlying conditions such as hypertension and diabetes, alcohol consumption, and exercise.\[7\]

This study shows how researchers can examine associations between smoking histories formed in everyday life and subsequent health outcomes without assigning people to smoke for research purposes.

Both examples demonstrate how researchers can examine past health information and healthcare histories, follow subsequent disease occurrence, and account for differences between groups in their analyses.

# **6\. What Advantages Do These Data Offer for Population Health Research?**

Korea’s health insurance claims data offer several advantages for studying health and healthcare across a large population.

* **They allow researchers to examine healthcare use across a broad population.**

Nationwide data provide a foundation for studying people of different ages and from different regions. They also allow researchers to investigate patterns of disease and treatment that may be difficult to capture using records from a single healthcare institution.\[1\]

* **They bring together records across healthcare institutions and over time.**

Linking individual records allows researchers to examine care received at different healthcare institutions and changes over time. This helps them identify past medical conditions and treatment histories and follow subsequent disease occurrence or hospitalizations over extended periods.\[1\]

* **They can save time and costs by making use of existing records.**

Rather than recruiting new participants and collecting data from scratch, researchers can use records accumulated during routine care. Another advantage is that information about past care does not have to rely solely on individuals’ memories.\[1\]

* **They can broaden the scope of research through linkage with other data.**

Linking claims records with sources such as national health screening data or KNHANES can supplement information on health status and lifestyle that is limited in claims data. This enables researchers to address a wider range of questions and account for differences between groups, including age, underlying conditions, and lifestyle factors, in their analyses.

Together, these advantages help researchers understand population health, disease, and treatment patterns using records of routine healthcare use.

# **7\. What Are the Limits of What Claims Data Can Tell Us?**

However, because these records are collected for insurance claims, they cannot capture every aspect of a patient’s health or treatment.

* **Prescription and dispensing records do not establish actual medication use.**

Even when someone collects medication from a pharmacy, it is difficult to verify directly how much they take or how consistently they take it. Dispensing dates and prescribed days of supply can be used to estimate medication persistence, but this is not the same as observing actual use.\[1\]

* **Not all clinical information is included.**

Even when a prescription or test is recorded, claims data alone may not reveal how much blood pressure or blood glucose subsequently improved. Information on disease severity, symptoms, and lifestyle may also be limited. Body weight, for example, is obtained from sources such as health screening data; it is not routinely available in claims data.\[1,2\]

* **Diagnosis codes may not fully reflect a person’s actual clinical condition.**

Diagnoses recorded for billing may differ from the clinical conditions researchers want to study. Researchers therefore need to consider diagnoses, medications, and procedures together when defining patient groups and assess the validity of those definitions.\[1,2\]

* **Information outside the claims system may be missing.**

Information not included in insurance claims, such as non-covered care, is difficult to capture. The absence of healthcare use or a record in the data should not automatically be interpreted as the absence of disease or symptoms. There is also a delay between the delivery of care and the availability of the corresponding data for research.\[1\]

* **Confounding cannot be completely eliminated.**

People prescribed a particular medication may be older or have more underlying conditions than those who are not. These characteristics, as well as the medication itself, may influence differences in subsequent health outcomes.

Researchers can adjust for differences using recorded information such as age and prior diagnoses, but the influence of unrecorded disease severity or lifestyle factors may remain.\[1\]

A large dataset therefore does not, by itself, guarantee accurate results or establish causality. Appropriate study design, analysis, and careful interpretation are also essential.

# **8\. What Is Possible in the United States? Current Conditions and Questions for Further Exploration**

Learning about Korea’s experience has led me to consider how broader linkage of routine healthcare records could help address questions that would be difficult to study by recruiting new participants. In particular, the ability to examine past healthcare histories alongside subsequent outcomes is valuable for long-term population health research.

Next, I would like to explore what claims databases and health data linkage infrastructure already exist in the United States, as well as the institutional and technical barriers to linking records across organizations. Another question is how to protect personal information while allowing researchers to continue using the data they need.

Building on Korea’s experience, I hope to explore how data infrastructure in the United States could be developed further to support broader and sustained population health research.

# **References**

1\. Kim S, Kim MS, You SH, Jung SY. Conducting and Reporting a Clinical Research Using Korean Healthcare Claims Database. Korean J Fam Med. 2020;41(3):146–152. https\://doi.org/10.4082/kjfm.20.0062

2\. Kyoung DS, Kim HS. Understanding and Utilizing Claim Data from the Korean National Health Insurance Service (NHIS) and Health Insurance Review & Assessment (HIRA) Database for Research. J Lipid Atheroscler. 2022;11(2):103–110. https\://doi.org/10.12997/jla.2022.11.2.103

3\. Health Insurance Review and Assessment Service. Healthcare Big Data Open System: Customized Research Data Guide. Accessed November 25, 2026\. https\://opendata.hira.or.kr/op/opb/selectHelhMedDataInfoView.do

4\. Health Insurance Review and Assessment Service. Customized Research Analysis User Guide (in Korean). https\://opendata.hira.or.kr/

5\. Kim JA, Yoon S, Kim LY, Kim DS. Towards Actualizing the Value Potential of Korea Health Insurance Review and Assessment (HIRA) Data as a Resource for Health Research: Strengths, Limitations, Applications, and Strategies for Optimal Use of HIRA Data. J Korean Med Sci. 2017;32(5):718–728. https\://doi.org/10.3346/jkms.2017.32.5.718

6\. Park S, Jeon SM, Jung SY, Hwang J, Kwon JW. Effect of late-life weight change on dementia incidence: a 10-year cohort study using claim data in Korea. BMJ Open. 2019;9:e021739. https\://doi.org/10.1136/bmjopen-2018-021739

7\. Cho JH, Shin SY, Kim H, et al. Smoking Cessation and Incident Cardiovascular Disease. JAMA Netw Open. 2024;7(11):e2442639. https\://doi.org/10.1001/jamanetworkopen.2024.42639

# **Official Sources: Health Insurance System**

* National Health Insurance Service. Health Security System. https\://www\.nhis.or.kr/english/wbheaa02300m01.do  
* National Health Insurance Service. Insurance Benefits. https\://www\.nhis.or.kr/english/wbheaa02600m01.do  
* National Health Insurance Service. Healthcare Benefits and Procedures (in Korean). https\://www\.nhis.or.kr/static/html/wbma/c/wbmac0102.html

# **Official Sources: Data Linkage**

* Korea Disease Control and Prevention Agency. National Health Screening (in Korean). https\://health.kdca.go.kr/healthinfo/biz/health/gnrlzHealthInfo/gnrlzHealthInfoView.do?cntnts\_sn=6671  
* Korea Disease Control and Prevention Agency. Use of National Health Survey Results (in Korean). https\://kdca.go.kr/kdca/3369/subview.do  
* Korea Disease Control and Prevention Agency. [2023 KDCA White Paper](https://www.kdca.go.kr/sites/kdca/download/2023%2B%EC%A7%88%EB%B3%91%EA%B4%80%EB%A6%AC%EC%B2%AD%2B%EB%B0%B1%EC%84%9C_%ED%8E%BC%EC%B9%A8.pdf) (in Korean).
