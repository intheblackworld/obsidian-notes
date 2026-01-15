#aivideogod 

貼上影片
請分析這個影片的腳本結構，敘事節奏和科普邏輯。然後模仿這個風格，策劃5個不同的科普短影音選題

模仿剛剛上傳的影片和拆解出來的內容，分別為這5個選題生成以下內容，並以表格的形式輸出：
1. 撰寫完整腳本
2. 把腳本拆解為9個關鍵節點並生出9個分鏡對應的生圖提示詞
3. 生成完整的影片生成提示詞
4. 撰寫該影片發佈在 xxx 的影片標題，簡介，tags


1️⃣ 《AI 數位變現 新手啟動包》 https://g98pelvkhx.feishu.cn/wiki/Xzntw8oQviQA6zkhXM1cns3HnFi?from=from_copylink

2️⃣ 《4 類 AI 員工提示詞》 https://g98pelvkhx.feishu.cn/docx/FtNddeQieoG22gxkbRRcfDKanYe?from=from_copylink

🔍 找不到變現路徑？為你提供 1v1 策略規劃

如果您不確定目前的經營狀況，或卡在流量無法轉化的瓶頸，歡迎填寫測評表單。我將協助您檢視內容系統，提供初步的策略建議：

【AI 內容獲客與變現路徑・策略診斷】👉 https://calendly.com/ethan-huang/ethan-1v1-line


### 九宮格分鏡提示詞

做一張3*3的分鏡圖，每張單獨的分鏡圖寬高比是9:16的豎版。保持每張圖片的機位和拍攝角度不變。只根據以下描述去改變圖片的內容，注意保持連貫性:（以下內容附上你的視頻腳本）

  

**第一個提示詞**

```Plain
请分析这个视频的脚本结构、叙事节奏和科普逻辑，然后模仿这个风格，策划5个不同的科普短视频选题
```

**第二個提示詞**

```Plain
模仿刚刚上传的视频和拆解出来的内容，分别为这5个选题生成以下内容，并以表格的形式输出：1.撰写完整脚本；
2.把脚本拆解为9个关键节点并生成9个分镜对应的生图提示词；
3.生成完整的视频生成提示词；
4.撰写该视频发布在TikTok上的视频标题、简介、tags。
```

第三個提示詞

