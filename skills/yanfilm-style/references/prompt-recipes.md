# Prompt Recipes

以下模板用于补足视觉信息，不要覆盖用户的硬约束。

## 角色迁移（默认）

> Use the supplied photo as the character identity reference, not as the composition reference. Preserve the same person’s facial identity and hairstyle, or preserve an animal/mascot’s species, head design, signature colors, material and anatomy. Use the bundled Yanfilm references as visual-grammar examples, not a closed location list. Either adapt one reference archetype or invent a new ordinary-life scene-and-pose combination with the same quiet observational logic. Re-stage the character with a believable full-body action, weight distribution, camera distance, environment ratio and contact with furniture, floor or props. Adapt clothing and objects to the scene unless the user asks to preserve them. Render a restrained salt-film photograph with believable natural or practical light, a limited neutral palette, realistic texture, fine organic color-negative grain, gentle highlight roll-off and slight scan softness. Do not reuse the source selfie crop or background by default. No invented text, border, logo, watermark, heavy damage, orange-teal grade or excessive bokeh.

## 未指定场景时的随机生成

> Invent one coherent ordinary-life scene that is not a direct copy of any bundled reference. Internally choose one specific place, one small everyday action, one anatomically credible pose with clear physical support, one restrained wardrobe, no more than two necessary props, one natural or practical light source, and one limited neutral palette. The subject must genuinely inhabit the space through correct scale, perspective, occlusion, contact shadows, gaze and hand interaction. Keep substantial environmental context and an observed-not-posed camera. Randomize the combination, not the realism: no surreal mismatch, decorative prop pile, implied plot, extra character, brand, text or watermark.

## 原构图轻编辑（仅用户明确要求）

> Edit the supplied photo while preserving the same person, pose, clothing, camera position, crop and spatial geometry. Change only the light, limited palette and subtle film texture. Do not reconstruct the scene. Use this variant only when the user explicitly asks to keep the original composition or background unchanged.

## 原图还原式角色替换

> Use the scene reference as the structural ground truth and the character reference only as the replacement identity. Reconstruct the same photograph while replacing only the original subject: preserve the exact aspect ratio, crop, camera position, perspective, subject scale and placement, head/shoulder/hip coordinates, body orientation, silhouette zone, pose, weight distribution, limb arrangement, gaze direction in viewer coordinates, hand-to-prop contact, occlusion, background objects, borders, negative space, lighting and film character. Preserve every scene-integrated prop and its state, including the same drink type, package color, straw direction, hand, and use action. Preserve existing environmental signs, package graphics and layout text; do not invent new text. Treat platform watermark/account overlays separately and remove them only when explicitly requested, without changing nearby scene text. Adapt only the identity-specific anatomy, face, species, signature colors and material needed to make the supplied character occupy the original subject's exact structural role. No re-composition, new pose, prop substitution, background redesign or opposite gaze direction.

局部反馈时在末尾追加：

> Change only [指定局部]. Lock every already-correct element, especially character identity, composition, position, pose, gaze, prop, scene text, lighting and film texture.

## 窗边室内

> A person pausing beside a large window in an ordinary room, [具体动作], observed from [机位], soft overexposed daylight at the window with believable interior falloff, paper white, muted blue, old wood and one warm skin-tone accent, substantial negative space, consumer color-negative film character, fine grain and gentle scan softness, calm and unembellished.

## 城市停驻

> A person resting at [楼梯/公告栏/栏杆/普通路口], [具体动作], the city remains readable and mundane, slightly cool overcast daylight, restrained concrete grey, off-white, muted green and brown palette, 35mm environmental portrait, imperfect off-center framing, moderate depth of field, fine film grain, no fashion-campaign posing.

## 阅读/功能空间

> A person absorbed in reading or waiting inside [书店/洗衣房/家电空间], surrounded by functional objects that remain legible, [蹲/靠/侧躺/蜷坐] with anatomically credible posture, mixed practical and ambient light, subdued paper, metal, wood and fabric colors, intimate documentary framing, consumer-film texture without retro gimmicks.

## 杂志编辑页

> Lay out the finished photograph as a restrained Japanese editorial page with generous white margin, one asymmetrically placed image field, a quiet grid, and only the exact user-provided copy. Use small readable typography and clear hierarchy. Keep all text away from the face and hands. Do not invent Japanese, page numbers, captions, logos, or filler text.

## 负面约束组件

按实际失败风险选择 3–6 项，不要机械堆满：

- no glossy commercial beauty lighting
- no airbrushed skin or doll-like face
- no orange-and-teal cinematic grade
- no candy pastel palette or creamy haze
- no excessive bokeh or fake lens flare
- no vintage prop collage
- no heavy scratches, dust, leaks, dates, VHS noise
- no Japanese text unless supplied verbatim
- no watermark, logo, account handle, or random glyphs
- no school uniform, cherry blossom, neon convenience store, or retro camera unless requested
