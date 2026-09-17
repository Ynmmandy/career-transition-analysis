# Career Transition Analysis

一个面向职业转型场景的 Codex Skill。它将个人经历、目标岗位和真实市场要求连接起来，帮助用户完成事实校验、可迁移能力提取、岗位匹配、Gap 分析、求职资产设计和行动路径规划。

它适合辅助职业决策，不承诺录用结果，也不替代持证职业顾问、招聘机构或受监管职业的资质判断。

## 能解决什么问题

- 从简历、个人说明书和项目经历中提取有证据支持的底层能力
- 将“想进入某个行业”拆解为具体岗位族和可能路径
- 使用真实 JD 建立岗位要求基准，比较候选人的能力与证据
- 区分能力缺口、行业认知缺口、经验缺口和证据缺口
- 比较直接转型、桥梁岗位和探索性方向
- 设计简历叙事、面试证据、Portfolio 和 30/60/90 天路线
- 根据投递与面试反馈持续更新判断

## 工作流程

```text
Fact Check
    ↓
Extraction
    ↓
Market and Matching
    ↓
Gap Analysis
    ↓
Assets and Prediction
```

完整流程包含三个阶段闸门：

1. 关键事实未确认，不进入评分。
2. 用户未选定优先方向，不深挖公司和作品集。
3. 初始判断必须通过真实投递和面试反馈继续校准。

## 目录结构

```text
career-transition-analysis/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── assessment-framework.md
    ├── intake-and-fact-ledger.md
    ├── market-research-protocol.md
    └── report-architecture.md
```

## 安装

将仓库克隆或复制到 Codex Skills 目录：

```bash
git clone https://github.com/Ynmmandy/career-transition-analysis.git \
  ~/.codex/skills/career-transition-analysis
```

重新启动或刷新 Codex 后，可以显式调用：

```text
使用 $career-transition-analysis 分析我的个人说明书，比较适合我的转行方向，并给出 Gap 补齐路线。
```

## 推荐输入

为了得到更可靠的结果，建议提供：

- 起止年月准确的教育和工作经历
- 职责、项目、成果及可验证的数字
- 感兴趣的行业、岗位和城市
- 薪资、期限、地域和风险约束
- 目标 JD、作品集或历史面试反馈（如有）

请在公开 Issue 中删除姓名、电话、邮箱、身份证明、雇主机密、客户信息和未公开业务数据。

## 设计原则

- 先确认事实，再解释能力
- 重要判断必须有候选人证据或市场来源
- 不把缺少证据自动判断为缺少能力
- 不把学校、证书或公司品牌直接等同于工作能力
- 不输出没有数据依据的精确录用概率
- 不为了贴近目标岗位而虚构指标、职责或行业术语
- 将行动建议转化为可以验收的作品或市场反馈

## 适用边界

该 Skill 对知识型、职能型岗位的相邻转型最有帮助。对于医生、律师等强资质职业，高度专业化的技术岗位，高管岗位，以及创业或自由职业，需要额外的领域标准和专业判断。

市场、薪资、公司和政策信息具有时效性。使用相关结论前，应核实检索日期、样本范围和原始来源。

## 贡献

欢迎通过 Issue 提交使用反馈，或通过 Pull Request 改进：

- 输入字段和事实校验机制
- 不同行业或岗位的扩展框架
- JD 样本编码和市场研究方法
- 预测边界和风险控制
- 匿名化的失败案例与修正经验

提交案例时，请只使用获得授权且完成匿名化的材料。

## License

[MIT](LICENSE)

---

## English summary

Career Transition Analysis is a Codex Skill for evidence-based career change planning. It validates candidate facts, extracts transferable capabilities, compares them with current job requirements, identifies gaps, and turns the result into job-search assets and an executable transition plan.

It is a decision-support framework, not a hiring guarantee or a statistically validated employment prediction model.
