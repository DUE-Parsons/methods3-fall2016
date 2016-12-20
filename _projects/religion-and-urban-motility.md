---
layout: project-page
title: "Religion and Urban Motility"
linkname: religion-and-urban-motility
author: "Priya Pinjani"
tagline: "What is the relationship between religion and urban space and how is it visible? Who makes it visible and who is it visible for? "
location:
    - place: Karachi, Sindh, Pakistan
project-link:
    - href: https://thenewschool.carto.com/u/priyapinjani/builder/8ac231c9-d4e1-4a29-acd3-b115ade25955/embed
tags:
    - tag: religion
    - tag:  archive
    - tag:  history
    - tag:  streets
    - tag: 
thumbnail-path: img/religion-and-urban-motility/jgyVzdf.jpg
img-folder: ../../img/religion-and-urban-motility/
timestamp: 12/18/2016 2:21:19
---
This is a story of narrow archiving in Karachi, where a pluralistic society of multiple faiths and ethnicities has cohabited a space for seven decades. This research is to understand the complexities of religions in a multi-dimensional, pluralistic, urban situation. The inquiry is necessary, in my view, to better define the politics involved that form the geographies of invisibility, insecurity and inequality in my hometown.

This first map was created for the joy of finding data, since Pakistan doesn’t have much open data. Mostly using Natural Earth Data’s world data sets, I created a map to see the correlation between the landscape and settlements in the country.
![]({{ page.img-folder }}pG0Qr0p.jpg)

I had a data set for this scale too, and wanted to show where Pakistan and Religion sit on a wider comparison with its neighboring countries, specifically India. I experimented with hatches 
here for the scores to try something new. 
![]({{ page.img-folder }}olfm3br.jpg)

The data sets I found for Karachi were through Open Street Map but they looked like this: ![]({{ page.img-folder }}LAe26T9.jpg) so I knew I had to fix this for any map I wanted to make. So I had georeference a random Karachi map, overlay that with OSM layer and google Earth for reconfirmation and work between those. The remaining information came from newspaper articles, government websites etc. to make my own data sets. 
![]({{ page.img-folder }}2FMHGFU.jpg)
![]({{ page.img-folder }}javgktN.jpg)
![]({{ page.img-folder }}mwfTHHf.jpg)

This is a pure photoshop traced map. More than the electoral votes, I wanted to show how the election constituencies not align with the city divisions as in the previous map.
![]({{ page.img-folder }}LYSCchz.jpg)

I was originally very ambitious and wanted to created shapefiles for morphology of the city as well. But because, even the basic one I had created (used for all the city maps) did not align properly with the city edges on google/carto, I fail to successfully trace these older maps. They were of much lower quality and too hard to georeferenced correctly.
![]({{ page.img-folder }}Qh4jlj2.jpg)

Using the 127 mosques that I found on OSM, I built that data set by tracing more mosques and other religious institutions/buildings that I found tagged on google. This too, was a GIS task of zooming in and zooming out into every street on a Google Street Layer and adding a point and giving it attributes.
![]({{ page.img-folder }}gd5zUjh.jpg)

A mapbox and photoshop job, this map shows the major cities of a region around Pakistan, selected by mere guesswork. I will use this map for my field work where I will map people’s/family’s routes to Karachi. In that conversation, I didn’t want to let India be the hinderance for people to recount their steps, so I got rid of the national boundaries, and kept the state ones to make it easier to orient. I kept a few major cities in each state so that they allow for a more precise way of positioning yourself. I then joined the major “towns” and “villages” of the province Sindh, because my guess is that I will end up meeting people more from that region than the rest.
![]({{ page.img-folder }}lsKtEoK.jpg)
A quick sample of what this map will grow to be like is here: ![]({{ page.img-folder }}BkH4b75.jpg) (Continuing with the same colours as the rest, Green is marker is for Muslims and Red is for Hindus)

My online map was the most tedious, but also the most revealing, even for me. With this map, I aim to classify the street names in Karachi by who they are named after; therefore, it required a lot of historical research of each individual name, to see who and what it could be in the history of the country, find their relevance and picture, and then identify their religion. Therefore, this map is only just the beginning, and I hope to expand on it next semester with my thesis project. It’s also a project that I would like to have crowdsourced, so people can continue to add images, stories, facts. For now, this map has some images embed in the popup, and the streets are categorized as “Muslim”, “Non-Muslim”, “British” and “Neutral”.

I started with a very messy road file from OSM on QGIS and did not intend to draw new roads myself. But because that file had incredibly broken roadlines, I had to start editing them and drawing new ones where necessary (/or where I happened to zoom in!). But I tried to keep my focus only on 3 Towns in Karachi – the older area i.e. Saddar and Lyari and the newer area Clifton. These towns allowed me a good enough comparison to make the point I was trying to make in this map.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/priyapinjani/builder/8ac231c9-d4e1-4a29-acd3-b115ade25955/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
![]({{ page.img-folder }}ACZFqA8.jpg)

Patterns like the following erupted where the secondary and tertiary streets were named British or Non-Muslim, and the primary streets were primarily Muslim named. 
![]({{ page.img-folder }}YkCBhMX.jpg)
![]({{ page.img-folder }}4G6eG55.jpg)
