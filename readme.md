# Digital Clinical Safety

Digital clinical safety refers to managing the risk of harm to patients (the recipients of care) that may potentially be introduced by digital technologies that are manufactured, implemented, and used to support direct patient care in health and social care.

Digital clinical safety must be considered across the full digital system lifecycle and is part of a broader patient safety culture. It is important to anticipate and prevent potential patient harms, but also to react effectively when a new risk is identified or if a patient comes to harm.

## Clinically Safe Digital Systems Should:

- Be free from unacceptable risk.
- Be supported with evidence that demonstrates that risk is acceptable.
- Feature controls that mitigate risk where necessary.

---

## NHS Digital

NHS Digital develops and delivers products and services for the wider health and care systems in England.

Patient safety is at the heart of everything that NHS Digital does, and the organisation is moving towards a culture of 'clinical by default', meaning every system and service that is developed or assured by NHS Digital must have digital clinical safety input, assessment, and verification.

### How Does NHS Digital Ensure Digital Clinical Safety Assessment and Verification Takes Place?

- The organisation employs clinicians to support the delivery of these products and services to provide assurance that these products are clinically safe, effective, and beneficial to the public, practitioners, and the wider NHS system.
- Clinical leads and safety experts are involved in all stages of the development process.
- The Clinical Safety Group at NHS Digital provides oversight and assurance of digital clinical safety wherever NHS Digital’s work is assessed as having a clinical impact. This includes ensuring products and services are developed to recognised safety standards and are approved for deployment into the live clinical environment.

---

## When Do We Need to Make Sure Digital Technology Is Safe?

Be mindful of digital technology and the potential it has to introduce new risks which could harm patients at every stage of the lifecycle. Ask yourself:

- If there is a deviation from the intended care process, what can happen to the patient and how severe can it be?
- If there is potential harm to the patient, what can you do to mitigate the risk?

---

## What Could Go Wrong?

### Examples:

1. **Change in Order Rules:**
   - **Risk:** The order rules change in the drop-down menu; this could lead to the patient being prescribed an unintended medication.
   - **Control Measures:**
     - The pharmacist double checks the prescription and notices the error.
     - A screen in the prescribing system ensures the prescriber checks the prescription is correct before signing.

2. **Same Name Warning Failure:**
   - **Risk:** The 'same name' warning may fail (due to a system design failure), leading to information being recorded in the wrong patient record. This could result in inappropriate patient care.
   - **Control Measures:**
     - The system has patient details in several places, such as the patient banner and when entering the record, prompting the clinician to recognise they are in the wrong record.
     - The system does not allow multiple records to be open at the same time, reducing the likelihood of the clinician recording information in the wrong record.

3. **Allergy Alert Failure:**
   - **Risk:** An allergy alert may not generate or may not be acted upon (due to poor system design). This could result in inappropriate medication being prescribed to the patient.
   - **Control Measures:**
     - The system has an icon on the patient record if they have an allergy recorded, and these are displayed on the medication screen.
     - The standard process includes the prescriber and pharmacist checking for allergies with the patient.
     - Allergies should also be checked at the point of administration.

---

## Types of Controls

Controls fall into three different categories: design (incorporated into the product), business process (how the product is incorporated in the care pathway), and training (training for users of the product).

### Examples:

1. **Design Controls:**
   - **Control:** Warnings and alerts.
   - **Evidence:** Product design documents and test evidence.

2. **Business Process:**
   - **Control:** Standard operating procedures.
   - **Evidence:** Process document.

3. **Training:**
   - **Control:** User guides and courses.
   - **Evidence:** Documents and training records.

### Best Type of Control:

Design controls are the strongest as they can eliminate or detect the hazard cause in the product. Business process and training controls are useful but cannot eliminate the hazard cause. They are dependent on the user of the product taking some action. 

---

## Digital Clinical Safety Considerations

When developing an application that offers capabilities such as:

- Single source of patient information.
- Appointment booking.
- Referral access.
- Order of medication.

It is necessary to consider digital clinical safety.

### What Does It Mean to Be Clinically Safe?

A supplier and health organisation should be able to justify why they believe a system to be safe. The argument and evidence to support this should be presented as a Clinical Safety Case Report (CSCR), demonstrating that a process has been followed to identify hazards and mitigate them where necessary.

---

## Examples of Digital Clinical Safety Incidents

### Example 1: Incorrect Dose Prescribed

- **Scenario:** A GP prescribes the wrong dose of a drug due to an error in the drug database. The pharmacist notices the error during dispensing and contacts the GP to correct it.
- **Outcome:** No harm to the patient; the pharmacist acts as a reactive control and identifies the error.
- **Action:** Reported as an incident by the GP practice to the system supplier for technical cause assessment.

### Example 2: Missing Prescribing Information

- **Scenario:** A patient’s discharge summary is missing the prescribing information for warfarin, resulting in the patient not being scheduled for a review.
- **Outcome:** No harm as the patient contacts the GP and an appointment is made.
- **Action:** Reported by the GP as an incident, with follow-up by the hospital and HIT supplier.

### Example 3: Wrong Patient Record

- **Scenario:** Two patients with the same name have their results saved to the wrong patient record.
- **Outcome:** Patient A experiences emotional distress; Patient B faces delayed care.
- **Action:** Reported to the system supplier to address a bug in the 'same name' warning.

### Example 4: Lab Result Delay

- **Scenario:** A patient with a serious infection is delayed appropriate treatment due to a lab result not being available on the HIT system.
- **Outcome:** The patient experiences a prolonged hospital stay and post-sepsis syndrome.
- **Action:** The incident is escalated to the lab and HIT supplier to investigate and prevent recurrence.

---

## Reflection

It is important that the process for reporting an incident is clear within your organisation. Ask yourself:

- How do I report an incident?
- Who do I report an incident to?
- Who is my clinical governance lead?

Including this information in staff induction can ensure all staff understand how to report an incident.

---

## Summary

Digital clinical safety is the avoidance of harm to patients as a result of technologies manufactured, implemented, and used to support direct patient care in health and social care. Digital clinical safety must be considered at each stage by everyone within the organisation.

---

**Next Steps:** Well done, you have now finished this chapter. You have discovered:

- What digital clinical safety is.
- What can go wrong when it comes to the use of digital technology and the control measures.
