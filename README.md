# Post GIS Database Orchestration  

**Student:** Jennifer Todd  
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 4 - Post GIS Database Orchestration  
**University of Arizona**  

## Project Description
This project focused on building spatial database skills using PostgreSQL and PostGIS in a containerized environment. I set up a PostGIS database, imported spatial datasets, and wrote SQL queries to perform spatial analysis.

## Tools and Technologies
- PostgreSQL
- PostGIS
- SQL
- Docker Compose
- Github Codespaces

## What I Did
- Set up a PostGIS-enabled PostgreSQL database using Docker Compose in Codespaces
- Imported shapefiles and created spatial tables within a database
- Wrote SQL queries to explore, filter, and analyze spatial data

## How to View / Run
- Open respository in Codespaces with Docker installed
- State database using Docker compose
- Connect to PostgreSQL/PostGIS database using SQL terminal

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   └── Dockerfile
    ├── sql/
    │   ├── 01_basic_sql_queries.sql
    │   ├── 02_geometry_queries.sql
    │   ├── 03_spatial_relationships.sql
    │   └── 04_spatial_joins.sql
    ├── demos/
    │   ├── demo_aggregation_queries.sql
    │   ├── demo_basic_queries.sql
    │   ├── demo_filtering_queries.sql
    │   └── demo_postgis_queries.sql
    └── docker-compose.yml
