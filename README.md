# BingeWatch

One Stop Recommendation System personalised recommendations for OTT Content. In an era saturated with entertainment options across numerous streaming platforms, finding the perfect show or movie can feel like searching for a needle in a haystack.

This is where we have a need for a consolidated movie recommendation system like BingeWatch. A groundbreaking project designed to revolutionise how viewers discover and engage with content.

With a focus on genre and mood-based filtering, as well as occasion-specific recommendations, the system promises to deliver personalised viewing suggestions tailored to individual preferences

# Demo Video

Experience the power of personalized content discovery:

[![Demo Video](https://img.youtube.com/vi/CCX3OuMF1FU/hqdefault.jpg)](https://youtu.be/CCX3OuMF1FU)

# Architecture Details

[![Codelabs Tutorial](https://img.shields.io/badge/Codelabs_Tutorial-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://codelabs-preview.appspot.com/?file_id=1z-pGIA6HOZregKgnnslvBE-ZZRUS_rhmiQvnVc8Xoww#0)

# Run Application Locally

1. Clone the repo.
2. Install the dependencies.

``` pip install -r requirements.txt ```
3. Run the Dockerfile to generate the image and run the Docker compose file to bring up the instances.
```
docker build -t <image_name> .

```
```
docker compose up -d
```
This is create an airflow instance, postgresDB, streamlit for frontend and fastapi for backend.
