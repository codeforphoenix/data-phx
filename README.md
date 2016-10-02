This is a list of data for public use in the Phoenix metropolitan area and to some extent the state of Arizona. 

You may also be interested in the list of [datasets commonly released](http://us-city.census.okfn.org/about/) by US cities and the [US Open Data Census](http://us-city.census.okfn.org). 

Please send a pull request if you find any data you think would be useful.

### City of Mesa's [Open Data Portal](http://open.mesaaz.gov/home)
- [OpenGIS](http://opengis.mesaaz.gov/)
	- [News Update](http://www.mesaaz.gov/city-hall/open-data/open-data-portal-welcome)
	- [Search Datasets](http://open.mesaaz.gov/search/)
	- [External Data Suggestions](http://www.mesaaz.gov/city-hall/open-data/suggest-dataset)

### City of Phoenix 
- [Open Data Portal](https://www.phoenix.gov/opendata)
- [Mapping Portal](http://maps.phoenix.opendata.arcgis.com/)

### Fire Department
- [Dispatch Information](https://www.phoenix.gov/fire/directory/regional-9-1-1/regional-dispatch-center)
- [Dispatch Listings](https://htms.phoenix.gov/publicweb/Default.aspx) 
  - [Nature codes](https://www.phoenix.gov/firesite/Documents/051051.pdf) (pdf) 
    - Additionally some of this data is free-form (EX: "VEHICLE FIRE","SNAKE REMOVAL","OCTOBERFEST")
    - Numerical Codes can be used to describe some incidents. The last page of [this document](https://www.phoenix.gov/firesite/Documents/074775.pdf) (pdf) covers some of these codes.
  - [Color Code Explanations](https://www.phoenix.gov/firesite/Documents/051002.pdf) (pdf)
  - [Unit Assignent Numbers](https://www.phoenix.gov/firesite/Documents/094635.pdf) (pdf)

### Police Department
- [Aggregate Crime Statistics](https://www.phoenix.gov/police/neighborhood-resources/crime-stats-maps)
- [Outreach Initiatives](https://www.phoenix.gov/police/outreach-initiatives) 
  - Includes data (pdf) re: Officer Involved Shootings, Police Demographics
- [Live Scanner Audio](http://www.broadcastify.com/listen/feed/12145)
- [Phoenix PD Operations Manual](https://www.phoenix.gov/policesite/Documents/operations_orders.pdf) (pdf) 
  - 1,129 pages of police policy and guidelines

### Justice Department

- [Supreme Court Case Lookup](http://apps.supremecourt.az.gov/publicaccess/caselookup.aspx)
- [Department of Corrections Inmate Search](https://corrections.az.gov/public-resources/inmate-datasearch)
  - You can yank the whole database by iterating 0-Infinity
  - Photo URL: `https://apps.azcorrections.gov/mugshots/{number}.jpg`
  - Info URL: `https://adconline.azcorrections.gov/Inmate_DataSearch/PrintInmate.aspx?ID={number}`
- [List of Sex Offenders](https://az.gov/app/sows/AbsconderList.xhtml)
- [Department of Corrections Death Row List](https://corrections.az.gov/node/431)
- [MCSO Mugshot API](http://www.mcso.org/)
  - Searches done via querystring parameters
  - Data only covers the last 3 days
- [DB of all Phoenix metro police departments](https://github.com/meetvasu15/freescale_backup/blob/c8bc37036f1f62ba3d86cbeda45f0679236e527e/Mag/sql/mag.sql)
  - also includes contact information for victims services based on location

### Public Transit

This data includes all bus stops, schedules, and possibly light rail information.

- [Developer Portal](http://phoenix.gov/publictransit/developers/index.html)
- [Google Transit Feed (zip)](http://phoenix.gov/webcms/groups/internet/@inter/@dept/@pubtrans/documents/web_content/google_transit.zip)
- [Transit GIS Data (zip)](http://phoenix.gov/webcms/groups/internet/@inter/@dept/@pubtrans/documents/web_content/phx_transit_gis.zip)
- [DOT GIS Maps](http://www.azdot.gov/maps)
- [Light Rail Shapefiles](https://github.com/adamklawonn/CityCircles/tree/master/citycircles_iphone/citycircles_server/Light_Rail)

### GIS

- [Maricopa County GIS API](http://gis.rdsa.maricopa.gov/rest/services/PlanNet/MapServer)
- [University of Arizona GIS Directory](http://www.library.arizona.edu/help/how/find/maps/gis/maps.html#arizona)

### Places

- [Places to work from](http://jlord.github.io/hack-spots/)

### Environmental Services

- [Health Inspection Reports](http://www.maricopa.gov/envsvc/envwebapp/business_search.aspx?as_type=Food&as_mobile=True)
- [Polluting Businesses](http://www.azdeq.gov/databases/banksearch.html)
  - Shows which business are polluting, which chemicals, how much, lat/lon, etc.
- [Leaking Water Tanks](http://www.azdeq.gov/databases/lustsearch.html)
- [Hazardous Material Incidents](http://www.azdeq.gov/databases/hwssearch.html)
- [List of Drywells](http://www.azdeq.gov/databases/drywellsearch.html)

### Education

- [AIMS Results](http://www.azed.gov/research-evaluation/aims-assessment-results/)
- [Norm-referenced test results](http://www.azed.gov/research-evaluation/norm-referenced-assessment-results/)
- [A-F Letter Grades](http://www.azed.gov/research-evaluation/a-f-accountability/)
- [Graduation Rates](http://www.azed.gov/research-evaluation/graduation-rates/)
- [Dropout Rates](http://www.azed.gov/research-evaluation/dropout-rate-study-report/)
- [Tax Credit Data](http://www.azdor.gov/ReportsResearch/SchoolTaxCredit.aspx)

### Legislature

- [Campaign Finance Contributions](http://www.azsos.gov/cfs/CandidateSummarySearch.aspx)
- [House Bill Search + List](http://www.azleg.gov/Bills.asp?view=allhouse)
- [Senate Bill Search + List](http://www.azleg.gov/Bills.asp?view=allsenate)
- [List of Legislators](http://www.azleg.gov/MemberRoster.asp)
  - Includes contact info and district info
- [House Agenda Schedule](http://www.azleg.gov/CommitteeAgendas.asp?Body=H)
- [Senate Agenda Schedule](http://www.azleg.gov/CommitteeAgendas.asp?Body=S)
