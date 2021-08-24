---
layout: default
title: schnellstart
published: true
---

# Determination of the beneficial owner with KYCnow

---

A beneficial owner according to §3 GwG is a natural person who owns or controls a company.
In addition, a beneficial owner can also be the person who initiates a transaction or who initiates the establishment of a business relationship.

To identify beneficial owners, ClariLab obtains the information from various providers, currently SCHUFA and Dun & Bradstreet.
ClariLab initially identifies beneficial owners exclusively based on their capital shares in the respective company. This is because distribution of voting rights is not always readily apparent. It is usually possible to conclude the control structures on the basis of the capital shares, which are predominantly equivalent to the ownership structures (presumptionprinciple).

The beneficial owner is always determined on the basis of the same set of rules, non-regarding of the provider and always along the interpretation and application instructions of the German banking industry.
The proof of investigation through SCHUFA is presented in the well-known GWG design while the proof of investigation through Dun & Bradstreet is presented in the KYCnow layout.

---

## Data sources

The information of the providers is not merged.

### Companies without relations outside of Germany
For companies without relations outside of Germany, ClariLab only uses information from SCHUFA.

For the inquiry object GmbH 1 from Fig. 1, since it has no links abroad, the information of SCHUFA would be used

### Companies with relations outside of Germany
For companies with relations outside of Germany, ClariLab only uses information from Dun & Bradstreet.

For the inquiry object GmbH 2 the data of Dun & Bradstreet would be used, since the company has links abroad, for example through a natural person abroad or a participating company abroad.
The data of Dun & Bradstreet would also be used for the inquiry object GmbH 3, as it is completely located abroad.

![Anfragelogik_EN](/assets/ubo/anfragelogik_EN.png)

It is not possible to decide on a specific provider from the outset. In the case of an inquiry for a company based in Germany, it is always first checked based on the information provided by SCHUFA. If, during this examination, it is determined that the requested company has links abroad, the investigation via SCHUFA is aborted and instead investigated with only the information from Dun & Bradstreet. 
When requesting a company based solely abroad, Dun & Bradstreet's information is used.

---

## General information about determination
As a basis for determining the beneficial ownership, the ownership and liability relationships, which result from the companies legal form, are used.

The investigation logic always distinguishes between single-story and multi-story structures.

In the case of single-story structures, meaning the direct participation of a single natural person in the requested company, exceeding the "25% threshold" leads to a position as a beneficial owner. (see Fig. 2, Cases A, B)

In the case of multi-story structures, meaning indirect participation via an intermediary company, owning a stake of >50% in the intermediary company means that it is considered to be controlled by the person. If the intermediary company also exceeds 25% direct participation in the requested company, the person indirectly involved is a beneficial owner. (see Fig. 2, Case C, D)

If an actual beneficial owner has been identified, no fictitious beneficial owners are issued.

![ubo_szenarien_a_d_EN](/assets/ubo/ubo_szenarien a_d_EN.png)

A: The natural person A is issued as a beneficial owner, as he directly has over 25% capital shares in the requested GmbH 1.

B: Natural person B is not a beneficial owner. This is because the person holds less than 25% capital shares in the requested company.

C: 70% of AG 1 is held by GmbH 2. It is therefore considered to be controlled by that company. 
95% of GmbH 2, on the other hand, are held by the natural person C, thus controlled by him. Therefore, person C is considered a beneficial owner of GmbH 1.
Person D is not a beneficial owner, since he holds only 5% of the capital in the company GmbH 2.

D: Similar to Person D, Person E does not control AG 2 as Person E only holds 45% of the capital. This means Person E does not control AG 2 and is therefore not regarded as a beneficial owner, regardless of the fact that AG 2 in itself holds more than 25% of the requested company GmbH 1.

![ubo_szenario_e_EN](/assets/ubo/ubo_szenario e_EN.png)

E: The natural person A is both directly and indirectly involved in GmbH 1.
The direct participation is below the 25% threshold.
In the case of indirect participation, A controls the intermediate company with more than 50%, which is why the 20% is credited to him as well.
According to the sum rule, A thus holds a 30% stake in GmbH 1 and is considered a beneficial owner.

### Fictitious beneficial owners
Only if no actual beneficial owner can be identified, the persons of the 1st management level are issued as fictitious beneficial owners.

There are various reasons why no beneficial owners can be identified. These reasons result from the aborts of the investigation.

![ubo_szenario_f_EN](/assets/ubo/ubo_szenario f_EN.png)

---

## Steps of determination

Several steps are necessary to determine the beneficial owners. So that these can be documented in a comprehensive manner, the results of all steps are documented.
For this purpose, a distinction is made between investigation results (1) and path results (2).

![pfad_vs_ermittlungsergebnis_EN](/assets/ubo/pfad_vs_ermittlungsergebnis_EN.png)

---

## Path Results

Path results can be identified beneficial owners. However, it can also happen that no conclusions can be drawn from a path. In this case, the investigation of the path is discontinued. A termination is a common process in the development of an investigation result and can have various reasons.

![pfadergebnisse_EN](/assets/ubo/pfadergebnisse_EN.png)

### Path results - SCHUFA

SCHUFA distinguishes between different reasons for cancellation, which are listed and explained below.

1. Beneficial ownership
If a beneficial ownership could be issued, whether by the sum rule or directly, this is recorded as a path result.

2. End of investigation
An end of investigation is issued, for example, when free float is determined or for example if municipalities or districts are determined.

3. No beneficial ownership
If a person is determined who does not meet the rules for the UBO determination, i.e. does not hold the necessary capital shares, this is expressed.

4. Termination due to ties abroad
If either the parent company or a natural person is abroad, a termination is issued because the path is not pursued.
This means there may be other UBOs abroad, but the data is not (yet) available.

5. Deleted from registry
The company has been deleted from the commercial register.

6. Blocked
A company involved is blocked, which is why no further investigation can be carried out.

7. Circular reference
In this case, there is a self-participation – either of the requested company itself or of a participating company.

8. Others
This termination of investigation is issued if a company has no capital shares. This would be the case, for example, with a foundation or an association.

---

## Investigation Results
The investigation results result from the path results. If path results are based exclusively on information from SCHUFA, the determination results are also output by SCHUFA. Once the path results are based on information from Dun & Bradstreet, the investigation results are also output based on that information.

### Investigation results - SCHUFA
SCHUFA distinguishes between four investigation results.

![ermittlungsergebnisse_schufa_EN](/assets/ubo/ermittlungsergebnisse_schufa_EN.png)

### Investigation Results - Dun & Bradstreet
ClariLab distinguishes between five investigation results

![ermittlungsergebnisse_dnb_EN](/assets/ubo/ermittlungsergebnisse_dnb_EN.png)