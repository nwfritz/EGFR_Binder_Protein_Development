Mini Project 2
Project Overview
This project is part of a course module, focusing on data analysis and signal processing using Python. It applies various computational techniques to address real-world problems, guiding users through data processing, model implementation, and analysis.

Requirements
Python 3.x
Jupyter Notebook
Libraries: numpy, pandas, matplotlib, scipy, sklearn
Ensure all packages are installed before running the notebook.
Sections in the Notebook

Introduction: Outlines the project's objectives and significance.

Data Import and Preprocessing: Steps to load, clean, and prepare data.

Exploratory Data Analysis (EDA): Visual and statistical methods to gain insights.

Signal Processing Techniques: Application of methods such as Fourier transforms and filtering.

Machine Learning Models: Model implementation and performance evaluation.

Results and Discussion: Analysis of outcomes and key findings.

Conclusion: Summarizes results and discusses future directions.

How to Run the Notebook
Clone this repository or download the notebook file.
Open it in Jupyter Notebook or JupyterLab.
Execute each cell in order to reproduce the results.

Results
After Running the Code 5 Different Times With Different inputs my Top 5 Protein Sequences were the Following...
1. ELEKKVEELLKELESKEIKDNIDEAKLKLCKDALKTYKECIKNSGEECTKVRLKYYFKALLIKGFWEAVAEVEKEKKEEIKKKVEKEWKIVEETEKLLYEILKEKKKKEGKEEELEKNEKEFEKKKKELEKKIEEIAKKLAEMLKYLKKIAEKLGEEYLKKLEELKEEIAKLLLLDDIKEALEKIKKLVEEFLKEAKEKKEKEFKEILEKDKEGNKEKVEKEKKEFEELIEKAKKAMEEAIKLIEELIKE - MLM Loss: 6.507120132446289
2. DLEEEVEALLAEEEAKPIEDLIDAARRALMRRIKETYEECIKNSGEEATKIRLKYYLRRLLIREFWAAVAAVRPERAAEIRARVDAAWEGVDRFEKLCEEILKKTKKEKGETEKLEENEKKFKEESEKLEEKMKEWGAELAEALKAARAIAERLGEEWLARLEALVERIAELLLQEDLAAALEAIRALGDAWLAEARAEHEARLAALLAEDPEGLSAELAAERAAFDALAAAAKAALDKAAAIAKEMIAE - MLM Loss: 6.586499849955241
3. SLEEKIAALIAELEAQEVKTLIDLETKILCKEIRETYAAAIANTGAEAADALLKTYFRYLLRKGFWDALAAVRPAEAAALKAEVEAGLKVVEELAKLCGAVLVATKTAAGHTAALAAQNATFNAAKAELEKKMKEVAKLLAEALAALRALAERAGPAALAELDALVEELARLLSLEDLEKAIEEMRALVAARLAALAAEHDAAAAARLAADPAGNAEAVAADRAAFAAAAAAAKKAADEAAKLLKEGIKK - MLM Loss: 6.590275128682454
4. EEIIKKQSELIDKIIKHLEDLKKKLEENFLKLLEKIEKLLYKKALKENPEVTKKMVEKMKKEYEKLLEEKKKKLEEIVKKTKEAIEKGDLEKAEEYVKKFMETIKESEKELLKLREKFLKEAKKLAKKLGLSETLVDLVKALSLKYETKLLILTIEKLIELFKELKSEKFKEKAFEYCKKLYELFSKILEKTLEEILKETKELIKKLGTSEEEQKELEELLKKVEKDIKEFKKKKEELEKEIKKLEKELK - MLM Loss: 6.61924934387207
5. MEELEKELKKKLGEAWEIFKEGIEILLGDSEEAKVLKEEIDKVFKTKSFEEQIKYFTDYFVTVGGKVADQLVKEGKKALEALKKFLEGLKLLLEALLEYVKKTGKKSKELIKNTSRILEALKKLLKKLIEYIKELLKKGVSDENIEELKKVLEVLKLALEALKICLELIAEQLEKVSEVLKKALELAEEALKLVEEAEKLLEELLKEKSEEEKKKLYEKLKKVLKEIIKKIEELIKLTEELLKEIEKLLK - MLM Loss: 6.623129208882649

The scores for my best protein were:  mpnn:1.057 plddt:0.900 ptm:0.822 pae:5.817 rmsd:2.620

They were all from the same inputs and from the 4th run of this project.

The inputs were:
Name: EGFR
Contigs: 250
pdb: GARU
Iterations:25
Hotspots:A-11
num_designs: 4
Symmetry: None
Order: 1
Chains: A
Num_Seqs: 8
Initial_Guess: True
Num_Recycles: 12
Rm_aa = ""
mpnn_sampling_temp: 0.1

W
References:

Schreiber, Amelie. Protein Binding Partners with ESM2. Hugging Face Blog.
Diffusion Model Reference: Concepts and methods taken from the diffusion.ipynb provided in the project files
