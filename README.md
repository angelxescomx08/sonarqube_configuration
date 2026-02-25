# Execute docker compose up to start the project

```bash
docker compose up -d
```

# Install sonar-scanner

# Create a new token in http://localhost:9000/account/security/

# Create a sonar-project.properties file in the root of the project

```properties
sonar.projectKey=mi-proyecto
sonar.projectName=Mi Proyecto
sonar.projectVersion=1.0
sonar.sources=.
sonar.host.url=http://localhost:9000
sonar.token=TU_TOKEN
```

# Execute the following command to scan the project

```bash
sonar-scanner -D sonar.token=token -D sonar.host.url=http://localhost:9000
```