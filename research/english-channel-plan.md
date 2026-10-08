# 미국 타깃 건축·인프라 쇼츠 채널 기획안

> 작성일: 2026-10-07 (미국 전용으로 개정) · 선행 문서: [architecture-shorts-kalkapi-5.md](./architecture-shorts-kalkapi-5.md)
> 원본 모델: 「신비한 건축사전」(구독 79.9만, 쇼츠 446개, 누적 3.27억 뷰) 포맷을 미국 시청자용으로 이식

---

## 0. 한 줄 컨셉

**"The America you drive through every day isn't what you think it is."**
미국인이 매일 보는 수탑·고속도로·강·댐·다운타운의 정체를 60초 안에 뒤집는, 얼굴 없는 AI 3D 단면도 채널.

**포지셔닝 한 문장**: Practical Engineering의 주제를 Zack D. Films의 속도로, 도면 언어(치수선·단면도)로, 미국 지명을 박아서.

**왜 미국만**
- 유튜브 쇼츠 광고 단가와 시청자 규모가 가장 크고, 소재 하나가 전국 단위로 공유됨(NYC·시카고·LA·휴스턴 소재는 그 도시 사람들이 자발적으로 퍼뜨림).
- 원본 채널의 성공 공식이 **"내 동네"** 특정성이었음. 미국판은 "내 도시"로 번역돼야 작동함.
- 소재가 바닥나지 않음: 미국 토목사(시카고 들어올리기, 갤버스턴 지반 높이기, 후버댐, 미시시피 29개 댐, 스피릿 호수 터널)는 그 자체가 원본 채널의 서울 지리 편과 1:1 대응됨.

| | 영어권 기존 | 우리 |
|---|---|---|
| 전문가 롱폼 (Practical Engineering, B1M, Stewart Hicks) | 8~20분, 얼굴 노출, 주 1편 | 60초, 얼굴 없음, 매일 |
| 범용 3D 쇼츠 (Zack D. Films) | 인체·동물·사고 등 모든 호기심 | 건축·인프라만. 수치와 단면도가 시그니처 |
| 소형 시도 (Hidden Civil Engineering 등) | 구독 2천 미만, 비주얼 약함 | AI 포토리얼 3D + 일관된 그래픽 규격 + 미국 지명 |

---

## 1. 채널 아이덴티티

### 채널명 후보 (핸들 가용성은 개설 시 확인)

| 후보 | 뉘앙스 | 비고 |
|---|---|---|
| **Under America** | 미국 전용 포지션을 이름에 박음. 중립적 | 1순위. 시리즈명 "Under Your City"와 호환 |
| **Hidden Blueprint** | 치수선·도면 비주얼과 직결. 중립적 | 2순위 |
| **The Concrete Truth** | "진짜 이유" 공식과 연결 | 3순위 |
| ~~Built Wrong?~~ | 비난 뉘앙스. 실존 건설사·건물주를 "잘못 지었다"고 암시해 신고·명예훼손 분쟁 소지 | **제외** |

채널명·시리즈명·제목 어디에도 "wrong", "scam", "fail", "dangerous", "cover-up" 같은 비난·공포 단어를 쓰지 않습니다(§10 참조).

### 바이오 (영어)
```
Everything you drive past every day has a secret under it.
60-second cutaways of American buildings, bridges, rivers and the stuff under your street.
All visuals AI-rendered. Every number sourced. New short daily.
```

### 시그니처 비주얼 규격 (v2: 실사 기반 시네마틱 3D)

**기준 한 줄: "뉴욕에서 드론 띄워 찍고 VFX를 얹었다"로 보여야 한다.** 미국 시청자는 픽사·게임 시네마틱·Zack D 급 3D에 익숙합니다. 모형·디오라마·받침대 위 단면처럼 보이는 순간 이탈합니다.

| 층 | 내용 | 금지 |
|---|---|---|
| **① 실사 베이스** | 실제 거리·옥상·지하를 찍은 사진(직접 촬영 또는 CC0)을 Nano Banana **Ingredients**로 넣어 구도·빛·재질을 그대로 가져온 포토리얼 장면. 35mm 아나모픽 느낌, 얕은 심도, 필름 그레인, 하이라이트 롤오프 | 받침대·전시대·디오라마·토이 룩 |
| **② 엑스레이 리빌** | 실사 장면 안에서 벽·바닥·땅이 **국소적으로** 유리처럼 투명해지며 내부가 드러남. 가장자리는 얇은 붉은 선 하나. 안쪽은 결로·녹·때가 있는 실물 재질 | 절단 단면·투시선·파란 홀로그램·다이어그램 |
| **③ 실물 3D 글자** | 큰자막은 장면 안에 **실제로 놓인 금속·석재 글자**. 장면 조명을 받고 그림자를 드리우며 카메라 이동 시 시차가 생김 | 떠 있는 UI 자막 |

