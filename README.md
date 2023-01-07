# 🐑 golang-pipeline
- CI/CD 학습을 위한 GitHub Workflow 샘플입니다. 

# 📚 기술 스택
- go 1.18
- docker
- docker-hub
- github workflow

# 🛠 아키텍처
- **추가 필요**

# 🌟 주요 기능
- GitHub Workflow 를 통해 생성한 두 가지 JOB 이 있으며 commit-push 실행시 hook 이벤트 발생 


- 첫 번째 JOB 의 경우 go unit test 를 위한 명령어 실행
  - master 브랜치 또는 tag 인 경우
- 두 번째 JOB 의 경우 docker build 이 후 DockerHub Repository 로 푸시
  - tag 인 경우

# 🌠 실행 화면
- [1] Tag 에 대한 Push 발생시 동작하는 화면
![GitHub Workflow](./docs/image/GitHub_Workflow.png)

- [2] Deploy 과정 이 후 DockerHub 에 생성된 화면
![DockerHub Repo](./docs/image/DockerHub_Repo.png)

# 😎 짧은 평
- CI/CD 학습을 위한 