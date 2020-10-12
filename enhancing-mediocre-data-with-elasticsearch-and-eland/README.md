# Enhancing Mediocre Data with Elasticsearch, Pandas and Eland #

## Elevator Pitch: ##

In the United States many cities present us with data as a part of oversight and federal compliance. However, there are several issues with the data that is provided in that it is often incomplete or in formats that make it hard to analyze with any regularity. This talk will break down how I was able to compile data from my local municipality and utilize open data to enrich monitoring capabalities.

**Audience Level: Intermediate**

## Description of Talk ##
After discovering that many major cities in the United States have open data projects that allow for a level of transparency. I was happy to discover that my own city had data available but quickly realized that the data had many issues that would make it difficult to analyze as-is.

In this talk, I will show how I was able to consolidate "Calls for Service" to the San Diego Police Department since 2015. This was done by importing the city-provided CSV files into Pandas DataFrames and making modifications to standardize data.

I will also convert approximate location data to a geo_point using Public geoJSON data and the filter capabilities in Elasticsearch. 

Lastly, I will show how you can bulk upload the data into and out of Elasticsearch via `eland` so that it can be visualized in Kibana or a public graphing platform and how I automated this process to check for updates.

## Materials ##

The following items will be included with my presentation:

- Slides
- Jupyter Notebook
- Docker Image

## About you ##

Jay is a Developer Advocate at Elastic, based in San Diego, Ca. A multipotentialite, Jay enjoys finding unique ways to merge his fascination with productivity, automation, and development to create tools and content to serve the tech community. You can connect with Jay via email at jay.miller@elastic.co.

Proposal Types

