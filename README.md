# Protected-Attribute Tag Association dataset

This dataset is a proposed benchmark for measuring biases in Vision-Language models like OpenAI CLIP. It consists of a list of images organized as a set of scenes, and a set of captions applicable to each scene, organized according to specific protected attributes. We consider the binary gender, 5 ethno-racial groups (Black, Caucasian, East-Asian, Hispanic-Latino and Indian), and 2 age categories (young, old). 

### Distribution of images in the different protected attribute groups

|Attrib |Scenes| Label       |Count|
-----------------------------------
| Age   | 8    | Young       | 3748 |
| Age   | 8    | Old         | 1186 |
| Race  | 24   | Black       | 1024 |
| Race  | 24   | Caucasian   | 1033 |
| Race  | 24   | EastAsian   | 1095 |
| Race  | 24   | Hispanic    |  948 |
| Race  | 24   | Indian      |  834 |
| Gender| 24   | Female      | 2529 |
| Gender| 24   | Male        | 2405 |
|-----------------------------------|
 

### Measuring mean Skew and mean Skew@k
