# Snapmaker U1 DIY Top Cover

*Read this in other languages: [English](README.md), [한국어](README_KR.md)*

3D 프린터 스냅메이커 U1용 탑커버 DIY 프로젝트입니다.

## 📋 프로젝트 개요

3D 스캐너로 측정한 데이터를 바탕으로 제작된 스냅메이커 U1용 탑커버 설계 및 출력 데이터를 공유합니다.

## 📸 프로젝트 갤러리

### 3D 스캔 과정
![3D 스캔](Photos/3dscan.png)
*레보포인트 매트로X로 스냅메이커 U1 스캔 중*

### 프레임 조립 및 테스트
<table>
  <tr>
    <td><img src="Photos/test1.png" alt="조립 테스트" width="300"/></td>
    <td><img src="Photos/installation.png" alt="설치" width="300"/></td>
  </tr>
  <tr>
    <td><em>프레임 가조립 테스트</em></td>
    <td><em>스냅메이커 U1에 설치</em></td>
  </tr>
</table>

### 성능 테스트 결과
<table>
  <tr>
    <td><img src="Photos/test2.png" alt="저온 테스트" width="300"/></td>
    <td><img src="Photos/result1.png" alt="온도 결과" width="300"/></td>
  </tr>
  <tr>
    <td><em>저온 테스트 (외기온도 10°C)</em></td>
    <td><em>챔버 내부 온도 26°C 달성</em></td>
  </tr>
</table>

![SoonSoon Frame Version 1](soonsoon_topcover_1.jpg)
*SoonSoon Frame Version 1 - 비닐 씌워서 사용 가능*

## 📁 폴더 구조

### SizeData
- 3D 스캔 데이터를 바탕으로 한 설계 데이터
- 다른 사용자들이 자신만의 커버를 제작할 때 참고할 수 있는 기본 데이터
- 포함 파일:
  - `U1_Body.stl` - U1 본체 스캔 데이터
  - `BaseGuide.stl` - 베이스 가이드
  - `SizeDataTopview.jpg` - 상면도 참고 이미지

### SoonsoonFrameVer1
비닐을 씌워서 사용하는 프레임 버전 1

**버전 1 특징:**
- **저비용 설계**: 최대한 저렴한 가격에 탑커버를 제작하기 위한 프로젝트
- **프레임 전용 설계**: 프레임만 제작하고 대형 비닐을 붙여서 내부 열이 빠져나가지 않도록 하는 용도
- **열 보온 기능**: 내부 열 유지 (소음 방지: ❌)
- **⚠️ 온도 주의사항**: 출력하는 곳의 온도가 20도가 넘어가는 곳에서는 사용하지 마세요 (U1이 망가지거나 출력품 품질이 떨어질 수 있습니다)

#### BottomGuide
- 하단 가이드 파트들 (8개 파트로 분할)
- 300x300mm 이상 프린터에서 출력 가능

#### TopGuide  
- 상단 가이드 파트들 (6개 파트로 분할)
- 일부 파트는 270x270mm 프린터에서도 출력 가능

#### PillarSet
- 기둥 세트 (상단/하단)

## 🛠️ 제작 정보

- **3D 스캔**: 레보포인트 매트로X 사용
- **설계 소프트웨어**: Fusion 360
- **출력 권장 사이즈**: 300x300mm 이상 (일부 파트는 270x270mm 가능)

## 📜 라이선스 및 사용 조건

### ✅ 허용 사항
- 개인 취미용 사용
- 교육용 사용
- 무료 사용

### ❌ 금지 사항
- 상업적 사용
- 재배포

### ⚠️ 특별 허가 필요
상업적 사용이나 재배포를 원하시는 경우 제작자의 사전 허락이 필요합니다.

## 🔧 사용 방법

1. `SizeData` 폴더의 데이터를 참고하여 본인만의 설계 진행
2. 또는 `SoonsoonFrameVer1` 폴더의 STL 파일들을 직접 출력
3. 출력된 프레임에 비닐을 씌워서 탑커버로 사용

## 📺 관련 영상

### 스냅메이커 U1 개봉기 및 사용기
[![스냅메이커 U1 개봉기 및 사용기](https://img.youtube.com/vi/_z2r_KzoY_w/maxresdefault.jpg)](https://youtu.be/_z2r_KzoY_w)

### 2일차 사용기 및 초기 사용시 주의사항
[![2일차 사용기 및 초기 사용시 주의사항](https://img.youtube.com/vi/NYfomqTddzs/maxresdefault.jpg)](https://youtu.be/NYfomqTddzs)

## 💖 프로젝트 후원

이 프로젝트가 도움이 되었다면 후원을 고려해주세요:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-후원-yellow.svg?style=flat-square&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/soonsoon)
[![PayPal](https://img.shields.io/badge/PayPal-기부-blue.svg?style=flat-square&logo=paypal)](https://paypal.me/soonsoon2)

## 📞 문의

상업적 사용이나 재배포 관련 문의:
- **GitHub**: soonsoon
- **이메일**: soonsoon@soonsoons.com
- **이슈**: 이 저장소에 이슈를 남겨주세요

---

**⚡ 주의사항**: 이 데이터는 개인 프로젝트로 제작되었으며, 사용 시 발생하는 모든 책임은 사용자에게 있습니다.