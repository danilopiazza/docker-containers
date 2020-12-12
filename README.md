# Docker Containers

[Docker Compose](https://docs.docker.com/compose/) container configuration.

## SonarQube

[SonarQube 8.6+](https://hub.docker.com/_/sonarqube) Docker image.

### Configuration

- Port: 9000
- URL: http://localhost:9000

#### Disable required user authentication

Set `sonar.forceAuthentication=false` in the `sonar.properties` file to disable enforced user authentication.

### References

1. https://docs.sonarqube.org/latest/setup/get-started-2-minutes/
2. https://docs.sonarqube.org/latest/setup/install-server/
