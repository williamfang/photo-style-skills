# 视觉合同与提示词模块

## 风格 DNA

这类画面来自“横向展开的真实山水照片”而不是传统绘画复刻。画幅像展开的长卷，但所有元素都应服从摄影真实：空气透视、真实地形、自然光照、云雾遮挡、林木密度、水体反射和建筑尺度。

关键特征：

- **21:9 超宽横幅**：主视觉沿水平方向展开，观者能从左到右浏览空间。
- **扁平展开**：不要深透视直冲画面中心；用山脊线、河岸线、雾带、林带、田埂和屋脊形成平行或缓慢错位的层。
- **多层远近**：前景可用水面、草坡、树梢、石岸或低雾压住画面；中景放村落、桥、亭、船、林带；远景放山脊、云海或天光。
- **写实自然光**：晨雾、阴天散射光、雨后低云、雪后冷光、夕阳斜照都可以；光线必须有方向或天气依据。
- **国风元素克制出现**：小体量古建、石桥、青瓦村落、松竹、江南水岸、徽派屋顶、栈道、远处寺塔等作为真实环境的一部分，不做舞台化中心物。
- **意境触发点**：每张至少有一个被距离、雾、雨、雪或水面留白包围的小尺度锚点，例如半隐小亭、远寺塔、断桥、孤舟、雪中暖窗、山腰细瀑、雾后屋脊或水边栈道。它负责让画面从普通风景照进入可停留的意境。
- **色彩克制**：自然青绿、灰蓝、墨绿、石灰、雪白、赭土、晨金可以组合；避免荧光青绿、厚重油画色、单一蓝紫或海报渐变。
- **无人或极少人**：默认无人。若需要人物，只能是很小的尺度参照，不成为主角。

## 构图模块

按场景选择一到两个模块组合，多张作品要明显变化：

1. **远山横列**：连续山脊从左到右铺开，云雾切分山腰，前景是水面或树梢。
2. **江湾展开**：河流或湖岸形成宽阔曲线，村落和树带沿岸散点分布。
3. **云海漂移**：低云横向穿过山谷，只露出山顶、亭台或松树轮廓。
4. **梯田层叠**：田埂像横向等高线铺满山坡，晨雾和水光削弱透视。
5. **雪线压境**：雪覆盖山脊、屋顶、石桥和林梢，冷暖光轻微分离。
6. **雨后青山**：湿润山体、低饱和绿、薄雾和反光石阶，空气通透但不艳。
7. **湖心孤亭**：小亭或桥在中景偏侧出现，周围大量水面和远山留白。
8. **古村散点**：黑瓦白墙或木屋贴着山脚展开，尺度很小，不能变成建筑广告图。

## 提示词骨架

```text
21:9 ultra-wide realistic landscape photograph, flat unfolded composition like a horizontal scroll but fully photographic,
[地点/季节/天气], layered Chinese landscape scenery with [山体/水面/云雾/林带/古建/村落] spreading laterally across the frame,
foreground [前景元素], midground [中景元素], background [远景元素],
one quiet poetic focal detail [半隐亭桥/远寺塔/孤舟/暖窗/细瀑/断续屋脊] surrounded by mist, distance or negative space,
soft natural light, atmospheric perspective, restrained natural colors, realistic terrain, real vegetation texture, water reflection, mist partially hiding distance,
no people unless tiny scale reference, no text, no calligraphy, no seal, no border, no watercolor, no ink painting, no illustration, no fantasy glow, no CGI, no poster design
```

中文提示词可这样写：

```text
21:9 超宽画幅，写实风景照片，像横向展开的自然山水长卷但不是绘画。
[季节/天气/地点]，[山、水、云雾、林带、古建或村落] 沿画面左右平铺展开。
前景是 [前景]，中景是 [中景]，远景是 [远景]。
必须有一个安静的小尺度意境锚点：[半隐亭桥/远处寺塔/孤舟/雪中暖窗/雨后细瀑/雾后屋脊]，被雾、距离或水面留白包围。
自然光、空气透视、低饱和真实色彩、真实地形、真实树冠纹理和水面反射。
不要人物主角、不要文字、不要书法、不要印章、不要边框、不要水墨画、不要插画、不要奇幻发光、不要 CG 概念图。
```

## 场景组合建议

- 春晨江南：薄雾、水网、青瓦白墙、嫩绿柳岸、远山灰蓝。
- 夏雨山谷：雨后青山、低云、湿石桥、瀑布细线、深绿林带。
- 秋日湖山：芦苇、浅金树冠、湖面反光、远处孤亭、清冷天空。
- 冬雪古村：白雪屋顶、黑瓦线条、枯树、远山冷雾、少量暖窗。
- 高原云海：山顶寺塔或小亭极小出现，大片云海横漂。
- 梯田清晨：水田反光、层叠曲线、村落散点、晨光扫过山坡。

## 常见失败与修正

- 像水墨画：加强“realistic landscape photograph, real vegetation texture, no ink painting, no brush strokes”。
- 像游戏概念图：加入“documentary travel photography, natural lens compression, no fantasy architecture, no dramatic matte painting”。
- 太中心化：强调“main forms distributed laterally, no single centered hero object, panoramic scroll-like layout”。
- 不够扁平：强调“compressed depth, layered horizontal bands, distant telephoto viewpoint, no strong vanishing point”。
- 太普通：加入“quiet poetic focal detail, partially hidden, surrounded by negative space and weather, not a scenic postcard”。
- 过度国风符号：删除灯笼、红衣人物、巨大宫殿、书法题字，改用真实小尺度古建和地貌。
- 颜色太艳：加入“muted greens, gray-blue distance, natural haze, restrained contrast”。
