# 放疗靶区勾画 Skill 快捷索引表

> 按解剖部位 + 场景分类 · 版本：v1.0 · 2026-07-31
>
> **使用说明**：收到病例后 → 按解剖定位 → 找到对应的 Skill → 可能还需加载配套 Skill

---

## 一、按解剖部位

### 🔵 口腔（Oral Cavity）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 口腔癌术后 PORT（舌/口底/颊黏膜/牙龈/硬腭/唇/磨牙后区） | `port-oral-postop` | `neoadjuvant-deescalation`（化免新辅助后） |
| 口腔癌术后 PORT（通用参考） | `oral-oropharynx-postop-rt-targets` | 同上 |
| **触发词**：舌癌术后、口底癌术后、颊黏膜术后、牙龈癌、硬腭、磨牙后区、皮瓣、口底铁律、颊淋巴结IX区 |

### 🔵 口咽（Oropharynx）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 口咽癌根治性 CRT/RT（扁桃体/舌根/软腭/咽壁） | `oropharynx-definitive-rt` | `neoadjuvant-deescalation`（化免新辅助后） |
| 口咽癌术后 PORT | `port-oropharynx-postop` | 同上 |
| 口咽癌术后 PORT（通用参考） | `oral-oropharynx-postop-rt-targets` | 同上 |
| **触发词**：扁桃体癌、舌根癌、软腭癌、咽壁、HPV+ 口咽癌、SIB、TORS术后 |

### 🔵 鼻咽（Nasopharynx）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 鼻咽癌根治性 RT/IMRT | `npc-rt-target-delineation` | — |
| **触发词**：鼻咽癌NPC、颅底孔道、海绵窦、咽旁间隙、EBV相关 |

### 🔵 鼻腔鼻窦（Sinonasal）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 上颌窦/筛窦/鼻腔癌 RT | `sinonasal-rt-targets` | — |
| 嗅神经母细胞瘤/SNUC 特殊类型 | 同上 | — |
| 诱导化疗后放疗 | 同上 | — |
| **触发词**：上颌窦癌、筛窦、鼻腔癌、嗅神经母细胞瘤、esthesioneuroblastoma、SNUC、视路保护 |

### 🔵 喉/下咽（Larynx / Hypopharynx）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 喉/下咽术后 PORT（全喉切除/部分喉/咽重建） | `larynx-hypopharynx-postop` | `neoadjuvant-deescalation` |
| 喉/下咽根治性 RT（保声/同步放化疗） | `larynx-hypopharynx-definitive` | 同上 |
| 抽疑问→先查总索引 | `laryngeal-hypopharyngeal-rt-targets` | 跳转专用 |
| **触发词**：喉癌、声门癌、声门上癌、下咽癌、梨状窝、环后区、全喉切除、Stoma、保声RT |

### 🔵 唾液腺（Salivary Gland）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 腮腺/颌下腺/舌下腺癌术后 PORT | `salivary-gland-rt-targets` | — |
| 淋巴上皮癌根治性 CRT | 同上 | — |
| **触发词**：腮腺癌、颌下腺、舌下腺、粘液表皮癌MEC、腺样囊性癌ACC、腺泡细胞癌、淋巴上皮癌 |

### 🔵 腺样囊性癌（ACC）专题

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| ACC 术后 RT（任何部位） | `adenoid-cystic-carcinoma-rt-targets` | — |
| 面神经径路/颅底孔道追踪/PNI | 同上 | — |
| **触发词**：腺样囊性癌、ACC、筛管型、神经侵犯PNI、面神经走行、颅底孔道、p63 |

### 🔵 眼眶（Orbit）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 眼眶肿瘤 RT（淋巴瘤/泪腺/视神经鞘脑膜瘤等） | `orbital-tumor-rt-targets` | `head-neck-lymphoma-rt-targets`（若为淋巴瘤） |
| **触发词**：眼眶、泪腺、眼内、眶尖、视神经、门+隔壁比喻、间室放疗 |

### 🔵 头颈部淋巴瘤（Lymphoma）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| HL/NHL 头颈部 ISRT/INRT | `head-neck-lymphoma-rt-targets` | — |
| DLBCL/滤泡性淋巴瘤/MALT/套细胞/ENKTL | 同上 | — |
| **触发词**：淋巴瘤、HL、NHL、DLBCL、滤泡性FL、MALT、套细胞MCL、ENKTL、ISRT、INRT |

### 🔵 原发不明颈部转移（CUP）

| 病例特征 | 主 Skill | 配套 Skill |
|----------|----------|-----------|
| 原发不明颈部转移癌 HNCUP | `cervical-cup-rt-targets` | — |
| 选择性黏膜照射/EBV/HPV分层 | 同上 | — |
| **触发词**：原发不明、CUP、HNCUP、颈部转移不明原发、选择性黏膜 |

---

## 二、按治疗场景（跨部位）

| 场景 | Skill | 适用范围 |
|:----:|-------|---------|
| **化免新辅助后降阶梯** | `neoadjuvant-deescalation` | 口腔/口咽/喉/下咽——pCR/MPR分层决策 |
| **再程放疗** | `reirradiation-plan-recommend` | 所有头颈部位——Quad-Shot、SBRT、累计BED |
| **DVH 计划审核** | `head-neck-dvh-plan-review` | 所有头颈部位——OAR约束、分级评估 |

---

## 三、特别说明

### 1. 主 Skill vs 总索引 Skill

部分解剖部位有**总索引 Skill**（如 `laryngeal-hypopharyngeal-rt-targets`），仅包含场景跳转说明，不包含勾画细则。**不要加载总索引来回答临床问题**——直接加载对应的自包含模块。

### 2. Skill 加载规则

| 原则 | 说明 |
|------|------|
| **同一场景多个 Skill 不矛盾** | `port-oral-postop`（自包含）+ `oral-oropharynx-postop-rt-targets`（参考）+ `neoadjuvant-deescalation`（降级）= 完整信息 |
| **不可跨瘤种借用** | 不同瘤种（如 SCC vs ACC、癌 vs 淋巴瘤）规则不通，不借用 |
| **无 Skill 覆盖** | 无对应 Skill 的病理类型/部位 → 搜 PubMed+CSCO+指南 → 反馈用户 |

### 3. 触发词优先级

```
病理 > 部位 > 治疗阶段 > 特殊因素
```

例：**"右腮腺 ACC 术后，面神经受侵"**
1. 病理 ACC → 先加载 `adenoid-cystic-carcinoma-rt-targets`（ACC专题）
2. 部位腮腺 → 再加载 `salivary-gland-rt-targets`（唾液腺通用）
3. 处理顺序：ACC专题优先（面神经/PNI规则更精准）

### 4. 配套 Skill 自动加载

| 病例特征 | 必加配套 |
|----------|---------|
| 化免新辅助后（无论PORT/根治性RT） | `neoadjuvant-deescalation` |
| 既往有放疗史/再程场景 | `reirradiation-plan-recommend` |
| 需要评估计划质量（给反馈时） | `head-neck-dvh-plan-review` |
| 眼眶淋巴瘤 | `orbital-tumor-rt-targets` + `head-neck-lymphoma-rt-targets` |
| 喉/下咽初次触及 | 先查 `laryngeal-hypopharyngeal-rt-targets` 确认跳转方向 |

---

> 维护：朱国培 · 上海九院放疗中心
> 更新记录：2026-07-31 v1.0 创始版
