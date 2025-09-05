📌 Project Overview

- **API Under Test**: Simple Grocery Store API  
- **Test Objectives**:
  - Validate CRUD operations (Products, Carts, Orders)
  - Verify response codes, headers, and body fields
  - Perform authentication and token-based requests
  - Data-driven testing with external JSON
  - CI/CD integration with Jenkins

## 🛠 Tools & Tech Stack

- [Postman](https://www.postman.com/) – for manual + automated API testing
- [Newman](https://github.com/postmanlabs/newman) – CLI execution of Postman collections
- [Rest Assured](https://rest-assured.io/) – Java-based API automation
- [TestNG](https://testng.org/) – test execution framework
- [Maven](https://maven.apache.org/) – dependency management
- [Jenkins](https://www.jenkins.io/) – CI/CD automation

  How to Run Tests

### 🔹 Run Postman Collection with Newman
```bash
newman run Postman_Collections/Grocery_API.postman_collection.json \
  -e Postman_Collections/env.json
