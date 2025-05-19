# Collaborative Online Pediatric and Perinatal Repository
---

## Collaborative Online Pediatric and Perinatal Repository Dataset

The dataset contains tabular information about various biobank resources. Below are the definitions for each column:

| Column Name             | Description                                                                                      |
|-------------------------|--------------------------------------------------------------------------------------------------|
| id                      | Unique identifier for each entry (row)                                                           |
| record_id               | Secondary record identifier (may duplicate id)                                                   |
| intro                   | Brief introduction or notes about the biobank (optional)                                         |
| name_biobank            | Name of the biobank or study                                                                     |
| inquiries               | Contact email or information for inquiries                                                       |
| type_of_biobank         | Types of samples or biobank (e.g., blood, urine, DNA, tissues). May include multiple values.     |
| other_type              | Description if "Other" is selected in type_of_biobank                                            |
| part_blood              | Specific parts of blood collected (e.g., whole blood, plasma, serum)                             |
| other_process_blood     | Details if "Other" processing for blood samples is used                                          |
| number                  | Estimated total number of samples collected                                                      |
| how_many                | Estimated number of participants or donors                                                       |
| use_others              | Availability or usage restrictions for other sample types                                        |
| age_participants        | Age range(s) of participants whose samples are collected                                         |
| when_collected          | Time period or condition when samples were collected (e.g., postpartum, gestational age)         |
| type_of_data            | Types of data associated with the samples (e.g., demographic, clinical, molecular, outcomes)     |
| other_data_blood        | Additional information about blood-related data, if not covered in type_of_data                  |
| date_and_time           | Date and time when sample/data was recorded or made available                                    |

- Fields enclosed in curly braces { } or double quotes "" indicate multiple possible selections.
- Some columns may be empty or contain "Other" with further specification in a corresponding "other_" column.