- **단위**: 피트·마일·톤·갤런(미국 단위) 우선, 미터는 쓰지 않음.
- **자막(소형)**: 흰색 산세리프(Inter Bold), 화면 하단 1/3, 한 번에 한 줄. 유행어 6개는 붉은 밑줄 한 줄.
- **연출 장치**: 매 편 하나. 디오라마 옆 소품이 아니라 **장면 속 실물**로(지하 펌프실의 압력 게이지, 공사 현장의 측량 막대, 취수탑 벽의 수위 눈금 등). 숫자는 편집에서.
- **카메라 언어**: 드론 오빗·하강, FPV로 창문 통과, 매크로 돌리. 모든 움직임에 무게. 한 편 안에서 빛이 흐름(블루아워 → 아침 → 골든아워).
- **지도 컷**: 매 편 1회, 실사 위성 느낌의 미국 지도에서 해당 도시로 줌인(0.5초).
- **로고**: 붉은 치수선으로 그린 ㄱ자 꺾쇠 + 채널명. 영상 끝 0.5초만 노출.
- **품질 게이트**: 생성물마다 첫 질문은 "이게 사진으로 보이나?" 아니면 탈락. 1편 컷 1·3·7이 기준 샷.

### 보이스 스펙
- 남성 또는 중성, 30대, 미국 일반(General American) 억양, 분당 150~160단어. 감탄·웃음 없음.
- ElevenLabs 계열 TTS 1개 보이스로 고정. 바꾸지 않음.

### 어투 규정: 정중한 안내자 (영어 존댓말)
일본어 시트의 「です・ます」, 한국어 시트의 "~해요"에 대응하는 영어 공손체입니다. 박물관 도슨트가 관람객에게 설명하는 톤.

| 하기 | 하지 않기 |
|---|---|
| 시청자를 "you"로 부르고 "we / let's"로 함께 보기 | 명령문 ("Don't push water up", "Look at this") |
| "You've probably seen…", "Here's the clever part", "I'd love you to remember", "Let's take a look", "Next time, let's visit…" | 속어·구어 ("cranked up", "cook in the sun", "gonna") |
| 완곡한 단정 ("they simply run out", "it gives you about 43 psi") | 시청자를 낮추는 표현 ("Almost nobody asks", "you never noticed") |
| 추산치엔 "about / around / as many as" | 비꼼·과장 ("insane", "mind-blowing") |
| 끝은 짧은 다음 편 안내 ("Next time, let's visit…") | 구독·좋아요 요청 |

고정 신호 문구(매 편 같은 자리, §4 6비트 시트): "Here's the problem." · "Now here's the maddening part." · "And this is where the thinking flips." · "Here's the clever part." · "But here's the part I'd love you to remember." · "Next time, let's visit…"


---

## 2. 콘텐츠 축 4개 (전부 미국 소재)

| 축 | 설명 | 비율 | 원본 채널 대응 |
|---|---|---|---|
| **A. Under Your City** | 상하수·지하철·매립지·강·운하·터널 | 35% | 한강·난지도·빗물받이·하수관 편 |
| **B. Inside Your Building** | 아파트·오피스·주택의 숨은 구조(수탑·목구조·댐퍼·엘리베이터) | 30% | 화장실 배관·층간소음·엘리베이터 편 |
| **C. Built Against Nature** | 홍수·허리케인·지진·가뭄과 싸운 미국 구조물 | 25% | 네팔 홍수·네덜란드·방파제 편 |
| **D. American Firsts** | 미국 토목사의 "사람이 했다" 이야기(시카고 들어올리기, 갤버스턴, 엠파이어 410일) | 10% | 고대 기술 편의 역할을 미국 근대사로 대체 |

### 도시 로테이션 (주 7편 기준)
NYC 2 · 시카고/중서부 1 · LA/서부 1 · 텍사스/남부 1 · 전국 공통(고속도로·주택·댐) 2. 같은 도시 연속 2일 금지.

---

## 3. 제목 공식

### 사용 템플릿 (한 편에 하나, 영상 첫 문장과 동일하게)
1. **부정 → 재정의**: `[Everyday thing] isn't [assumption]. It's [reframe].`
   *"NYC water towers aren't for storage. They're the city's water pressure."*
