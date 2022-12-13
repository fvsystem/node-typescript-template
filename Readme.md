<p align="center">

### ABOUT

</p>

This is a template for applications that use Node 16 with Typescript. This template has eslint configured, tests with Jest, lint commit (using conventional commits) and docker configuration for production an dev environment.

<p align="center">

### USING

</p>

To use this template, press the "Use Template" button on first page of this repository on Github, this will create a repository on your Github account, from which you can execute git clone command.

If you have docker installed on your machine, you can run the development environment by executing the following command:

```
docker compose up --build -d

docker-compose exec node bash
```

This docker configuration is not ready to expose ports, please, check docker documentation in case you need to expose ports.

<p align="center">

### COMMITING

</p>

To commit on this repository, run the following command:

```
npm run commit
```

It will guide your through the conventional commit template. If you do not follow the conventional commit, a hook will prevent your commit to be completed.
