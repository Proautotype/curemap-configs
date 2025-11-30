## Configuration Server Resources

This repository contains all curemap microservices application configurations; Each microservice has 3 main profiles mapping to the 3 environment it is deployed.

### Profiles
- Default
- Quality Assurance (qa)
- Production (prod)

### Setup
Setup describes a configuration name, and content;
  * #### Configuration Name
    * application's name (as stated in spring.application.name)
  * #### Configuration Content
    * It's simply the microservice configuration needed or optional to the operation of the service, it is either partly or whole. Meaning the content may represent the whole application properties.
      * Content
        * Database Configuration
        * Redis Configuration
        * Config configuration
        * Rabbitmq configuration
        * logger config
        * Other spring related configurations