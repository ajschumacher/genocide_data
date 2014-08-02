
# Genocide Data

I recently became interested in preventing genocide with data. I think this is not an easy thing to do. I undertook to identify data sources that might be relevant, and thanks to many wonderful people, I can present the following results!


###\#1. Karen Payne's "[GIS Data Repositories](https://docs.google.com/spreadsheet/ccc?key=0AuApi46szKw4dDhVM1dZNmpld3dIQWdRS2NnRkZDQWc&usp=drive_web#gid=47)", "[Conflict](https://docs.google.com/spreadsheet/ccc?key=0AuApi46szKw4dDhVM1dZNmpld3dIQWdRS2NnRkZDQWc&usp=drive_web#gid=54)" section.

[Karen](http://www.cviog.uga.edu/faculty-staff/paynek) has assembled a phenomenal collection of references to datasets, curated within a publicly accessible Google spreadsheet. I'm sure many of the other things I'll mention are also included in her excellent collection!

> This list of data repositories was compiled by [Karen Payne](http://www.cviog.uga.edu/faculty-staff/paynek) of the [University of Georgia's Information Technologies Outreach services](http://www.cviog.uga.edu/itos), with funding provided by [USAID](http://www.usaid.gov/), to point to free downloadable primary geographic datasets that may be useful in international humanitarian response. The repositories are grouped according to the tabs at the bottom


###\#2. The [Global Database of Events, Language, and Tone (GDELT)](http://gdeltproject.org/)

[Kalev Leetaru](http://www.kalevleetaru.com/) of [Georgetown University](http://www.georgetown.edu/) is super helpful and runs this neat data munging effort. There is a *lot* of data available. The [GDELT Event Database](http://data.gdeltproject.org/events/index.html) uses [CAMEO codes](http://eventdata.parusanalytics.com/data.dir/cameo.html); in [this scheme](ttp://data.gdeltproject.org/documentation/CAMEO.Manual.1.1b3.pdf), there is code "203: Engage in ethnic cleansing". There's also the [Global Knowledge Graph (GKG)](http://data.gdeltproject.org/gkg/index.html) which may be better for identifying genocide, because one can identify "Material Conflict events that are connected to the genocode theme in the GKG."

GDELT is now [listed](http://catalog.data.gov/dataset/global-database-of-events-language-and-tone-gdelt-project) on [data.gov](http://www.data.gov/) in coordination with the [World Wide Human Geography Data working group](https://wwhgd.org/).

[Jay Yonamine](https://twitter.com/jay_yonamine) did [some work](http://jayyonamine.com/?p=645) using GDELT to forecast violence in Afghanistan.


###\#3. The [Humanitarian Data Exchange](http://data.hdx.rwlabs.org/)

This new project seems very promising - [Javier Teran](https://twitter.com/JTeran2000) was very helpful in describing what's currently available: "datasets on refugees, asylum seekers and other people of concern in our HDX repository that may be useful for your research". By the time you read this, there may be even more genocide-related data!


###\#4. [Uppsala conflict database](http://www.pcr.uu.se/research/ucdp/datasets/)

> The Uppsala Conflict Data Program (UCDP) offers a number of datasets on organised violence and peacemaking, all of which can be downloaded for free


###\#5. [USHMM](http://www.ushmm.org/) / [Crisis in Darfur](http://www.ushmm.org/learn/mapping-initiatives/crisis-in-darfur)

[Max](http://richmanmax.com/) writes:

> the [National Holocaust Museum](http://www.ushmm.org/) has done quite a bit about collecting and visualizing this kind of data.  In particular, a few years back they led a [large mapping project around Darfur](http://www.ushmm.org/learn/mapping-initiatives/crisis-in-darfur)


###\#6. AAAS [Geospatial Technology and Human rights topic](http://www.aaas.org/topics/geospatial-technologies-and-human-rights)

The [American Association for the Advancement of Science](http://www.aaas.org/) has a collection of research related to [Geospatial Technology and Human rights](http://www.aaas.org/topics/geospatial-technologies-and-human-rights). Start reading!


###\#7. [Amnesty International](http://www.amnesty.org/)

I haven't looked into what data they might have and make available, but it seems like a relevant organization.


###\#8. [Tech Challenge for Atrocity Prevention](http://www.thetechchallenge.org/)

[USAID](http://www.usaid.gov/) and [Humanity United](http://www.humanityunited.org/) ran a group of competitions in 2013 broadly around fighting atrocities against civilians. You can read about it via [PR Newswire](http://www.prnewswire.com/news-releases/innovative-thinkers-from-around-the-world-create-new-technologies-for-predicting-mass-atrocities-231592141.html) and [Fast Company](http://www.fastcoexist.com/3022972/when-and-where-will-atrocities-will-occur-this-algorithm-knows). I found the modeling challenge particularly interesting - it was hosted by [TopCoder](http://www.topcoder.com/), as I understand it, and the [winners](http://thetechchallenge.org/winners/model.html) came up with some interesting approaches for predicting atrocities with existing data.


###\#9. [elva.org](http://elva.org/)

This is a tip I haven't followed up on, but it could be good:

> Hi, I would reach out to Jonne Catshoek of [elva.org](http://elva.org/), they have an awesome platform and body of work that is really unappreciated. They also have a very unique working relationship with the nation of Georgia that could serve as a model for other work.


###\#10. The [CrisisMappers](http://crisismappers.net/) community

"The humanitarian technology network" - this group is full of experts in the field, organizes the International Conference of Crisis Mappers, and has an active and helpful [Google Group](https://groups.google.com/forum/#!forum/crisismappers). The group is closed membership but welcoming; connecting there is how I found many of the resources here. Thanks CrisisMappers!


###\#11. [CrisisNET](http://crisis.net/)

The illustrious [Chris Albon](https://twitter.com/chrisalbon) introduced me to [CrisisNET](http://crisis.net/), "the firehose of global crisis data":

> [CrisisNET](http://crisis.net/) finds, formats and exposes crisis data in a simple, intuitive structure that’s accessible anywhere. Now developers, journalists and analysts can skip the days of tedious data processing and get to work in minutes with only a few lines of code.

Examples of what you can do with it:

 * [Tracking War in Gaza using Facebook](http://blog.crisis.net/tracking-gaza-at-war-using-facebook/)
 * [Mapping Refugees and Fighting in Iraq with UNHCR and Social Media](http://blog.crisis.net/mapping-refugees-in-iraq/)
 * [Tracking Syrian Barrel Bombs](http://blog.crisis.net/tracking-syrian-barrel-bombs/)

Tutorials and documentation on how to do things with it:

 * [Get Crisis Data with Python and pandas](http://blog.crisis.net/get-crisis-data-with-python-and-pandas/)
 * [Making large CrisisNET requests with Python](http://blog.crisis.net/making-large-crisisnet-requests-using-python/)
 * [Export CrisisNET data to CSV with Python](http://blog.crisis.net/export-requests-to-csv-with-python/)
 * [Functional Programming in Python for Crisis Data Bliss](http://blog.crisis.net/functional-programming-in-python-for-crisis-data-bliss/)
 * [Choropleth Maps with D3](http://blog.crisis.net/choropleth-maps-with-d3/)
 * [API documentation](http://api.crisis.net/page/documentation)


###\#12. PITF

All I know is that PITF could be some sort of relevant dataset; I haven't had time to investigate.


#### This document

I'll post this on [my blog](http://planspace.org/), where it's easy to leave comments with additions, corrections, and so on without knowing git/github, but the "official" version of this document will live [on github](http://github.com/ajschumacher/genocide_data/) and any updates will be made there. Document license is Creative Commons Share-Alike, let's say.


#### More thanks:

 * Thanks of course to everyone who provided help with the resources they're involved with providing and curating - I tried to give this kind of credit as much as possible above!
 * Special thanks to [Sandra Moscoso](https://twitter.com/sandramoscoso) and Johannes Kiess of the [World Bank](http://www.worldbank.org/) for providing pointers to number 2 and more!
 * Special thanks to [Max Richman](http://richmanmax.com/) of [GeoPoll](http://research.geopoll.com/) for providing numbers 4, 5, 6, and 7.
 * Special thanks to [Minhchau "MC" Dinh](https://twitter.com/minhchaudinh) of [USAID](http://www.usaid.gov/) for extra help with number 8!
 * Number 9 was provided via email; all I have is an email address, and I thought people probably wouldn't want their email addresses listed. Thanks, person!
 * Special thanks to [Patrick Meier](https://twitter.com/PatrickMeier) of [iRevolution](http://irevolution.net/) for connecting me first to number 10!
