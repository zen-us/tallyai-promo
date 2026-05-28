# TallyAI Directory Submission Kit

> 一键提交至 20+ 免费目录。每个条目包含：URL、提交方式、预填信息。

---

## 如何使用

### 方案 A：让 Claude Code 用浏览器操作（推荐）
```bash
# 把这份文件交给 Claude Code，说：
# "用浏览器打开以下目录的提交页面，填入预填信息，提交 TallyAI"
```

### 方案 B：自己手动提交（5 分钟/个）
打开 URL → 粘贴对应字段 → 提交。

### 方案 C：API 自动提交（Dev.to 等支持 API 的）
```bash
# 先设置 API key 环境变量
export DEVTO_API_KEY="your-key"
# 然后用脚本批量提交
```

---

## 一、支持 API 的目录（可以自动化）

### 1. Dev.to — API 可用 ✅

| 字段 | 值 |
|------|-----|
| URL | https://dev.to/api/articles |
| 方法 | POST, API Key |
| 设置 Key | https://dev.to/settings/extensions → 生成 API Key |
| 标题 | AI Bookkeeping in Google Sheets: Stop Manual Data Entry |
| 标签 | ai, productivity, freelancing, google-sheets |
| 正文 | 见下文 `blog-post.md` |

**预填文章（复制到 Dev.to 编辑器或通过 API 发送）：**
→ 见 `/Users/zen/Documents/Intelligence/项目/TallyAI/blog-post-ai-bookkeeping.md`

---

## 二、需要浏览器的目录（提交数据预填）

### 2. Product Hunt

| 字段 | 值 |
|------|-----|
| URL | https://www.producthunt.com/posts/new |
| 产品名 | TallyAI |
| 标语 | AI-powered bookkeeping inside Google Sheets |
| 描述 | Describe expenses in plain English — "client lunch $45" or "Adobe subscription $55/mo" — and the AI handles categorization automatically. No install, no API key needed. |
| 链接 | https://www.etsy.com/shop/TallyAI |
| 价格 | Free template with Etsy purchase ($12.99, 75% off with SEED100) |

### 3. SaaSHub

| 字段 | 值 |
|------|-----|
| URL | https://www.saashub.com/submit |
| 产品名 | TallyAI |
| 网站 | https://tallyai.etsy.com |
| 描述 | AI bookkeeping template for Google Sheets. Describe expenses in plain English, AI auto-categorizes. No install, no ChatGPT key needed. |
| 标签 | bookkeeping, accounting, google-sheets, ai, freelance |

### 4. AlternativeTo

| 字段 | 值 |
|------|-----|
| URL | https://alternativeto.net/new/ |
| 产品名 | TallyAI |
| 描述 | AI Smart Bookkeeping Template for Google Sheets |
| 类别 | Accounting, Bookkeeping, Personal Finance |

### 5. Indie Hackers

| 字段 | 值 |
|------|-----|
| URL | https://www.indiehackers.com/products/new |
| 产品名 | TallyAI |
| 月收入 | $0 (just launched) |
| 描述 | AI bookkeeping template that auto-categorizes expenses from plain text descriptions. Built for freelancers. |
| 链接 | https://www.etsy.com/shop/TallyAI |

### 6. BetaList

| 字段 | 值 |
|------|-----|
| URL | https://betalist.com/submit |
| 产品名 | TallyAI |
| 标语 | AI Bookkeeping in Google Sheets |
| 描述 | Describe expenses in plain English — AI categorizes them automatically. Works in Google Sheets, no install needed. |
| 链接 | https://tallyai.etsy.com?coupon=SEED100 |

### 7. FutureStack

| 字段 | 值 |
|------|-----|
| URL | https://usefuturestack.com/submit |
| 产品名 | TallyAI |
| 描述 | AI-powered bookkeeping inside Google Sheets. Describe expenses in plain words, AI handles the rest. |
| 类别 | Productivity, Finance |

### 8. NewTool.site

| 字段 | 值 |
|------|-----|
| URL | https://newtool.site/submit |
| 产品名 | TallyAI |
| 描述 | AI Smart Bookkeeping Template for Google Sheets |
| 类别 | Finance, Productivity |

### 9. AI Tools Lister

| 字段 | 值 |
|------|-----|
| URL | https://aitoolslister.com/submit |
| 产品名 | TallyAI |
| 描述 | AI bookkeeping template for Google Sheets. Plain English expense tracking. |
| 类别 | AI, Finance, Productivity |

### 10. Peerlist

| 字段 | 值 |
|------|-----|
| URL | https://peerlist.io/launch |
| 产品名 | TallyAI |
| 描述 | AI-powered bookkeeping in Google Sheets for freelancers |
| 标签 | bookkeeping, ai, freelance, google-sheets |

### 11. Uneed

