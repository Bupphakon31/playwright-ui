# Playwright UI Testing Project

## การติดตั้ง

### 1. Clone โปรเจค
```bash
git clone <repository-url>
cd playwright-ui
```

### 2. ติดตั้ง Dependencies
```bash
npm install
```

### 3. ติดตั้ง Playwright Browsers
```bash
npx playwright install
```

## การใช้งาน

### รัน Tests
```bash
# รัน tests ทั้งหมด
npm test

# รัน tests แบบ UI mode
npm run test:ui

# รัน tests แบบเห็น browser
npm run test:headed

# รัน tests ในโหมด debug
npm run test:debug
```

### Format Code
```bash
# Format ไฟล์ทั้งหมด
npx prettier --write .

# ตรวจสอบ formatting
npx prettier --check .
```

## โครงสร้างโปรเจค
```
playwright-ui/
├── testCases/ui/          # Test files
├── configs/               # Configuration files
├── .github/workflows/     # GitHub Actions
├── playwright.config.ts   # Playwright configuration
├── globalVariables.ts     # Global variables and env setup
└── package.json          # Dependencies
```

## Dependencies
- `@playwright/test` - Playwright testing framework
- `dotenv` - Environment variables management
- `prettier` - Code formatting