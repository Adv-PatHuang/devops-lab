# devops-lab

DevOps 課程實作用的範例專案，沒有任何第三方套件。

## 本機執行

有 Node.js 與 npm：

```bash
npm ci
npm run lint
npm run format:check
npm test
npm run build
```

沒有 npm（離線環境）：

```bash
bash scripts/check-all.sh
```

完成後的目錄結構：

```text
devops-lab/
├── .gitattributes
├── .gitignore
├── README.md
├── package-lock.json
├── package.json
├── scripts/
│   ├── build.sh
│   ├── check-all.sh
│   ├── format-check.sh
│   ├── lint.sh
│   └── test.sh
├── src/
│   ├── app.js
│   └── index.html
└── tests/
	└── app.test.js
```
