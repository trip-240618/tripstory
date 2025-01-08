<img src="https://github.com/user-attachments/assets/37770302-aa61-4121-addc-3066043b45e9" width="100%">

# 트립스토리 (TirpStory)
> “여행 계획 세우는 거,,, 왜 이렇게 힘든 거야!!!”
> 
> “일정 짜려고 하니까 어디부터 시작해야 할지 모르겠고,,, 머리만 아프네,,,”
> 
> “모두가 만족할 만한 일정은 어떻게 만들지?”


트립스토리라면 이런 고민 한 방에 해결!
내 여행 스타일에 맞는 템플릿, 친구들과 함께 만드는 일정 그리고 추억을 간직할 기록 관리까지!

**지금 바로 트립스토리에서 간편하게 여행을 시작해보세요! 🚀✨**

## 목차
1. [주요 기능](#주요-기능)
2. [배포 링크](#배포-링크)
3. [프로젝트 아키텍처](#프로젝트-아키텍처)
4. [기술 스택](#기술-스택)
5. [라이브러리](#라이브러리)
6. [폴더 구조](#폴더-구조)

   
## 🚧 개발 기간

> 2024.09 ~ 2024.12.

## 주요 기능

### 1. 메인 홈

<img src="https://github.com/user-attachments/assets/db4727cf-db4a-44b6-8d07-0d493dbde5ce" width="100%">

### 2. 여행일정 (Mbti - J형)
<img src="https://github.com/user-attachments/assets/64ee9644-df99-4e77-acd8-fea277d9dcdb" width="100%">

### 3. 여행일정 (Mbti - P형)
<img src="https://github.com/user-attachments/assets/6e97c72a-3a33-410b-b704-4cf522c838ae" width="100%">

### 4. 보관함
<img src="https://github.com/user-attachments/assets/07aa0d6f-3306-4117-bd48-1f6a3ea69dea" width="100%">

### 5. 여행기록
<img src="https://github.com/user-attachments/assets/bc2659bb-5293-4204-841a-440396b47f56" width="100%">

## 배포 링크
- [앱스토어 배포 링크](https://apps.apple.com/kr/app/%ED%8A%B8%EB%A6%BD%EC%8A%A4%ED%86%A0%EB%A6%AC/id6529530493)
- 플레이스토어 배포 준비중

## 프로젝트 아키텍처
<img src="https://github.com/user-attachments/assets/c570f853-a203-43c4-a1b5-32b0f698223f" width="100%">

## 기술 스택
<img class="badge" src="https://img.shields.io/badge/Flutter-3.24.0-blue"> <img class="badge" src="https://img.shields.io/badge/dart-3.5.0-blue">

## 라이브러리
| 라이브러리                  | Version     | 
| ---------------------------- | :-----:  |
| kakao_flutter_sdk            | `1.9.3`  |
| sign_in_with_apple           | `6.1.1`  |
| google_sign_in               | `6.2.1`  |
| stomp_dart_client            | `2.0.0`  |
| flutter_jailbreak_detection  | `1.10.0` |
| get                          | `4.6.6`  |
| firebase_messaging           | `15.0.3` |
| flutter_local_notifications  | `17.2.1+1` |
| google_maps_flutter          | `2.6.0`  |
| google_places_flutter        | `2.0.9` |
| flutter_quill                | `10.4.5` |
| flutter_quill_extensions     | `10.4.5` |
| connectivity_plus            | `6.1.1` |
| google_maps_cluster_manager_2| `3.2.0` |
| flutter_cache_manager        | `3.4.1` |

## 폴더 구조
```
lib
├── App
│   ├── API
│   ├── Config
│   ├── Notification
│   ├── Permission
│   └── Sns
├── Component
│   ├── Button
│   ├── Container
│   ├── Dialog
│   ├── Empty
│   ├── History
│   ├── Loading
│   ├── TextForm
│   └── Toast
├── Controller
│   └── State
├── Model
├── Screen
│   ├── Login
│   ├── Main
│   ├── MyPage
│   └── Trip
└──  Util
     ├── Color
     ├── CustomMarker
     ├── FileUtils
     ├── Font
     └── HistoryClusterItem
```
