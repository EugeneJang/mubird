# 영어 건축·인프라 쇼츠 채널 기획안

> 작성일: 2026-10-07 · 선행 문서: [architecture-shorts-kalkapi-5.md](./architecture-shorts-kalkapi-5.md)
> 원본 모델: 「신비한 건축사전」(구독 79.9만, 쇼츠 446개, 누적 3.27억 뷰) 포맷을 영어권으로 이식

---

## 0. 한 줄 컨셉

**"The city you walk through every day isn't what you think it is."**
매일 보는 건물·거리·강·다리의 정체를 60초 안에 뒤집는, 얼굴 없는 AI 3D 단면도 채널.

**포지셔닝 한 문장**: Practical Engineering의 주제를 Zack D. Films의 속도로, 도면 언어(치수선·단면도)로 보여 준다.

| | 영어권 기존 | 우리 |
|---|---|---|
| 전문가 롱폼 (Practical Engineering, B1M, Stewart Hicks) | 8~20분, 얼굴 노출, 주 1편 | 60초, 얼굴 없음, 매일 |
| 범용 3D 쇼츠 (Zack D. Films) | 인체·동물·사고 등 모든 호기심 | 건축·인프라만. 수치와 단면도가 시그니처 |
| 소형 시도 (Hidden Civil Engineering 등) | 구독 2천 미만, 비주얼 약함 | AI 포토리얼 3D + 일관된 그래픽 규격 |

---

## 1. 채널 아이덴티티

### 채널명 후보 (핸들 가용성은 개설 시 확인)

| 후보 | 뉘앙스 | 비고 |
|---|---|---|
| **Built Wrong?** | 부정 훅과 톤 일치. 물음표가 클릭 유도 | 1순위. 짧고 검색 쉬움 |
| **Hidden Blueprint** | 치수선·도면 비주얼과 직결 | 2순위 |
| **The Concrete Truth** | "진짜 이유" 공식과 연결, 말장난 | 3순위 |
| **Under Your City** | 필러 A 이름과 겹침 | 서브 시리즈명으로 활용 |
| **Not A River** | 1위 영상 오마주 | 시리즈명으로 활용 |

### 바이오 (영어)
```
Everything you walk past every day has a secret under it.
60-second cutaways of buildings, bridges, rivers and the stuff under your street.
All visuals AI-rendered. Every number sourced. New short daily.
```

