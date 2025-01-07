# Extracting structured information from unstructured text

## Short summary
The aim of this investigation was to develop a computational methodology for automating the extraction and linkage of terms of interest from digitised historical datasets. We experimented with two approaches: the first used regex and NER methods whilst the second used generative AI and a few-shot prompting strategy.

In automating the extraction of information, we hoped to facilitate the construction of knowledge graphs to more easily create linkages between collections objects, people, historic buildings, trades etc. Whilst it is possible to use Generative AI to construct knowledge graphs directly from unstructured information, in this investigation we divided the process into two sections in order to better understand the techniques for automating information extraction before adding in the additional complexity of graph creation.  



## People 
**Nayomi Kasthuri Arachchi**: Conceptualization, Formal analysis, Methodology, Software, Validation, Writing - original draft, Writing - review & editing 

**Alex Butterworth**: Conceptualization, Data curation, Investigation, Methodology, Resources, Supervision, Writing - original draft, Writing - review & editing

**Felix Needham-Simpson**: Data curation, Formal analysis, Software 




## Data
Digitised extracts from:
- Trade Directories for Bradford and environs e.g. Lund’s, White’s, Ibbetson’s and those from the Leicester collection
- Textile business records (see Hudson, Pat. The West Riding Wool Textile Industry: A Catalogue of Business Records from the Sixteenth to the Twentieth Century. Edington, Wiltshire: Pasold Research Fund, 1975)
- Patents of invention (see Woodcroft, Bennet. Titles of Patents of Invention, Chronologically Arranged: From March 2, 1617 (14 James I) to October 1, 1852 (16 Victoriæ). London: G.E. Eyre and W. Spottiswoode, 1854)
- An architectural survey of textile mills (see Giles, Colum, and Ian H. Goodall. Yorkshire Textile Mills: The Buildings of the Yorkshire Textile Industry, 1770–1930. London: HMSO, 1992)



## Method

## Tools
- Jupyter notebooks (hosted and tested in Google Colab running Python 3.10.12)
- Python
- OpenAI GPT 4o-mini

## Outputs
- A set of routines for applying few-shot prompting for structured data extraction that can be generalised for use on a wide range of CSVs containing historical records. The example notebooks contributed to this repo are specified below. 



## Key initial findings








## Licence 
This work is licensed under a [Creative Commons Attribution 4.0 License - CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