2. **진짜 이유**: `The real reason [familiar thing] [does X].`
   *"The real reason American houses are built from wood."*
3. **숫자 쇼크**: `[Number] [unit] [preposition] [familiar place].`
   *"150 million tons of garbage under New York's newest park."*
4. **사람이 했다**: `[City] didn't [fix X]. It [lifted / moved / drained] [the whole thing].`
   *"Chicago didn't drain the swamp. It lifted the entire city out of it."*

### 규칙
- 60자 이내, 숫자는 아라비아 숫자, 단위는 미국식.
- 도시명은 가능하면 제목 첫 3단어 안에.
- 금지: "shocking", "you won't believe", "insane", 이모지, 느낌표.
- 금지: 실존 회사·개인·건물주를 향한 비난형 표현("built wrong", "scam", "cover-up", "negligence"). 사실은 말하되 책임 귀속은 공식 조사 결과 인용으로만.
- 제목 = 영상 0:00의 첫 문장 = 첫 자막.

---

## 4. 대본 템플릿: 6비트 시트 + 고정 유행어

원본 「신비한 건축사전」이 매 편 반복하는 박자는 여섯 개입니다. **훅 → 문제 제시 → 환장할 노릇(악화) → 발상의 전환 → 해법의 묘 → 반전**. 이 채널은 각 박자에 **고정 영어 문구(유행어)**를 붙여, 대본을 쓸 때 여섯 칸을 먼저 채우고 문구를 그대로 박습니다. 문구가 매 편 같은 자리에 나오면 시청자가 기다리게 되고, 그게 유행어가 됩니다.

### 4-1. 6비트 시트 (대본 쓰기 전에 이 표를 먼저 채운다)

| # | 비트 | 원본 채널의 말 | 고정 영어 문구 (그대로 사용) | 역할 | 위치 |
|---|---|---|---|---|---|
| 1 | **HOOK** 부정 훅 | "X는 Y가 아닙니다" | `[Thing] isn't [assumption]. It's [reframe].` + `Let me show you how.` / `Let's take a look.` | 상식 부정, 3초 안에 | 0:00 |
| 2 | **PROBLEM** 문제 제시 | "문제는 ~였습니다" | **"Here's the problem."** | 풀어야 할 조건 하나를 명확히 | 15~25% |
| 3 | **MADDENING** 환장할 노릇 | "환장할 노릇이죠" | **"Now here's the maddening part."** | 뻔한 해법이 왜 안 되는지. 막힌 길 2개 | 25~35% |
| 4 | **FLIP** 발상의 전환 | "이때 발상을 전환합니다" | **"And this is where the thinking flips."** | 문제를 뒤집는 한 문장 | 35~45% |
| 5 | **CLEVER** 해법의 묘 | "그래서 ~한 겁니다" | **"Here's the clever part."** | 메커니즘 디테일, 숫자 2~3개 | 45~70% |
| 6 | **REMEMBER** 반전 | "그런데 사실은…" | **"But here's the part I'd love you to remember."** | 스케일 점프 또는 이름·시간의 반전 | 75~90% |
| + | **NEXT** 다음 편 | — | **"Next time, let's visit…"** | 티저 한 줄 | 마지막 5초 |

규칙:
- 2·3·4·5·6의 고정 문구는 **단어 하나도 바꾸지 않습니다.** 변형하면 유행어가 안 됩니다.
- MADDENING은 반드시 **막힌 길을 보여주는 비주얼**과 함께. 압력을 올리면 관이 터지는 장면, 땅을 파면 물이 나오는 장면처럼 "해 봤는데 안 됨"을 그립니다.
- FLIP은 한 문장. "Instead of A, B."의 꼴이 가장 좋습니다.
- 어투는 §1 정중한 안내자 규정 유지. "maddening"은 상황을 향한 말이고 사람을 향하지 않습니다.

### 4-2. 타임라인 (120~130초 기준)

```
0:00–0:07   HOOK        부정 훅 + "Let me show you how."
0:07–0:20   SETUP       시대·장소·상식 (숫자 1개)
0:20–0:30   PROBLEM     "Here's the problem." + 조건 한 문장
0:30–0:42   MADDENING   "Now here's the maddening part." + 막힌 길 2개 (비주얼 필수)
0:42–0:48   FLIP        "And this is where the thinking flips." + Instead of A, B.
0:48–1:25   CLEVER      "Here's the clever part." + 메커니즘·숫자·결과
1:25–1:50   REMEMBER    "But here's the part I'd love you to remember." + 반전 2단
1:50–2:00   TURN        훅을 비튼 마지막 한 줄 + 1초 정적
2:00–2:06   NEXT        "Next time, let's visit…"
```
55초 쇼츠 버전은 SETUP·CLEVER를 줄이고 여섯 문구는 전부 유지합니다.

