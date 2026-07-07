## Section 1: System Description and Classification

## System Description

\*\*System Name:\*\* TalentScreen AI

\*\*System Description:\*\* An AI-powered resume screening tool that uses natural language processing (NLP) to analyze, rank, and filter job applications. It assigns each candidate a suitability score (0–100) and automatically advances candidates above a predefined threshold to the interview stage.

\*\*Intended Purpose:\*\* Recruitment and selection of job applicants by analyzing and filtering resumes and evaluating candidate suitability.

\*\*EU AI Act Classification:\*\* High-Risk (Annex III, Area 4(a): AI systems intended to be used for the recruitment or selection of natural persons, including analyzing and filtering job applications and evaluating candidates.)

\*\*Applicable Obligations:\*\*  
\- Article 9 – Risk Management System  
\- Article 10 – Data Governance  
\- Articles 13–14 – Transparency and Human Oversight  
\- Article 26(7) – Information to Workers and Their Representatives

TalentScreen AI is designed to improve recruitment efficiency by reducing the time required to review large volumes of applications. Because it directly influences employment opportunities, errors or biases in the system could significantly affect applicants' careers and expose organizations to legal, ethical, and reputational risks. Consequently, robust governance, transparency, and ongoing monitoring are essential throughout its lifecycle.

## Section 2: Stakeholder and Context Mapping (NIST AI RMF MAP)

\#\# Stakeholder and Context Mapping

\#\#\# Primary Users (Deployers)  
\- HR Teams  
\- Hiring Managers  
\- Talent Acquisition Specialists

\#\#\# Affected Individuals  
\- Job applicants  
\- Candidates from protected groups (gender, age, ethnicity, disability status, etc.)

\#\#\# Organizational Context  
The organization uses TalentScreen AI to process high volumes of job applications while improving recruitment efficiency and consistency. The system is intended to support—not replace—human decision-making.

\#\#\# Deployment Setting  
Integrated into the organization's Applicant Tracking System (ATS) as the first-stage screening tool before human review.

\#\#\# Applicable Laws and Standards  
\- EU AI Act  
\- GDPR  
\- National Anti-Discrimination Laws  
\- Organizational Diversity, Equity and Inclusion (DEI) Policies

\#\# Benefits

\- Faster processing of large numbers of applications  
\- Consistent initial screening criteria  
\- Reduced recruitment costs  
\- Reduced time-to-hire  
\- Improved recruiter productivity

\#\# Potential Harms

\- Discriminatory filtering based on proxy characteristics  
\- Historical bias reproduced through training data  
\- Lack of transparency for rejected applicants  
\- Privacy risks from processing sensitive personal information  
\- Reduced employment opportunities for marginalized groups  
\- Reputational and legal risks for employers

Although TalentScreen AI offers significant operational benefits, its deployment requires careful governance to ensure fairness, accountability, transparency, privacy, and compliance with applicable regulations. Continuous monitoring is essential to prevent discriminatory outcomes and maintain stakeholder trust.

## Section 3: Risk Measurement and Evaluation (NIST AI RMF MEASURE)

## \#\# Identified Risks by Trustworthiness Characteristic

\#\#\# Fairness and Bias (MEASURE 2.11)  
The system may discriminate against candidates from underrepresented groups because the training data reflects historical hiring decisions that contain bias.

\#\#\# Transparency and Accountability (MEASURE 2.8)  
Candidates may not understand why they were rejected because the AI scoring process is not easily explainable.

\#\#\# Privacy (MEASURE 2.10)  
The system processes sensitive personal information, creating risks if unnecessary data is collected or retained.

\#\#\# Validity and Reliability (MEASURE 2.5)  
The model may perform well for some job roles but poorly for others, resulting in inconsistent hiring decisions.

\#\#\# Safety (MEASURE 2.6)  
Incorrect large-scale rejection of qualified applicants could significantly harm livelihoods and organizational reputation.

\#\#\# Security and Resilience (MEASURE 2.7)  
Attackers may manipulate resumes or exploit vulnerabilities to influence candidate rankings or compromise the system.

\#\#\# Model Drift (MEASURE 2.5)  
Over time, changes in applicant populations or job requirements may reduce model accuracy if the system is not regularly monitored and retrained.

## \#\# Prioritized Risk Summary

\#\# Prioritized Risk Summary

RISK-001 (Bias) and RISK-002 (Transparency) received the highest scores (20/25) because historical hiring data frequently contains bias, and AI-driven scoring models can be difficult to explain. These risks have the greatest potential to negatively affect applicants, particularly individuals from underrepresented or protected groups.

The interaction between bias and limited transparency compounds the overall risk. Candidates who experience discriminatory outcomes may be unable to understand or challenge the decisions because the reasoning behind the AI's recommendations is not sufficiently explainable. Addressing both fairness and transparency should therefore be the organization's highest priority before deployment.

## Section 4: Risk Treatment and Mitigation Controls (NIST AI RMF MANAGE)

\#\# High-Priority Risk Treatment

\#\#\# RISK-001 – Bias (Risk Score: 20\)

The organization should perform regular fairness audits using disaggregated performance metrics across protected characteristics. Training data should be reviewed and balanced before each model update, and disparate impact testing should be completed before deployment. Responsibility for implementing these controls rests with the AI Development Team before initial deployment, supporting compliance with Article 9 of the EU AI Act.

\#\#\# RISK-002 – Transparency (Risk Score: 20\)

Candidates should receive meaningful explanations describing how their applications were evaluated, while the organization should publish high-level information about the AI system's decision-making process. HR Compliance should implement these measures within 30 days of deployment to support Articles 13–14 of the EU AI Act relating to transparency and human oversight.

\#\#\# RISK-005 – Safety (Risk Score: 16\)

Human reviewers should verify large-scale rejection decisions before they become final, and applicants should have access to an accessible appeals process. The AI Governance Committee should oversee these safeguards from the start of deployment in accordance with Article 9 of the EU AI Act.

\#\#\# Escalation Considerations

Although these mitigation measures significantly reduce identified risks, transparency controls may still be insufficient for candidates seeking detailed explanations or wishing to challenge automated decisions. Legal counsel should periodically review compliance with evolving AI regulations and employment laws to ensure continued alignment with regulatory expectations.

## Section 5: Recommendations and Ongoing Monitoring

\#\# Monitoring Frequency

The organization should conduct quarterly bias and fairness audits, annual AI Impact Assessment reviews, and continuous monitoring of key performance indicators such as rejection rates, score distributions, false-positive rates, and demographic disparities.

\#\# Trigger Conditions

An immediate reassessment should occur whenever the model is retrained, expanded to additional job categories, significant candidate complaints are received, material performance degradation is detected, or new regulatory guidance becomes effective.

\#\# Accountability

The AI Governance Committee is responsible for overseeing compliance, approving deployment decisions, reviewing audit findings, and suspending or terminating the system if risks exceed the organization's acceptable tolerance levels. Executive leadership should receive regular governance reports to ensure continued accountability.  
