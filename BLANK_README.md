<a name="readme-top"></a>

<div align="center">

  <img src="./images/logo.svg" alt="logo" width="200" height="auto" />

<details closes>
  <summary>
    <h1>project_title</h1>
  </summary>
    project_title_explaination
</details>

  <p>
    project_description
  </p>

<!-- Badges -->
<p>
  <a href="https://github.com/github_username/repo_name/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/github_username/repo_name" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/github_username/repo_name" alt="last update" />
  </a>
  <a href="https://github.com/github_username/repo_name/network/members">
    <img src="https://img.shields.io/github/forks/github_username/repo_name" alt="forks" />
  </a>
  <a href="https://github.com/github_username/repo_name/stargazers">
    <img src="https://img.shields.io/github/stars/github_username/repo_name" alt="stars" />
  </a>
  <a href="https://github.com/github_username/repo_name/issues/">
    <img src="https://img.shields.io/github/issues/github_username/repo_name" alt="open issues" />
  </a>
  <a href="https://github.com/github_username/repo_name/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/github_username/repo_name.svg" alt="license" />
  </a>
</p>

<h4>
    <a href="https://github.com/github_username/repo_name/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/github_username/repo_name">Documentation</a>
  <span> · </span>
    <a href="https://github.com/github_username/repo_name/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/github_username/repo_name/issues/">Request Feature</a>
  </h4>

</div>

<br/>

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [:notebook\_with\_decorative\_cover: Table of Contents](#notebook_with_decorative_cover-table-of-contents)
  - [:star2: About project\_title](#star2-about-project_title)
    - [:camera: Screenshots](#camera-screenshots)
    - [:space\_invader: Tech Stack](#space_invader-tech-stack)
  - [:toolbox: Getting Started](#toolbox-getting-started)
    - [:bangbang: Prerequisites](#bangbang-prerequisites)
    - [:gear: Installation](#gear-installation)
    - [Type checks](#type-checks)
    - [:test\_tube: Running Tests](#test_tube-running-tests)
    - [Test coverage](#test-coverage)
      - [Running tests with pytest](#running-tests-with-pytest)
    - [:running: Run Locally](#running-run-locally)
  - [:eyes: Usage](#eyes-usage)
  - [:compass: Roadmap](#compass-roadmap)
  - [:wave: Contributing](#wave-contributing)
  - [Commiting your code](#commiting-your-code)
    - [:scroll: Code of Conduct](#scroll-code-of-conduct)
  - [:grey\_question: FAQ](#grey_question-faq)
  - [:warning: License](#warning-license)
  - [:handshake: Contact](#handshake-contact)
  - [:gem: Acknowledgements](#gem-acknowledgements)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- About the Project -->
## :star2: About project_title

project_description

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`,`project_title_explaination`, `project_description`

<!-- Screenshots -->
### :camera: Screenshots

<div align="center">
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>

<!-- TechStack -->
### :space_invader: Tech Stack

<details closes>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
    <li><a href="https://nextjs.org/">Next.js</a></li>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://tailwindcss.com/">TailwindCSS</a></li>
  </ul>
</details>

<details closes>
  <summary>Server</summary>
  <ul>
    <li><a href="https://www.djangoproject.com/">Django</a></li>
    <li><a href="https://www.django-rest-framework.org/">Django REST Framework</a></li>
    <li><a href="https://channels.readthedocs.io/en/stable/">Django Channels</a></li>
    <li><a href="https://www.graphene-python.org/">Graphene</a></li>
  </ul>
</details>

<details closes>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
    <li><a href="https://redis.io/">Redis</a></li>
    <li><a href="https://neo4j.com/">Neo4j</a></li>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
  </ul>
</details>

<details closes>
<summary>DevOps</summary>
  <ul>
    <li><a href="https://www.docker.com/">Docker</a></li>
    <li><a href="https://www.jenkins.io/">Jenkins</a></li>
    <li><a href="https://circleci.com/">CircleCLI</a></li>
  </ul>
</details>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Getting Started -->
## :toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

activate virtualenv and install requirements

```sh
  pip install -r requirements/local.txt
```

### :gear: Installation

Via pip into a `virtualenv`:

```sh
  pip install repo_name
```

In `settings.py` add the following:

```python

INSTALLED_APPS = (
    ...
    'repo_name'
)

```

To enable access to the user interface add the following to your urls.py:

```python
urlpatterns += [path('repo-name/', include('repo-name.urls', namespace='repo-name'))]
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Running Tests -->
### Type checks

Running type checks with mypy:

```bash
  mypy project_title
```

### :test_tube: Running Tests

To run tests, run the following command

### Test coverage

To run the tests, check your test coverage, and generate an HTML coverage report:

```bash
  coverage run -m pytest\
  coverage html\
  open htmlcov/index.html\
```

#### Running tests with pytest

```basg
  pytest
```

<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/github_username/repo_name.git
```

Go to the project directory

```bash
  cd project_title
```

Install dependencies

```bash
  pip install -r requirements/local.txt
```

Start the server

```bash
  python mananage.py migrate\
  python manage.py runserver
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Usage -->
## :eyes: Usage

Example 1: Creating a New User
To create a new user, make a POST request to the /api/users/ endpoint with the required user information.

```python
import requests

url = "http://localhost:8000/api/users/"

data = {
    "username": "john_doe",
    "email": "john.doe@example.com",
    "password": "secretpassword",
}

response = requests.post(url, json=data)

if response.status_code == 201:
    print("User created successfully!")
else:
    print("Failed to create user.")

```

<!-- Roadmap -->
## :compass: Roadmap

- [x] Todo 1
- [ ] Todo 2

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/github_username/repo_name/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" />
</a>

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

See `contributing.md` for ways to get started.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Commiting your code

Before sending patches please make sure you have [pre-commit](https://pre-commit.com/) activated in your local git repository:

```sh
pre-commit install
```

This will ensure that your code is cleaned before you commit it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Code of Conduct -->
### :scroll: Code of Conduct

Please read the [Code of Conduct](https://github.com/github_username/repo_name/blob/master/CODE_OF_CONDUCT.md)

<!-- FAQ -->
## :grey_question: FAQ

<details closes>
  <summary>Question 1</summary>
  <p>Answer</p>
</details>

<details closes>
  <summary>Question 2</summary>
  <p>Answer</p>
</details>

<details closes>
  <summary>Question 3</summary>
  <p>Answer</p>
</details>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- License -->
## :warning: License

Distributed under the no License. See LICENSE.txt for more information.

<!-- Contact -->
## :handshake: Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - <email@email_client.com>

LinkedIn: [https://www.linkedin.com/in/linkedin_username/](https://www.linkedin.com/in/imperiumx/)

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<!-- Acknowledgments -->
## :gem: Acknowledgements

Use this section to mention useful resources and libraries that you have used in your projects.

- [Shields.io](https://shields.io/)
- [Awesome README](https://github.com/matiassingers/awesome-readme)
- [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
- [Readme Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
