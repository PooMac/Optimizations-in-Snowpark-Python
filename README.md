# Optimizations-in-Snowpark-Python

## Overview

This guide contains key tips for optimal performance when using Snowpark Python.  The guide is broken up into multiple notebooks, each covering a key concept that can improve performance and/or efficiency while running workloads in Snowpark.  

## First - Prefer Snowpark df over Pandas df


## Second - Use Vectorized UDFs wherever numerical computation is involved and also wherever thrid party libraries use vector like operations for computation.


## Third - Use cachetools library in UDFs and SPs, wherever you read the files and store them in the memory.


