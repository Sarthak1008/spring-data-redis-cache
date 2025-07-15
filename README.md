# 🚀 Spring Boot Redis Caching Example

This project demonstrates how to integrate **Redis** with a **Spring Boot** application for caching using Spring's annotation-based caching abstraction.

## 📦 Technologies Used

- Spring Boot
- Spring Cache Abstraction
- Redis
- Spring Data Redis
- Maven / Gradle
- Java 8+

---

## ✅ Features

- Enable and configure caching in Spring Boot
- Connect Spring Boot with Redis server
- Use `@Cacheable`, `@CacheEvict`, and `@CachePut`
- Configure TTL (Time-To-Live) for cache entries
- Define custom cache key generators
- Condition-based caching

---

## 🔧 Setup Instructions

### 1. 🧱 Prerequisites

- Java 8 or higher
- Redis Server installed and running on `localhost:6379`
- Maven or Gradle

### 2. 📁 Add Dependencies

#### For Maven:
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-redis</artifactId>
</dependency>
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-cache</artifactId>
</dependency>
```

### ⚙️ Configuration (`application.properties`)

```properties
spring.cache.type=redis
spring.redis.host=localhost
spring.redis.port=6379
```

### 📌 Annotations Used

- `@EnableCaching` – Enable caching support
- `@Cacheable` – Read from/write to cache
- `@CacheEvict` – Remove entries from cache
- `@CachePut` – Update cache without skipping method

---

### 🧪 Verify with Redis CLI

```bash
redis-cli
> KEYS *
> GET your-cache-key
```

![Redis image](https://miro.medium.com/v2/resize:fit:1167/1*7opjR94hTXrBPrYF7EDgqg.png)
