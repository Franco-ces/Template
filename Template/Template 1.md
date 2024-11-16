# Arquitectura de referencia para la migración del monolito
## Context and Problem Statement

Se planea realizar una migración de tipo Brownfield, manteniendo la página operativa mientras se lleva a cabo una transición progresiva de los servicios del monolito a microservicios, sin interrumpir la experiencia de los clientes

## Considered Options

### Tecnologias para crear los microservicios
* Spring Boot
* Micronaut
* Quarkus


### contenedorización de microservicios en el sistema

* Docker
* Kubernetes (para la orquestación de contenedores)
* Entornos virtualizados tradicionales (por ejemplo, con máquinas virtuales).
  
### API Gateway para gestionar la comunicación entre clientes y microservicios

* Kong API Gateway
* AWS API Gateway
* NGINX
* Traefik

  

## Decision Outcome

Chosen option: "{title of option 1}", because {justification. e.g., only option, which meets k.o. criterion decision driver | which resolves force {force} | … | comes out best (see below)}.

<!-- This is an optional element. Feel free to remove. -->
### Consequences

* Good, because {positive consequence, e.g., improvement of one or more desired qualities, …}
* Bad, because {negative consequence, e.g., compromising one or more desired qualities, …}
* … <!-- numbers of consequences can vary -->
