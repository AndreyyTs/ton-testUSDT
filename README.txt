Эта папка — готовый статический сайт для GitHub Pages (только фронт и TonConnect-манифест).

Выложите её содержимое в корень репозитория (или в branch gh-pages), чтобы в корне лежали index.html, assets/, tonconnect-manifest.json, app-icon.svg, .nojekyll.

Страницы
1. Репозиторий → Settings → Pages
2. Branch: main (или gh-pages), Folder: / (root)
3. Сайт будет: https://andreyyts.github.io/ton-testUSDT/

Сборка уже с base /ton-testUSDT/ под этот URL. Если переименуете репозиторий — заново соберите проект с другим VITE_BASE_PATH и поправьте url/iconUrl в site/public/tonconnect-manifest.json в полном проекте или отредактируйте tonconnect-manifest.json здесь вручную.
