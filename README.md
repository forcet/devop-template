# CI/CD Templates · Helm + OpenShift

Este repositorio contiene **workflows reutilizables de GitHub Actions** para:

- Desplegar aplicaciones con Helm en OpenShift.
- Integrarse fácilmente con proyectos que **construyen su propia imagen Docker**.
- Soportar proyectos que **solo hacen deploy usando una imagen ya existente**.

La idea es centralizar la lógica de deploy en un solo lugar y que los repos de aplicaciones solo llamen a estos workflows.
