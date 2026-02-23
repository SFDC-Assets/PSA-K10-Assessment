![Public Sector Accelerators logo](/docs/Logo_GPSAccelerators_v01.png)

# Kessler Psychological Distress Scale (K10) Assessment

**Use OmniScript to capture and score Kessler Psychological Distress Scale (K10) Assessment responses.**

[**Accelerator Listing**](https://gpsaccelerators.developer.salesforce.com/accelerator/a0wDo000001C3AwIAK/k10-assessment)


## Description

Streamline the way your organization measures and responds to client well-being with the K10 Psychological Distress Assessment Accelerator. This pre-built, ready-to-deploy Omniscript component allows you to quickly and easily capture self-reported psychological distress, directly within your Salesforce environment.

Based on the clinically-validated Kessler Psychological Distress Scale (K10), this tool presents a 10-item questionnaire focused on anxiety and depressive symptoms experienced within the last four weeks. The Omniscript guides your clients, patients, or constituents through this assessment in a seamless, user-friendly, and step-by-step flow, improving completion rates and ensuring data accuracy.

Replace static PDFs or clunky web forms with a modern, fully-guided digital experience. The Omniscript's intuitive, guided steps is less overwhelming for users, which is especially critical when dealing with sensitive health information.

The Total Score is calculated based on the selected responses and captured as part of Assessment Question Response. This score can be used to view the history of K10 score using standard Assessment History component.

The questions and assessment are created in English only.

## Key Assets

This Accelerator includes the following assets:
* An [**unmanaged package**](https://login.salesforce.com/packaging/installPackage.apexp?p0=04tQE00000JD2fNYAT) that includes:
    * Assessment Question Config (x11) - the 10 assessment questions and 1 scoring question
    * Omni Script (x1) - K10 Assessment


## Before You Install


**License Requirements**
* Industry Solution (Industry Common Component)
  _eg. Nonprofit Cloud, PublicSector Cloud, Health Cloud, Education Cloud; requires Communities for external_

**Accelerator or Technology-Specific Assumptions**
* You have enabled [Discovery Framework](https://help.salesforce.com/s/articleView?id=ind.psc_dynamic_assessments_prerequisites.htm&type=5) and provided the right permissions. 
* You are using OmniStudio's native runtime.

**General Assumptions**
* You are using this Accelerator in a sandbox or test environment. It is recommended that you not install any Accelerator directly into production environments.
* If you do not have a Salesforce org licensed to you, try one of our industry solutions for free with one of our [trial environments](https://gpsaccelerators.developer.salesforce.com/trials).
* You are using this Accelerator in conjunction with the Salesforce Lightning Experience (LEX) - not the Classic UI.


## Installation

Ensure that you always trial in the sandbox environment. Follow the Package Installation steps below:
- Select **Install for All Users**
- **Under Advanced Options**, select Compile only the Apex in the package
- Click **Install**

## Additional Configuration (Optional)

**Fields in the Assessment record**

The assessment records created, upon completion, has the following fields populated.
- Assessment Name: K10 Assessment
- Status: Completed

You can Deactivate the K10 Assessment Omniscript to add and/or modify additional Remote Options.


**Assessment History**

If you are looking to see the visual chart of the changes in the K10 score over time, you can [configure the Assessment record's lightning page to add the Assessment History compponent](https://help.salesforce.com/s/articleView?id=sf.hc_assessments_use_assessment_history.htm&type=5).


**Assessment Score Calculation**

The K10 Assessment Score is calculated using Formula Properties in the Omniscript. The scores as allocated as follows
| Response | Score |
| -------- | ----- |
| None of the time  | 1  |
| A little of the time | 2  |
| Some of the time | 3  |
| Most of the time | 4  |
| All of the time | 5  |
| No response | 9  |



## Additional Resources

The K10 questions and score calculations are based on the [Primary Mental Health Care - Minimum Data Set documentation](https://docs.pmhc-mds.com/projects/data-specification/en/v5.0/data-model-and-specifications.html#k10-question-1)


## Revision History

**1.0 Initial Release (January 2026)** - Initial release of the Kessler Psychological Distress Scale (K10) Assessment Accelerator. Includes pre-configured Assessment Question records based on the clinically-validated K10 scale and a complete OmniScript to capture client responses and calculate psychological distress scores. Delivered as an unmanaged package to allow customers full customization and modification capabilities.


## Acknowledgements

This Accelerator was developed through the collaborative efforts of the following team members:
- [Brenda Wai](https://github.com/bwhhwja) - Lead Builder and Project Lead
- Hayley Morris - Technical Builder and Architect
- [Emmanuel Schweitzer](https://github.com/eschweitzer78) - PMO Guide and Project Management

Special thanks to the broader GPS Accelerator community for their guidance and support throughout the development process, Chris Tye for being our Executive Sponsor and advocate for this project, and Geovanna Pazmino for helping us test the package.

## Terms of Use


Thank you for using Global Public Sector (GPS) Accelerators.  Accelerators are provided by Salesforce.com, Inc., located at 1 Market Street, San Francisco, CA 94105, United States.

By using this site and these accelerators, you are agreeing to these terms. Please read them carefully.

Accelerators are not supported by Salesforce, they are supplied as-is, and are meant to be a starting point for your organization. Salesforce is not liable for the use of accelerators.

For more about the Accelerator program, visit: [https://gpsaccelerators.developer.salesforce.com/](https://gpsaccelerators.developer.salesforce.com/)
