<div align="center">

<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:4ECDC4,100:45B7D1&height=200&section=header&text=LemonDouble&fontSize=60&fontColor=ffffff&fontAlignY=35&desc=Homelab%20%7C%20Home%20Automation%20%7C%20ML%20%7C%20Open%20Source&descSize=18&descAlignY=55&animation=fadeIn" width="100%" />

![Profile Views](https://komarev.com/ghpvc/?username=Lemondouble&color=45B7D1&style=flat-square&label=Profile+Views)

</div>

## ⚡ Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**Infra & DevOps**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Cloud & Storage**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white)

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**IoT & Automation**

![Home Assistant](https://img.shields.io/badge/Home_Assistant-18BCF2?style=for-the-badge&logo=homeassistant&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white)

</div>

---

## 🏠 Homelab

<table>
<tr><td>

가정용 K3S 클러스터를 ArgoCD GitOps로 운영하고 있습니다.

| | 노드 | 스펙 |
|---|---|---|
| 🖥️ | Control | Mini PC — Ryzen 3750H |
| 🎮 | GPU Worker | Ryzen 5600x / RTX 3090 / 64GB |

**운영중인 서비스**: Auth Server (Go SSO), ML Server (TTS/ML, RTX 3090), Search Server (OpenSearch), Immich, LibreChat, Ollama, Misskey, RustFS, Argo Workflows, Home Assistant 등

**인프라 스택**: Traefik, Longhorn (SSD/NVMe/HDD 3계층), CloudNative PG (pgvector), MetalLB, cert-manager, KEDA, Sealed Secrets

</td></tr>
</table>

---

## 🔧 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Home Assistant 커스텀 통합
| Repo | 설명 |
|---|---|
| [ble_controller](https://github.com/Lemon-HACS/ble_controller) | BLE GATT 기반 범용 컨트롤러 |
| [extended_graph_agents](https://github.com/Lemon-HACS/extended_graph_agents) | LangGraph 스타일 멀티에이전트 워크플로우 |
| [lemon_tts](https://github.com/Lemon-HACS/lemon_tts) | 다국어→일본어 TTS 통합 |

</td>
<td width="50%" valign="top">

### Obsidian 플러그인
| Repo | 설명 |
|---|---|
| [kanban](https://github.com/Lemon-Obsidian/kanban) | 풀기능 칸반 보드 (v2) |
| [git-sync](https://github.com/Lemon-Obsidian/git-sync) | 자동 Git 동기화 |
| [image-manager](https://github.com/Lemon-Obsidian/image-manager) | 이미지 자동 최적화 (WebP/AVIF) |
| [write-helper](https://github.com/Lemon-Obsidian/write-helper) | LLM 기반 글쓰기 보조 |

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ML / TTS
| Repo | 설명 |
|---|---|
| [Style-Bert-VITS2](https://github.com/LemonDouble/Style-Bert-VITS2) | 일본어 TTS 라이브러리 (Fork) |
| [lemon-pyopenjtalk-prebuilt](https://github.com/LemonDoubleHQ/lemon-pyopenjtalk-prebuilt) | pyopenjtalk 사전빌드 wheel |

</td>
<td width="50%" valign="top">

### 기타
| Repo | 설명 |
|---|---|
| [claude-slack-bridge](https://github.com/LemonDouble/claude-slack-bridge) | Claude Code ↔ Slack MCP 브릿지 |
| [skopeo-setup-action](https://github.com/LemonDouble/skopeo-setup-action) | GitHub Actions skopeo 셋업 |
| [misskey](https://github.com/LemonDouble/misskey) | 셀프호스팅 Misskey 인스턴스 |

</td>
</tr>
</table>

---

## 🌏 Open Source Contributions

| 연도 | 프로젝트 | PR | 내용 |
|:---:|---|---|---|
| 2025 | [rustfs/rustfs](https://github.com/rustfs/rustfs) | [#1018](https://github.com/rustfs/rustfs/pull/1018) | Helm chart storageSize를 data/log 별도 파라미터로 분리 |
| 2025 | [thuliteio/doks](https://github.com/thuliteio/doks) | [#1356](https://github.com/thuliteio/doks/pull/1356) | Hugo 버전 업그레이드 호환성 수정 |
| 2025 | [Jaydee94/kubeseal-webgui](https://github.com/Jaydee94/kubeseal-webgui) | [#278](https://github.com/Jaydee94/kubeseal-webgui/pull/278) | Secret 클립보드 복사 기능 수정 |
| 2024 | [opensearch-project/helm-charts](https://github.com/opensearch-project/helm-charts) | [#618](https://github.com/opensearch-project/helm-charts/pull/618) | opensearch.yml security plugin 충돌 수정 |
| 2023 | [minio/operator](https://github.com/minio/operator) | [#1910](https://github.com/minio/operator/pull/1910) | existingSecret YAML 들여쓰기 수정 |
| 2023 | [getsentry/sentry](https://github.com/getsentry/sentry) | [#60571](https://github.com/getsentry/sentry/pull/60571) | 문서 오타 수정 |
| 2023 | [stepci/stepci](https://github.com/stepci/stepci) | [#66](https://github.com/stepci/stepci/pull/66) | CLI 기본 명령어 출력 추가 |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=LemonDouble&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=45B7D1&icon_color=4ECDC4&text_color=FFFFFF" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LemonDouble&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=45B7D1&text_color=FFFFFF&langs_count=8" height="170" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=LemonDouble&theme=tokyonight&hide_border=true&background=0D1117&ring=45B7D1&fire=FF6B6B&currStreakLabel=4ECDC4" width="700" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:4ECDC4,100:45B7D1&height=100&section=footer" width="100%" />

</div>
