# End-To-End-Spotify-ETL-Datapipeline-project
This project implements a serverless ETL pipeline for Spotify data using AWS Lambda functions. It extracts metadata ( artists, albums, songs) from the Spotify Web API, applies transformations such as normalization, deduplication, and enrichment, and stores the processed datasets in Amazon S3.
The pipeline is orchestrated with AWS EventBridge, ensuring automated scheduling and execution. Its modular design highlights scalability, cost efficiency, and resilience, making it suitable for real-world streaming data scenarios.
By structuring Spotify data into clean, query-ready formats, this pipeline enables downstream analytics such as identifying trending songs, analyzing artist popularity, and studying playlist engagement patterns.

