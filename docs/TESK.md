# 個人網站開發任務清單

## Phase 0 — 專案初始化（一次性）

### 0.1 初始化專案

**任務清單**

- [ ] Initialize Next.js project (App Router, TypeScript)
- [ ] Install Tailwind CSS
- [ ] Setup ESLint
- [ ] Add .gitignore

**完成定義**

- `npm run dev` 可正常啟動
- 首頁可在 localhost 顯示

### 0.2 專案文件初始化

**任務清單**

- [ ] Add README.md
- [ ] Add SPEC.md
- [ ] Add TASKS.md

**完成定義**

- Repo clone 下來可理解專案目標與範圍

---

## Phase 1 — 全站架構（不做設計）

### 1.1 建立全站 Layout

**任務清單**

- [ ] Create root layout (`app/layout.tsx`)
- [ ] Add basic HTML structure (header, main, footer)
- [ ] Ensure layout applies to all pages

**完成定義**

- 所有頁面共用 layout
- 不需要樣式，只要結構正確

### 1.2 Header 與導覽列

**任務清單**

- [ ] Add navigation links (Home / Projects / Blog / About)
- [ ] Setup basic routing links

**完成定義**

- 點擊導覽可正確切換頁面
- 不需要 active state

### 1.3 Footer

**任務清單**

- [ ] Add footer section
- [ ] Add placeholder social links

**完成定義**

- Footer 顯示於所有頁面底部

---

## Phase 2 — 靜態頁面

### 2.1 Home Page

**任務清單**

- [ ] Create home page (`app/page.tsx`)
- [ ] Add basic intro text
- [ ] Add CTA link to Projects or Blog

**完成定義**

- 首頁可正常顯示內容
- CTA 導向正確

### 2.2 About Page

**任務清單**

- [ ] Create about page (`app/about/page.tsx`)
- [ ] Add static personal description

**完成定義**

- 可透過 `/about` 存取

---

## Phase 3 — Projects（作品集）

### 3.1 專案資料結構

**任務清單**

- [ ] Create project data source (JSON or MD)
- [ ] Define project fields (title, description, tech, links)

**完成定義**

- 可在程式中讀取專案資料

### 3.2 Projects 列表頁

**任務清單**

- [ ] Create projects page (`/projects`)
- [ ] Render project list
- [ ] Display basic project info

**完成定義**

- 專案資料正確顯示
- External links 可開啟

---

## Phase 4 — Blog（文章系統核心）

### 4.1 建立內容目錄

**任務清單**

- [ ] Create `/content/blog` directory
- [ ] Add sample MDX article with frontmatter

**完成定義**

- Repo 中已有至少一篇文章檔案

### 4.2 讀取文章資料

**任務清單**

- [ ] Implement MDX parsing
- [ ] Extract frontmatter (title, date, summary)

**完成定義**

- 程式可取得文章 metadata

### 4.3 Blog 列表頁

**任務清單**

- [ ] Create blog list page (`/blog`)
- [ ] Sort articles by date
- [ ] Render title, date, summary

**完成定義**

- 新增文章檔案後，列表自動更新

### 4.4 Blog 動態路由

**任務清單**

- [ ] Create dynamic route (`/blog/[slug]`)
- [ ] Render article content
- [ ] Handle not-found case

**完成定義**

- 可直接透過 URL 存取文章
- 不存在文章顯示 404

### 4.5 MDX 功能支援

**任務清單**

- [ ] Enable code block rendering
- [ ] Enable image rendering

**完成定義**

- Code block 與圖片顯示正常

---

## Phase 5 — SEO 與體驗

### 5.1 Metadata

**任務清單**

- [ ] Add global metadata
- [ ] Add per-page metadata
- [ ] Add blog post metadata

**完成定義**

- 每個頁面有正確 title 與 description

### 5.2 基本 RWD

**任務清單**

- [ ] Ensure layout works on mobile
- [ ] Fix obvious overflow issues

**完成定義**

- 手機瀏覽無版面崩壞

---

## Phase 6 — UI 微調（最後才做）

### 6.1 Typography

**任務清單**

- [ ] Define font scale
- [ ] Apply consistent spacing

### 6.2 Visual Polish

**任務清單**

- [ ] Improve spacing
- [ ] Improve readability

**完成定義**

- 網站整體視覺一致
- 不追求炫技

---

## Phase 7 — 部署與收尾

### 7.1 部署

**任務清單**

- [ ] Deploy to Vercel
- [ ] Verify build success

### 7.2 專案整理

**任務清單**

- [ ] Update README with project description
- [ ] Add screenshots
- [ ] Verify links

**完成定義**

- 可公開分享網站與 repo
