---
type: source_packet
project: postictal
module: lgs-post-visit
created: 2026-06-22
status: draft_source_packet
---

# LGS Post-Visit Module - Source Packet

## Purpose
Create a simple patient-family education module for Lennox-Gastaut syndrome (LGS), designed to be shared after clinic counseling. The module should help caregivers remember the major categories:
- what LGS means
- why seizure type matters
- how clinicians approach medicines, rescue plans, safety, and non-medicine options
- what to track before the next visit
- where to find reliable resources

## Source Standard
This is not a literature-review module. It should rely on reputable patient-facing and professional education sources, then use clinician review for local framing.

## Sources Used

### MedlinePlus Genetics - Lennox-Gastaut Syndrome
URL: https://medlineplus.gov/genetics/condition/lennox-gastaut-syndrome/

Used for:
- general patient-facing LGS overview
- multiple seizure types
- developmental and EEG-pattern framing

Notes:
- MedlinePlus Genetics describes LGS as a severe epilepsy condition beginning early in life, often involving multiple seizure types, developmental delays, and characteristic EEG patterns.
- It supports the syndrome-level framing that LGS is not one single seizure type.

### Epilepsy Foundation - Lennox-Gastaut Syndrome
URL: https://www.epilepsy.com/what-is-epilepsy/syndromes/lennox-gastaut-syndrome

Used for:
- general patient-facing LGS overview
- common treatment categories
- medication examples
- dietary therapies and other treatment framing

Notes:
- Epilepsy Foundation describes antiseizure medications as the first treatment path in epilepsy/LGS, while noting that LGS seizures often require two or more medicines and may remain difficult to control.
- It lists examples such as valproic acid, lamotrigine, topiramate, felbamate, rufinamide, clobazam, and fenfluramine, while leaving room for other medicines.
- It describes dietary therapies such as ketogenic diet, modified Atkins diet, and low glycemic index treatment as options that may reduce seizures in some people with LGS.
- NotebookLM import note, 2026-06-22: this URL imported into NotebookLM as a Cloudflare challenge page and was removed from the generation notebook. The local source packet preserved the prior reviewed summary, but the generated audio used MedlinePlus, ILAE, CDC, LGS Foundation, and local packet sources instead.

### Children's Hospital of Philadelphia - Lennox-Gastaut Syndrome
URL: https://www.chop.edu/conditions-diseases/lennox-gastaut-syndrome

Used for:
- treatment category overview
- rescue therapy as separate from daily anti-seizure medications
- diet, device, and support-service framing

Notes:
- CHOP describes treatment as commonly including combinations of anti-seizure medications for different seizure types, rescue therapies for clusters, implantable devices such as VNS or RNS when medications are not effective, ketogenic diet in some cases, and rehabilitation / school supports.
- This supports separating daily medicine, rescue medicine, diet therapy, devices, and family support into distinct patient-facing categories.

### ILAE EpilepsyDiagnosis.org - Lennox-Gastaut Syndrome
URL: https://www.epilepsydiagnosis.org/syndrome/lgs-overview.html

Used for:
- syndrome-level framing
- multiple seizure types
- developmental / epileptic encephalopathy framing
- EEG context and diagnostic caution

Notes:
- ILAE frames LGS as a syndrome characterized by multiple drug-resistant seizure types, cognitive/behavioral impairment, and characteristic EEG findings.
- Tonic seizures in sleep are emphasized as an important seizure type.
- LGS usually evolves from a prior epilepsy syndrome or etiology rather than appearing fully formed at first seizure onset.

### CDC - First Aid for Seizures
URL: https://www.cdc.gov/epilepsy/first-aid-for-seizures/index.html

Used for:
- first-aid basics
- timing seizures
- when to seek emergency help

Notes:
- CDC first aid emphasizes staying with the person, keeping them safe from injury, turning them gently onto one side when appropriate, and timing the seizure.
- CDC recommends immediate medical attention / 911 if a seizure lasts more than 5 minutes, and lists other escalation situations such as repeated seizures, breathing difficulty, injury, seizure in water, first-time seizure, or failure to return to usual state.

### Epilepsy Foundation - Seizure First Aid
URL: https://www.epilepsy.com/recognition/seizure-first-aid

Used for:
- prior draft first-aid and emergency-help framing

Notes:
- NotebookLM import note, 2026-06-22: this URL imported into NotebookLM as a Cloudflare challenge page and was removed from the generation notebook. CDC first aid was used as the clean public source for the generated audio.

