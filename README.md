# GenreClassifier

End-to-End Machine Learning Pipeline. Runs on GCP using BigQuery, TFX, Vertex AI and Kubeflow. Docker container is supposed to be deployed on Cloud Run for online predictions.

The model is a music genre classifier trained on Spotify Data and the prediction section is just for testing at this point.

To run this project you're gonna need to follow this steps:

1. Set up a GCP Project
2. Create a Bucket
3. Run a JupyterLab instance on Vertex AI's Workbench (paste and run the notebook in there)
4. Set-up a BigQuery dataset and table
5. Build the Docker Container and deploy it in Cloud Run
6. Create a Service Credential and allow the project to access it
