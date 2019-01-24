# NDC-database-analysis

We are trying to find the duplication of the drug in the dataset. For example, if two drugs got the same curative effect but they have different name, we could eliminate them from the dataset. Also, if two drugs have same name but different  curative effect, we could clear the data by changing the name of these drugs.


# Team members

Le Qin

Qingxu Wang

Zening Li

# Dataset attribute

- ProductID  Text/string: Concatenation of the NDCproduct code and SPL documentID

Example: "0002-1445_e779cf1f-265c-4fed-931d-102fbaf7e14b" and "0002-3232_996cd2a5-d0e1-4031-a54c-4672c6a14674"

- ProductNDC  Text/string: The labeler code and product code segments of the National Drug Code number

Example: "0002-0800" and "0002-3231"

- ProductTypeName  Text/string: type of product

Example: "HUMAN PRESCRIPTION DRUG" and "HUMAN OTC DRUG"

- ProprietaryName  Text/string: Trade name

Example: "Sterile Diluent" and "Strattera"

- ProprietaryNameSuffix  Text/string: A suffix to the proprietary name

Example: "Weekly" and " "(There is no specific suffix)

- NonProprietaryName  Text/string: Active ingredient(s) of the product

Example: "diluent" and "testosterone"

- DosageFormName  Text/string: The translation of the DosageForm Code

Example: "INJECTION, SOLUTION" and "CAPSULE"

- RouteName  Text/string: The translation of the Route Code

Example: "SUBCUTANEOUS" and "TOPICAL"

- StartMarketingDate Text/string: Starting date of its marketing of the drug product

Example: "19870710" and "20010316"

- EndMarketingDate  Text/string: Ending date the product will no longer be available on the market

Example: "20190131" and " "(The reason is this product is still available)

- MarketingCategoryName Text/string: final marketed product categories

Example: "NDA" and "BLA"

- LabelerName Text/string: Name of Company

Example: "Eli Lilly and Company" and "Merck Sharp & Dohme Corp."

- SubstanceName   Text/string: Active ingredient list

Example: "WATER" and "NEISSERIA MENINGITIDIS GROUP B RECOMBINANT LP2086 A05 PROTEIN VARIANT ANTIGEN; NEISSERIA MENINGITIDIS GROUP B RECOMBINANT LP2086 B01 PROTEIN VARIANT ANTIGEN"

- StrengthNumber Text/string: strength values of each active ingredient

Example: "3; 25" and "80"

- StrengthUnit  Text/string: units to be used with the strength values

Example: "mg/.5mL" and "mL/mL"

- Pharm_Classes Text/string: reported pharmacological class categories

Example: "Interleukin-17A Antagonist [EPC],Interleukin-17A Antagonists [MoA]" and "Norepinephrine Uptake Inhibitors [MoA],Serotonin and Norepinephrine Reuptake Inhibitor [EPC],Serotonin Uptake Inhibitors [MoA]"

- DEASchedule Text/string: assigned DEA Schedule number

Example: "CIV" and " "(No DEA Schedule number)

- NDC_Exclude_Flag Text/String: whether the product has been removed/excluded from the NDC Directory for failure to respond to FDA’s requests for correction to deficient or non-compliant submissions.

Example: "N" and "E"

- Listing_Record_Certified_Through Text/String: date when the listing record will expire.

Example: "20191231" and " "(The record will not expire)
