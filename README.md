# Updated CBL
This repo builds on the original CBL (McCauley & Christiansen 2019a) and additionally:
- implements the frame detection logic from McCauley & Christiansen (2019b)
- allows to switch the detection of chunk boundaries from backwards transitional probabilities to PMI or normalized PMI (Bouma 2009)
- expands the frame detection logic to also accommodate chunks as slot elements in frames
- makes the frame frequency criterion flexible (cf. Cameron-Faulker, Lieven & Tomasello 2003; Bunzeck & Diessel 2025)

If you use this code, please cite the following paper:
- McCauley, S. M., & Christiansen, M. H. (2019a). Language learning as language use: A cross-linguistic model of child language development. *Psychological Review*, 126(1), 1–51. https://doi.org/10.1037/rev0000126

## How to use it
In order to run the CBL model on an input corpus, the corpus must be appropriately cleaned/prepared. 

The folder "Sample Corpora" includes detailed instructions for corpus preparation, along with a sample corpus ("anne_excerpt.capp") and a toy corpus ("toy_data.capp"). 

The same folder also includes instructions for creating the "gold standard" shallow parse used to evaluate the model's shallow parsing performance, 
along with an example of a gold standard file. 

## References
- Bouma, G. (2009). Normalized (Pointwise) mutual information in collocation extraction. In C. Chiarcos, R. E. de Castilho, & M. Stede (Eds.), *From Form to Meaning: Processing Texts Automatically*, Proceedings of the Biennial GSCL Conference 2009 (S. 31–40). Gunter Narr Verlag. https://svn.spraakdata.gu.se/repos/gerlof/pub/www/Docs/npmi-pfd.pdf
- Bunzeck, B., & Diessel, H. (2025). The richness of the stimulus: Constructional variation and development in child-directed speech. *First Language*, 45(2), 152–176. https://doi.org/10.1177/01427237241303225
- Cameron‐Faulkner, T., Lieven, E., & Tomasello, M. (2003). A construction based analysis of child directed speech. *Cognitive Science*, 27(6), 843–873. https://doi.org/10.1207/s15516709cog2706_2
- McCauley, S. M., & Christiansen, M. H. (2019a). Language learning as language use: A cross-linguistic model of child language development. *Psychological Review*, 126(1), 1–51. https://doi.org/10.1037/rev0000126
- McCauley, S. M., & Christiansen, M. H. (2019b). Modeling children’s early linguistic productivity through the automatic discovery and use of lexically-based frames. *Proceedings of the Annual Meeting of the Cognitive Science Society*, 41. https://escholarship.org/uc/item/644529zb