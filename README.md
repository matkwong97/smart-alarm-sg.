# Smart Alarm SG
Created by Matthew Kwong © 2026.

## Deploy with GitHub and Cloudflare Pages
1. Create a public GitHub repository named `smart-alarm-sg`.
2. Upload all files in this folder to the repository ROOT (not a nested folder).
3. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git → select repository.
4. Framework preset: None; Build command: leave blank; Build output directory: `/`.
5. Deploy and open the assigned `pages.dev` URL.
6. On iPhone: Safari → Share → Add to Home Screen.

## Important
Browsers cannot guarantee scheduled background audio, particularly on locked iPhones. Keep the page open and active for the alarm to fire; use a native alarm as backup. The app works offline after first load, but offline capability does not grant background alarm privileges. The theme uses approximate 06:00/18:00 local clock times, not live astronomical sunrise/sunset. All settings stay in browser local storage.
