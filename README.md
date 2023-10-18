<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>time-capsule-server</h1>
<h3>◦ Preserve the future, with Time Capsule Server!</h3>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/.ENV-ECD53F.svg?style&logo=dotenv&logoColor=black" alt=".ENV" />
<img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style&logo=TypeScript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Prisma-2D3748.svg?style&logo=Prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/Fastify-000000.svg?style&logo=Fastify&logoColor=white" alt="Fastify" />
</p>
<img src="https://img.shields.io/github/license/FranciscoYlderlan/time-capsule-server?style&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/FranciscoYlderlan/time-capsule-server?style&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/FranciscoYlderlan/time-capsule-server?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/FranciscoYlderlan/time-capsule-server?style&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running time-capsule-server](#-running-time-capsule-server)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project is a time capsule server that allows users to send messages to their future selves. It provides a RESTful API that enables users to create and retrieve messages stored in a database. The server utilizes Prisma as the ORM tool to interact with the SQLite database and enables fast and efficient retrieval of user messages. Its value proposition lies in its ability to facilitate personal reflection and provide a means for individuals to communicate with their future selves.

---

## 📦 Features

Exception: 

---


## 📂 Repository Structure

```sh
└── time-capsule-server/
    ├── .env
    ├── .gitignore
    ├── package.json
    ├── pnpm-lock.yaml
    ├── prisma/
    │   ├── dev.db
    │   ├── dev.db-journal
    │   ├── migrations/
    │   └── schema.prisma
    ├── src/
    │   └── server.ts
    └── tsconfig.json
```


---

## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                                | Summary                   |
| ---                                                                                                 | ---                       |
| [pnpm-lock.yaml](https://github.com/FranciscoYlderlan/time-capsule-server/blob/main/pnpm-lock.yaml) | HTTPStatus Exception: 400 |

</details>

<details closed><summary>Src</summary>

| File                                                                                          | Summary                                                                                                                                                                                                                                                                                      |
| ---                                                                                           | ---                                                                                                                                                                                                                                                                                          |
| [server.ts](https://github.com/FranciscoYlderlan/time-capsule-server/blob/main/src/server.ts) | This code sets up a fastify server that listens for GET requests on the "/users" endpoint. It uses Prisma Client to query the database and retrieve a list of users, which is then returned as the server response. The server runs on port 3333 and is accessible at http://localhost:3333. |

</details>

<details closed><summary>Prisma</summary>

| File                                                                                                     | Summary                                                                                                                                                                                                      |
| ---                                                                                                      | ---                                                                                                                                                                                                          |
| [schema.prisma](https://github.com/FranciscoYlderlan/time-capsule-server/blob/main/prisma/schema.prisma) | This Prisma schema file configures the Prisma Client code generator and sets up a datasource for an SQLite database. It defines a User model with properties for id (automatically generated UUID) and name. |

</details>

<details closed><summary>Migrations</summary>

| File                                                                                                                            | Summary                                                                                                                                                                                                                                          |
| ---                                                                                                                             | ---                                                                                                                                                                                                                                              |
| [migration_lock.toml](https://github.com/FranciscoYlderlan/time-capsule-server/blob/main/prisma/migrations/migration_lock.toml) | The "migration_lock.toml" file in the "prisma/migrations" directory serves as a provider-specific file for SQLite. It shouldn't be manually modified and should be included in the version-control system (e.g., Git) to track changes properly. |

</details>

<details closed><summary>20231012143655_create_users_table</summary>

| File                                                                                                                                                  | Summary                                                                                                                                                                                          |
| ---                                                                                                                                                   | ---                                                                                                                                                                                              |
| [migration.sql](https://github.com/FranciscoYlderlan/time-capsule-server/blob/main/prisma/migrations/20231012143655_create_users_table/migration.sql) | The code creates a table called "User" with two columns: "id" and "name". The "id" column is set as the primary key and is of type TEXT. The "name" column is also of type TEXT and is required. |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

### 🔧 Installation

1. Clone the time-capsule-server repository:
```sh
git clone https://github.com/FranciscoYlderlan/time-capsule-server
```

2. Change to the project directory:
```sh
cd time-capsule-server
```

3. Install the dependencies:
```sh
► INSERT-TEXT
```

### 🤖 Running time-capsule-server

```sh
► INSERT-TEXT
```

### 🧪 Tests
```sh
► INSERT-TEXT
```

---


## 🛣 Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  LICENSE-TYPE` License. See the [LICENSE-Type](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ List any resources, contributors, inspiration, etc.`

---
[↑ Return](#Top)
