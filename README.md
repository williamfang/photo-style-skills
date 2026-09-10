# photo-style-skills

方崴的可复用照片风格 Codex skills 集合。每个风格独立维护在 `skills/` 下，例图只用于对应 skill 的视觉分析，不会自动作为生成构图模板。

如果这些 skill 对你有帮助，欢迎赞助支持： [Ko-fi.com/williamfang](https://ko-fi.com/williamfang)

## 风格目录

| Skill | 用途 | 调用 |
|---|---|---|
| [`yanfilm-style`](skills/yanfilm-style) | 克制、自然、生活化的盐系胶片影像与角色替换 | `$yanfilm-style` |
| [`street-flash-noir`](skills/street-flash-noir) | 粗颗粒高反差黑白街拍，支持倾斜快拍、直闪、拖影和反射 | `$street-flash-noir` |
| [`flat-guofeng-landscape`](skills/flat-guofeng-landscape) | 21:9 扁平展开写实国风自然风景，强调层峦、云雾、水岸和自然留白 | `$flat-guofeng-landscape` |

## 安装单个 skill

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo williamfang/photo-style-skills \
  --path skills/street-flash-noir
```

将 `skills/street-flash-noir` 替换为 `skills/yanfilm-style` 或 `skills/flat-guofeng-landscape`，即可安装另一个风格。

## 使用示例

```text
用 $street-flash-noir 将这个人物放进东京街头，场景自由创作，生成 3:4 黑白街拍。
```

```text
用 $yanfilm-style，把这张角色照片变成盐系胶片生活写真。
```

```text
用 $flat-guofeng-landscape 生成 4 张 21:9 扁平展开写实国风风景，分别做春晨水乡、夏雨山谷、秋日湖山、冬雪古村。
```

## 目录约定

每个 skill 目录包含自己的 `SKILL.md`、`agents/openai.yaml` 以及所需的 `references/` 或 `assets/`。新增照片风格时，保持独立目录，并在本 README 的风格目录中登记。
