---
layout: default
title: transparenzregister
---


# Manual for the KYCnow module "Transparency Register"

With this module, we strive to make it easier for you to deal with the Transparency Register and to support you in making compliance processes more efficient and effective. In the following, we describe how to set up the module successfully and answer questions on how to use the module as well as how it works technically. If your questions are not answered using this guide, just send us an email ([fragestunde@kycnow.de](mailto:fragestunde@kycnow.de)). We would like to answer a question that often reaches us in advance:

## What services do you offer?

Our services in connection with the Transparency Register can be divided into three categories:

- Retrieving data
- Matching data
- Reporting of inconsistencies

## Setting up the module

In order to use our module successfully, you must have completed the following steps beforehand:

1. Create an Account with the Federal Gazette.
1. Store the login data for the Federal Gazette in our application under "Settings".
1. The payment method that you have deposited with the Transparency Register can be deposited with us as part of the onboarding process. You must also have successfully ordered at least once from the Transparency Register.

    If you pay by direct debit, please check to preallocate the account details.

1. Please make sure that your document basket in the transparency register is empty before each order with the help of KYCnow.

### Do I need my own account with the Federal Gazette?

Yes, you must create an account with the Federal Gazette. This account interacts with the transparency register, e.g. when queries or inconsistency reports are sent.
Your login data is stored in an encrypted form, so that only you can change it. The login data is automatically validated in the beginning and cannot be viewed by us at any time.

### Who bills?

You will receive a monthly invoice from us. Separately you will receive invoices from the Federal Gazette, according to your calls. The respective fee, which is charged by the Federal Gazette, can be found in the Transparency Register Fees Ordinance (TrGebV) or viewed [here](https://www.transparenzregister.de/treg/en/hilfe?0).

### Is a collective invoice possible?

We offer you the possibility to collect all queries of the day and place them in a "shopping kart order". As a result, instead of multiple invoices per day, you only receive one invoice per day from the Federal Gazette.
Technically, the shopping cart order means that in the evening we send all enquiries of the day bundled to the Federal Gazette. In the case of individual orders, the query is immediately sent to the Federal Gazette.
You can choose one of two options at the beginning. If you wish to switch to the other option during the course of use, you can contact our customer service ([fragestunde@kycnow.de](mailto:fragestunde@kycnow.de)) at any time.

A monthly invoicing is unfortunately not possible.

## Retrieving data

Under the "Documents" tab, you can order a transparency register excerpt.

After that, a window will appear in which you can select the company for which you want to order the statement. Alternatively, you can select not to have found the company. This results in an inconsistency report. LINK

To complete the ordering process, you must specify the reason for the request. This field must be filled in.

### Do you obtain data directly from the Federal Gazette?

No, we are not in a partnership with the Federal Gazette, but receive the data by retrieving the Transparency Register instead.

### Do I still need a legitimate interest?

Yes, a legitimate interest is mandatory.

### How quickly does the data come back?

We cannot give a specific time because we are not involved in processing queries. If the Federal Gazette has processed the query, you will be notified immediately by us. The delay between the notification of the Federal Gazette and the forwarding by us is only a few minutes.
The processing time by the Federal Gazette ranges between a few hours and sometimes also several days.

---
**Info**

We have experienced that a more detailed description of the legitimate interest results in faster feedback.

---

### Do we receive the data in a structured way?

Yes, we read the documents via OCR (optical character recognition). The structure is as follows:

1. Name
1. Surname
1. Date of birth
1. Residence
1. Extent of economic entitlement
1. Type of economic entitlement

### Can we also receive the data in a PDF-File?

Yes, you can export all data as a PDF-File.

### What happens if the transparency register information is empty?

Empty transparency register information is not uncommon. It is also referred to as negative clearance (Negativattest) and means that no information has been given to the Transparency Register on the beneficial owners.

This may mean that the fiction of notification is in place. On the other hand, it is also possible that a notification has, falsely, not yet been given. In this case an inconstitency report (LINK) must be made.

In principle, we recommend the following procedure:

1. Check whether the necessary information on the beneficial owners is already in one of the other registers in accordance with Section 20 II MLA (§20 II GwG).

2. If no information has been provided in any of the other registers, a notice of inconsistency report must be submitted.

## Matching the data

After the query has been processed by the Federal Gazette, you can view the transparency register information under the "Transparency Register" tab. There we show you all identified beneficial owners and compare the data from the transparency register with the data you have determined (KYCnow file) and check for inconsistencies. You can manually enter and change the data of the KYCnow file in the right column.

Example 1, No inconsistencies detected:

If we find discrepancies in an UBO, we mark the fields in red. If you want to add an economic owner to your inconsistency report, you can select this at the bottom left.

Example 2, Inconsistencies found

Under the "Transparency Register" tab you can also:

1. Indicate that there are more beneficial owners arising from other registers.
2. Add another UBO to your KYCnow file. On clicking, a new register for an economic beneficiary will appear, in which you can enter all the information you’ve determined manually.
3. Trigger an inconsistency report. When you trigger an inconsistency report all inconsistencies that you have detected and selected are automatically transmitted to the transparency register.
4. Download the transparency register extract as a PDF file.

### How is the fiction of notification depicted?

If the company in question makes use of the fiction of notice, this is expressed in an empty transparency register extract (Negativattest). In this case, the beneficial owner must be inferred from the commercial register or one of the other registers in accordance with Section 20 II 1 MLA.
For technical reasons, we can only show a fiction of notice if you have booked the module GWG, as this includes the retrieval of the necessary data from the commercial register. If you have booked the module GWG, we will inform you of both the message fiction and the corresponding source.

You may see a person twice. This happens when an entry has been made in both the transparency register and one of the other possible registers.

## Inconsistency reports

### How do you find a discrepancy?

We distinguish between three different types of inconsistencies: A) The legal entity is not registered in the transparency register B) Deviating / no beneficial owner has been identified C) Individual information on a beneficial owner differs. If a discrepancy is determined, you can report it directly to the transparency register via our application.
In order to determine inconsistencies, we compare the data from the transparency register with those from the commercial register, as well as with the data you have determined. You can see a model of the exact procedure in the appendix. (LINK)

