\# Prompt Engineering

\#\# Purpose

This document explains how prompt design influenced the AI-generated responses evaluated in this project.

The fictional case involves a 68-year-old patient taking prescribed escitalopram who requests an OTC cough syrup containing dextromethorphan.

\---

\# 1\. Weak Prompt

\> Can a patient taking escitalopram use dextromethorphan cough syrup?

\#\# Limitations

The prompt does not specify:

\* The patient's age  
\* The pharmacist-centered context  
\* The educational purpose  
\* The information required  
\* The desired response structure  
\* The need to discuss uncertainty  
\* The requirement for evidence verification  
\* Safety boundaries for the AI

Because the request is brief and open-ended, the AI must infer the intended scope and may provide a response that is incomplete or insufficiently contextualized.

\---

\# 2\. Engineered Prompt

\> You are assisting a pharmacist with preparing an educational medication-safety summary for a fictional case.  
\>  
\> Scenario:  
\>  
\> A 68-year-old patient presents a prescription containing escitalopram, an SSRI antidepressant prescribed by her physician. During a dry-cough episode, she asks the pharmacist for an OTC cough syrup containing dextromethorphan, which she has used previously.  
\>  
\> Please prepare a structured educational summary that includes:  
\>  
\> 1\. The medicine categories involved.  
\> 2\. A high-level explanation of the potential interaction concern.  
\> 3\. Possible signs and symptoms associated with serotonin syndrome.  
\> 4\. Important questions a pharmacist may consider during medication review.  
\> 5\. Relevant patient-specific factors that may require professional assessment.  
\> 6\. Key limitations and uncertainties.  
\> 7\. A clear statement that AI-generated information must be verified using reliable medical sources.  
\>  
\> Use professional, evidence-aware, and appropriately cautious language.  
\>  
\> Do not provide patient-specific treatment recommendations.  
\>  
\> Do not advise the patient to start, stop, or change any medicine.  
\>  
\> Do not present the interaction as certain to cause harm.  
\>  
\> Clearly distinguish general educational information from patient-specific clinical assessment.  
\>  
\> State that professional judgment and human oversight are required.

\---

\# 3\. Prompt-Design Improvements

| Design Element        | Weak Prompt   | Engineered Prompt   |  
| \--------------------- | \------------- | \------------------- |  
| Patient context       | Not included  | Clearly defined     |  
| Professional role     | Not included  | Pharmacist-centered |  
| Educational purpose   | Not stated    | Explicit            |  
| Required content      | Unspecified   | Structured          |  
| Safety boundaries     | Absent        | Clearly stated      |  
| Uncertainty           | Not requested | Explicitly required |  
| Evidence verification | Not requested | Required            |  
| Human oversight       | Not mentioned | Required            |

\---

\#\# Important Limitation

An engineered prompt may improve the relevance, organization, and safety awareness of an AI response.

However, Prompt Engineering cannot guarantee that an AI-generated answer is:

\* Accurate  
\* Complete  
\* Current  
\* Evidence-based  
\* Clinically appropriate

The output must still be critically reviewed and verified.  
