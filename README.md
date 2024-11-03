# back-end-stack
## Back-end development conventions and agreements

------

### Philosophy

----

- <b>Data Integrity</b> - We prioritize data consistency and correctness
- <b>Statelessness</b> - We follow stateless principles wherever possible for better scalability
- <b>Readability</b> - We write code that is clear, self-documenting, and easy to understand
- <b>Pure Functions</b> - We write pure functions, no side effects, single responsibility
- <b>Divide et Impera</b> - We create microservices to help organize code and make it more maintainable, testable, and scalable
  - we should split different "complicated" chunks of business logic into different services, like file reading/writing, etc. 

---

### Code Conventions

---

#### Naming

- <b>File Naming</b> - We follow the [kebab-case](https://en.wikipedia.org/wiki/Kebab_case) naming convention
- <b>Class Naming</b> - We follow the [PascalCase](https://en.wikipedia.org/wiki/PascalCase) naming convention
- <b>Method Naming</b> - We follow the [camelCase](https://en.wikipedia.org/wiki/CamelCase) naming convention
- <b>Variable Naming</b> - We follow the [camelCase](https://en.wikipedia.org/wiki/CamelCase) naming convention
- <b>Parameter Naming</b> - We follow the [camelCase](https://en.wikipedia.org/wiki/CamelCase) naming convention
- <b>Database poles Naming</b> - We follow the [snake_case](https://en.wikipedia.org/wiki/Snake_case) naming convention

#### Style

- Every project will have similar prettier and eslint configurations

---

### Tech stack

<b>Typescript</b> till we do not need to build something <b>EXTRA</b> like new Cloud Storage or new Google Meet


- <code>Node.js</code>
- <code>Express.js</code>
- <code>MongoDB</code>
  - <code>Mongoose</code>
- <code>PostgreSQL</code>  
  - <code>Sequelize</code>
- <code>Redis</code>
- <code>JWT</code>
- <code>bcrypt</code>
- <code>dotenv</code>

#### Service communication

- <b>HTTP</b> - `axios` for simpler communication   
- <b>GRPC</b> - `grpc` to get more efficient and secure communication
- <b>WebSockets</b> - `socket.io` to get real time communication
- <b>MQTT</b> - `mqtt` to get more efficient and secure communication(notification)

#### Data validation

- <b>Validation</b> - `zod` for data validation

#### Testing

- <b>Testing</b> - `jest`