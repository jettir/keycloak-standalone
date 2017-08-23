# Keycloak Docker image

Example Dockerfile with Keycloak server.

## Usage

To boot in standalone mode

docker run -p 8080:8080 jettir/keycloak

This image extends the [`jboss/base-jdk`](https://github.com/JBoss-Dockerfiles/base-jdk) image which adds the OpenJDK distribution on top of the [`jboss/base`](https://github.com/JBoss-Dockerfiles/base) image. 
