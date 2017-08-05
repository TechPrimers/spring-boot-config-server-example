# Spring Cloud Config Server Example in a Spring Boot App

- `config-client` - The actual App which is going to use some property
- `config-server` - The Config Server which is pointing to a GIT Repo to pick the property file.
- `config-client.properties` - The actual property file which is used by the config-server to push it to config-client. This is present inside the config-server folder (which is created as Git Repo)
