# flutter_on_docker

A new Flutter project.

### To build image
```
docker image build -t flutter-on-docker -f ./Dockerfile .   
```

### To run a container
run this command inside the root of this project
```
docker container run -p 3000:3000 --volume ${PWD}:/app/ -it flutter-on-docker
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
