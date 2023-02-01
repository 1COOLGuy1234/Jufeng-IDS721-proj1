# Cloud Continuous Delivery of Microservice (MLOps or Data Engineering Focused)

## Task
- Create a Microservice in Flask or Fast API
- Push source code to Github
- Configure Build System to Deploy changes
- Use IaC (Infrastructure as Code) to deploy code
- Use either AWS, Azure, GCP (recommended services include Google App Engine, AWS App Runner or Azure App Services)
- Containerization is optional, but recommended

## Week1

Now the Flask API can work. I write some simple function to test the API function.

## Week2

Depoly this Flask API project on Docker.

1. write the `requirements.txt`
2. write the `dockerfile`
3. run `docker image build -t flask-api .`
4. run `docker run -p 63333:5000 -d flask-api`
5. visit `localhost:63333`

Deploy the project on AWS

### Print time
Print the current Eastern Standard Time

## TODO
finish the github workflow

