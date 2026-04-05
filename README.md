1.Docker

 Create simple app(eg. in Pythonie or Node.js), that will:
- return "Hello DevOps" on / (root Directory)
- Write Dockerfile to do that
- Create image and run it locally

2. K8S (kubernets)

Create:
- Deployment (1–2 replicas)
- Service (ClusterIP or NodePort)
Make sure the app is working in a Cluster

3. Helm

 Create simple Helm Chart for that app:
- Deployment and Service as templates
- values.yaml containing:
    - image.repository
    - image.tag
    - replicaCount

4. Install app using:

helm install my-app ./chart
