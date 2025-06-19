# Tasks and Assiggments:

* Assignment 1: Day 1 – Setting up Go environment

  * Install Go: follow official guide at [https://go.dev/doc/install](https://go.dev/doc/install) ([gobyexample.com][1])
  * Configure editor (VSCode, Vim, etc.) per Go docs
  * Set GOPATH/GOBIN or use modules (GO111MODULE=on)
  * Verify with `go version`, `go env`, `go run hello.go`
  * Internal doc: “Assignment - Day1” Google Doc (check Discord pinned or email)

* Assignment 2: Go basics + GitHub

  * Go tutorials: [https://gobyexample.com/](https://gobyexample.com/) ([gobyexample.com][1])
  * Git basics: Pro Git book at [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2) ([git-scm.com][2])
  * GitHub setup: [https://try.github.io/](https://try.github.io/) ([try.github.io][3])
  * Common commands: [https://dzone.com/articles/top-20-git-commands-with-examples](https://dzone.com/articles/top-20-git-commands-with-examples) ([dzone.com][4])
  * Tasks: install/configure Git, create GitHub account, clone/fork repo, commit/push, PR workflow
  * Internal doc: “Assignment 2” Google Doc (check Discord pinned or email)

* Assignment 3: GoFr codebase exploration & observability

  * Fork GoFr repo: [https://github.com/gofr-dev/gofr](https://github.com/gofr-dev/gofr) (fork then clone)
  * Explore directory structure, read README, identify key packages
  * Spin up Docker containers: e.g.

    * `docker run --name gofr-mysql -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=test -p 2001:3306 -d mysql:8.0.30`
    * `docker run --name gofr-redis -p 2002:6379 -d redis:7.0.5`
  * Run example server: `go run main.go` inside examples/http-server
  * Hit endpoints, capture trace ID, use tracer.gofr.dev or Jaeger/Zipkin endpoints for observability
  * Understand what a trace is by reading OpenTelemetry docs or GoFr observability guide
  * Internal doc: “Assignment 3 – GoFr Codebase & Observability Challenge” Google Doc (check Discord pinned or email)

* Assignment 4: Design patterns & architecture in Go

  * Study SOLID principles, common Go patterns (factory, decorator, adapter, etc.) via Refactoring.Guru or Go-specific articles
  * Understand dependency injection in Go (using interfaces, constructor injection)
  * Review example code in GoFr or other Go projects
  * This assignment is self-learning; not evaluated but required for understanding
  * Internal doc: “Assignment 4 – Golang Design Patterns & Architecture” Google Doc (check Discord pinned or email)

* Problem statements & proposal (due 26 June 2025)

  * Check inbox for email from GoFr SoC containing: problem statements link, proposal requirements, submission form, deadline 26 June 2025, contributing guidelines
  * Read contributing guidelines in GoFr repo (likely at [https://github.com/gofr-dev/gofr/blob/main/CONTRIBUTING.md](https://github.com/gofr-dev/gofr/blob/main/CONTRIBUTING.md))
  * Prepare proposal aligning with selected problem from statements
  * Submit before deadline

* Important notes & links:

  * Go official docs: [https://go.dev/doc/](https://go.dev/doc/)
  * Go by Example: [https://gobyexample.com/](https://gobyexample.com/) ([gobyexample.com][1])
  * Pro Git book: [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2) ([git-scm.com][2])
  * GitHub setup: [https://try.github.io/](https://try.github.io/) ([try.github.io][3])
  * Top Git commands: [https://dzone.com/articles/top-20-git-commands-with-examples](https://dzone.com/articles/top-20-git-commands-with-examples) ([dzone.com][4])
  * GoFr repo: [https://github.com/gofr-dev/gofr](https://github.com/gofr-dev/gofr)
  * Observability: tracer.gofr.dev, Docker images for Zipkin/Jaeger per internal docs
  * Discord threads: check pinned messages in Day 1–4 threads, HelpLine thread, GoFr SoC announcements
  * Use channel general-golang for doubts; only post in that day’s thread for assignment discussion.

Execute exactly these tasks in order. No extra steps.

[1]: https://gobyexample.com/ "Go by Example"
[2]: https://git-scm.com/book/en/v2 "Git"
[3]: https://try.github.io/ "Set up Git - GitHub Docs"
[4]: https://dzone.com/articles/top-20-git-commands-with-examples "Top 20 Git Commands With Examples"
`