# Izicap homework


- Start the project by creating a new pipline in jenkins.

- The tools used in Jenkinsfile are maven "M3" and jdk "JDK11" which can be configured via Jenkins Global Tool Configuration.

- You can either copy the Jenkinsfile content into you pipeline script or use the "Pipeline script from SCM" option.

- If you are using macOS or Lunix change "bat" by "sh" in your pipeline script

- Change the credentials in the 'Push Image to Docker Hub' stage to your dockerhub credentials or remove that stage if you don't want to push the build.

- Make sure that docker is running

- Click on "Build Now" and start the built image on docker after the build is finished

- Use the "/export" endpoint to export the data into a csv file 