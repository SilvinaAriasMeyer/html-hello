# Social Commerce Dashboard (HTML + Tailwind CSS v4)

该项目已重置为仅使用 HTML 与本地编译的 Tailwind CSS v4（不使用 CDN）。

## 环境要求

- Node.js 18+
- Python 3（可选，用于运行 `server.py`）

## 安装

```bash
npm install
npm run build:css
```

以上命令会从 `src/input.css` 生成 `styles.css`。

## 开发

1. 启动 Tailwind 监听：

```bash
npm run watch:css
```

2. 启动本地服务器：

```bash
python3 server.py
```

3. 打开 `http://localhost:3000`。

## 目录说明

- `index.html`：移动优先的响应式仪表盘页面
- `src/input.css`：Tailwind v4 输入文件
- `styles.css`：编译后的 CSS
- `package.json`：脚本与依赖

## 说明

不使用 `cdn.tailwindcss.com`，也不包含 Tailwind v3 配置方式。