### 시그니처 비주얼 규격
- **색**: 배경은 중립 콘크리트 톤, 강조는 단 하나 **빨간 치수선(#E53935)**. 다른 색 강조 금지.
- **자막**: 흰색 산세리프(Inter Bold), 화면 하단 1/3, 한 번에 한 줄, 숫자는 1.3배 크기.
- **카메라**: 돌리인 → 땅속/벽속으로 들어가는 단면 공개가 매 편의 "시그니처 샷"(5~12초 지점).
- **로고**: 빨간 치수선으로 그린 ㄱ자 꺾쇠 + 채널명. 영상 끝 0.5초만 노출.

### 보이스 스펙
- 남성 또는 중성, 30대, 미국 일반 억양, 느리고 건조하게(분당 150~160단어). 감탄·웃음 없음.
- 문장 끝을 내리는 서술형. 질문문은 편당 1개 이하.
- 도구: ElevenLabs 계열 TTS 1개 보이스로 고정. 바꾸지 않음(채널 정체성).

---

## 2. 콘텐츠 축 4개

| 축 | 설명 | 비율 | 원본 채널 대응 |
|---|---|---|---|
| **A. Under Your City** | 하수·상수·지하철·매립지·강·방파제 등 도시 인프라 | 35% | 한강·난지도·빗물받이·하수관 편 |
| **B. Inside Your Building** | 아파트·오피스·주택의 숨은 구조(배관·방수·소음·엘리베이터·댐퍼) | 30% | 화장실 배관·층간소음·엘리베이터 편 |
| **C. Built Against Nature** | 홍수·지진·바다·바람과 싸운 구조물, 재난 시사 | 20% | 네팔 홍수·네덜란드·방파제 편 |
| **D. Ancient Engineering** | 로마·페르시아·잉카 등 기계 없이 해결한 기술 | 15% | 로마 벨라리움·온돌·남한산성 편 |

지리 비중 가이드: 미국 50% · 영국/유럽 20% · 글로벌(일본·중동·한국 포함) 30%. 한국 소재는 "Why Korean apartments..." 호기심 프레임으로 월 2~3편.

---

## 3. 제목 공식

### 사용 템플릿 (한 편에 하나, 영상 첫 문장과 동일하게)
1. **부정 → 재정의**: `[Everyday thing] isn't [assumption]. It's [reframe].`
   *"NYC water towers aren't for storage. They're the city's water pressure."*
2. **진짜 이유**: `The real reason [familiar thing] [does X].`
   *"The real reason apartment noise comes through your walls, not your ceiling."*
3. **숫자 쇼크**: `[Number] [unit] [preposition] [familiar place].`
   *"150 million tons of garbage under New York's newest park."*
4. **사람이 했다**: `[Natural-looking thing] was [built / moved / drained] by hand.`
   *"This island used to be three islands. People glued them together."*

### 규칙
- 60자 이내, 숫자는 아라비아 숫자로.
- 금지: "shocking", "you won't believe", "insane", 이모지, 느낌표.
- 제목 = 영상 0:00의 첫 문장. 자막도 같은 문장.

---

## 4. 대본 템플릿 (55초, 125~145단어)

```
0:00–0:03  HOOK        제목 문장 그대로. 부정문.
0:03–0:12  SETUP       시청자가 아는 상식 1문장 + "그게 아니다" 1문장 + 연도 하나
0:12–0:35  MECHANISM   어떻게 작동하는지. 숫자 2~3개(크기·연도·톤수). 단면 공개 샷과 동기화
0:35–0:50  COST        그래서 생긴 결과·부작용·논란·현재 상태
0:50–0:55  TURN        훅을 한 번 더 비튼 마지막 한 줄. 질문·구독 요청 없음(루프 유도)
```

문장 규칙: 한 문장 12단어 이하, 숫자는 한 문장에 하나, 접속사로 문장 잇지 않기.

---

## 5. 제작 파이프라인 (편당 약 2.5~3시간 목표)

| 단계 | 도구 | 산출물 | 시간 |
|---|---|---|---|
| 1. 소재 선정 | 이 문서 §6 캘린더 + Reddit r/engineering, r/urbanplanning, 지역 뉴스 | 제목 1문장 | 10분 |
| 2. 사실 검증 | 출처 2개 이상(공공기관·논문·주요 언론). 숫자마다 URL 기록 | `facts.md` | 30분 |
| 3. 대본 | §4 템플릿 | 125~145단어 | 20분 |
| 4. 샷리스트 | 7샷 × 8초 | 프롬프트 7개 | 15분 |
| 5. 영상 생성 | Google Flow / Veo 3.1, 9:16 | 클립 7개 (재생성 포함) | 40분 |
| 6. 음성 | ElevenLabs 고정 보이스 | WAV | 5분 |
| 7. 편집 | CapCut 또는 Premiere. 치수선 프리셋(After Effects 템플릿 1회 제작) | 55초 mp4 | 40분 |
| 8. 업로드 | 제목·설명·해시태그 §5-2 | YouTube Shorts → TikTok → Reels | 10분 |

### 5-1. 공통 비주얼 프롬프트
```
photorealistic 3D architectural cutaway of [SUBJECT], vertical 9:16,
slow cinematic dolly-in, camera passes through the surface to reveal the section,
thin red dimension lines and small labels overlaid, overcast neutral daylight,
muted concrete and steel palette, no readable text, no people in focus, 8 seconds
```
샷 역할 고정: ①외관 와이드 → ②단면 진입(시그니처) → ③메커니즘 클로즈업 → ④숫자 비교 그래픽 → ⑤타임랩스/연대 → ⑥결과·현재 → ⑦훅 리프레이즈용 와이드 복귀.

### 5-2. 업로드 메타 규격
- 제목: 훅 문장. 설명 1줄째: 훅 재진술, 2줄째: 출처 2~3개 링크, 3줄째: `All visuals AI-generated for illustration.`
- 유튜브 "변경·합성된 콘텐츠" 공개 설정 **항상 ON**(AI 포토리얼이므로 의무).
- 해시태그 3개 고정 + 1개 가변: `#engineering #architecture #infrastructure` + 소재 태그.
- 업로드 시각: 미국 동부 오후 5~7시(한국 오전 6~8시). 1일 1편으로 시작, 4주 후 데이터 보고 2편으로.

---

## 6. 런칭 4주 캘린더 (28편)

★ = 원본 채널 상위 30에 직접 대응하는 소재. 각 줄: 제목(훅) / 핵심 숫자 / 축.

### Week 1 — 미국 시청자가 "매일 보는 것"으로 시작
| # | 제목(훅) | 핵심 숫자 | 축 |
|---|---|---|---|
| 1 | NYC water towers aren't storage. They're the city's water pressure. | 6층 이상 의무, 탱크 최대 1만 7천 개, 제조사 2곳 | B |
| 2 | ★ The 130-ton monster under London wasn't grease. It was soap. | 2017 화이트채플 팻버그 130t, 250m, 9주 제거 | A |
| 3 | ★ Staten Island's new park is 150 million tons of New York's garbage. | 1948~2001, 2,200에이커, 최고 225ft | A |
| 4 | ★ Hoover Dam is still cooling down. Without these pipes, it'd take 125 years. | 1인치 파이프 582마일, 하루 얼음 1,000t | C |
| 5 | ★ The Mississippi above St. Louis isn't a river. It's 29 lakes in a row. | Lock & Dam 29개, 9ft 항로 | A |
| 6 | Round manhole covers aren't a design choice. A square one can fall in. | 무게 약 250lb, 대각선 길이 차 | A |
| 7 | ★ The Colosseum had air conditioning. It was made of sails. | 관중 5만, 돛대 약 240개, 해군 운용 | D |

### Week 2 — "내 건물 안"으로 들어가기
| # | 제목(훅) | 핵심 숫자 | 축 |
|---|---|---|---|
| 8 | ★ Your upstairs neighbor isn't loud. Your building is made of wood. | 미국 저층 아파트 경량 목구조, 충격음 전달 경로 | B |
| 9 | Taipei 101 has a 660-ton steel ball hanging inside it. On purpose. | 660t, 직경 5.5m, 87~92층 | B |
| 10 | ★ Why Korean apartments get torn down at 30 years. It's not age. | 벽식 구조, 벽=기둥, 배관 매립 | B |
| 11 | The Citicorp tower was about to fall. Only one student noticed. | 1978, 스틸티 접합부 볼트→용접, 허리케인 시즌 | B |
| 12 | Elevators don't wait for the cable to snap. They brake at 115% speed. | 조속기, 안전장치, 1853 오티스 | B |
| 13 | ★ This 555-meter tower runs AC at full blast with the chillers off. | 빙축열: 밤에 얼음, 낮에 녹임(미국 사례로 치환 가능) | B |
| 14 | ★ The green on apartment roofs isn't waterproofing. It's sunscreen for it. | 우레탄 방수층 UV 보호 탑코트, 재도장 주기 | B |

### Week 3 — 자연과 싸운 구조물
| # | 제목(훅) | 핵심 숫자 | 축 |
|---|---|---|---|
| 15 | ★ Mount St. Helens left a dam of rubble. The Army drilled a hole in the mountain instead. | 1985 터널 8,500ft, 하류 홍수 피해 10억$ 추정 | C |
| 16 | ★ China didn't wait for this quake lake to burst. Soldiers cut it open. | 2008 탕자산, 수로 475m, 25만 대피 | C |
| 17 | Venice isn't sinking faster. It's being lifted by 78 steel gates. | MOSE 78개 게이트, 2020 가동 | C |
| 18 | Tokyo built a cathedral underground. It's for rainwater. | 수조 177m×78m×25m, 기둥 59개, 터널 6.3km | C |
| 19 | ★ The Netherlands didn't build windmills for flour. They were pumps. | 풍차 약 1만 기, 국토 26% 해수면 아래 | C |
| 20 | ★ Miami Beach isn't a beach. It's trucked-in sand held by a wall. | 양빈 사업, 수중 구조물(해운대 편 치환) | C |
| 21 | The Thames Barrier was meant to close twice a year. Now it's over 200 times. | 1982, 게이트 10개, 폐쇄 횟수 | C |

### Week 4 — 고대 기술 + 서울 소재 교차
| # | 제목(훅) | 핵심 숫자 | 축 |
|---|---|---|---|
| 22 | Roman concrete heals its own cracks. We only figured out how in 2023. | 석회 덩어리(lime clasts), MIT 연구 | D |
| 23 | ★ Masada has no spring. Herod stored 40,000 cubic meters of water on a desert rock. | 저수조 12개, 73년 농성 | D |
| 24 | ★ Korean floors were heated with no furnace. The kitchen fire did it. | 온돌, 구들장, 영하 20도 | D |
| 25 | Persians made ice in the desert 2,000 years ago. With a building. | 야크찰(yakhchal), 높이 18m, 야간 복사 냉각 | D |
| 26 | ★ Seoul's main river isn't a river. It's a 36-km lake between two walls. | 수중보 2개, 수심 2.5m, 수서곤충 52 vs 18 | A |
| 27 | ★ Seoul's second river is a faucet. It's pumped 11 km uphill every day. | 청계천, 20년째 펌프 | A |
| 28 | Chicago didn't fix its river. It turned it around. | 1900년 역류, 운하 | A |

---

## 7. 첫 3편 풀 대본 (영어, 녹음 가능)

### Ep.1 — NYC water towers aren't storage. They're the city's water pressure.
```
[0:00] New York's rooftop water towers aren't for storing water. They're for pushing it.
[0:03] The city's mains deliver pressure for about six floors. Above that, a faucet just hisses.
[0:10] So since the 1800s, any building taller than six stories has had to make its own pressure. With gravity.
[0:17] A pump in the basement lifts water to the roof all day. The tank holds it. Height does the rest: every 10 feet of water adds about 4 psi.
[0:27] The tanks are still made of wood. Cedar staves, steel hoops, no glue. Wood swells when wet and seals itself.
[0:35] Two family companies build almost all of them. Up to 17,000 tanks sit on the skyline, and most are replaced every 30 to 35 years.
[0:45] The city could have built bigger mains and higher pressure. It would have burst every old pipe under the street.
[0:51] So the skyline is the water system. Every tank is a tiny reservoir, 100 feet in the air.
```
샷: ①맨해튼 옥상 와이드 ②탱크 단면 진입(치수선 "6 floors") ③지하 펌프→옥상 배관 흐름 ④"10 ft = 4 psi" 그래픽 ⑤삼나무 판 클로즈업 ⑥1800년대→현재 타임랩스 ⑦스카이라인 복귀.

### Ep.2 — The 130-ton monster under London wasn't grease. It was soap.
```
[0:00] The thing that blocked a London sewer in 2017 weighed 130 tons. It wasn't grease. It was soap.
[0:04] Whitechapel, east London. Workers found a solid mass 250 meters long, longer than two football pitches, filling a Victorian sewer.
[0:13] It started as cooking oil poured down sinks. In the pipe it met calcium from hard water and the sewer walls.
[0:21] Fat plus calcium is a chemical reaction. The same one that makes bar soap. It hardens into something you break with pickaxes.
[0:30] Wet wipes gave it a skeleton. The soap filled the gaps. Nine weeks, a crew with jet hoses and hand tools, to clear it.
[0:39] The sewer was built in the 1860s for a city of three million. London now has nine million and a fatberg found every few weeks.
[0:48] A piece of this one sits in the Museum of London. It was still sweating and growing mold behind the glass.
[0:53] Every drop of oil in your sink is already on its way to the next one.
```
샷: ①런던 거리 → 맨홀로 진입 ②벽돌 하수관 단면, 팻버그 치수선 "250 m" ③싱크대→배관 기름 흐름 ④지방+칼슘 → 비누 반응 그래픽 ⑤물티슈 골격 클로즈업 ⑥1860년대 공사 장면 ⑦박물관 유리 케이스.

### Ep.3 — Staten Island's new park is 150 million tons of New York's garbage.
```
[0:00] New York's biggest new park isn't built on land. It's built on 150 million tons of garbage.
[0:04] Fresh Kills, Staten Island. From 1948 to 2001, nearly everything the city threw away came here by barge.
[0:12] Four mounds grew. The tallest reached about 225 feet, higher than the Statue of Liberty next door.
[0:19] By the 1990s it was called the largest landfill on Earth. The smell reached New Jersey. Leachate ran into the creeks.
[0:27] So they capped it. Layers of plastic liner, clay and soil over the trash, and hundreds of wells drilled into the pile to pull out methane.
[0:37] That gas is piped to a plant and sold. Enough to heat about 20,000 homes.
[0:43] Now it's 2,200 acres of grassland, almost three times the size of Central Park, opening in phases until the 2030s.
[0:50] The hills are still settling. The ground drops a little every year, because what's under it is still rotting.
[0:55] You're not walking on a hill. You're walking on a city's last 50 years.
```
샷: ①초원 와이드 → 땅속 단면 진입 ②단면 층: 흙/점토/라이너/쓰레기, 치수선 "225 ft" ③1948→2001 바지선 타임랩스 ④자유의 여신상 높이 비교 ⑤메탄 포집정 → 관로 → 플랜트 ⑥센트럴파크 3배 면적 비교 ⑦침하 애니메이션 후 초원 복귀.

> 출처 메모: NYC 수탑(6층 규정·1만 7천 개·2개 제조사) · 화이트채플 팻버그(130t·250m·9주, Thames Water 2017) · Fresh Kills(1948~2001·150M short tons·2,200acres·90~225ft, Wikipedia/NYC Parks). 업로드 전 설명란에 각 URL 2개씩 기입.

---

## 8. 운영 목표 (첫 90일)

| 지표 | 목표 | 근거 |
|---|---|---|
| 업로드 | 90일 90편(1일 1편) | 원본 채널 "매일 업로드". 알고리즘 노출 표본 확보 |
| 평균 시청 지속률 | 70% 이상(55초 중 38초) | 쇼츠 추천 핵심 지표. 훅 3초 내 이탈률 모니터 |
| 루프 | "본 비율" 100% 초과 영상 월 10편 | 마지막 문장이 첫 문장으로 되돌아가게 작성 |
| YPP 진입 | 구독 1,000 + 쇼츠 90일 1,000만 뷰 | 수익화 조건 |
| 히트 | 100만 뷰 이상 3편 | 원본 채널은 21%가 100만 뷰. 우리는 90편 중 3편 보수 목표 |

주간 리뷰 체크: 상위 3편·하위 3편의 공통점(축·지리·제목 공식)을 기록하고 다음 주 캘린더 비중 조정.

---

## 9. 차별화 포인트와 리스크

### 차별화 (Zack D. Films가 건축을 건드려도 남는 것)
1. **도면 언어**: 치수선·단면도·연대 그래픽. 범용 채널은 안 함.
2. **수치 밀도**: 편당 숫자 3개, 전부 출처 있음. 설명란에 링크.
3. **장소 특정성**: "어떤 빌딩"이 아니라 "네가 매일 지나는 그 빌딩". 지역 시청자 공유 유도.
4. **시리즈 반복**: Not A River / Under Your Street / Inside Your Walls 3개 시리즈 태그로 묶어 재생목록 소비 유도.

### 리스크와 대응
| 리스크 | 대응 |
|---|---|
| AI 생성 콘텐츠 정책 변화·수익화 제한 | "변경된 콘텐츠" 공개 항상 ON. 내레이션·대본은 사람이 작성·검증했음을 설명란에 명시. 반복적·대량생산형으로 분류되지 않도록 편당 고유 단면도·고유 수치 유지 |
| 사실 오류 | 숫자마다 출처 2개. 오류 발견 시 고정 댓글로 정정, 심하면 삭제 후 재업로드 |
| 포토리얼 AI가 실제 사진으로 오해 | 설명란 고정문구 + 치수선 오버레이가 "일러스트"임을 시각적으로 표시 |
| 재난·사망 소재(네팔·지진호) | 숫자 중심 서술, 피해자 묘사 금지, 사건 후 2주 내 업로드 지양 |
| 한국 소재 과다로 미국 시청자 이탈 | 한국 소재 월 2~3편 상한, 반드시 "Why Korean..." 비교 프레임 |

---

## 10. 다음 액션 (순서대로)

1. 채널명 핸들 확인 후 개설, 바이오·로고·치수선 After Effects 템플릿 제작 (1일)
2. Week 1의 7편 사실 검증 시트 작성, 숫자별 URL 기록 (1일)
3. Ep.1~3 대본으로 Flow 테스트 생성 → 비주얼 규격(색·카메라·치수선) 확정 (2일)
4. 7편 선제작 후 1일 1편 업로드 시작. TikTok·Reels 동시 게시
5. 2주차 데이터로 축 비중·업로드 시각 조정, 4주차에 1일 2편 전환 여부 결정
