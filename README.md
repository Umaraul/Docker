# Docker

Cluster running:
![alt text](https://github.com/Umaraul/Docker/blob/main/CourseProject/Cluster%20running.PNG?raw=true)

Workloads running:
![alt text](https://github.com/Umaraul/Docker/blob/main/CourseProject/Workloads%20running.PNG)


Services running:
![alt text](https://github.com/Umaraul/Docker/blob/main/CourseProject/Services%20running.PNG)

On the console:
![alt text](https://github.com/Umaraul/Docker/blob/main/CourseProject/svc%20and%20pods.PNG)

Instructions to run:
1. Containerize docker images:

Driver: https://hub.docker.com/repository/docker/umaraul/driver
Apache Hadoop: https://hub.docker.com/r/bde2020/hadoop-namenode
		          https://hub.docker.com/r/bde2020/hadoop-datanode
Spark: https://hub.docker.com/r/bitnami/spark
Nginx: https://hub.docker.com/_/nginx


2. SonarQube and Notebook will be installed from helm 
SonarQube: https://artifacthub.io/packages/helm/sonarqube/sonarqube
Jupyter Notebook: https://artifacthub.io/packages/helm/jupyterhub/jupyterhub

3. Create a kubernetes cluster: Navigation menu -> Kubernetes engine -> Clusters -> Create -> GKE standard -> us-east1-c -> create
4. Install helm3 and kubectl 
5. Connect to kubernetes cluster that you created -> click on the cluster name -> connect -> copy the command in the console
6. Clone this repo and change directory to it
7. Change .yaml files in datanode and namenode deployments and change to your project name
7. Run this: 
chmod +x app.sh
8. Finally, this will run all kubectl files and provide a driver link where the applications can be run
./app.sh

Made the GUI using an html file!

Link for Application: https://drive.google.com/file/d/1JdXKAZxP5olZBweBon__GUrlcYH20FNj/view?usp=sharing

Link for Code: https://drive.google.com/file/d/1R9VgySPk05-pIgwpW5lgxD3rBauN5tN6/view?usp=sharing


References: 
For installing helm3: https://computingforgeeks.com/install-and-use-helm-3-on-kubernetes-cluster/
