<h1 align="center">🐳 Local Enviroment</h1>

<p align="center">Local Containerized Environment supports various programming languages</p>

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

## Introduction 👋

localenviroment is a tool designed for local development, allowing you to execute code in multiple languages without installing numerous tools on your PC. With [Docker](https://www.docker.com/) as the only prerequisite, you can seamlessly run code in various environments.

## Prerequisites 🔓

Before you begin, ensure that you have [Docker](https://docs.docker.com/engine/install/) installed. It's also helpful to have a basic understanding of Docker concepts.

## Key Features 🚀

- **Quickly write and run code**: localenviroment allows you to rapidly write and execute code in containerized environments locally.

- **[localenviroment](./localenviroment) script**: The repository includes a convenient `localenviroment` script that simplifies the execution of code in different languages within Docker containerized environments.

- **[env](./env/) folder**: Contains the code and document for each supported language.

- **[config.yaml](./config.yaml) file**: This config file allows users to configure their target environment settings easily. This includes specifying Docker images, default container names, and base commands for each language.

## Demo 🔥

```bash
# Clone localenviroment repository
git clone https://github.com/nholuongut/local-env.git
cd localenviroment
# Execute python code
./localenviroment python env/python/demo.py
# Execute javascript code
./localenviroment javascript env/javascript/demo.js	
```

## Supported Environment 🚀

Current support languages in below table

| Language   | Quick Start                                     | User guide                      | Image                                                 |
| ---------- | ----------------------------------------------- | ------------------------------- | ----------------------------------------------------- |
| Python     | `./localenviroment python env/python/demo.py`          | [python](./env/python/)         | [Find](https://hub.docker.com/_/python)               |
| Powershell | `./localenviroment powershell env/powershell/demo.ps1` | [powershell](./env/powershell/) | [Find](https://hub.docker.com/_/microsoft-powershell) |
| Groovy     | `./localenviroment groovy env/groovy/demo.groovy`      | [groovy](./env/groovy/)         | [Find](https://hub.docker.com/_/groovy)               |
| Javascript | `./localenviroment javascript env/javascript/demo.js`  | [javascript](./env/javascript/) | [Find](https://hub.docker.com/_/node/)                |
| Golang     | `./localenviroment golang env/golang/demo.go`          | [go](./env/golang/)             | [Find](https://hub.docker.com/_/golang/)              |
| Java       | `./localenviroment java env/java/demo.java`            | [java](./env/java/)             | [Find](https://hub.docker.com/_/openjdk)              |

## Usage 📖

To use the localenviroment tool, follow these steps:

### 1. Clone

Clone the repository:

```bash
git clone https://github.com/nholuongut/local-env.git
cd localenviroment
```

### 2. Configure

Configure your environment:

- Edit the [config.yaml](config.yaml) file to specify the details of the environment you want to use, for example:

```yaml
# File: ./config.yaml
python:
  image: 'python:3.12'
  default_container_name: 'pyEnv'
  base_command: 'python'
```

### 3. Code

Write your own code under [env](./env/), for example:

- Python: [python](./env/python/)
- Powershell: [powershell](./env/powershell/)

### 4. Run

Run a script:

- Use the following command format to run your script within the containerized environment:

```bash
./localenviroment <language> <script_path>
```

For example, to run a Python script:

```bash
./localenviroment python env/python/demo.py
```

### 5. More

Refer to the user guide for detailed instructions on using each supported environment. Links to the user guides are available in the table above.

## Troubleshooting

- For common issue, visit [troubeshooting.md](./docs/troubeshooting.md)

## Contributing
- See: [CONTRIBUTING.md](./CONTRIBUTING.md)
- If you find this repository helpful, kindly consider showing your appreciation by giving it a star ⭐ Thanks! 💖
- Feel free to open a new issue if you encounter the localenviroment bug or want to request more content about localenviroment
- Submit a new issue (🐛) if you encounter the bug/error when using this repo

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)
* If you find this repository helpful, kindly consider showing your appreciation by giving it a star ⭐ Thanks! 💖

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