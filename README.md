# GiantVirusMarkersInProtists

## Project Overview

This project investigates the presence of viral-like genes in protist species to explore possible ancient viral integration events. Using protein datasets from diverse protists and known viral marker genes, I perform homology searches, analyze significant hits, and visualize the results to understand viral footprints in protist genomes.

---

## Datasets

- **Protist Protein Datasets:**  
  Protein sequences for the following protist species were collected from the NCBI protein database:  
  - *Euglena gracilis*  
  - *Naegleria fowleri*  
  - *Trypanosoma brucei*  

- **Viral Marker Genes:**  
  Known viral marker proteins such as DNA polymerase B, RNA polymerase, and capsid proteins from giant viruses (e.g., ASFV, Mimivirus) were used as queries for homology searches.

---

## Methodology

1. **Dataset Collection:**  
   Protein sequences for the target protists were downloaded programmatically using Biopython Entrez API.

2. **Homology Search:**  
   BLASTp was used to find homologous sequences between viral marker proteins and protist proteomes.

3. **Analysis:**  
   Significant hits were extracted, aligned, and analyzed to assess similarity.

4. **Visualization:**  
   Results were visualized using bar plots and heatmapsto summarize viral-like gene distribution and similarity.

---

## Tools & Libraries

- [Biopython](https://biopython.org/) — sequence handling and NCBI API access  
- [NCBI BLAST+](https://blast.ncbi.nlm.nih.gov/Blast.cgi) — local and remote BLASTp searches  
- [pandas](https://pandas.pydata.org/) and [matplotlib](https://matplotlib.org/) — data analysis and plotting  

---

## How to Run

1. Clone the repository or download the notebook files.  
2. Run the dataset collection notebook section to download protist protein sequences.  
3. Run the homology search section to perform BLASTp with viral marker genes.  
4. Analyze and visualize the results using provided code cells.  
5. Review the summary and conclusions in the final notebook section.

---

## Contact

For questions or collaboration, please contact:  
**Laiba Asif**  
Email: laibasif99@gmail.com

---

## Acknowledgements

Thanks to the NCBI database for providing protein sequence data and to Biopython developers for easy data retrieval and processing.

---

## License

This project is licensed under the MIT License.
