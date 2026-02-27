# 🌿 Stochastic Auto Green

<p align="center">
  <img src="https://images.weserv.nl/?url=https://images.pexels.com/photos/61098/pexels-photo-61098.jpeg&w=1200&h=300&fit=cover&a=center" width="100%" alt="auto-green banner">
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/10041107/auto-green?style=flat-square" />
  <img src="https://img.shields.io/github/stars/10041107/auto-green?style=flat-square" />
  <img src="https://img.shields.io/github/forks/10041107/auto-green?style=flat-square" />
</p>

<p align="center">
  <b>An intelligent, human-like GitHub contribution bot.</b><br>
  <i>확률적 로직을 기반으로 한 인간미 넘치는 자동 잔디 관리 봇</i>
</p>

---

### 💡 Why auto-green?

Fixed-time bots are predictable. **auto-green** mimics human irregularity using stochastic probability.  
기계적으로 매일 같은 시간에 커밋하는 봇은 쉽게 들통납니다. **auto-green**은 "인간의 불규칙성"을 모방합니다.  

* **Randomized Timing (24h)**: 매일 새벽 첫 실행 시 그날의 커밋 시간을 무작위로 예약합니다.
* **Weighted Probabilities**: 평일(95%)과 주말(40%)의 확률을 다르게 설정하여 실제 활동 패턴을 모사합니다.

---

### 📊 Probability Logic (잔디 심기 로직)

| Day (요일) | Success Rate (확률) | Description (설명) |
| :--- | :--- | :--- |
| **Weekdays (평일)** | **95%** | 성실한 개발자의 모습 (Most days) |
| **Weekends (주말)** | **40%** | 충분한 휴식을 즐기는 주말 (Relaxing) |
| **Time (시간)** | **Target Hour** | 0~23시 중 무작위 1회 결정 및 대기 |

---

### 🚀 Quick Start (설정 방법)

1. **Repository Settings**:
   * 레포지토리의 **settings** > **Actions** > **General**로 이동합니다.
   * **Workflow permissions** 섹션에서 **Read and write permissions**를 활성화하고 저장하세요.

2. **Workflow File Setup**:
   * `.github/workflows/auto_green_example.yml` 파일을 복제합니다.
   * 복제한 파일의 이름을 `auto_green.yml`로 변경하세요. (이름이 정확해야 GitHub Actions가 인식합니다.)

3. **Git Identity Setup**:
   * 생성한 `auto_green.yml` 파일 내부의 `git config` 설정에 본인의 정보를 입력하세요.
   * `user.email`: 본인의 GitHub **settings** > **Emails**에 등록된 Primary Email.
   * `user.name`: 본인의 GitHub Username.

4. **Manual Trigger**:
   * **Actions** 탭에서 `Stochastic Auto Green` 워크플로를 선택하고 **Run workflow**를 클릭하여 수동으로 실행해 보세요.

5. **Automatic Operation**:
   * 설정이 완료되면 매시간 워크플로가 가동되며, 예약된 시간에 자동으로 잔디를 심습니다.
   * 추적 파일(`last_update.txt`, `target_decision.txt`)은 자동으로 관리됩니다.

---

## ☕ Support & Donation

이 프로젝트가 마음에 드셨다면 별(⭐)을 눌러주시고, 개발자에게 따뜻한 커피 한 잔을 선물해 주세요!  
If this project helped you, please consider buying me a coffee!

<p align="left">
  <a href="https://buymeacoffee.com/10041107" target="_blank">
    <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me a Coffee">
  </a>
</p>

---

### ⚖️ License

**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**

* **Non-Commercial**: 비상업적 용도로만 사용 가능합니다.
* **Attribution**: 2차 가공 및 재배포 시 반드시 원작자(**@10041107**)의 출처를 밝혀야 합니다.
* **Modification**: 비상업적 목적의 자유로운 수정을 허용합니다.

---
<p align="right">Maintained with ❤️ by <a href="https://github.com/10041107">10041107</a></p>