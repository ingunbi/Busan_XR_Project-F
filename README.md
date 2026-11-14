# Project-F · Unreal 콘텐츠 제작 아카이브

![게임·XR·웹 개발을 표현한 공통 컨셉 표지](docs/images/developer-workshop.png)

<sub>공통 소개 이미지 · AI로 제작한 컨셉 아트이며 실제 프로젝트 실행 화면이 아닙니다.</sub>

**캐릭터 선택, 전투 스테이지와 승패 화면을 구성한 Unreal Engine 프로젝트입니다.**

부산 XR 프로젝트 과정의 콘텐츠 제작 자료를 보관합니다. 저장소에는 여러 전투 공간, 캐릭터·스테이지 선택 화면, VRM4U 플러그인이 포함되어 있습니다.

## 살펴볼 부분

| 구성 | 저장소 위치 |
| --- | --- |
| 전투 공간 | `Content/Level/Battle_Stage/` — Space·Office·SkyIsland·Volcano·WinterNight·WindMill 등의 맵 |
| 화면 흐름 | `Content/UI_LV/` — 로고·메인 메뉴·캐릭터 선택·승패 화면 |
| 스테이지 선택 | `Content/Level/Select_Window/` |
| 프로젝트 콘텐츠 | `Content/Project_F/` |
| 플러그인 | `Plugins/VRM4U/` |

## 열어보기

1. 저장소 전체를 내려받습니다.
2. **Unreal Engine 5.2**에서 [`Project_F.uproject`](Project_F.uproject)를 엽니다.
3. 콘텐츠 브라우저에서 `Content/UI_LV/Logo` 또는 살펴볼 전투 맵을 엽니다.
4. 필요한 플러그인과 에셋 참조를 확인한 뒤 에디터에서 실행합니다.

프로젝트 설정의 시작 맵은 `Logo`이지만 게임 기본 맵은 `Mainmenumap`으로 기록되어 있습니다. 현재 파일 목록에서 후자는 확인되지 않으므로 패키징 전에 맵 경로를 점검해야 합니다. 이번 문서 정리에서는 에디터 실행·패키징·XR 기기 동작을 검증하지 않았습니다.

## 입력 설정

설정 파일에는 방향키 이동, Space 점프, Z 공격, X 능력, C 추가 공격, 왼쪽 Shift 방어, 왼쪽 Control 변신, P 일시정지가 등록되어 있습니다. 실제 동작은 열린 맵과 Blueprint 연결에 따라 달라질 수 있습니다.

## 보관 범위

교육 과정의 제작 아카이브입니다. 포함된 외부 에셋·플러그인의 사용과 재배포에는 각 원저작자의 조건이 적용될 수 있습니다. 저장소 공개 자체가 모든 콘텐츠의 자유로운 재사용 허가를 뜻하지 않습니다.

---

[김인권 · GitHub](https://github.com/ingunbi) · [전체 프로젝트](https://inkwonworks.ingunbi.workers.dev/) · [IceCubeLab](https://www.icecubelab.com/)
