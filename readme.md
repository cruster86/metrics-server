Апстрим проект: https://github.com/kubernetes-sigs/metrics-server/tree/master

Сборка образа из апстрим проекта:

  - сборочный образ: `FROM golang:latest as build`
  - релизный образ: `FROM gcr.io/distroless/static:latest-amd64`