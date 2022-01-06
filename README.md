# International Phonebook

This repository holds the [UI (Frontend)](https://github.com/m-ohamed/intl-phonebook-ui) and the [Service (Backend)](https://github.com/m-ohamed/intl-phonebook-svc) as well as the Docker Compose file used to run each dockerized project.

To correctly clone this repository and all its submodules please run the following command:

```sh
git clone --recurse-submodules -j8 https://github.com/m-ohamed/intl-phonebook.git
```

To run the whole project please run the following command in the root folder of your project:

```sh
docker-compose up --build
```
