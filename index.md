# The Matrix: connecting and re-using digital records and archives of archaeological investigations

## Contents
* <a href="#a">Archaeological Process & Data Modelling</a>
* <a href="#b">Digital Data & Stratigraphic Standards
* <a href="#c">Matrix – Stratigraphic & Temporal Relations and Chronological Modelling
* <a href="#d">Re-use of digital data
* <a href="#e">Phaser - prototype Grouping and Phasing software tool
* <a href="#f">References	
* <a href="#g">Contact the Project team:
* <a href="#h">Acknowledgements

Archaeologists, are particularly concerned to make sure that the digital records of excavations are digitally archived and preserved safely for future research, because an archaeological excavation cannot be repeated. Once the archaeology is dug away then often the digital record is all that remains to enable future researchers to  understand what was discovered. This focus on preservation has helped address the principle concerns about "how do we keep this stuff digitally". But although there are now a number of well established digital archives, such as [The Archaeology Data Service](https://archaeologydataservice.ac.uk/) at the University of York, the next challenge is whether the data are preserved and accessible in ways that make that data most useful to others beyond the archives and the archivists?
  
##<a name="a">Introductory Video recording from a Research Seminar on The Matrix Project presented for MOLA archaeologists on 15-07-2021 </a> - opens in YouTube
[![Matrix Research Seminar for MOLA](/images/Matrix_Seminar.jpg)](https://www.youtube.com/watch?v=ffYAx60ILoU)

This project will investigate how digital data from archaeological excavations can be made more useful and beneficial to a range of users and audiences. It will produce a plan and methods to get such data more consistently recorded, analysed, disseminated and archived in a way that is Findable, Accessible, Interoperable and Re-useable ([FAIR](https://www.force11.org/group/fairgroup/fairprinciples)).

![Archaeologist Recording](/images/Archaeologist_Recording_KM.jpg) 

## <a name="a">Archaeological Process & Data Modelling</a>
The stratigraphic record, usually in some form of a stratigraphic matrix, with associated relationships and data, acts as a primary, if not the primary piece of _**evidence**_ for how, and in what order, the site was excavated. As such the stratigraphic matrix (often known as a “Harris Matrix”) is the key mechanism that enables anyone less familiar with the site, to re-visit the excavation records, understand what data is most relevant for any particular research questions, or problems encountered, and piece together the underlying details of how the interpretations by the excavator(s) were actually arrived at. 

![Harris 1979 – Fig2 & Historic England Recording Manual - 2015](/images/rope_of_time.png)

However, such records are often only held on paper or scanned copies of matrix diagrams that cannot easily be re-used with associated data. Often the key archaeological phasing data created in analysis and needed for synthesis work and interpretive understanding in written reports, is not so well documented or archived and shared consistently, if at all. This results in key records being unsearchable or remaining unconnected to other data and at best usually requires lengthy and wasteful re-keying if any one wishes to work with the archives from such sites.

![Harris 1979 – Fig2 & Historic England Recording Manual - 2015](/images/Phase_diagram.png) 

<https://en.wikipedia.org/w/index.php?title=Phase_(archaeology)&oldid=928228844>

## <a name="b">Digital Data & Stratigraphic Standards
">Digital Data & Stratigraphic Standards
The Matrix project will address current problems caused by the lack of standardized approaches to digital archiving of such archaeological data using the particular case study of stratigraphic and phasing data. Stratigraphic data form the backbone of all the related archaeological records from each excavated site and are essential for integrated analysis, wider synthesis and accessible archiving of the growing body of archaeological data and reports generated through the commercially funded archaeological sector as well as academic research in the UK and internationally.

![Matrix - Stratigraphic & Allen Temporal Relations](/images/Matrix_Temporal_Relations.png)
_Allen temporal operators explicitly highlighted in a matrix diagram from Silbury Hill ([Silbury Hill digital archive](https://archaeologydataservice.ac.uk/archives/view/silbury_eh_2014/) from ADS)_

## <a name="c">Matrix – Stratigraphic & Temporal Relations and Chronological Modelling
One difference between a Bayesian chronological model and an archaeological sequence diagram is that the Bayesian chronological model may include temporal relationships that cannot be expressed by just using the stratigraphic Before/After/Equals as defined by the Harris matrix. The Matrix project will explore whether more explicit use of Allen temporal operators and temporal primitive relationships in stratigraphic analysis processes can aid in the generation of digital data for use in chronological modelling, and better re-use of stratigraphic data in digital archives.

![Matrix - Stratigraphic & Temporal Relations and Chronological Modelling](/images/Dye_Buck_DAG.png)

_Example Directed Acyclic Graph (DAG) for chronological modelling - Dye & Buck 2015_

## <a name="d">Re-use of digital data
The focus of digital archaeological archives and museums is now switching from simply providing better access to digital archives, to questions of how are users in commercial units, curatorial organizations and academics, along with members of the public, going to make best use of this growing body of digital information and data.
A process model output will enable the research team to distil and demonstrate the most common approaches, data flows, and processes used in the life-cycle of the relevant data. Prototype software can then be used as a vehicle to explain and present to end users and other audiences how the data flows through and between different data systems and activities.

## <a name="e">Phaser - prototype Grouping and Phasing software tool
The Prototype _**is not intended currently to be fully functioning**_ Matrix recording and Stratigraphic Phasing analysis and archiving software.  It would need more development and administrative work to make it available e.g. as Open and FAIR software through an online tool with suitable registration for an archaeological community of users.

The Prototype _**is designed to enable demonstration**_ and an overview of what we have developed so far in the Matrix project and particularly to elicit feedback from the archaeological community on what such an online tool might need to do to encourage archaeologists involved in Post-excavation analysis to use it and support it’s improvement and sustainability through its development life-cycle.

Please note that in the current prototype stage _**it is not recommended to try loading a CSV file with more than around 500 individual context records**_. Depending upon feedback on this initial development, the software could be further developed to enable larger numbers of records, but this would require more time spent in the second half of the Matrix project on testing and resolving scaleability issues. 

The prototype is currently available from the following web link: [https://cbinding.github.io/tmp123/](https://cbinding.github.io/tmp123/)

An example test data set is available here: [https://raw.githubusercontent.com/stratigraphic/matrix/main/CTD2021-Test-Data/CTD2021-phaser-20210504114322-with-Dating-test-data.json](https://raw.githubusercontent.com/stratigraphic/matrix/main/CTD2021-Test-Data/CTD2021-phaser-20210504114322-with-Dating-test-data.json) 

Here is a short video clip explaining how to Import a CSV file into Phaser software 
<video width="320" height="240" controls>
  <source type="video/mp4" src="https://github.com/stratigraphic/matrix/blob/gh-pages/images/Importing_CSV_file_example5.mp4?raw=true">
</video>

Or make your own .CSV file data set using the following 5 key fields with the matching field name headings.
CSV column heading names need to be exactly as spelt below:
* siteCode
* contextNo
* contextType
* stratRelationship
* relatedContextNo

## <a name="f">References
* Allen, J.F. (1983) 'Maintaining Knowledge about Temporal Intervals'. Communications of the ACM 26, 11, 832-843.
* Binding, C. (2010) Implementing archaeological time periods using CIDOC CRM and SKOS. The Semantic Web: Research and Applications : ESWC 2010.
* Dye, T.S. & Buck, C.E. (2015) Archaeological sequence diagrams and Bayesian chronological models. Journal of Archaeological Science, 63. 84 - 93. 
* Harris, E.C. (1979) The Laws of of Archaeological Stratigraphy. World Archaeology Vol. 11, No1. 
* May, K. 2020 The Matrix: Connecting Time and Space in Archaeological Stratigraphic Records and Archives, Internet Archaeology 55. <https://doi.org/10.11141/ia.55.8> 
* Roskams, S. (2001) Excavation. Cambridge: Cambridge University Press. 
* Tudhope, D., May, K., et al. (2011) 'Connecting Archaeological Data and Grey Literature via Semantic Cross Search', Internet Archaeology 30. <https://doi.org/10.11141/ia.30.5>

## <a name="g">Contact the Project team: 
* Keith May     PI - Historic England and University of South Wales - Keith.May(at)HistoricEngland.org.uk
* Ceri Binding  RA - University of South Wales
* James Taylor  RA - University of York

## <a name="h">Acknowledgements
AHRC grant AH/T002093/1 <https://gtr.ukri.org/projects?ref=AH%2FT002093%2F1>

![Acknowledgements](/images/Acknowledgement_logo_group.png)


### Matrix Project additional info on ResearchGate: <https://www.researchgate.net/project/The-Matrix-connecting-and-re-using-digital-records-and-archives-of-archaeological-investigations  >