### 4-3. 매 편 빠지지 않게 하는 장치
1. 제작 시트 §4(녹음 원고) 아래에 **비트 체크 표**를 두고, 여섯 문구가 몇 번 컷에 있는지 적습니다. 빈칸이 있으면 대본 미완성.
2. 컷 테이블의 화면 설명에 MADDENING 컷은 "막힌 길" 비주얼이 있는지, FLIP 컷은 "뒤집히는 동작"이 있는지 확인합니다.
3. 유행어는 자막에서도 같은 스타일로 강조합니다(붉은 밑줄 한 줄). 시청자가 글자로도 기억하게.

문장 규칙: 한 문장 14단어 이하, 숫자는 한 문장에 하나, 명령문·속어 금지.

---

## 5. 제작 파이프라인 (편당 약 3.5~4시간 목표)

| 단계 | 도구 | 산출물 | 시간 |
|---|---|---|---|
| 1. 소재 선정 | §6 캘린더 + r/engineering, r/urbanplanning, r/nyc·r/chicago 등 도시 서브레딧, 지역 뉴스 | 제목 1문장 | 10분 |
| 2. 사실 검증 | 출처 2개 이상(USGS·USACE·시 정부·주요 언론). 숫자마다 URL 기록 | `facts.md` | 30분 |
| 3. 대본 | §4 템플릿 | 125~145단어 | 20분 |
| 4. 로케이션·샷리스트 | 모티브 장소 선정, 사진 확보(직접/CC0), 컷별 샷 | 로케이션 표 + 프롬프트 | 25분 |
| 5. 스틸 생성 | Nano Banana Pro + 로케이션 사진 Ingredients | 레퍼런스 6장 + 컷별 시작/끝 스틸 | 50분 |
| 5b. 영상 생성 | Google Flow / Veo 3.1, 9:16, 프레임→영상 | 클립 7~18개 | 60분 |
| 6. 음성 | ElevenLabs 고정 보이스 | WAV | 5분 |
| 7. 편집 | CapCut 또는 Premiere. 치수선 프리셋(AE 템플릿 1회 제작) | 55초 mp4 | 40분 |
| 8. 업로드 | §5-2 메타 | YouTube Shorts → TikTok → Reels | 10분 |

### 5-1. 공통 비주얼 프롬프트 (v2)
```
Vertical 9:16, 2K. Photorealistic cinematic still that looks like a real location shoot in [CITY], captured on a full-frame camera with a 35mm anamorphic lens: shallow depth of field, gentle oval bokeh, natural film-like color, soft highlight roll-off, subtle grain. Real materials with wear. Atmospheric light with volumetric haze. Any "x-ray" reveal is a localized, physically plausible effect: a surface turns to clear glass only in one bounded area, with a single thin red edge line; what is inside is rendered as real, lit, worn material, never as a diagram. Large captions are real 3D letters physically placed in the scene (brushed metal or stone), catching the scene's light and casting shadows. Strictly no model, no diorama, no display base, no cutaway edges, no blueprint lines, no hologram, no UI overlays, no cartoon, no toy look, no oversaturation, no readable text other than the specified caption letters, no logos, no brand signage, no license plates, no visible human faces.
```
샷 역할 고정: ①실사 도입(드론/로우앵글) + 지도 줌인 → ②엑스레이 리빌(시그니처) → ③메커니즘 매크로 → ④실물 3D 글자 숫자 → ⑤타임랩스/연대 → ⑥결과·현재 → ⑦훅 리프레이즈용 와이드 복귀.
로케이션 사진은 직접 촬영 또는 CC0만 Ingredients로 사용. 스트리트뷰·타인 사진은 참고용. 생성물의 간판·얼굴·번호판은 제거.

### 5-2. 업로드 메타 규격
- 제목: 훅 문장. 설명 1줄째: 훅 재진술, 2줄째: 출처 2~3개 링크, 3줄째: `All visuals AI-generated for illustration.`
- 유튜브 "변경·합성된 콘텐츠" 공개 설정 **항상 ON**.
- 해시태그 3개 고정 + 도시 태그 1개: `#engineering #architecture #infrastructure` + `#nyc` 등.
- 업로드 시각: 미국 동부 오후 6시(한국 오전 7시). 서부 시청자까지 저녁 피드 커버. 1일 1편으로 시작, 4주 후 2편 전환 검토.

