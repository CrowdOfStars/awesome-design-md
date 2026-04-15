# Awesome DESIGN.md

66 份品牌设计规范文件，让 AI 按照知名品牌风格生成 UI。

> 基于 [Google Stitch DESIGN.md](https://stitch.withgoogle.com/docs/design-md/overview/) 格式，每份文件包含完整的色彩体系、字体规范、组件样式、布局原则等 9 个标准化章节。

## 使用方式

### 模式一：单文件拷贝

将某个品牌的 `DESIGN.md` 复制到你的项目根目录，然后告诉 AI 按照它来设计界面。

```bash
# 复制 Claude 的设计风格到项目中
cp design-md/claude/DESIGN.md ./DESIGN.md
```

然后对 AI 说：

> "请按照 DESIGN.md 中的设计规范来设计一个登录页面。"

---

### 模式二：Skills 使用（推荐）

将整个项目放到 AI 工具的 skills/context 目录下，AI 会自动识别并按品牌风格设计 UI。

**Gemini CLI：**
```bash
# 全局安装（所有项目可用）
cp -r awesome-design-md ~/.gemini/skills/

# 或仅当前项目
cp -r awesome-design-md .gemini/skills/
```

**其他 AI 工具（Claude Code、Cursor 等）：**
将项目放到工具的上下文目录中，AI 会读取 `AGENTS.md` 自动获取能力。

使用时直接说：

> "按照 Claude 的风格来设计界面"
> "用 Stripe 的设计语言做一个定价页"
> "参考 Linear 的风格设计一个看板"

AI 会自动定位对应品牌的 `DESIGN.md`，读取设计规范后执行界面设计。

## 品牌目录

### AI & LLM
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Claude | `claude` | 暖色赤土陶瓷调，干净的编辑式布局 |
| Cohere | `cohere` | 渐变色彩，数据密集型仪表盘 |
| ElevenLabs | `elevenlabs` | 暗色电影感 UI，音频波形美学 |
| Minimax | `minimax` | 粗体暗色界面，霓虹点缀 |
| Mistral AI | `mistral.ai` | 法式极简主义，紫色调 |
| Ollama | `ollama` | 终端风格，单色简约 |
| OpenCode AI | `opencode.ai` | 开发者暗色主题 |
| Replicate | `replicate` | 白色画布，代码优先 |
| RunwayML | `runwayml` | 电影暗色 UI，媒体丰富布局 |
| Together AI | `together.ai` | 开源 AI 基建，蓝图风格 |
| VoltAgent | `voltagent` | 纯黑画布，翡翠绿点缀 |
| xAI | `x.ai` | 硬朗单色，未来极简 |

### 开发工具
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Cursor | `cursor` | AI 代码编辑器，暗色渐变 |
| Expo | `expo` | React Native，暗色代码风 |
| Lovable | `lovable` | AI 全栈构建器，活泼渐变 |
| Raycast | `raycast` | 效率启动器，彩色渐变 |
| Superhuman | `superhuman` | 高端暗色 UI，紫色光晕 |
| Vercel | `vercel` | 黑白精确，Geist 字体 |
| Warp | `warp` | 现代终端，区块式界面 |

### 后端 & DevOps
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| ClickHouse | `clickhouse` | 黄色点缀，技术文档风 |
| Composio | `composio` | 暗色配多彩集成图标 |
| HashiCorp | `hashicorp` | 企业级简洁黑白 |
| MongoDB | `mongodb` | 绿叶品牌，开发者文档 |
| PostHog | `posthog` | 开发者友好暗色 UI |
| Sanity | `sanity` | 红色点缀，内容优先 |
| Sentry | `sentry` | 暗色仪表盘，粉紫点缀 |
| Supabase | `supabase` | 暗色翡翠主题 |

### 效率 & SaaS
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Cal.com | `cal` | 干净中性 UI |
| Intercom | `intercom` | 友好蓝色，对话式 UI |
| Linear | `linear.app` | 超级极简，紫色点缀 |
| Mintlify | `mintlify` | 绿色点缀，阅读优化 |
| Notion | `notion` | 暖色极简，衬线标题 |
| Resend | `resend` | 暗色极简，等宽字体 |
| Zapier | `zapier` | 暖橙色，插画驱动 |

### 设计工具
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Airtable | `airtable` | 多彩友好，结构化美学 |
| Clay | `clay` | 有机形状，柔和渐变 |
| Figma | `figma` | 多彩活泼，专业感 |
| Framer | `framer` | 黑蓝大胆，动效优先 |
| Miro | `miro` | 明黄点缀，无限画布 |
| Webflow | `webflow` | 蓝色点缀，精致营销 |

### 金融科技
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Binance | `binance` | 币安黄，交易所紧迫感 |
| Coinbase | `coinbase` | 蓝色信任感 |
| Kraken | `kraken` | 紫色暗色 UI，数据密集 |
| Revolut | `revolut` | 暗色渐变卡片，金融精确 |
| Stripe | `stripe` | 紫色渐变，轻盈优雅 |
| Wise | `wise` | 明绿色，友好清晰 |

### 电商 & 零售
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Airbnb | `airbnb` | 暖珊瑚色，摄影驱动 |
| Meta | `meta` | 摄影优先，Meta 蓝 |
| Nike | `nike` | 单色，巨型 Futura 字体 |
| Shopify | `shopify` | 暗色电影感，霓虹绿 |

### 媒体 & 消费科技
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| Apple | `apple` | 高端白色空间，SF Pro |
| IBM | `ibm` | Carbon 设计系统，蓝色 |
| NVIDIA | `nvidia` | 绿黑能量，技术力量美学 |
| Pinterest | `pinterest` | 红色点缀，瀑布流 |
| PlayStation | `playstation` | 三层面布局，青色交互 |
| SpaceX | `spacex` | 黑白硬朗，全屏影像 |
| Spotify | `spotify` | 绿色暗底，专辑封面驱动 |
| The Verge | `theverge` | 酸性薄荷+紫外光 |
| Uber | `uber` | 黑白大胆，都市能量 |
| WIRED | `wired` | 纸白报纸密度，墨蓝链接 |

### 汽车
| 品牌 | 目录 | 风格特征 |
|------|------|----------|
| BMW | `bmw` | 暗色高端，德系工程美学 |
| Bugatti | `bugatti` | 影院级黑，单色，纪念碑式字体 |
| Ferrari | `ferrari` | 明暗对比编辑式，法拉利红 |
| Lamborghini | `lamborghini` | 纯黑殿堂，金色点缀 |
| Renault | `renault` | 极光渐变，NouvelR 字体 |
| Tesla | `tesla` | 极致减法，电影级摄影 |

## DESIGN.md 内容结构

每份文件包含 9 个标准化章节：

| # | 章节 | 内容 |
|---|------|------|
| 1 | Visual Theme & Atmosphere | 设计氛围、密度、哲学 |
| 2 | Color Palette & Roles | 语义色名 + Hex + 功能角色 |
| 3 | Typography Rules | 字体族、完整层级表 |
| 4 | Component Stylings | 按钮、卡片、输入框、导航及状态 |
| 5 | Layout Principles | 间距尺度、网格、留白哲学 |
| 6 | Depth & Elevation | 阴影系统、层次结构 |
| 7 | Do's and Don'ts | 设计准则与反模式 |
| 8 | Responsive Behavior | 断点、触控目标、折叠策略 |
| 9 | Agent Prompt Guide | 快速色彩参考、组件提示词 |

## 品牌别名

| 用户说 | 对应目录 |
|--------|----------|
| Anthropic / Claude AI | `claude` |
| Linear | `linear.app` |
| Mistral | `mistral.ai` |
| Together | `together.ai` |
| xAI / Grok | `x.ai` |
| OpenCode | `opencode.ai` |
| Runway | `runwayml` |
| Cal / Cal.com | `cal` |
| The Verge | `theverge` |

## License

MIT License - see [LICENSE](LICENSE)
