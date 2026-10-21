# 전도영 (Do Yeong Jeon)

SW와 기반 Infra를 함께 설계하고 구현해 온 SW 엔지니어입니다. 대학원에서 강화학습 기반 SW 시스템을 연구했고, 이후 AI 모델 서빙 플랫폼과 K8s·GPU 인프라를 설계하고 운영해 왔습니다.  
I'm a software engineer who designs and builds software together with the infrastructure it runs on. I researched reinforcement learning-based software systems in graduate school, and have since designed and operated AI model serving platforms and Kubernetes/GPU infrastructure.

업무 코드와 대학원 연구 코드는 각각 회사와 연구실 저장소에 있어 공개되어 있지 않습니다.  
Work and graduate research code live in company and lab repositories and are not public.

**기술 / Skills**
- SW Design: UML · SRS · C4 · ADR
- Backend: Python · FastAPI · SQLAlchemy · MariaDB · PostgreSQL
- Infra: Kubernetes · Helm · NVIDIA GPU Operator · DRA · Prometheus · GitLab CI/CD · GCP
- Serving·MLOps: vLLM · TEI · Kubeflow Training Operator · MLflow

**공개 기여 / Open source**
- kubernetes-sigs/dra-driver-nvidia-gpu [#1272](https://github.com/kubernetes-sigs/dra-driver-nvidia-gpu/issues/1272)  
  gpu-kubelet-plugin이 NVML 라이브러리를 찾을 때 같은 이름의 디렉터리를 선택해 재시작을 반복하는 문제를 보고했고, 수정 PR [#1275](https://github.com/kubernetes-sigs/dra-driver-nvidia-gpu/pull/1275)가 머지됐습니다.  
  Reported an NVML library discovery bug in gpu-kubelet-plugin; fixed by the merged PR #1275.  
  같은 탐색 코드를 쓰던 NVIDIA/go-nvlib [#108](https://github.com/NVIDIA/go-nvlib/pull/108)과 NVIDIA/k8s-device-plugin [#2025](https://github.com/NVIDIA/k8s-device-plugin/pull/2025)에도 같은 수정이 머지됐습니다. 수정 PR은 모두 다른 기여자가 작성했습니다.  
  The same fix was also merged into NVIDIA/go-nvlib #108 and NVIDIA/k8s-device-plugin #2025, which share the same discovery code. All fix PRs were written by other contributors.

**연락 / Contact**  
[LinkedIn](https://www.linkedin.com/in/do-yeong-jeon)