---

## 6. 런칭 4주 캘린더 (28편, 전부 미국)

★ = 원본 채널 상위 30에 직접 대응하는 소재. 각 줄: 제목(훅) / 핵심 숫자 / 축 / 도시.

### Week 1 — 전국이 아는 것부터
| # | 제목(훅) | 핵심 숫자 | 축 | 도시 |
|---|---|---|---|---|
| 1 | NYC water towers aren't for storing water. They're the city's water pressure. | 6층 이상 의무, 탱크 최대 1만 7천 개, 제조사 2곳 | B | NYC |
| 2 | ★ Chicago didn't drain the swamp. It lifted the entire city out of it. | 1850~60년대, 4~14ft, 1에이커 블록을 잭스크루 6,000개로 | D | 시카고 |
| 3 | ★ Staten Island's new park is 150 million tons of New York's garbage. | 1948~2001, 2,200에이커, 최고 225ft | A | NYC |
| 4 | ★ Hoover Dam isn't one block of concrete. It's 215 columns, because one pour would've taken 125 years to cool. | 1인치 파이프 582마일, 하루 얼음 1,000t | C | 네바다/애리조나 |
| 5 | ★ The Mississippi above St. Louis isn't a river. It's 29 lakes in a row. | Lock & Dam 29개, 9ft 항로 | A | 중서부 |
| 6 | The real reason American houses are built from wood. | 목재 가격·지진·공기 | B | 전국 |
| 7 | Round manhole covers aren't just a design choice. A square one could fall in. | 약 250lb, 대각선 차이 | A | 전국 |

### Week 2 — 내 건물 안
| # | 제목(훅) | 핵심 숫자 | 축 | 도시 |
|---|---|---|---|---|
| 8 | ★ Your upstairs neighbor isn't loud. Your building is made of wood. | 경량 목구조 충격음, resilient channel | B | 전국 |
| 9 | The Citicorp tower had a flaw. The engineer who found it fixed it himself. | 1978, 접합부 볼트→용접, 허리케인 시즌. ※ 역사적·종결 사안, 공학 윤리 미담 프레임으로만 | B | NYC |
| 10 | The Empire State Building went up in 410 days. Here's the trick. | 1930~31, 주당 4.5층, 조립식 철골 | D | NYC |
| 11 | Elevators don't wait for the cable to snap. They brake at 115% speed. | 조속기, 1853 오티스 | B | 전국 |
| 12 | The Golden Gate Bridge is never finished being painted. It can't be. | 1937, 도장 상시 작업, 소금 안개, International Orange | B | SF |
| 13 | Trinity Church in Boston stands on 4,500 wooden logs. They must stay wet. | 백베이 매립지, 목재 파일, 지하수위 | B | 보스턴 |
| 14 | ★ The green on apartment roofs isn't waterproofing. It's sunscreen for it. | 방수층 UV 보호 탑코트, 재도장 주기 | B | 전국 |

### Week 3 — 자연과 싸운 미국
| # | 제목(훅) | 핵심 숫자 | 축 | 도시 |
|---|---|---|---|---|
| 15 | ★ Mount St. Helens left a dam of rubble. The Army drilled through a mountain instead. | 1985 터널 8,500ft, 하류 피해 10억$ 추정 | C | 워싱턴주 |
| 16 | ★ Galveston didn't rebuild after 1900. It jacked up 2,000 buildings and poured sand under them. | 방파제 17ft·3마일, 1903~11, 건물 2,000채 | C | 텍사스 |
| 17 | Las Vegas drilled a 3-mile straw under Lake Mead. In case the lake drops below the other two. | $8.17억, 24ft 직경, 860ft 깊이 | C | 라스베이거스 |
| 18 | Chicago built 109 miles of tunnels under the city. They're empty on purpose. | TARP 109.4마일, 350ft 깊이, 2.3B갤런 | C | 시카고 |
| 19 | New Orleans doesn't drain. It pumps. Every drop. | 절반이 해수면 아래, 우드 스크루 펌프, 1913 | C | 뉴올리언스 |
| 20 | ★ Miami Beach isn't a beach. It's trucked-in sand. | 1970년대 이후 양빈, 침식 주기 | C | 마이애미 |
| 21 | ★ The LA River isn't a river. It's a 51-mile concrete drain. | 1938 홍수, 51마일, USACE | A | LA |