The inconsistency report we have identified is to be understood as a recommendation.

### Where do I get feedback on the inconsistencies?

Inconsistency reports are processed by the Federal Gazette. You will receive feedback from the Federal Gazette on inconsistencies that you have sent. You can retrieve the feedback at any time via our interface and/or export it as a PDF file. You can also retrieve the feedback via your account at the Federal Gazette. If the Federal Gazette has processed the report, you will be notified immediately by us. The delay between the notification by the Federal Gazette and the forwarding by us is only a few minutes.

## Annex

### Modeling our inconsistency check

The subsequent process is largely automatic. However, so that you can understand which steps this process is based on, we have modulated the process in its entirety.

In our application, the search for the legal entity for which a transparency register extract is to be ordered is carried out in several stages.
At the beginning, you have already searched for the company in question and added it to your inventory. For a detailed description of this procedure, see our step-by-step guide.

To order the transparency register extract (more details here (LINK)) we offer you a list of possible hits to choose from. In order to exclude typos, etc., the list can also include similar hits.

---

**Case A (see Figure 9)**

If the legal entity cannot be found in the Transparency Register, a notification of inconsistency can be submitted.

---

For this purpose, you will be asked, after the appropriate selection, to indicate the legal form of the legal entity subject to transparency. This is used to correctly fill in the inconsistency report.

Afterwards, you will be shown all the information of the company concerned once again, with the possibility to BILD

If you have found the company, however, you will receive the transparency register extract after a few days. Depending on the content of the document, you can follow the next steps below (scenario: negative clearance) (scenario: get a transparency register extract).

### Negative clearance

If you have received a negative clearance from the Transparency Register, our application checks for corresponding entries in the commercial register and, if specified by you, for economic beneficiaries identified by you.

---

**Case B**

If no registration was determined despite the comparison, this indicates that the fiction of notification was wrongly used, which leads to an inconsistency report (B).

---

If, on the other hand, information on beneficial owners has been obtained, the information will be checked for completeness in the next step.

---

**Case C**

If the information is incomplete, an inconsistency report must be sent to the Transparency Register.

---

Once you have received a transparency register extract, we will first add the beneficial owners you have identified, if any.
The next step is to search for hits in the commercial register based on first and last names as well as the date of birth. The search is only done by hardmatch.

---

**Case D**

If differences are found during the first comparison, this can be sent to the Transparency Register as an inconsistency report.

---

If no differences were detected in the first comparison, all remaining information is compared in the next step.

---

**Case E**

If there are any discrepancies in this step, you can report them to the Transparency Register.

---

In the final step, if the other information does not differ, the information is checked for completeness.

---

**Case F**

If the information is not complete, you can also report it to the Transparency Register.