# JWT-secrets

The goal for this project was to find as many public-available JWT secrets as possible to help developers and DevOpses identify it by traffic analysis at the Wallarm NGWAF level.

For now (20/04/2024) the list consists of 103682

We focused on Google Search and GitHub Dorks by using mainly two query patterns:
1. ```jwt example +TECHNOLOGY``` where the ```TECHNOLOGY``` is the language itself like PHP, Ruby, Rails or framework like CodeIgniter, ExpressJS, Laravel, Struts of Flask.
2. Google BigQuery search based on 3M GitHub Projects.