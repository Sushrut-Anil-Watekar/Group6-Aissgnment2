# B-Tree Database Indexing Project

## Project Overview
This project implements and benchmarks various tree-based indexing structures used in databases. The primary data structures compared include:

- **B-Trees** (for balanced indexing)
- **AVL Trees** (for self-balancing binary search operations)
- **Red-Black Trees** (for general-purpose balanced search operations)

The project includes theoretical analysis, empirical benchmarking, and unit tests to validate correctness and performance.

---

## Prerequisites
Ensure you have the following installed:
- **Java 11+**
- **Apache Maven**
- **JUnit 5** (comes with Maven dependencies)
- **Git** (if cloning from a repository)

---

## Cloning the Repository
To clone this repository, use the following command:

```sh
 git clone <repository-url>
 cd btree-database
```

---

## Building the Project
Use Maven to clean, compile, and package the project:

```sh
mvn clean install
```

This will:
- Remove any previous builds
- Compile the source code
- Run unit tests
- Package the application

---

## Running Tests
To execute unit tests:

```sh
mvn test
```

This will run the JUnit test suite to validate the correctness of insertions, deletions, and searches in the tree structures.

---

## Project Structure
```
.
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── com.database.indexing
│   │   │   │   ├── AVLTree.java
│   │   │   │   ├── BTree.java
│   │   │   │   ├── BTreeNode.java
│   │   │   │   ├── Main.java
│   ├── test
│   │   ├── java
│   │   │   ├── com.database
│   │   │   │   ├── BTreeTest.java
│   │   │   │   ├── TreePerformanceTest.java
├── pom.xml (Maven build configuration)
├── README.md
```

---

## Contact
For questions or contributions, feel free to open an issue or submit a pull request!
