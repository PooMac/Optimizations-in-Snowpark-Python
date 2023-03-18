# Optimizations-in-Snowpark-Python

## Overview

This guide has been designed to provide key tips for achieving optimal performance when using Snowpark Python. It is divided into multiple notebooks, each of which covers a specific concept that can help improve performance and efficiency when running workloads in Snowpark. These tips can help users maximize the potential of the Snowpark framework and optimize their Snowpark Python code for better performance.

## First - Prefer Snowpark df over Pandas df


## Second - Use Vectorized UDFs wherever numerical computation is involved and also wherever thrid party libraries use vector like operations for computation.


## Third - Use cachetools library in UDFs and SPs, wherever you read the files and store them in the memory.


