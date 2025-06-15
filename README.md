# My Go Learning Journey

This repository documents my journey to learn, and hopefully master, the Go programming language. My long-term goal is to build very fast, efficient, and reliable web applications.

This plan is structured in four phases, from foundational knowledge to production-ready skills. This includes a detailed, project-based checklist to track my progress in learning the Go programming language. For each concept, the goal is to build the small project associated with it.

---

![GitHub last commit](https://img.shields.io/github/last-commit/your-username/your-repo-name?style=for-the-badge)
![Repo status](https://img.shields.io/badge/status-in%20progress-green?style=for-the-badge)

<a href="https://www.linkedin.com/in/mikenavales/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>

---

## Philosophy

- **Code Every Day:** Consistency over intensity.
- **Build, Don't Just Read:** Solidify knowledge through practical application.
- **Embrace Simplicity:** Write clear, readable, and idiomatic Go.

---

## Phase 1: The Foundation - Language Fundamentals

| Completed | Concept | Mini-Project / Problem |
| :--- | :--- | :--- |
| **`[ ]`** `Date:__/__/2025` | **Go Toolchain & Setup** | [Compile and run a "Hello, World!" program.](./01-foundation/01-go-toolchain-setup/) |
| **`[ ]`** `Date:__/__/2025` | **Packages & Imports** | [Use the `math` package to find a square root.](./01-foundation/02-packages-imports/) |
| **`[ ]`** `Date:__/__/2025` | **Variables & Constants** | [Calculate your age from your birth year.](./01-foundation/03-variables-constants/) |
| **`[ ]`** `Date:__/__/2025` | **Basic Data Types** | [Print the underlying type of different variables.](./01-foundation/04-basic-data-types/) |
| **`[ ]`** `Date:__/__/2025` | **The `fmt` Package** | [Create a formatted receipt with aligned columns.](./01-foundation/05-fmt-package/) |
| **`[ ]`** `Date:__/__/2025` | **Functions** | [Write a `greet(name)` function and call it.](./01-foundation/06-functions/) |
| **`[ ]`** `Date:__/__/2025` | **Control Flow: `if/else`** | [Check if a number is even or odd.](./01-foundation/07-if-else/) |
| **`[ ]`** `Date:__/__/2025` | **Control Flow: `switch`** | [Assign prizes based on a ranking number (1-3).](./01-foundation/08-switch/) |
| **`[ ]`** `Date:__/__/2025` | **Control Flow: `for` Loop** | [Write a "FizzBuzz" program (1-100).](./01-foundation/09-for-loop/) |
| **`[ ]`** `Date:__/__/2025` | **Composite Type: Arrays** | [Declare an array of weekdays and print them.](./01-foundation/10-arrays/) |
| **`[ ]`** `Date:__/__/2025` | **Composite Type: Slices** | [Use `append` to add to a slice of hobbies.](./01-foundation/11-slices/) |
| **`[ ]`** `Date:__/__/2025` | **Composite Type: Maps** | [Create a map of countries to their capital cities.](./01-foundation/12-maps/) |

---

## Phase 2: Thinking in Go - Idiomatic Concepts

| Completed | Concept | Mini-Project / Problem |
| :--- | :--- | :--- |
| **`[ ]`** `Date:__/__/2025` | **Pointers** | [Write a function that takes a pointer to an `int` and squares the value.](./02-idiomatic-go/01-pointers/) |
| **`[ ]`** `Date:__/__/2025` | **Structs** | [Define a `User` struct and print an instance of it.](./02-idiomatic-go/02-structs/) |
| **`[ ]`** `Date:__/__/2025` | **Methods** | [Add a `Deactivate()` method to the `User` struct.](./02-idiomatic-go/03-methods/) |
| **`[ ]`** `Date:__/__/2025` | **Interfaces** | [Define a `Notifier` interface and implement it with `Email` and `SMS` structs.](./02-idiomatic-go/04-interfaces/) |
| **`[ ]`** `Date:__/__/2025` | **Error Handling** | [Create a function that returns an `error` if a given year is in the future.](./02-idiomatic-go/05-error-handling/) |
| **`[ ]`** `Date:__/__/2025` | **Goroutines** | [Launch two goroutines to print numbers and letters concurrently.](./02-idiomatic-go/06-goroutines/) |
| **`[ ]`** `Date:__/__/2025` | **`sync.WaitGroup`** | [Use a `WaitGroup` to make the main function wait for other goroutines to finish.](./02-idiomatic-go/07-waitgroup/) |
| **`[ ]`** `Date:__/__/2025` | **Channels (Unbuffered)** | [Create a "ping-pong" app using a channel for communication.](./02-idiomatic-go/08-unbuffered-channels/) |
| **`[ ]`** `Date:__/__/2025` | **Channels (Buffered)** | [Demonstrate how a buffered channel blocks only when it's full.](./02-idiomatic-go/09-buffered-channels/) |
| **`[ ]`** `Date:__/__/2025` | **`select` Statement** | [Use `select` to receive a message from the first of two channels to respond.](./02-idiomatic-go/10-select/) |
| **`[ ]`** `Date:__/__/2025` | **Ranging & Closing Channels** | [Use a `for range` loop to receive all values from a channel that a producer closes.](./02-idiomatic-go/11-range-close-channels/) |

---

## Phase 3: Building Web Applications

| Completed | Concept | Mini-Project / Problem |
| :--- | :--- | :--- |
| **`[ ]`** `Date:__/__/2025` | **`net/http` Server** | [Create a basic web server on port 8080.](./03-web-applications/01-net-http-server/) |
| **`[ ]`** `Date:__/__/2025` | **Request Handling** | [Create an endpoint `/time` that shows the current time in Davao City.](./03-web-applications/02-request-handling/) |
| **`[ ]`** `Date:__/__/2025` | **Response Writing** | [Create an endpoint that writes a custom `400 Bad Request` status code.](./03-web-applications/03-response-writing/) |
| **`[ ]`** `Date:__/__/2025` | **JSON Handling** | [Create an endpoint `/user` that responds with a `User` struct as JSON.](./03-web-applications/04-json-handling/) |
| **`[ ]`** `Date:__/__/2025` | **Project Structure** | [Refactor HTTP handlers into a separate `handlers` package.](./03-web-applications/05-project-structure/) |
| **`[ ]`** `Date:__/__/2025` | **3rd Party Router** | [Use `chi` or `gin` to create a route with a URL parameter like `/hello/{name}`.](./03-web-applications/06-third-party-router/) |
| **`[ ]`** `Date:__/__/2025` | **Database `sql` package** | [Write a CLI app that connects to a database and runs `SELECT 1`.](./03-web-applications/07-database-sql/) |
| **`[ ]`** `Date:__/__/2025` | **CRUD API Logic** | [Create a `POST /users` endpoint that reads JSON from the request body.](./03-web-applications/08-crud-logic/) |

---

## Phase 4: Production Readiness & Ecosystem

| Completed | Concept | Mini-Project / Problem |
| :--- | :--- | :--- |
| **`[ ]`** `Date:__/__/2025` | **Unit Testing** | [Write a unit test for your `greet(name)` function.](./04-production-readiness/01-unit-testing/) |
| **`[ ]`** `Date:__/__/2025` | **Table-Driven Tests** | [Refactor your `greet` test into a table-driven test with multiple cases.](./04-production-readiness/02-table-driven-tests/) |
| **`[ ]`** `Date:__/__/2025` | **Benchmarking** | [Write a benchmark to measure the performance of a function.](./04-production-readiness/03-benchmarking/) |
| **`[ ]`** `Date:__/__/2025` | **The `context` Package** | [Use `context` in an HTTP handler to detect when a client cancels a request.](./04-production-readiness/04-context/) |
| **`[ ]`** `Date:__/__/2025` | **Middleware** | [Write a simple logging middleware that prints the path of every request.](./04-production-readiness/05-middleware/) |
| **`[ ]`** `Date:__/__/2025` | **Dockerfile for Go** | [Create a multi-stage `Dockerfile` to build a minimal container for your web app.](./04-production-readiness/06-dockerfile/) |
| **`[ ]`** `Date:__/__/2d025` | **Cross-Compilation** | [Build `windows/amd64` and `linux/amd64` binaries from your machine.](./04-production-readiness/07-cross-compilation/) |
| **`[ ]`** `Date:__/__/2025` | **Profiling with `pprof`** | [Add `pprof` endpoints to your web server and inspect the CPU profile.](./04-production-readiness/08-profiling/) |
