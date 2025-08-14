# 👋 안녕하세요! 문제 해결에 진심인 시스템 아키텍트 지향 개발자입니다

> **복잡한 분산 시스템 환경에서의 디버깅과 트러블슈팅을 통해 성장하는 개발자**  
> 단순히 코드를 넘어 인프라, 네트워크, 환경 설정, 그리고 외부 서비스 정책까지 종합적으로 고려하는 시스템적 사고 능력을 갖춘 개발자입니다.

<div align="center">
  
## 📊 GitHub 통계
  
  <a href="https://github.com/dorisuni">
    <img height="140" src="https://github-readme-stats.vercel.app/api?username=dorisuni&hide=issues&show_icons=true&theme=dark" />
  </a>
  <a href="https://github.com/dorisuni">
    <img height="140" src="https://github-readme-stats.vercel.app/api/top-langs?username=dorisuni&layout=compact&langs_count=8&theme=dark" />
  </a>
  
</div>

---

## 🛠️ 주요 기술 스택

### 💼 백엔드 & MSA
```java
Java 17 | Spring Boot 3.x | Spring Cloud (Gateway, Kubernetes Discovery, Eureka)  
Spring Security (JWT) | JPA (Hibernate) | PostgreSQL | Apache Kafka | Gradle
```
**성장 역량**: MSA 환경에서 발생하는 Kafka 연결, 서비스 디스커버리, Health Check, RBAC, JWT 인증, CORS 등 거의 모든 유형의 문제를 심층 분석 및 해결할 수 있는 숙련된 디버깅 능력

### ☁️ 클라우드 & DevOps
```yaml
Kubernetes (Minikube, Argo CD) | Docker | Jenkins | WSL 2 | Cloudflare Tunnels
```
**성장 역량**: Kubernetes Pod의 생명 주기, Health Probe, RBAC 권한 관리, DNS 기반 서비스 디스커버리 등 K8s 핵심 개념에 대한 실질적 이해

### 🤖 로보틱스 & 비전
```python
Python | Intel RealSense SDK (pyrealsense2) | Open3D | ROS 2 Humble | RTAB-Map | RViz2
```
**성장 역량**: .bag 파일 스트림 처리, ROS 2 노드 간 통신 및 토픽 리매핑, 3D 맵핑 알고리즘 연동 등 복잡한 로보틱스 시스템 디버깅 능력

### 📱 프론트엔드
```javascript
React Native | Expo | TypeScript | Axios | HTML5 | JavaScript ES6+
```
**성장 역량**: React Native/Expo 환경에서의 의존성 및 버전 호환성 문제 해결, 프로젝트 병합 및 코드 컨벤션 표준화

---

## 💡 핵심 프로젝트 & 성과

### 🏢 1. Coubee MSA Platform (E-commerce Backend System)
**기술 스택**: Spring Boot MSA, Kubernetes, Kafka, JWT, PortOne SDK

**주요 성과**:
- Spring Boot MSA를 Kubernetes(Minikube)에 성공적으로 배포
- Kafka & Zookeeper의 Kubernetes 내부 배포 및 안정화
- API Gateway를 통한 중앙 집중식 JWT 인증 시스템 구현
- PortOne (TossPay, KakaoPay) 결제 연동 문제 해결
- Cloudflare Tunnel을 이용한 E2E 테스트 완료

### 📷 2. Intel RealSense 3D 재구성 시스템
**기술 스택**: Python, Intel RealSense SDK, ROS 2, RTAB-Map

**주요 성과**:
- Intel RealSense .bag 파일의 컬러 및 깊이 스트림 시각화 구현
- ROS 2 환경에서 RTAB-Map을 이용한 3D 매핑 성공
- 공식 패키지의 한계를 우회한 커스텀 ROS 2 노드(bag_player.py) 개발
- 이기종 데이터 포맷 간의 브릿지 구축

### 🚀 3. Jenkins CI/CD & React Native 마이그레이션
**기술 스택**: Jenkins, React Native, Expo, TypeScript

**주요 성과**:
- 대규모 컴파일 에러(Lombok, Enum, 클래스 충돌 등) 체계적 해결
- 구버전 React Native 프로젝트의 핵심 기능을 최신 프로젝트로 성공적 이식
- 한글/영문 변수명 혼용 문제 표준화 및 중복 파일 제거

---

## 🚀 문제 해결 전문성

### 🎯 핵심 전략
**"Configuration is Code"** - 코드 로직만큼 설정 파일의 중요성을 인지하고 환경별 설정을 명확히 분리

### 🔧 진단 도구 마스터리
```bash
kubectl logs | kubectl describe pod | ros2 topic | 브라우저 개발자 도구
```
각 기술 스택의 핵심 진단 도구를 능숙하게 활용하여 데이터 흐름과 이벤트, 로그를 종합적으로 분석

### 🧩 문제 단순화 전략
복잡한 문제 발생 시 모든 의존성을 제거한 최소 기능의 독립 테스트 환경을 구축하여 문제 원인 분리 및 범위 좁히기

### ⚠️ 디버깅 원칙
> *"코드는 동일한데 특정 조건에서만 실패한다면, 문제는 코드가 아니라 데이터 또는 설정에 있을 확률이 높다"*

---

## 🌱 학습 & 성장 마인드셋

### 📚 학습 패턴
- **실전 중심**: 실제 코드 예제 분석 및 직접 구현을 통한 학습
- **오류 기반**: 오류 메시지를 가장 중요한 학습 자료로 활용
- **딥 워크**: AI와의 집중적인 대화를 통한 실시간 문제 해결

### 🤝 AI와의 협업 철학
AI를 빠른 문제 해결과 학습 가속화의 파트너로 활용하되, 제안을 맹신하지 않고 스스로 비판적 질문을 던지며 검증하는 인간 판단의 중요성 인지

---

## 📈 성장 계획

### 🎯 단기 목표 (향후 1.5개월)
- **Kubernetes 고급 운영**: Helm, Kustomize, Operator 패턴, GitOps 파이프라인 구축
- **Spring Cloud 심화**: Circuit Breaker, Retry, Rate Limiting 등 MSA 복원력 패턴
- **Kafka 고도화**: Kafka Streams, Kafka Connect를 활용한 데이터 파이프라인 구축
- **클라우드 실전**: AWS/Azure/GCP 실제 환경 MSA 배포 및 운영
- **테스트 코드**: JUnit 5, Mockito, Testcontainers 활용 능력 강화

### 🌟 장기 비전 (6개월 ~ 1년)
- MSA 아키텍처 기반 실서비스 개발 및 배포 경험 완료
- 주요 클라우드 플랫폼 핵심 서비스 활용 능력 확보
- CI/CD 및 모니터링 시스템 구축 기여 수준 달성
- **로보틱스 × 백엔드/클라우드 융합형 개발자**로서 새로운 가치 창출

---

## 📫 연락처

<div align="center">
  
  <a href="mailto:daizy13125@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white" />
  </a>
  <a href="https://velog.io/@daizy13125">
    <img src="https://img.shields.io/badge/Tech%20Blog-11B48A?style=for-the-badge&logo=Vimeo&logoColor=white" />
  </a>
  
</div>

---

<div align="center">
  
### 💭 개발 철학
**"끊임없이 학습하고 성장하는 문제 해결 중심의 시스템 아키텍트"**

*복잡한 시스템의 문제를 해결할 때 가장 큰 성취감을 느끼며,*  
*기술적 깊이와 폭넓은 시야를 모두 갖춘 개발자로 성장하고 있습니다.*

</div>
