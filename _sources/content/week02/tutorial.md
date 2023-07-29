# Tutorial 2: More PySpark, and Geospatial Visualisations

This week we will cover a lot content that is essential for succeeding in Project 1. We'll look at how to do more advanced data manipulation in PySpark, and will also cover how to visualise our TLC data on the map of NYC.

We'll spend pretty much the whole tutorial working through the notebook, which should act as a valuable reference for you as you continue working on Project 1.

## Project 1 Reminder

```{important}
**If you haven't started, *get started...***
```

## Tutorial Outline

In the session today we will:
1. Quickly look at the content we missed at the end of last week
2. Discuss Spark's usage of *lazy evaluation*
3. Troubleshoot broken `.parquet` schemas
4. Look at more operations in PySpark
   - Renaming
   - Creating derived columns
   - User Defined Functions (UDFs)
5. Look at Spark SQL
6. *Take a break*
7. Install and process shapefiles with `GeoPandas`
8. Produce geospatial visualisations with `folium`
9. Provide tips for including useful visualisations in Project 1
10. Produce other visualisations, including heatmaps for visualising correlation
11. Look at just a few functions from `pyspark.ml`

There's a lot to cover, and this might be the most technical/dry tutorial, but it's all valuable for Project 1 and building your understanding of Spark.