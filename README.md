

<h1 align="center">UK Charities Network Analysis</h1>


<p align="center">
<img src="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/outputs/gif.gif?raw=true" title="pyvis" height="300">
</p>


<h1 align="center">Technologies Used</h1>
<p align="center">
<a href="https://networkx.org/" target="_blank" rel="noreferrer"><img src="https://networkx.org/_static/networkx_logo.svg" width="150" height="36" alt="NetworkX" /></a>
<a href="https://gephi.org" target="_blank" rel="noreferrer"><img src="https://gephi.org/images/logo.png" width="150" height="36" alt="Gephi" /></a>
</p>


<p align="center">
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a>
<a href="" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/PranavBansal04/UK-Charities-Network-Analysis/46bf18ca9aa275008037f108dcae883385b81d6e/outputs/colab-icon.svg" width="40" height="36" alt="Colab" /></a>
<a href="https://numpy.org/" target="_blank" rel="noreferrer"><img src="https://numpy.org/doc/stable/_static/numpylogo.svg" width="100" height="40" alt="Numpy" /></a>
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"><img src="https://pandas.pydata.org/static/img/pandas_white.svg" width="100" height="38" alt="Pandas" /></a>
<a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/768px-Visual_Studio_Code_1.35_icon.svg.png?20210804221519" width="36" height="36" alt="Visual Studio" /></a>
</p>

# 
# 

<h1 align="center"> Description</h1>
<p align="center">
    <div style="text-align: justify; text-justify: newspaper; margin: 5px 100px">
        The 'voluntary sector' in the UK refers to organisations whose primary purpose is to create social impact
        rather than wealth. It is often called the third sector, civil society, or the not-for-profit sector. The voluntary
        sector is independent from local and national government, and contributed almost £20 billion to the UK
        economy in 2020 which is approximately 0.9% of the total GDP according to NVCO Almanac 2021.
        Charities are the largest single category within the voluntary sector. Due to the lack of availability of data, there have
        been a very few studies done on UK Charities but in the recent times more and more data has become more accessible which makes
        research easier. In particular, the Charity Commission for England and Wales, the primary regulator of registered charities in 
        the UK has made access to its records public. Using this data it is possible to analyse both financial statements and governance
        practices of charities in the UK. In this project we have applied methods from network science to analyse the
        overlap between trustees on different charities and derive quantitative insights about both the non-profit
        organisations and their trustees. This project also focuses on classification of UK charities into multiple categories
        and analysis of grant data. Specifically, we have tried analyzing the flow of funds among these charities. All the research
        work has been done under the supervision of <a href="https://cos.northeastern.edu/people/louis-shekhtman/">Dr. Louis Shekhtman</a> and 
        <a href="https://www.khoury.northeastern.edu/people/albert-laszlo-barabasi/">Prof. Albert-László Barabási</a> at <a href="https://www.networkscienceinstitute.org/">NetSI, Northeastern University</a>.
    </div>
</p>

#
<div align="center" style="margin:20px 0px">
        <img src="https://uploads-ssl.webflow.com/5c9104426f6f88af009ef3ad/5d83de8fdb4091605831e95d_NU_NetworkScienceInstitute_RGB-01-p-500.png" width="260" height="60">
</div>


#
#
<h1 align="center">Key Work done:</h1>

<ul>

<li>Analysis of charity data from <a href="https://www.gov.uk/government/organisations/charity-commission">UK Charity Cmmission</a></li>

<li>Creation of multigraph networks using <a href="https://networkx.org/">NetworkX</a> by linking charities and trustees together</li>

<li>Network visualization using <a href="https://gephi.org/">Gephi</a> and <a href="https://pyvis.readthedocs.io/en/latest/introduction.html#">Pyvis</a></li>

<li>Classification of UK Charities using various methods and categorywise analysis</li>

<li>Analysis of grants data provided by <a href="https://grantnav.threesixtygiving.org/#">360Giving GrantNav</a></li>

<li>Visualization of flow of funds among various regions of UK</li>

<li>Analysis of flow of funds towards Universities in UK</li>

<ul>

#
<h1 align="center">Prerequisites</h1>

<ul>
<li>Numpy</li>

    $ pip install numpy

<li>Pandas</li>

    $ pip install pandas

<li>NetworkX</li>

    $ pip install networkx

<li>Pyvis</li>

    $ pip install pyvis

<li>Gephi</li>

    $ Download from - https://gephi.org/

</ul>

#
<h1 align="center">Getting Started</h1>

Clone the repository:

    $ git clone https://github.com/PranavBansal04/UK-Charities-Network-Analysis.git

Change directory:

    $ cd UK-Charities-Network-Analysis


Now you will be able to see all Ipython notebooks which can be directly uploaded to Google Colab and run.

#

<h3>Files:</h3>

Although the provided notebooks can be run completely independently but following the given order will streamline everything.

- <a href="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/UK_Boards_Network_Initial.ipynb">UK_Boards_Network_Initial.ipynb</a> - contains initial analysis of the data, includes pre processing and cleaning of dataset

- <a href="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/UK_Boards_BFS.ipynb">UK_Boards_BFS.ipynb</a> - includes function for building charity and trustee networks using BFS and exporting network data as gexf

- <a href="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/UK_Charities_Classification.ipynb">UK_Charities_Classification.ipynb</a> - several classifications have been explored for UK charities - ML based, Rules Based etc

- <a href="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/UK_Grants.ipynb">UK_Grants.ipynb</a> - contains analysis of grant data and code for building region network for visualizing flow of funds

#

<h1 align="center">Results:</h1>

Degree distributions for UK charity data:

<img align="center" src="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/outputs/boards_over_trustees.png?raw=true">
<img align="center" src="https://github.com/PranavBansal04/UK-Charities-Network-Analysis/blob/master/outputs/trustees_over_boards.png?raw=true>


## License

[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)