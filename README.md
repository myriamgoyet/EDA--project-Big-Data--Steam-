# EDA with Big Data : Steam project

Fictive project completed as part of my Data Science Fullstack training at Jedha (Paris).

## Project description 🚧

You're working for Ubisoft, a French video game publisher. They'd like to release a new revolutionary videogame! They asked you conduct a global analysis of the games available on Steam's marketplace in order to better understand the videogames ecosystem and today's trends.
Goals 🎯

The ultimate goal of this project is to understand what factors affect the popularity or sales of a video game. But your boss asked you to take advantage of this opportunity to analyze the video game market globally.

## Scope of this project 🖼️

You'll have to use Databricks and PySpark to conduct this EDA. Particularly, you'll have to use Databrick's visualisation tool to create the visualizations.

The dataset is available in our S3 bucket at the following url: s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json.

# How I answered :
### Analysis at the "macro" level
link to the Databricks notebook : https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1766541244398891/3062825961113241/1352941473034176/latest.html

    - Which publisher has released the most games on Steam?
    - What are the best rated games?
    - Are there years with more releases? Were there more or fewer game releases during the Covid, for example?
    - How are the prizes distributed? Are there many games with a discount?
    - What are the most represented languages?
    - Are there many games prohibited for children under 16/18?

### Genres analysis

    - What are the most represented genres?
    - Are there any genres that have a better positive/negative review ratio?
    - Do some publishers have favorite genres?
    - What are the most lucrative genres?

### Platform analysis

    - Are most games available on Windows/Mac/Linux instead?
    - Do certain genres tend to be preferentially available on certain platforms?

### Main insights :