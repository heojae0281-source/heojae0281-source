<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:39d353&height=200&section=header&text=Hi%20there%20👋%20I'm%20Heo%20Jae&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Autonomous%20Driving&descAlignY=58&descSize=18" width="100%"/>

<img src="assets/hamster.png" width="180" alt="허재 햄스터"/>

```bash
$ whoami
> 허재 (heojae0281-source) — 자율주행을 만드는 개발자 🐹
$ cat interests.txt
> Autonomous Driving · Sensor Fusion
```

</div>

---

### 🧑‍💻 About Me

- 🚗 **FOSCAR**에서 HL FMA 2026 자율주행 스케일카를 만들었어요
- 📡 **카메라 + 라이다**로 장애물을 인지하고 안전하게 멈추는 기능을 개발했어요
- 🏁 SEA:ME 해커톤 2026 참가
- 📫 Contact: **heojae0281@gmail.com**

---

### 🚗 Projects

<table>
<tr><td>

#### 🏁 FOSCAR · HL FMA 2026 — 1/5 스케일카 자율주행
<sub>2026.07 – 2026.09 · 팀 프로젝트 · ROS 2 Humble · C++ / Python</sub>

**인지·안전 정지 파트를 맡아 개발했어요.**

- 📡 **라이다 장애물 인지 (`fma_obstacle`)**
  - 장애물 인지 노드를 처음 만들고, 3D Velodyne → 2D YDLiDAR G2로 포팅
  - 판단 로직을 ROS와 분리한 순수 모듈로 빼서 시뮬레이션 시나리오로 **TDD**
- 🛑 **긴급제동 · 동적 장애물 정지**
  - 차로를 가로지르는 동적 장애물 긴급제동 구현
  - 카메라·라이다 **교차 확인 정지 판단 노드(`fma_stop_decision`)** 설계·구현
  - 6초 재판단, 미션 구간 게이팅, 강제 해제 잠금 정책 설계
- 👁️ **YOLO 비전 인지**
  - 더미 인형 검출기(`fma_dummy_detector`): ROI 트리거, 다중 클래스, 재학습 모델 교체·검증
  - YOLO11 앞차 인지 시 6초 정차 패키지(`fma_rearcar_detector`) 신설
- 🚙 **실차 통합**
  - 미션 인덱스 도달 시 동적 장애물 스택을 자동 실행하는 bringup 런치
  - 정속 주행 + 긴급제동 실차 시험 런치와 문서 작성

</td></tr>
</table>

---

### 🛠️ Tech Stack

<div align="center">

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>

**Robotics & Autonomous Driving**<br/>
<img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/LiDAR-0d1117?style=for-the-badge&logo=lidar&logoColor=39d353"/>

**Environment & Tools**<br/>
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>

</div>

---

### 🐍 Contribution Snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/heojae0281-source/heojae0281-source/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/heojae0281-source/heojae0281-source/output/github-snake.svg" />
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/heojae0281-source/heojae0281-source/output/github-snake-dark.svg" />
</picture>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:39d353,50:1f6feb,100:0d1117&height=120&section=footer" width="100%"/>
