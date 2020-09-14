---
date: '2'
title: 'Locality-based Recommendation System using Neo4j'
cover: './demo.png'
github: ''
external: ''
tech:
  - Neo4j
  -	Python
  - Cypher
  - Spatial
  - Apoc
  - GDS Library
  - Yelp
  - OpenStreetMap
  - Overpass API
  
showInProjects: true
---

Often times, we look for restaurant/business recommendations that are the closest to us. This application does just that and then some! The [Yelp dataset](https://www.yelp.com/dataset/documentation/main) provides the restaurant information and the geography of the location is provided by [OpenStreetMap](https://www.openstreetmap.org/export#map=5/51.500/-0.100). The valid navigation paths to the buildings are found by an architecture of roads and intersections created using the Neo4j Graph database. The application allows a person to view restaurants within the radius they want (in the map view or the list view). It then also shows the navigation to the user's choice of restaurant. Apart from this, the users can add filters several filters such as price, key words, and/or sort it based on different factors.
