<div align="center">

# 👋 Selam, ben Samet Akbal
### **Backend Software Engineer** & Java Ecosystem Specialist

<p align="center">
  <a href="https://www.linkedin.com/in/sametakbal/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://x.com/akbaldev"><img src="https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white" alt="X"/></a>
  <a href="https://www.youtube.com/user/aisV25"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/></a>
</p>

</div>

---

### ☕ Java Core Profile

```java
public interface SoftwareEngineer {
    String getFocus();
    List<String> getCoreEcosystem();
    void buildResilientSystems();
}

public record SametAkbal(
    String name,
    String title,
    List<String> coreEcosystem,
    String architectureFocus
) implements SoftwareEngineer {

    @Override
    public String getFocus() {
        return "High-Performance Backend Systems & Distributed Architecture";
    }

    @Override
    public List<String> getCoreEcosystem() {
        return List.of("Java 21+", "Spring Boot / WebFlux", "Spring AI", "Apache Kafka", "PostgreSQL & Oracle");
    }

    @Override
    public void buildResilientSystems() {
        System.out.println("Let's scale and conquer.");
    }
}
