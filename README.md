# Software Evolution - Practical Session: Building a GitHub Bot

## About the Guest Lecturer
[Mairieli Wessel](https://mairieli.github.io/) is an Assistant Professor at the department of software science at [Radboud University Nijmegen, The Netherlands](https://www.ru.nl/).

## Preparations

Before coming to the practical session, please do the following:

- Make sure you have **[Python 3.9.X](https://www.python.org/downloads/release/python-399/)** installed on your machine.
- Make sure you also have **[npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)** installed.
- Create a [**GitHub account**](https://github.com/signup) if you do not already have one yet.

There are other **important resources** that we are going to use throughout the session:

- **Flask** as our Python webserver
    - Installation: `pip install -U Flask`
    - Flask documentation: [https://flask.palletsprojects.com](https://flask.palletsprojects.com/)
- **PyGitHub** to communicate with GitHub
    - Installation: `pip install PyGitHub`
    - PyGitHub documentation: [https://pygithub.readthedocs.io](https://pygithub.readthedocs.io/)
- **cryptography** for decrypting our GitHub App certificates
    - Installation:  `pip install cryptography`
    - cryptography documentation: [https://cryptography.io](https://cryptography.io/)
- **smee.io** to receive payloads from GitHub
    - Installation: `npm install --global smee-client`
    - After the installation, validate the it by running: `smee --version` . If the *smee* version appears, you are good to go!
