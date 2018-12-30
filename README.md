# BIAccelarator

Readme file edited with [Dillinger].

BIAccelator is a web platform that automates BI implementation tasks.
Features already implemented include Extraction tasks (built on top of SSIS) from other databases (supporting OLEDB connections).

This features include:

  - Manage the flow easily with a web interface
  - Collect Source database metadata
  - Create all staging database structure as a copy of your sources
  - Create SSIS project to Extract data and load to your staging database **(Under development)**

From this point forward you are on your own until new releases to this project

# New Features!

  - Automated SSIS deploy **(in progress)**
  - Schedule ETL run jobs **(in progress)**

### Tech

BIAccelator uses the following technologies and libraries (all credits included to the authors):

* .NET MVC
* SSIS
* SQL Server
* [EzAPI] - Automate your SSIS implementation (for SQL Server 2016). Programmatically create SSIS packages and projects.


### Todos

 - Automate project deployment to the SQL Server
 - Deployed project scheduling
 - Data Warehouse creation and implementation of CDC table load types (0, 1, 2)
 - SSAS Automated creation and deploy
    - Structure Creation (Tables and Relationships)
    - Deploy to SSAS
    - SSAS partitions processing

License
----

GNU GENERAL PUBLIC LICENSE Version 3


**Free Software. Keep it free to others as well.**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>
   [EzAPI]: <https://github.com/fpvmorais/EzApi2016>
   [Dillinger]: <https://dillinger.io/>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
