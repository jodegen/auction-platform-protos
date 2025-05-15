---

# Auction Platform Protos

This repository contains the Protocol Buffers (Protobuf) definitions used for communication between microservices in the Auction Platform via gRPC.

## 🚀 Purpose

- Define messages and gRPC services used across the microservices.
- Shared contract between backend services (e.g., Auction, User, Bidding).
- Ensures consistency, type safety, and interoperability.

## 🔧 Technologies

- [Protocol Buffers v3](https://developers.google.com/protocol-buffers)
- gRPC

## 🚀 Usage

### 📦 Import via Maven

1. First, authenticate with GitHub Packages (if not already):

```xml
# Add to ~/.m2/settings.xml

<servers>
  <server>
    <id>github</id>
    <username>your-github-username</username>
    <password>${GITHUB_TOKEN}</password>
  </server>
</servers>
```

2.	Add this to your microservice’s pom.xml:

```xml
<dependency>
  <groupId>com.jodegen.auction</groupId>
  <artifactId>auction-platform-protos</artifactId>
  <version>1.0.0</version>
</dependency>
```

3.	Add repository configuration:

```xml
<repositories>
  <repository>
    <id>github</id>
    <url>https://maven.pkg.github.com/jodegen/auction-platform-protos</url>
  </repository>
</repositories>
```

## 🔐 Authentication Tip

Use a GitHub Personal Access Token (classic) with read:packages scope for authentication with Maven.
