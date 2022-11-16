# Protected-Attribute Tag Association dataset

This dataset is a proposed benchmark for measuring biases in Vision-Language models like OpenAI CLIP. It consists of a list of images organized as a set of scenes, and a set of captions applicable to each scene, organized according to specific protected attributes. We consider the binary gender, 5 ethno-racial groups (Black, Caucasian, East-Asian, Hispanic-Latino and Indian), and 2 age categories (young, old). 

### Distribution of images in the different protected attribute groups

<table>
<tr>
<td>Attribute</td><td>Scenes</td><td>Label</td><td>Count</td>
</tr>
<tr><td>Age</td><td>8</td><td>Young</td><td>3748</td></tr>
<tr><td>Age</td><td>8</td><td>Old</td><td>1186</td></tr>
<tr><td>Race</td><td>24</td><td>Black</td><td>1024</td></tr>
<tr><td>Race</td><td>24</td><td>Caucasian</td><td>1033</td></tr>
<tr><td>Race</td><td>24</td><td>EastAsian</td><td>1095</td></tr>
<tr><td>Race</td><td>24</td><td>Hispanic</td><td>948</td></tr>
<tr><td>Race</td><td>24</td><td>Indian</td><td>834</td></tr>
<tr><td>Gender</td><td>24</td><td>Female</td><td>2529</td></tr>
<tr><td>Gender</td><td>24</td><td>Male</td><td>2405</td></tr>
</table>

### Measuring mean Skew and mean Skew@k