### Week 4 — 숨은 코드·도시 미스터리
| # | 제목(훅) | 핵심 숫자 | 축 | 도시 |
|---|---|---|---|---|
| 22 | Central Park's lampposts aren't decoration. They're a map. | 1,600개, 앞 숫자=가로번, 끝자리 짝=동/홀=서, 1907 | A | NYC |
| 23 | ★ The Alaska pipeline zigzags for 800 miles. It's not the terrain. | 열팽창, 지지대 위, 영구동토 | C | 알래스카 |
| 24 | Seattle's downtown has a second downtown under it. | 1889 대화재, 거리 1층 높이 상승 | D | 시애틀 |
| 25 | ★ Chicago didn't clean its river. It turned it around. | 1900 역류, 운하 28마일 | A | 시카고 |
| 26 | Hoover Dam's clocks show two times. The state line runs through the middle. | 네바다·애리조나 시간대 | D | 네바다 |
| 27 | The Washington Monument changes color a third of the way up. Money ran out. | 150ft 지점, 1854~79 중단 | D | DC |
| 28 | ★ Manhattan's skyline has a gap in the middle. It's not zoning. It's the rock. | 맨해튼 편암 깊이(통설 검증 포함) | A | NYC |

---

## 7. 첫 3편 풀 대본 (영어, 녹음 가능)

### Ep.1 — NYC water towers aren't for storing water. They're the city's water pressure.
전체 제작 시트: [episodes/under-america/EP01_nyc_water_towers.md](../episodes/under-america/EP01_nyc_water_towers.md) (90초, 18컷, 정중한 안내자 어투로 작성 완료)

### Ep.2 — Chicago didn't drain the swamp. It lifted the entire city out of it.
```
[0:00] Chicago didn't drain its swamp. It picked up the whole city and lifted it out. Let me show you how.
[0:05] In the 1850s, downtown Chicago sat barely above Lake Michigan. The streets were mud, and sewage had nowhere to go. Cholera came back every summer.
[0:14] The fix needed sewers, and sewers need a slope. Chicago had none. So the engineers decided the city itself would have to be higher.
[0:22] Here's the clever part. Not the land. The buildings. Crews slid jackscrews under entire brick blocks and turned them a quarter turn at a time.
[0:30] One block on Lake Street: a full acre, 35,000 tons, 6,000 screws. It rose over four days, and the shops stayed open the whole time.
[0:39] Through the 1850s and 60s, the downtown went up between 4 and 14 feet. New streets were laid on top of the old ones.
[0:47] But here's the part I'd love you to remember. The dirt dug out for the new sewers is what filled the gap underneath.
[0:52] So downtown Chicago isn't standing on the ground. It's standing on a city that's still buried below it.
[0:56] Next time, let's visit a park in New York that's built on 150 million tons of garbage.
```
샷: ①시카고 다운타운 와이드 + 지도 줌인 ②거리 단면 진입: 현재 거리 아래 옛 지면, 치수선 "4–14 ft" ③잭스크루 클로즈업, 손이 돌리는 모션(얼굴 없음) ④1에이커 블록 들어올리기 와이드 ⑤하수관 경사 그래픽 ⑥1850→1870 타임랩스 ⑦현재 거리 복귀.

### Ep.3 — Staten Island's new park is 150 million tons of New York's garbage.
```
[0:00] New York's biggest new park isn't built on land. It's built on 150 million tons of garbage. Let's take a look.
[0:05] Fresh Kills, Staten Island. From 1948 to 2001, nearly everything the city threw away came here by barge.
[0:13] Four mounds grew. The tallest reached about 225 feet, higher than the Statue of Liberty across the harbor.
[0:20] By the 1990s it was called the largest landfill on Earth. The smell reached New Jersey, and leachate ran into the creeks.
[0:28] Here's the clever part. They capped it: plastic liner, clay and soil over the trash, and hundreds of wells drilled into the pile to draw out the methane.
[0:38] That gas is piped to a plant and sold. It's enough to heat around 20,000 homes.
[0:44] Today it's 2,200 acres of grassland, almost three times the size of Central Park, opening in phases into the 2030s.
[0:51] But here's the part I'd love you to remember. The hills are still settling. The ground drops a little every year, because what's underneath is still breaking down.
[0:58] You're not standing on a hill. You're standing on a city's last 50 years.
[1:02] Next time, let's head west to Hoover Dam, a wall of concrete that should have taken 125 years to cool.
```
샷: ①초원 와이드 + 지도 줌인 → 땅속 단면 진입 ②단면 층: 흙/점토/라이너/쓰레기, 치수선 "225 ft" ③1948→2001 바지선 타임랩스 ④자유의 여신상 높이 비교 ⑤메탄 포집정 → 관로 → 플랜트 ⑥센트럴파크 3배 면적 비교 ⑦침하 애니메이션 후 초원 복귀.

