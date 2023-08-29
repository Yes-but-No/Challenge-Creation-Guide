# Challenge Creation Guide

## Challenge Template
The challenge file structure is fixed and is as follows:
```
challenge_name/
├─ dist/
│  ├─ file_to_give_to_people
├─ service/
│  ├─ dockerfile
├─ chall.yaml
├─ README.md
```

The `dist` directory is for specifying files that should be given to participants, and the `service` directory is for files to be run in a docker container if the challenge needs to be hosted.

The `chall.yaml` file is a special configuration file that must be present in every challenge folder. It is used to programmatically create the challenges.

In the `example` directory of this repository, you will see a sample challenge to showcase the template.
