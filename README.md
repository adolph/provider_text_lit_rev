# A review of provider targeted mobile device messaging literature

## Introduction/Background

The Electronic Health Record system is not just a passive recorder of health care provider inputs, but also acts as a communication mechanism among providers for care coordination and from decision support systems to providers. The latter often take the form of alerts when the provider is actively using the EHR. The former typically appear similarly to email messages where the messages appear in a single place and link out to different records to activities for the provider to complete.

The rise of the EHR as locus of activity has occurred at the same time as the diffusion of mobile phones. Despite the coincidence, use of mobile messaging by providers is often limited to replication of the time honored pager, with little integration to the EHR (Hagedorn et al. 2019). However, the mobile device has capabilities for much more. Despite the heavy usage of mobile device messaging documented by Hagedorn at al. and clearly visible everywhere, there are no systematic reviews of integrations between EHRs and mobile messaging, which makes this review novel.

There is a recent effort by an academic medical institution to leverage mobile devices for urgent but asynchronous alerts. Known as “same day second signatures” these represent infusion therapy orders that are signed right before the patient arrives for treatment. The providers wait to sign until after the patient’s pre-treatment lab results are ready. Each order is signed by two providers who each perform an independent review of the results and dosing. This is performed in between treating other patients during the day and as a result the two signing providers may not be able to speak to one another immediately to prompt the second signature. This communication is often performed by yellow sticky notes or other means. While EHR inbox messages are generated, the urgent messages are undifferentiated from routine messages and are not helpful for understanding which patients face a delay in care without swift action.

## Hypothesis/Research Question

To better understand if this effort is worth documenting in the literature, this systematic review of how text messaging has been characterized in the literature has been undertaken. What literature exists to support the efficacy of and describe concerns about provider alerting from the EHR using mobile device messaging?

## Method

The search procedure was to search PubMed with MeSH terms, analyze the resulting abstracts and take note of articles germane to the research question.
The PubMed search performed was for the last 10 years of freely available English language literature with MeSH keywords of “Health Personnel” and “text messaging.”

A spreadsheet of resulting articles was coded for population, intervention, direction and message type through qualitative analysis of the article abstracts.

This was filtered by provider population with text message intervention and the results tabulated by pivot table.

## Data Results

### PubMed Search String

  (
    "Health Personnel"[MeSH Terms] AND
    "text messaging"[MeSH Terms] ) AND
    "2012/01/01 00:00":"3000/01/01 05:00"[Date - Publication] AND
    (
      (y_10[Filter]) AND
      (ffrft[Filter]
    )
  )

Search results and qualative coding [available in this csv](csv-search-results-coded.csv).

### Count of Results by Messaging Target

| Target of Messaging | Count of Articles |
| ------------------- | ---------------- |
| Patient | 92 |
| Provider | 55 |
| N/A | 17 |
| Total | 164 |

### Provider Messages by Direction and Type

| Direction | Alert | Education | Both | Data | Decision Support | N/A |
| --------- | ----- | --------- | ---- | ---- | ---------------- | --- |
| To | 8 | 14 | 1 | 1 | 0 | 0 |
| From | 0 | 0 | 0 | 1 | 0 | 0 |
| 2-way | 2 | 4 | 9 | 6 | 1 | 0 |
| N/A | 0 | 0 | 0 | 0 | 0 | 4 |
| Total | 10 | 18 | 10 | 8 | 1 | 4 |

## Limitations

This review was limited to freely available English language literature. Given the number of articles referencing efforts in Africa and the earlier uptake of text messages outside the United States, there may be significant literature in other languages germane to this topic.

Additionally, the search was limited to articles indexed in PubMed. This should capture the larger part of literature about text messages sent to providers from EHRs. However, some articles may exist in information technology focused journals that would be helpful in understanding the efforts of other health care systems.

## Future Research

This review suggests publishing an article about results from implementing a same day second signature text message alert system.

Additionally literature characterizing:
 - How text messaging fits within other methods and
 - The regulatory information security dimensions of text messaging and
 - How text messaging can add to alert fatigue

## Conclusion

Cuencain 2016 and Simon et al. in 2019 found that text messages were an effective method of reaching health care providers. Analysis of messages sent between providers by Hagedorn et al in 2019 show that over a three week period providers text message with about a dozen others at a rate of 2-3 an hour. Beyond effectiveness and use, Barry et al. 2020 found that providers welcomed significant and personalized alerts via text message since they were interested in taking action on the alerted information. However, the results of experiments performed by Baseman et al. in 2013 “suggest that information delivered too frequently and/or repetitively through numerous communication channels may have a negative effect on the ability of health care providers to effectively recall emergency information.” As a significant channel of communication, text messages deserve further research.

## Citations

 - Hagedorn, P. A., Kirkendall, E. S., Spooner, S. A., & Mohan, V. (2019). Inpatient Communication Networks: Leveraging Secure Text-Messaging Platforms to Gain Insight into Inpatient Communication Systems. Applied Clinical Informatics, 10(3), 471–478. https://doi.org/10.1055/s-0039-1692401
 - Cuenca, A. E. (2016). Instant Messaging: A Simple Tool to Improve Teamwork and Wait Times. Family Practice Management, 23(5), 28–30.
 - Simon, L. E., Rauchwerger, A. S., Chettipally, U. K., Babakhanian, L., Vinson, D. R., Warton, E. M., Reed, M. E., Kharbanda, A. B., Kharbanda, E. O., & Ballard, D. W. (2019). Text message alerts to emergency physicians identifying potential study candidates increase clinical trial enrollment. Journal of the American Medical Informatics Association: JAMIA, 26(11), 1360–1363. https://doi.org/10.1093/jamia/ocz118
 - Barry, T., Guerin, S., Headon, M., & Bury, G. (2020). GPs who volunteer to be first responders for out-of-hospital cardiac arrest: A qualitative study. The European Journal of General Practice, 26(1), 33–41. https://doi.org/10.1080/13814788.2019.1681194
 - Baseman, J. G., Revere, D., Painter, I., Toyoji, M., Thiede, H., & Duchin, J. (2013). Public health communications and alert fatigue. BMC Health Services Research, 13, 295. https://doi.org/10.1186/1472-6963-13-295

