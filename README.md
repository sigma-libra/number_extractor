# Number Extractor

## The problem

[Here is a large pdf document](https://www.saffm.hq.af.mil/Portals/84/documents/FY25/FY25%20Air%20Force%20Working%20Capital%20Fund.pdf?ver=sHG_i4Lg0IGZBCHxgPY01g%3d%3d). We want to find the largest number in this document. The unit is not important (could be dollars, years, pounds, etc), we're just looking for the greatest numerical value in the document.

For a bonus challenge if you have time, take natural language guidance from the document into consideration. For example, where the document states that values are listed in millions, a value of 3.15 would be considered to be 3,150,000 instead of 3.15.

## Instructions to run

### Using jupyter notebook

1. Install python3 and pip3 
2. Install jupyter notebook: https://jupyter.org/install
3. Install the python libraries listed at the top of the notebook
```
pip install PyPDF2
pip install numwords_to_nums
pip install spacy
python -m spacy download en_core_web_sm
```
4. Run the notebook

