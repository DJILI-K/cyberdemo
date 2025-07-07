# cyberdemo

![Java CI](https://github.com/DJILI-K/cyberdemo/actions/workflows/ci.yml/badge.svg)

> Un projet d'exemple Spring Boot avec tests unitaires, couverture de code avec JaCoCo et intégration continue via GitHub Actions.

---

##  Technologies utilisées

- Java 21 / 22 / 24
- Spring Boot
- Maven
- JUnit 5
- JaCoCo
- GitHub Actions

---

##  Structure du projet
cyberdemo/
├── src/
│ ├── main/java/... # Code source de l'application
│ └── test/java/... # Tests unitaires
├── .github/workflows/ci.yml # Fichier d'intégration continue
├── pom.xml # Configuration Maven
└── README.md # Ce fichier

---

##  Lancer les tests

```bash
mvn test

mvn verify

target/site/jacoco/index.html


---