> 출처 메모: NYC 수탑(6층 규정·1만 7천 개·제조사 2곳) · 시카고 들어올리기(4~14ft, Lake St 블록 6,000 잭스크루·35,000t·4일, Wikipedia "Raising of Chicago") · Fresh Kills(1948~2001·150M short tons·2,200acres·90~225ft, Wikipedia/NYC Parks). Ep.2의 "600명"과 Ep.3의 "2만 가구 난방"은 업로드 전 1차 출처로 재확인.

---

## 8. 운영 목표 (첫 90일)

| 지표 | 목표 | 근거 |
|---|---|---|
| 업로드 | 90일 90편(1일 1편) | 원본 채널 "매일 업로드". 알고리즘 노출 표본 확보 |
| 평균 시청 지속률 | 70% 이상(55초 중 38초) | 쇼츠 추천 핵심 지표. 훅 3초 이탈률 모니터 |
| 루프 | "본 비율" 100% 초과 영상 월 10편 | 마지막 문장이 첫 문장으로 되돌아가게 작성 |
| 미국 시청 비중 | 70% 이상 | 애널리틱스 지역 탭. 60% 아래면 도시명 노출·업로드 시각 조정 |
| YPP 진입 | 구독 1,000 + 쇼츠 90일 1,000만 뷰 | 수익화 조건 |
| 히트 | 100만 뷰 이상 3편 | 원본 채널은 21%가 100만 뷰. 90편 중 3편 보수 목표 |

주간 리뷰: 상위 3편·하위 3편의 공통점(축·도시·제목 공식)을 기록하고 다음 주 캘린더 비중 조정.

---

## 9. 차별화 포인트와 리스크

### 차별화
1. **도면 언어**: 치수선·단면도·연대 그래픽. 범용 채널은 안 함.
2. **수치 밀도**: 편당 숫자 3개, 전부 출처 있음. 미국 단위.
3. **도시 특정성**: "어떤 빌딩"이 아니라 "네가 매일 지나는 그 빌딩". 지도 줌인 컷으로 지역 공유 유도.
4. **시리즈 반복**: Not A River / Under Your Street / Inside Your Walls / Lifted Cities 4개 시리즈 태그로 재생목록 소비 유도.

### 리스크와 대응
| 리스크 | 대응 |
|---|---|
| AI 생성 콘텐츠 정책·수익화 제한 | "변경된 콘텐츠" 공개 항상 ON. 대본·검증은 사람이 했음을 설명란에 명시. 편당 고유 단면도·고유 수치로 대량생산형 분류 회피 |
| 사실 오류 | 숫자마다 출처 2개(USGS·USACE·시 정부 우선). 오류 시 고정 댓글 정정, 심하면 삭제 후 재업로드 |
| 포토리얼 AI를 실사로 오해 | 설명란 고정문구 + 치수선 오버레이가 "일러스트"임을 시각적으로 표시 |
| 재난 소재(허리케인·지진·붕괴) | 숫자 중심 서술, 피해자 묘사 금지, 진행 중인 재난은 2주 내 업로드 지양 |
| 특정 도시 편중 | §2 도시 로테이션 준수. 같은 도시 연속 2일 금지 |
| 미국 외 시청 유입으로 CPM 하락 | 제목·자막에 도시명·미국 단위 유지, 업로드 시각 미국 저녁 고정 |
| **신고·커뮤니티 가이드 경고·삭제** | **§10 가드레일 전부 통과한 편만 업로드. 체크리스트 1개라도 실패하면 소재 교체** |

---

## 10. 신고·경고·삭제 회피 가드레일 (업로드 전 필수 체크)

원칙: **이 채널은 "건물이 어떻게 작동하나"를 설명하는 채널이고, "누가 잘못했나"를 따지는 채널이 아닙니다.** 분쟁·공포·피해자가 없는 소재만 고릅니다.

