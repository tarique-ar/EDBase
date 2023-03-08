# EDBase: Generating a Lexicon Base for Eating Disorders Via Social Media

The repository contains two csv files: *EDBase_Anwar2022IEEEJBHI.csv* and *EDterms_Pater2016CharacterizingCSCW.csv*

+ *EDBase_Anwar2022IEEEJBHI.csv*: This file contains the EDBase lexicon terms generated in [1]. There are a total of 3794 rows, where each row corresponds to one term and has three columns: "term", "ED score", and "parent term" (in the same order). The seed terms have their ED score as 1 and parent term as null, e.g., "eatingdisorders,1,null". The rest of the terms have their calculated values for them, e.g., "anorexia_nervosa,0.903859306,eatingdisorders". Note that an underscore refers to the "space" character.


<p align="center">
  <img src="https://user-images.githubusercontent.com/114371022/223755030-08eaefa7-27bb-41c9-a759-726d2847c523.png" width="600">
</p>


- *EDterms_Pater2016CharacterizingCSCW.csv*: This files contains the ED terms extracted in [2]. There are a total of 444 terms separated by commas, all being in the same row.

#### References
[1] Tarique Anwar, Matthew Fuller-Tyszkiewicz, Hannah K. Jarman, Mohammad Abuhassan, Adrian Shatte, WIRED Team, and Suku Sukunesan, EDBase: Generating a Lexicon Base for Eating Disorders Via Social Media, IEEE Journal of Biomedical and Health Informatics, vol. 26 no. 12, pp. 6116-6125, 2022

[2] Jessica A. Pater, Oliver L. Haimson, Nazanin Andalibi, and Elizabeth D. Mynatt, "Hunger Hurts but Starving Works": Characterizing the Presentation of Eating Disorders Online, In Proc. of the 19th ACM Conference on Computer-Supported Cooperative Work & Social Computing (CSCW '16), pp. 1185-1200, 2016

If you find our research useful, please consider citing our paper.
```
@ARTICLE{9906413,
  author={Anwar, Tarique and Fuller-Tyszkiewicz, Matthew and Jarman, Hannah K and Abuhassan, Mohammad and Shatte, Adrian and Team, WIRED and Sukunesan, Suku},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={EDBase: Generating a Lexicon Base for Eating Disorders Via Social Media}, 
  year={2022},
  volume={26},
  number={12},
  pages={6116-6125},
  doi={10.1109/JBHI.2022.3211151}}
```

# Contact

[Tarique Anwar](https://www-users.york.ac.uk/~ta1114/)