### LGS Foundation - About LGS
URL: https://www.lgsfoundation.org/about-lgs-2/

Used for:
- family-centered resource links
- caregiver support framing
- resource navigation after diagnosis

Notes:
- The LGS Foundation has sections for new families, seizure/safety learning, caregiver support, patient navigators, family resources, and information/material requests.

## Draft Clinical Claims For Review
- LGS is not one seizure type; it is a syndrome where multiple seizure types can occur.
- The most useful next-step question is often not "which medicine is best?" but "which seizure type are we trying to reduce first, and what risk are we trying to reduce?"
- Medicine plans in LGS are often combinations rather than a single drug solution.
- Non-medicine options can include diet therapy, neuromodulation devices such as VNS, and surgery-oriented evaluation in selected cases.
- RNS or DBS should be framed only as specialist-program discussion categories for selected patients, not as standard next steps for every LGS family.
- Corpus callosotomy may be discussed in selected cases, especially when drop seizures and injuries are a major problem, but should be framed as risk-reduction discussion rather than cure.
- Rescue medicines should be used only according to the prescribed seizure action plan.
- The family's tracking notes are clinically useful when they capture what happened before, during, and after events.

## Claims To Avoid Without Review
- Any statement that a named drug is best for a specific patient.
- Any statement that a family should start, stop, or change medication.
- Any promise of seizure freedom.
- Any fixed ranking of LGS treatment options.
- Any emergency threshold that conflicts with the patient's own seizure action plan.
- Any local Emory process instruction that has not been verified.

## NotebookLM Audio Generation Log
- 2026-06-22: Created notebook `Postictal LGS After-Visit Guide` (`0e393a12-27da-4378-953c-7eea61ad06f9`).
- Clean source IDs used for audio: LGS Foundation (`fb745290-5b61-4b60-bdd0-c0291c8e83d3`), CDC seizure first aid (`c834c424-adb7-4f57-bcac-b6a565697685`), ILAE EpilepsyDiagnosis LGS (`c81f8d65-c17b-4bfa-9c31-a0b59c243906`), MedlinePlus Genetics LGS (`ca29b51a-5c72-43d4-9daa-dd3261627cf7`), local audio steering brief (`f9b68f37-c9a7-4680-82a0-37b7bc7c6724`), local source packet (`3a90e8e7-aa75-4662-91aa-650a796a9324`).
- Generated artifact: `LGS Seizure Tracking and Rescue Plans` (`f6de48f4-2902-4e51-a873-6cb21e499d60`).
- Local file: `assets/audio/lgs-after-visit-notebooklm.m4a`.
- Duration: 2:03, which undershoots the planned 5-8 minute target. Treat as a web-embedded proof-of-format draft, not the final patient-facing audio.
- 2026-06-22 update: Expanded medication, device/procedure, diet, and rescue-plan framing for a team-shareable pilot. Regenerate audio from the updated source packet before sharing.
- 2026-06-22 update: Created notebook `Postictal LGS Medications Devices Pilot` (`732622a2-8178-4e0d-8267-ccffb6fd0fcf`) and generated updated artifact `Targeting the most dangerous LGS seizures` (`05e9fedd-0da6-4391-ab6d-0324b9f4a3be`).
- Clean source IDs used for updated audio: LGS Foundation (`579651e8-ad7b-406f-95e5-57df1ec05a77`), CDC seizure first aid (`c0ef4e39-dfc1-414b-8311-708e08b6a9c8`), ILAE EpilepsyDiagnosis LGS (`b68bf7d6-240c-4d12-9ddf-07b592770a68`), CHOP LGS (`7b671cc5-37b3-47bb-a9eb-aac393faaf46`), MedlinePlus Genetics LGS (`ab51f906-786d-47c8-93f9-e02163ec51f4`), updated local audio steering brief (`3491e6aa-614c-449a-a5c2-3f0378313be8`), updated local source packet (`b7a8403c-9b5a-4987-8eb1-c320d4cf9f06`).
- Updated local file: `assets/audio/lgs-after-visit-medications-devices-notebooklm.m4a`.
- Updated duration: 1:37, which still undershoots the planned 5-8 minute target.
- Longer NotebookLM retry: artifact `A Caregiver Guide to Lennox-Gastaut Syndrome` (`7a6aed22-2fa7-4c1b-9c8b-102ad8ab6aa2`) eventually completed at 56:59 and about 110 MB. It overshot the target and was not embedded or committed to GitHub.
