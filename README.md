# 零外内容运营 Skills

这是一套用于零外美护产品内容生产的可复用 Skills。它将产品资料、周文案、分镜、素材管理、剪辑交付和数据复盘拆成独立能力，避免每周反复沟通相同规则。

## 已收录 Skills

| Skill | 解决的问题 | 典型产出 |
|---|---|---|
| `lingwai-product-facts` | 产品事实与合规边界 | 产品事实卡、可说/不可说清单 |
| `lingwai-weekly-test-matrix` | 周内容测试规划 | 钩子与卖点测试矩阵 |
| `lingwai-infoflow-voiceover` | 带货信息流配音 | 15—30秒配音文案 |
| `lingwai-personal-account-oral` | 男性测评视角真人口播 | 25—35秒真人口播 |
| `lingwai-storyboard-shotlist` | 文案转可执行镜头 | 分镜、镜头汇总、补拍单 |
| `lingwai-asset-library` | 素材整理与调用 | 素材目录、命名、镜头索引 |
| `lingwai-broll-ai-prompts` | B-roll与AI素材 | B-roll清单、9:16提示词 |
| `lingwai-weekly-production-qc` | 周生产和交付质检 | 周排期、交付清单、质检结果 |
| `lingwai-creative-performance-review` | 投放数据复盘 | 素材复盘与规则更新 |

## 推荐调用顺序

1. 用 `lingwai-product-facts` 更新产品事实、合规边界和当天活动。
2. 用 `lingwai-weekly-test-matrix` 规划钩子与卖点，再调用配音或真人口播 Skill。
3. 文案确认后用 `lingwai-storyboard-shotlist` 汇总镜头和补拍缺口。
4. 拍摄前后用 `lingwai-asset-library` 整理素材；需要成分插入画面时用 `lingwai-broll-ai-prompts`。
5. 用 `lingwai-weekly-production-qc` 管理剪辑、命名和交付。拿到数据后用 `lingwai-creative-performance-review` 优化下一周。

## 使用说明

将需要的 Skill 文件夹复制到 Codex 的 skills 目录。首次使用前，提供产品备案、包装信息、当前价格活动、现有素材目录和本周产量。

产品事实以包装、备案资料、商品页和已确认资料为准。价格、赠品、库存和活动期必须在发布当天核对。信息流配音卖痛点、证据、价格和下单；真人口播卖人物视角、真实场景和使用感。
