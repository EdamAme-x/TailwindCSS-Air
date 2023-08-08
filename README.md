# TailwindCSS-Air
軽量版 TailwindCSSです。 エラーメッセージ等も出ない様になっています。開発ではCDN、本番ではAIR(Local)を推奨します。
動作確認はしています。

## パフォーマンス


| NAME | BYTES | URL | Ratio |
| ---- | ---- | ---- | ---- |
| CDN | 362807 bytes | [https://cdn.tailwindcss.com/3.3.3](https://cdn.tailwindcss.com/3.3.3) | 100% |
| AIR | 342708 bytes | [https://raw.githubusercontent.com/EdamAme-x/TailwindCSS-Air/main/tailwind-air.js](https://raw.githubusercontent.com/EdamAme-x/TailwindCSS-Air/main/tailwind-air.js) | 94% |

## ToDo

- 文字列を変数で共通化してリテラルで読み込む。
- 動作自体を高速化
