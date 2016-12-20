---
layout: project-page
title: "Affordable Opportunity in Charlotte-Mecklenburg"
linkname: affordable-opportunity-in-charlotte-mecklenburg
author: "Paul Kardous"
tagline: "Potential Sites for Affordable Housing in Charlotte"
location:
    - place: Charlotte, North Carolina, USA
project-link:
    - href: https://thenewschool.carto.com/u/pkardous/builder/69f94d20-a1d7-11e6-9703-0ef24382571b/embed
tags:
    - tag: Affordability
    - tag:  accessibility
    - tag:  housing
    - tag:  poverty
thumbnail-path: img/affordable-opportunity-in-charlotte-mecklenburg/e8E3nTH.jpg
img-folder: ../../img/affordable-opportunity-in-charlotte-mecklenburg/
timestamp: 12/19/2016 1:45:04
---
Charlotte, North Carolina has been experiencing unprecedented growth since the early 1980’s. As the population continues to boom, it has put a strain on the availability of affordable housing. Due to rising market rents, and the lack of incentive for developers to construct additional non-luxury units a task force has been set up to explore alternatives to stimulate the creation of affordable housing in the city and county.

One of the findings of this task force was to create a database of potential sites for affordable housing to be constructed. This database is a first step in the creation of this database. It includes most land currently off the tax rolls and in the hands of either city, state, or local government, or in the hands of nonprofit and religious organizations that may be interested in partnering to help create a more affordable community.

![]({{ page.img-folder }}iKOyAvB.jpg)

Using data from the City of Charlotte Open Data Portal, Mecklenburg County GIS, the US Census Bureau, and the Charlotte Area Transit System I tried to begin to piece together  a picture of the parcels of land which could be analyzed -- in partnership with the owners -- for their potential to be used as sites for additional units of affordable housing. One of the main factors was to map the accessibility of these potential sites. Looking at the location of CATS bus and rail stops, I drew a buffer of ¼ mile around each bus stop, and ½ mile around each rail stop to highlight areas accessible via transit. In addition, I used recent US Census data on poverty joined with the census tracts in which it was measured, as well as the number of units of currently vacant housing to illustrate the current situation in different parts of the city.

![]({{ page.img-folder }}ALTcCXH.jpg)

To begin to create a more detailed picture, I picked the Derita neighborhood to focus on. Derita is accessible to both transit, as well as employment centers. It also has a large number of currently vacant parcels owned by the city, as well as numerous parcels owned by other governments or by nonprofits.

![]({{ page.img-folder }}ROARzSi.jpg)

Looking at poverty data for Derita, it is important to note that while there is indeed high rates of poverty in certain parts of the neighborhood, there should be careful consideration to make sure that the number of people in poverty does not adversely impact on the long term viability of the neighborhood and its residents.

![]({{ page.img-folder }}BQssn2I.jpg)

Steps have been taken to create an online tool that is incorporating additional information presented with the maps worked out in qGIS. This map on CARTO includes the parcel data and the number of vacant housing units in each neighborhood (census tract) and the correlation between them. There will be additional layers of data added to the online map to better facilitate a discussion with possible partners going forward.


<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/pkardous/builder/69f94d20-a1d7-11e6-9703-0ef24382571b/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


Hopefully this is a first step in creating a tool that allows for dialogue in the community, and which in the future can aid in the site selection for the creation of additional units of affordable housing in Charlotte-Mecklenburg.