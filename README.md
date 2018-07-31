# Face Recognition
This is a slightly modified version of [Adam Geity's Facial Recognition Repo](https://github.com/ageitgey/face_recognition). The dockerfile has been changed to work with an [Argo workflow demo](https://github.com/EliZucker/Argo-Workflow-Test).

## Usage
In the main directory, run (with gcloud)
```
gcloud container builds submit --tag gcr.io/<your-project> . 
```
