# 수범의 국민학교 하루 (1994): 영상 AI용 프롬프트

목표: 9:16 세로, 실사로 움직이는 20초 영상. 4초짜리 컷 5개.
추천 앱: Kling(클링), Hailuo, Runway 중 하나. 이미지→영상(image-to-video)과 캐릭터 참조 기능이 있는 앱이면 돼요.

---

## STEP 1. 어린 수범이 기준 사진 만들기

앱의 이미지 생성 기능(또는 ChatGPT 이미지 생성)에 **본인 사진을 참조 이미지로 넣고** 아래 프롬프트를 입력하세요.

```
Using the uploaded photo as the face reference, create a photorealistic portrait of the same person as a 9-year-old Korean boy in 1994.
Keep his face shape, eyes, eyebrows, smile and ear shape recognizable.
Short black 1990s bowl-style haircut, navy-and-white striped sweater, red boxy elementary school backpack.
Neutral background, soft daylight, 35mm film photo look, natural skin, waist-up, looking at camera with a small smile.
```

→ 마음에 드는 결과 1장을 고르세요. 이후 모든 컷에서 이 사진을 **캐릭터 참조(Character/Element reference)**로 써요.

---

## STEP 2. 컷별 영상 생성 (각 5초 생성, 편집 때 4초로 잘라요)

공통 설정: 비율 9:16 · 길이 5초 · 가장 높은 화질 · 캐릭터 참조 = STEP 1 사진

공통 스타일 문구 (각 프롬프트 끝에 붙이세요):
```
Seoul 1994, nostalgic 35mm film look, warm color grading, soft film grain, realistic natural motion, handheld camera feel.
```

공통 네거티브 프롬프트 (지원하는 앱만):
```
modern smartphone, modern cars, LED signs, distorted face, extra fingers, morphing, text artifacts, cartoon
```

### 컷 1: 아침에 눈뜨기 (0–4초)
```
The boy wakes up on a folded floral quilt on the floor of a small 1990s Korean bedroom, sits up, rubs his eyes and stretches.
Morning sunlight through yellowed curtains, a twin-bell alarm clock on a wooden dresser, red school backpack by the wall,
window view of a hillside neighborhood with red-brick houses and utility poles. Slow push-in camera.
```

### 컷 2: 등굣길 (4–8초)
```
The boy walks down a narrow Seoul alley toward school, swinging a cloth indoor-shoe bag in circles, then turns back to the camera and grins.
Red-brick houses, green metal gates, a small stationery shop with toys hanging outside, other kids with backpacks in the background.
Camera follows behind him, tracking shot.
```

### 컷 3: 운동장 조회 (8–12초)
```
The boy stands in a line of schoolchildren on a dirt elementary school playground during Monday morning assembly,
fidgets in the sun, whispers to the friend next to him and both try not to giggle.
Beige four-story school building with a big clock and a Korean flag in the background, plane trees. Medium shot, slight handheld sway.
```

### 컷 4: 받아쓰기 100점 (12–16초)
```
In a 1990s Korean classroom with wooden desks and a green chalkboard, the boy proudly lifts a dictation test paper
with a big red circled "100" toward the camera, then makes a V sign with both hands and smiles.
Classmates and a teacher softly blurred behind him, warm window light. Static camera, slow zoom-in.
```
(마지막 V 포즈는 지금 사진 속 수범님 포즈를 그대로 가져온 장면이에요.)

### 컷 5: 해질녘 집으로 (16–20초)
```
At sunset the boy runs up a hillside alley toward home with his backpack bouncing, stops, turns around and waves goodbye to friends.
Warm orange evening light, a mother leaning out of a green gate in the background, utility poles silhouetted.
Camera slowly pulls back.
```

---

## STEP 3. 클립 올려주기

만든 클립 5개(컷1~컷5)를 그대로 올려주세요. 제가 아래 작업으로 20초 영상을 완성할게요.

- 컷마다 4초로 자르고 부드럽게 연결
- 레퍼런스 스타일의 검은 박스 자막
  1. You wake up in Seoul, 1994.
  2. 실내화 주머니 빙빙 돌리며, 등굣길
  3. 월요일 아침, 운동장 조회 시간
  4. 받아쓰기 100점. 오늘은 칭찬받는 날
  5. 1994, 수범의 하루
- 잔잔한 피아노 음악, LP 지직거림, 학교 종소리(딩동댕동)
- 필름 색감과 노이즈로 다섯 컷의 톤 맞추기

### 팁
- 얼굴이 사진과 다르게 나오면, 같은 프롬프트로 2–3번 다시 생성해서 가장 닮은 걸 고르세요.
- 손이나 종이가 뭉개지면 "slow, gentle movement"를 추가하면 안정적이에요.
- 무료 크레딧이 적으면 컷 1, 2, 4만 먼저 만들어도 돼요. 3컷이면 12초 영상으로 편집할 수 있어요.
