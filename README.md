# election-analysis
# Elections Anaylsis

# *INTRODUCTION*

This Repository holds information associated with the Election analysis.It currently holds information about the elections result common data format(CDF)project
this  format, known as the Election Results Common Data Format Specification, is comprehensive and detailed in its coverage of election results.
 this format is for exchanging election  data from voting systems used for managing
elections and tabulating election results across states and Districts
 The format serves as a basic export of election information from an election management system (EMS) to news media and general public
The format accommodates highly detailed election results data and is sufficiently flexible 
to accommodate many different types of contests and political structures. 
>  THE GRAPHICAL REPRESENTATION OF THE MAP ALONG WITH CURRENT RULING PARTIES


# *The primary features of this specification are:*


The primary features of this specification are:

1.  Major data elements and their attributes and associations are fully defined .
2.  Election data and results can be reported at flexible levels from highly aggregated to very detailed.
3.  Detailed reporting includes the ruling party along with the color of that party and year specified with it.
4.  Geopolitical units of geography can be specified in a flexible manner to mirror reporting structures used across states and districts.
5. Election:
The period during which an election is being conducted and election results reports are produced. 
The reports include aggregated results data or more detailed, precinct-level reporting, depending on the capabilities of the reporting jurisdiction.


# *PURPOSE*

Election analysis CDF project has the goal of specifying format for election management system. this model represent the various objects like(states,Districts)
and their associated attributes, and specifies the relationships between and among the objects
Election results can be reported directly from election offices in this format regardless of voting system manufacturer,
thus enabling interoperability

There are currently 4 sets of requirements located in this repository that are related to interoperability and the CDFs:

1.  Principles & Guidelines 01. - High Quality Design

2.  Principles & Guidelines 02. - High Quality Implementation

3.  Principles & Guidelines 03 - Transparency

4.  Principles & Guidelines 04 - Interoperability

# *PDLC(Project Development Life Cycle)*
the project consists of the following process:

1.  collecting dataset.
2.  filtering the dataset.
3.  visualization of dataset using geopandas.
4.  creating interactive maps using bokeh.

# *INSTALLATION*

*  Prerequisites:
1.  ubuntu or windows

*  TECHNOLOGIES

1.   phyton

2.  pandas

3.  geo pandas

4.  Bokeh
# *Data*
India maps shaply files are form [arcgis.com](https://www.arcgis.com/home/item.html?id=cf9b387de48248a687aafdd4cdff1127)
# *Bokeh Documentation*
bokeh documentation [here](https://docs.bokeh.org/en/latest/index.html)
# *MOTIVATION*

This specification was motivated primarily to reduce the inherent complexity for election officials in collecting and publishing election data, 
The process of reporting election results is a highly complicated activity that occurs over several different time frames and in multiple scenarios.



# *GEOPOLITICAL GEOGRAPHY*

The primary types of geopolitical geography include those geographies that run elections such as states,
 electoral districts .Generally, the media and election analysts wish to obtain voting results broken out by these units, thus the process of running an election includes
 associating contests and vote counts with these units so that they can be ultimately reported.
  The following sections break down geopolitical geography into three primary types and show how the geographies interrelate. These three types are:


1.  Governmental-based geography
2. Political-based geography
3. Administrative-based geography.

# *GOVERNMENTAL-BASED GEOGRAPHY* 


Governmental-based geography refers to entities that (1) run elections and (2) are well-established and do not change over time, 
with the exception of some cities. 
For many states, the governmental-based geography is hierarchical.
Governmental-based geographies are associated with
offices that are elected jurisdiction-wide such as for Governor, County Clerk, Supervisor, Treasurer, Assessor, Highway Commissioner.

# *POLITICAL-BASED GEOGRAPHY*

Political-based geographies are those that tend to be population-based and therefore may change with each 
Census every 10 years in a process known as re-districting. Political-based geographies are generally known as electoral districts.

# *CONTRIBUTORS*

1. J.Bharathi Parasad

2. P.Ashrith Kumar

3. M.Saahith Reddy

4. G.Manikanta
