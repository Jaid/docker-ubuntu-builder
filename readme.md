# docker-ubuntu-builder

![Latest GitHub release](https://img.shields.io/github/v/release/Jaid/docker-ubuntu-builder?label=Release&style=flat-square) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/Jaid/docker-ubuntu-builder/Push%20Docker?label=CI&style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNCAxNCIgd2lkdGg9IjE0IiBoZWlnaHQ9IjE0Ij48cGF0aCBmaWxsPSIjZmZmIiBkPSJNNyAxNGMzLjg2NiAwIDcgLTMuMTM0IDcgLTdTMTAuODY2IDAgNyAwIDAgMy4xMzQgMCA3czMuMTM0IDcgNyA3em0zLjA5IC04LjI4NUw2LjU5IDkuMjE1Yy0wLjI1NyAwLjI1NyAtMC42NzMgMC4yNTcgLTAuOTI3IDBsLTEuNzUgLTEuNzVjLTAuMjU3IC0wLjI1NyAtMC4yNTcgLTAuNjczIDAgLTAuOTI3czAuNjczIC0wLjI1NyAwLjkyNyAwbDEuMjg1IDEuMjg1TDkuMTYgNC43ODVjMC4yNTcgLTAuMjU3IDAuNjczIC0wLjI1NyAwLjkyNyAwczAuMjU3IDAuNjczIDAgMC45Mjd6Ii8+PC9zdmc+)  
![DockerHub stars](https://img.shields.io/docker/stars/jaidchen/ubuntu-builder?label=DockerHub+stars&color=1c90ed&style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNCAxMi40NDQiIHdpZHRoPSIxNCIgaGVpZ2h0PSIxMi40NDQiPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik03LjcwMiAwLjQzOGMtMC4xMjkgLTAuMjY3IC0wLjQwMSAtMC40MzggLTAuNyAtMC40MzhzLTAuNTY5IDAuMTcgLTAuNyAwLjQzOEw0Ljc0IDMuNjUzIDEuMjQ5IDQuMTY4Yy0wLjI5MiAwLjA0NCAtMC41MzUgMC4yNDggLTAuNjI1IDAuNTI3cy0wLjAxNyAwLjU4OCAwLjE5MiAwLjc5NUwzLjM0OSA3Ljk5N2wtMC41OTggMy41NDFjLTAuMDQ5IDAuMjkyIDAuMDczIDAuNTg4IDAuMzE0IDAuNzYxczAuNTU5IDAuMTk0IDAuODIyIDAuMDU2bDMuMTE4IC0xLjY2NSAzLjExOCAxLjY2NWMwLjI2MyAwLjEzOSAwLjU4MSAwLjExOSAwLjgyMiAtMC4wNTZzMC4zNjIgLTAuNDY5IDAuMzE0IC0wLjc2MUwxMC42NTggNy45OTdsMi41MzMgLTIuNTA2YzAuMjA5IC0wLjIwNyAwLjI4NCAtMC41MTUgMC4xOTIgLTAuNzk1cy0wLjMzMyAtMC40ODQgLTAuNjI1IC0wLjUyN2wtMy40OTMgLTAuNTE1TDcuNzAyIDAuNDM4eiIvPjwvc3ZnPg==) ![DockerHub pulls](https://img.shields.io/docker/pulls/jaidchen/ubuntu-builder?color=1c90ed&label=DockerHub%20pulls&logo=docker&logoColor=white&style=flat-square) ![Docker image size](https://img.shields.io/docker/image-size/jaidchen/ubuntu-builder/main?arch=arm64&label=Image+size&color=1c90ed&style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNCAxMS4yIj48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMi40NSAyLjFhLjcuNyAwIDAgMSAuNy0uN2guMzVhLjcuNyAwIDAgMSAuNy43djdhLjcuNyAwIDAgMS0uNy43aC0uMzVhLjcuNyAwIDAgMS0uNy0uN3YtLjdIMS40YS43LjcgMCAwIDEtLjctLjdWNi4zYS43LjcgMCAxIDEgMC0xLjRWMy41YS43LjcgMCAwIDEgLjctLjdoMS4wNXYtLjd6bTkuMSAwdi43aDEuMDVhLjcuNyAwIDAgMSAuNy43djEuNGEuNy43IDAgMSAxIDAgMS40djEuNGEuNy43IDAgMCAxLS43LjdoLTEuMDV2LjdhLjcuNyAwIDAgMS0uNy43aC0uMzVhLjcuNyAwIDAgMS0uNy0uN3YtN2EuNy43IDAgMCAxIC43LS43aC4zNWEuNy43IDAgMCAxIC43Ljd6TTkuMSA0Ljl2MS40SDQuOVY0LjloNC4yeiIvPjwvc3ZnPg==)