```Plain
<role>
You are an award-winning trailer director + cinematographer + storyboard artist. Your job: turn ONE reference image into a cohesive cinematic short sequence, then output AI-video-ready keyframes.
</role>

<input>
User provides: one reference image (image).
</input>

<non-negotiable rules - continuity & truthfulness>
First, analyze the full composition: identify ALL key subjects (person/group/vehicle/object/animal/props/environment elements) and describe spatial relationships and interactions (left/right/foreground/background, facing direction, what each is doing).
Do NOT guess real identities, exact real-world locations, or brand ownership. Stick to visible facts. Mood/atmosphere inference is allowed, but never present it as real-world truth.
Strict continuity across ALL shots: same subjects, same wardrobe/appearance, same environment, same time-of-day and lighting style. Only action, expression, blocking, framing, angle, and camera movement may change.
Depth of field must be realistic: deeper in wides, shallower in close-ups with natural bokeh. Keep ONE consistent cinematic color grade across the entire sequence.
Do NOT introduce new characters/objects not present in the reference image. If you need tension/conflict, imply it off-screen (shadow, sound, reflection, occlusion, gaze).
</non-negotiable rules - continuity & truthfulness>

<goal>
Expand the image into a 10–20 second cinematic clip with a clear theme and emotional progression (setup → build → turn → payoff).
The user will generate video clips from your keyframes and stitch them into a final sequence.
</goal>

<step 1 - scene breakdown>
Output (with clear subheadings):
Subjects: list each key subject (A/B/C…), describe visible traits (wardrobe/material/form), relative positions, facing direction, action/state, and any interaction.
Environment & Lighting: interior/exterior, spatial layout, background elements, ground/walls/materials, light direction & quality (hard/soft; key/fill/rim), implied time-of-day, 3–8 vibe keywords.
Visual Anchors: list 3–6 visual traits that must stay constant across all shots (palette, signature prop, key light source, weather/fog/rain, grain/texture, background markers).
</step 1 - scene breakdown>

<step 2 - theme & story>
From the image, propose:
Theme: one sentence.
Logline: one restrained trailer-style sentence grounded in what the image can support.
Emotional Arc: 4 beats (setup/build/turn/payoff), one line each.
</step 2 - theme & story>

<step 3 - cinematic approach>
Choose and explain your filmmaking approach (must include):
Shot progression strategy: how you move from wide to close (or reverse) to serve the beats
Camera movement plan: push/pull/pan/dolly/track/orbit/handheld micro-shake/gimbal—and WHY
Lens & exposure suggestions: focal length range (18/24/35/50/85mm etc.), DoF tendency (shallow/medium/deep), shutter “feel” (cinematic vs documentary)
Light & color: contrast, key tones, material rendering priorities, optional grain (must match the reference style)
</step 3 - cinematic approach>

<step 4 - keyframes for AI video (primary deliverable)>
Output a Keyframe List: default 9–12 frames (later assembled into ONE master grid). These frames must stitch into a coherent 10–20s sequence with a clear 4-beat arc.
Each frame must be a plausible continuation within the SAME environment.

Use this exact format per frame:

[KF# | suggested duration (sec) | shot type (ELS/LS/MLS/MS/MCU/CU/ECU/Low/Worm’s-eye/High/Bird’s-eye/Insert)]
Composition: subject placement, foreground/mid/background, leading lines, gaze direction
Action/beat: what visibly happens (simple, executable)
Camera: height, angle, movement (e.g., slow 5% push-in / 1m lateral move / subtle handheld)
Lens/DoF: focal length (mm), DoF (shallow/medium/deep), focus target
Lighting & grade: keep consistent; call out highlight/shadow emphasis
Sound/atmos (optional): one line (wind, city hum, footsteps, metal creak) to support editing rhythm
Hard requirements:
Must include: 1 environment-establishing wide, 1 intimate close-up, 1 extreme detail ECU, and 1 power-angle shot (low or high).
Ensure edit-motivated continuity between shots (eyeline match, action continuation, consistent screen direction / axis).
</step 4 - keyframes for AI video>

<step 5 - contact sheet output (MUST OUTPUT ONE BIG GRID IMAGE)>
You MUST additionally output ONE single master image: a Cinematic Contact Sheet / Storyboard Grid containing ALL keyframes in one large image.
Default grid: 3x3. If more than 9 keyframes, use 4x3 or 5x3 so every keyframe fits into ONE image.
Requirements:
The single master image must include every keyframe as a separate panel (one shot per cell) for easy selection.
Each panel must be clearly labeled: KF number + shot type + suggested duration (labels placed in safe margins, never covering the subject).
Strict continuity across ALL panels: same subjects, same wardrobe/appearance, same environment, same lighting & same cinematic color grade; only action/expression/blocking/framing/movement changes.
DoF shifts realistically: shallow in close-ups, deeper in wides; photoreal textures and consistent grading.
After the master grid image, output the full text breakdown for each KF in order so the user can regenerate any single frame at higher quality.
</step 5 - contact sheet output>

<final output format>
Output in this order:
A) Scene Breakdown
B) Theme & Story
C) Cinematic Approach
D) Keyframes (KF# list)
E) ONE Master Contact Sheet Image (All KFs in one grid)
</final output format>
```

**第四個提示詞**：

```Plain
【通用的視頻提示詞】
將參考圖片中的故事板網格轉化為連續視頻。規則：
- 按從左到右、從上到下的順序讀取每個畫面
- 每個畫面作為關鍵幀，平滑過渡到下一個
- 保持角色、服裝、環境、光線完全一致
- 不要在視頻中顯示任何文字、標籤或標注
- 輸出純淨畫面，單一連續視頻
風格：電影質感，自然鏡頭過渡，統一色調
```