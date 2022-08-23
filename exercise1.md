# CI/CD for a Python App

## CI Setup

Below listed are common tools to perform the relevant CI steps:

- CI Server:
  - self-hosted: Jenkins, Buildbot, BuildMaster, Drone, Concourse
  - cloud: Semaphore, GitHub Actions, GitLab CI
- Linting: Pylint, flake8, black, pre-commit
- Testing: Pytest, codecov
- Building: Travis CI
- Hosting: PythonAnywhere, PyPi

As each one has its own strengths, speciality and compatiblity, care has to be taken to select the right set of solutions.

## Self-hosted or Cloud-based/Managed?

For the project with 6 developers, it is recommended to make use of cloud-based CI/CD solutions because cloud-based solutions:

- are cheaper to start out (no need to purchase the hardware and software upfront)
- are faster to set up (self-hosted solution may need a new hire/extra resources need to bring in to set up and manage the CI/CD infrastructure)
- have security taken care of
- provide out-of-box solutions for integration

As the project is about to release, the whole team must work together on development rather than setting up the CI/CD pipeline, it is advisable to make use of cloud-based solutions initially. However, the actual needs of the project must be considered carefully and check whether a managed solution is flexible enough to adapt to all requirements.
