## Running a express js inside k8s

We have defined files like mongo-config.yaml , mongo-app.yaml, secrets.yaml and web-app.yaml

mongo-config.yaml contains neccesary configuration for mongodb-server.

mongo-app.yaml contains neccesary instruction to setup a mongodb inside a container which is management k8s.

secrets.yaml contains the neccessary secrets like password , username etc

web-app.yaml contains the instructions to build a container running mongo-express