| 字段 | 值 |
|------|-----|
| URL | https://uneed.io/submit |
| 产品名 | TallyAI |
| 描述 | AI Bookkeeping Template for Google Sheets — describe expenses in plain English |
| 类别 | Productivity, Finance |

### 12. OpenHunts

| 字段 | 值 |
|------|-----|
| URL | https://openhunts.com/submit |
| 产品名 | TallyAI |
| 描述 | AI Smart Bookkeeping — expense tracking in Google Sheets |
| 标签 | ai, bookkeeping, finance |

### 13. LaunchDB

| 字段 | 值 |
|------|-----|
| URL | https://bigideasdb.com/launchdb |
| 产品名 | TallyAI |
| 描述 | AI bookkeeping template for freelancers. No install, no API key, just Google Sheets. |
| 类别 | Finance, Productivity |

### 14. MicroLaunch

| 字段 | 值 |
|------|-----|
| URL | https://microlaunch.net/submit |
| 产品名 | TallyAI |
| 描述 | AI-powered bookkeeping in Google Sheets — describe expenses, AI categorizes |
| 标签 | saas, productivity, finance |

### 15. ProductFame

| 字段 | 值 |
|------|-----|
| URL | https://productfame.com/submit |
| 产品名 | TallyAI |
| 描述 | AI Smart Bookkeeping Template for Google Sheets |
| 类别 | Business, Finance |

---

## 三、社交媒体帖文（直接用 promotion-posts.md）

Reddit / Twitter / Indie Hackers / 小红书 / 微信朋友圈的帖文已经写好：
→ `/Users/zen/Documents/Intelligence/项目/TallyAI/promotion-posts.md`

**优先发帖顺序：**
1. Reddit r/smallbusiness — 最大的目标受众
2. Indie Hackers Products — 社区最友善
3. Twitter/X — 覆盖面广
4. Reddit r/freelance — 精准用户
5. 小红书 — 中文市场
6. 微信朋友圈 — 私域流量

---

## 四、批量提交脚本（浏览器控制台用）

打开每个目录的提交页面后，在浏览器控制台粘贴以下 JS 代码可加速填表：

```javascript
// === TallyAI 自动填表脚本 ===
// 粘贴到浏览器控制台运行（在每个提交页面运行一次）

const fields = {
  'name': 'TallyAI',
  'title': 'TallyAI — AI Bookkeeping in Google Sheets',
  'description': 'AI-powered bookkeeping inside Google Sheets. Describe expenses in plain English — "client lunch $45" or "Adobe subscription $55/mo" — and the AI handles categorization automatically. No install, no ChatGPT key, no learning curve.',
  'url': 'https://tallyai.etsy.com?coupon=SEED100',
  'tagline': 'AI bookkeeping that works from plain English descriptions',
  'price': '$12.99 (75% off with SEED100)',
  'category': 'Finance',
  'tags': 'AI, bookkeeping, accounting, freelance, google-sheets',
};

// Auto-fill common input patterns
document.querySelectorAll('input, textarea').forEach(el => {
  const name = (el.name || '').toLowerCase();
  const id = (el.id || '').toLowerCase();
  const placeholder = (el.placeholder || '').toLowerCase();
  
  for (const [key, value] of Object.entries(fields)) {
    if (name.includes(key) || id.includes(key) || placeholder.includes(key)) {
      el.value = value;
      el.dispatchEvent(new Event('input', { bubbles: true }));
      break;
    }
  }
});

console.log('✅ TallyAI auto-fill complete! Check the form and submit.');
```

---

## 五、进度跟踪

| # | 目录 | 状态 | 日期 | 备注 |
|---|------|------|------|------|
| 1 | Dev.to | ⏳ | — | 需 API key |
| 2 | Product Hunt | ❌ | — | 需浏览器 |
| 3 | SaaSHub | ❌ | — | 需浏览器 |
| 4 | AlternativeTo | ❌ | — | 需浏览器 |
| 5 | Indie Hackers | ❌ | — | 需浏览器 |
| 6 | BetaList | ❌ | — | 需浏览器 |
| 7 | FutureStack | ❌ | — | 需浏览器 |
| 8 | NewTool.site | ❌ | — | 需浏览器 |
| 9 | AI Tools Lister | ❌ | — | 需浏览器 |
| 10 | Peerlist | ❌ | — | 需浏览器 |
| 11 | Uneed | ❌ | — | 需浏览器 |
| 12 | OpenHunts | ❌ | — | 需浏览器 |
| 13 | LaunchDB | ❌ | — | 需浏览器 |
| 14 | MicroLaunch | ❌ | — | 需浏览器 |
| 15 | ProductFame | ❌ | — | 需浏览器 |

> **更新状态：** 改 ❌ 为 ✅ 并填日期。提交后把链接加到备注。
