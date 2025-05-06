# django_app2

youtube link https://www.youtube.com/watch?v=DvwhgXpLE-I&t=971s

$ django-admin startproject config .


open docker desktop first
docker build .

docker images


docker tag 4f576b17d488 europe-west1-docker.pkg.dev/django-tutorial-459022/django-tutorial/quickstart:second

docker rmi europe-west1-docker.pkg.dev/django-tutorial-459022/django-turtorial/quickstart:latest

docker push europe-west1-docker.pkg.dev/django-tutorial-459022/django-tutorial/quickstart:second  

gcloud run deploy --image europe-west1-docker.pkg.dev/django-tutorial-459022/django-tutorial/quickstart:second