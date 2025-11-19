# CI/CD
CI/CD with GitHub Actions

- GitHub Actions workflow: `.github/workflows/deploy.yml`
- 서버 서비스 파일: `/etc/systemd/system/image-service.service`
- 코드 푸시 시 자동 빌드 및 배포, systemd로 서비스 관리
- 레포지토리의 setting에서 Actions secrets and variables 등록
