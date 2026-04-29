# Tina Retirement Project

靜態退休規劃頁面，部署在 Firebase Hosting。

## 線上網址
- https://tinaretirement-18e44.web.app

## 目前內容
- `index.html`：主頁面（含密碼入口、退休規劃 UI、Firebase Realtime Database 同步）
- `firebase.json`：Firebase Hosting 設定
- `.firebaserc`：Firebase 專案綁定

## 部署方式
```bash
firebase deploy --only hosting
```

## 備註
- 目前密碼保護是前端頁面閘道，屬於「避免路人直接看到內容」等級，不是高安全性的真正身分驗證。
- 若之後要提升安全性，建議改成 Firebase Authentication 或後端驗證。
- 目前 Firebase project id / hosting site：`tinaretirement-18e44`
