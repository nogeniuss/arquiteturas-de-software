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
