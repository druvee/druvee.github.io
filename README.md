# druvee.github.io
Welcome to Andrew Volz's github page. Since mid 2019, this page hosts an collection of small tools and open source projects related to urban planning and real estate analysis that I am currently working on.
The bulk of the projects here are personal interest or reflect issues I've identified professionally but do not have (and are unlikely to ever recieve) funding for due to their niche appeal or archival nature.
Academic work is forthcoming pending licensing.
A few links to professional projects have been included as well, but source code is limited to those were a public interest and licensing overrides private interests.
# Projects
## Assessment of Fair Housing Tools
[Community Analysis Tool](http://fairhousing.tools)

Created in collaboration with the Chicago Area Fair Housing Alliance, the Community Analysis Tool allows community members to explore discrepancies in life outcomes in context of the availability of family rental housing within Cook County Municipalitites. The tool relies on a Python data aggregation and analysis pipeline which feeds into a Dash application. The tool furthers work completed in our 2018 report, [*A City Fragmented*](https://www.povertylaw.org/aldermanic-report)
## Community Development Advisory Council Districting
evoDistrict (repo currently private)

Created in collaboration with the Chicago Area Fair Housing Alliance, evoDistrict is a Python evolutionary solver for equity oriented redistricting problems, based loosely on the alogorithms outlined in PEAR (Liu et. al. 2016) and RedistrictR (Izenman et. al. 2017). evoDistrict is desinged for Chicago, IL, in response to community discussion following the 2019 election of Mayor Lori Lightfoot and the removal of Aldermen as primary landuse decision makers. As the change in power left a pressing need to identify who would take over these responsibilites and how to ensure that the process involved meaningful community representation, the tool provides a method for quickly prototyping districts with a wide set of constraints which would be overwhelming if approached manually.
## Zoning Reclassification Text to Geometry
[zrc2geom](https://github.com/druvee/zrc2geom)

Zoning changes are legislative acts which enumerate a municipalities values and goals for the built environment. Frequently, zoning power is misused or applied unevenly tot he detriment of the city as a whole. While a record of zoning exists as far back as any municpalities' legislative records go, these unfortunately predate GIS and are rendered unusable for modern analysis by virtue of being locked in text. zrc2geom tackles the problem of record digitization by exploiting consistent structures in the descriptions to generate [Shapely](https://github.com/Toblerity/Shapely) geometries from publicly available streetline and other existing data.
## Office Market Internal Transition Dynamics
OMITD (repo currently private)

Created in collaboration with UIC's College of Urban Planning and Public Affairs, OMITD is an agent based model of commercial real estate markets. The model itself is written in Netlogo with supporting analysis in Python.