### 11-1. 소재 선택 금지 목록
| 금지 | 이유 | 대신 |
|---|---|---|
| 진행 중인 재난·사고(발생 2주 이내), 사망자 수 강조 | 민감 사건 정책, 시청자 신고 | 역사적(10년 이상 지난) 사례, 구조 메커니즘 중심 |
| 실존 건설사·건물주·개발사·공무원을 향한 책임 귀속 | 명예훼손 신고, 법적 분쟁 | 공식 조사 보고서 결론만 인용하거나 소재 제외 |
| 소송 진행 중인 건물(침하·균열·하자 분쟁) | 당사자 신고 | 종결 사안만, 가능하면 제외 |
| 댐·교량·상수도·전력망의 **취약점·공격 시나리오** | 유해·위험 콘텐츠 정책 | 작동 원리와 안전장치만 설명 |
| 건강 공포(석면·라돈·납 등) 단정 표현 | 의료 오정보 신고 | 규제 기관(EPA 등) 문구 그대로 인용, 수치만 |
| 실존 인물의 AI 얼굴·목소리, 실제 참사 현장 재현 | 합성 미디어·괴롭힘 정책 | 사람은 실루엣·원거리, 구조물만 포토리얼 |
| 뉴스 영상·타인 사진·지도 스크린샷·상업 음원 사용 | 저작권 신고(Content ID) | 100% AI 생성 비주얼 + YouTube 오디오 라이브러리 또는 라이선스 음원 |
| 정치·종교·인종·젠더가 얽힌 도시 이슈(재개발 갈등, 홈리스, 국경 장벽) | 논쟁 유발, 광고 제한 | 제외 |
| 과장·공포 제목("could collapse", "deadly", "they don't want you to know") | 오해 유발 콘텐츠·클릭베이트 정책 | 사실 진술형 부정 훅만 |

### 11-2. 업로드 전 체크리스트 (전부 YES여야 업로드)
```
[ ] 제목·대본의 모든 숫자에 출처 URL 2개 이상이 facts.md에 있다
[ ] 실존 회사·개인에 대한 평가·비난 문장이 0개다
[ ] 사망·부상 묘사가 없고, 피해자 수는 역사적 사건에서만 1회 이하 언급한다
[ ] 비주얼 100% 자체 AI 생성, 음원은 라이브러리/라이선스, 로고·상표가 화면에 없다
[ ] 유튜브 "변경·합성된 콘텐츠" 공개 설정 ON, 설명란에 "All visuals AI-generated" 문구
[ ] 제목에 wrong / scam / deadly / collapse / cover-up / exposed 류 단어가 없다
[ ] 소재가 진행 중 재난·소송·정치 논쟁과 무관하다
[ ] "어린이용 아님"으로 설정, 연령 제한 사유(폭력·공포 연출) 없음
[ ] 대본은 사람이 작성·검증했고 편마다 고유 단면도·고유 수치가 있다 (대량생산형 분류 회피)
```

### 11-3. 28편 리스크 점검 결과
- **교체**: #12 Millennium Tower(침하 분쟁, 소송 이력) → Golden Gate 도장 편으로 교체 완료.
- **프레임 제한**: #9 Citicorp는 1978년 종결 사안이자 공학 윤리 미담으로만 서술, 책임 언급 없음. #15 스피릿 호수·#16 갤버스턴은 역사적 사례로 사망자 수 강조 없이 구조 중심.
- **주의**: #19 뉴올리언스는 카트리나 언급 금지(정치·피해 민감), 1913년 펌프 시스템 원리만. #23 알래스카 파이프라인은 송유관 사고·환경 논쟁 언급 금지, 열팽창 구조만.
- 나머지 24편은 역사·공학 원리 소재로 저위험.

### 11-4. 경고를 받았을 때
- 1회 경고(스트라이크 전 단계) 시 해당 영상 즉시 비공개, 원인 항목을 11-1에 추가, 유사 소재 대기열 전부 재검토.
- 이의 제기는 출처가 완비된 경우에만. 아니면 삭제 수용.

---

## 11. 다음 액션 (순서대로)

1. 채널명 핸들 확인 후 개설, 바이오·로고·치수선 AE 템플릿·미국 지도 줌인 템플릿 제작 (1일)
2. Week 1의 7편 사실 검증 시트 작성, 숫자별 URL 기록 (1일)
3. Ep.1~3 대본으로 Flow 테스트 생성 → 비주얼 규격 확정 (2일)
4. 7편 선제작 → 편당 §10-2 체크리스트 통과 확인 → 1일 1편 업로드 시작. TikTok·Reels 동시 게시
5. 2주차 데이터로 도시 로테이션·업로드 시각 조정, 4주차에 1일 2편 전환 여부 결정
