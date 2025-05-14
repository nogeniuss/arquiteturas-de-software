# arquiteturas-de-software
# Modelos de Arquitetura de Software - Fluxos em Mermaid

## 1. Arquitetura Monolítica

```mermaid
graph TD
    A[Interface do Usuário] --> B[Lógica de Negócio]
    B --> C[Banco de Dados]
```

## 2. Arquitetura em Camadas (Layered)

```mermaid
graph TD
    A[UI Layer] --> B[Application Layer]
    B --> C[Domain Layer]
    C --> D[Data Access Layer]
    D --> E[Database]
```

## 3. Arquitetura Modular

```mermaid
graph TD
    A[Core Module] --> B[Auth Module]
    A --> C[User Module]
    A --> D[Payment Module]
```

## 4. Microkernel

```mermaid
graph TD
    A[Core Kernel] --> B[Plugin A]
    A --> C[Plugin B]
    A --> D[Plugin C]
```

## 5. Cliente-Servidor

```mermaid
graph TD
    A[Client] --> B[Server]
    B --> C[Database]
```

## 6. P2P (Peer-to-Peer)

```mermaid
graph TD
    A[Node A] --> B[Node B]
    B --> C[Node C]
    C --> A
```

## 7. SOA (Service-Oriented Architecture)

```mermaid
graph TD
    A[Client] --> B[Service Registry]
    B --> C[Service A]
    B --> D[Service B]
    B --> E[Service C]
```

## 8. Microserviços

```mermaid
graph TD
    A[API Gateway] --> B[Service A]
    A --> C[Service B]
    A --> D[Service C]
    B --> E[Database A]
    C --> F[Database B]
    D --> G[Database C]
```

## 9. Serverless

```mermaid
graph TD
    A[Event Source] --> B[Function 1]
    B --> C[Function 2]
    C --> D[Database]
```

## 10. Data-Centric

```mermaid
graph TD
    A[Data Sources] --> B[Data Processing]
    B --> C[Data Storage]
    C --> D[Data Access Layer]
```

## 11. ETL

```mermaid
graph TD
    A[Extract] --> B[Transform]
    B --> C[Load]
    C --> D[Data Warehouse]
```

## 12. Data Lake

```mermaid
graph TD
    A[Raw Data] --> B[Data Lake]
    B --> C[Processing Layer]
    C --> D[Analytics]
```

## 13. Data Warehouse

```mermaid
graph TD
    A[Data Sources] --> B[ETL Process]
    B --> C[Data Warehouse]
    C --> D[Reporting]
```

## 14. DDD (Domain-Driven Design)

```mermaid
graph TD
    A[Domain Layer] --> B[Application Layer]
    B --> C[Infrastructure Layer]
```

## 15. Arquitetura Hexagonal

```mermaid
graph TD
    A[Core Domain] --> B[Ports]
    B --> C[Adapters]
    C --> D[External Systems]
```

## 16. CQRS

```mermaid
graph TD
    A[Command] --> B[Write Model]
    A --> C[Query]
    B --> D[Event Store]
    D --> C[Read Model]
```

## 17. Event Sourcing

```mermaid
graph TD
    A[Event] --> B[Event Store]
    B --> C[Projection]
    C --> D[Read Model]
```

## 18. Event-Driven

```mermaid
graph TD
    A[Event Producer] --> B[Event Bus]
    B --> C[Event Consumer]
```

## 19. Stream Processing

```mermaid
graph TD
    A[Data Stream] --> B[Processor 1]
    B --> C[Processor 2]
    C --> D[Data Sink]
```

## 20. Actor Model

```mermaid
graph TD
    A[Actor A] --> B[Actor B]
    B --> C[Actor C]
```

## 21. Clean Architecture

```mermaid
graph TD
    A[Entities] --> B[Use Cases]
    B --> C[Interface Adapters]
    C --> D[Frameworks & Drivers]
```

## 22. Onion Architecture

```mermaid
graph TD
    A[Core] --> B[Domain]
    B --> C[Application Services]
    C --> D[Infrastructure]
```

## 23. Serverless Event-Driven

```mermaid
graph TD
    A[Event Source] --> B[Function]
    B --> C[Data Store]
```

## 24. Micro Frontend

```mermaid
graph TD
    A[App Shell] --> B[Frontend 1]
    A --> C[Frontend 2]
    A --> D[Frontend 3]
```

## 25. Lambda Architecture

```mermaid
graph TD
    A[Data Stream] --> B[Batch Processing]
    A --> C[Real-Time Processing]
    B --> D[Data Warehouse]
    C --> D
    D --> E[Analytics]
```

## 26. Edge Computing

```mermaid
graph TD
    A[Edge Device] --> B[Edge Server]
    B --> C[Cloud Server]
```

## 27. Space-Based Architecture

```mermaid
graph TD
    A[Data Grid] --> B[Processing Unit 1]
    A --> C[Processing Unit 2]
    B --> D[Data Store]
    C --> D
```

## 28. Arquitetura Baseada em Componentes

```mermaid
graph TD
    A[Component Registry] --> B[Component A]
    A --> C[Component B]
    A --> D[Component C]
```

## 29. Arquitetura em Mall

```mermaid
graph TD
    A[Mall Core] --> B[Service A]
    A --> C[Service B]
    A --> D[Service C]
```

## 30. Arquitetura de Nuvem Híbrida

```mermaid
graph TD
    A[On-Premises] --> B[Private Cloud]
    A --> C[Public Cloud]
    B --> D[Data Sync]
    C --> D
```

## 31. Arquitetura Big Data

```mermaid
graph TD
    A[Data Ingestion] --> B[Data Processing]
    B --> C[Data Storage]
    C --> D[Data Analysis]
```

## 32. Arquitetura Multi-Tenant

```mermaid
graph TD
    A[Application Instance] --> B[Tenant A]
    A --> C[Tenant B]
    A --> D[Tenant C]
```

## 33. Arquitetura IoT

```mermaid
graph TD
    A[IoT Devices] --> B[Edge Gateway]
    B --> C[Cloud Services]
    C --> D[Analytics]
```

## 34. Arquitetura de Sistemas Reativos

```mermaid
graph TD
    A[Event Stream] --> B[Reactive Component A]
    A --> C[Reactive Component B]
    A --> D[Reactive Component C]
```

## 35. Arquitetura Orientada a Agentes

```mermaid
graph TD
    A[Agent A] --> B[Agent B]
    B --> C[Agent C]
    C --> A
```

## 36. Arquitetura de Referência TOGAF

```mermaid
graph TD
    A[Business Architecture] --> B[Application Architecture]
    B --> C[Data Architecture]
    C --> D[Technology Architecture]
```

## 37. Arquitetura Orientada a Serviços em Nuvem (SOA Cloud)

```mermaid
graph TD
    A[Service Registry] --> B[Cloud Service A]
    A --> C[Cloud Service B]
    A --> D[Cloud Service C]
```
