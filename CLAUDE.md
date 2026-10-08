# sitrip homepage

Company homepage for sitrip (시트립), served at https://sitrip.co.kr via GitHub Pages.
Plain HTML + CSS, no build step: `index.html`, `styles.css`, `CNAME`.

## Design system: Wanted Design System (do not replace)

This site uses the **Wanted Design System** (Wanted Lab, CC BY 4.0) as its design basis.
Source: https://www.figma.com/community/file/1355516515676178246/wanted-design-system

- Keep the Wanted look: tokens in `:root` of `styles.css` (primary `#0066FF`, label/background/line colors, radius 8/12/16/24, Pretendard typography scale). Change or add UI by reusing these tokens and the existing patterns (`.btn`, `.chip`, `.card`, `.feature`, `.section`).
- Do not switch to another design system, UI kit, CSS framework (Tailwind, Bootstrap, etc.), or a different color palette/font unless the user explicitly asks to change the design.
- Dark mode follows `prefers-color-scheme`; when adding a color token, define it in both the light and dark blocks.

## Licensing rules (commercial site)

- **Keep the attribution** in the footer (`.footer__credit`) and the header comment in `styles.css`. CC BY 4.0 requires it. If you modify the design, it stays "Modified by sitrip."
- **No photos, illustrations, or stock images.** Do not copy any images, icons, or illustrations from the Wanted Figma file or anywhere else.
- **Do not use the Wanted logo or the "wanted" name** in sitrip branding (trademark not covered by CC BY).
- Fonts: only **Pretendard** (SIL OFL 1.1, via jsDelivr). Do not add Wanted Sans or other fonts unless their license is confirmed for commercial use.
- Only add assets whose license clearly allows commercial use, and note the license in the footer credit.

## Privacy

- Never commit personal documents (contracts, IDs, photos). `.gitignore` blocks jpg/jpeg/heic/pdf.
- Do not put the business address or 사업자등록번호 on the page unless the user asks.

## Content

- sitrip: 여행에 필요한 모든 서비스를 만드는 회사. First product: 여행 가계부 (in development).
- **AI 검색 is the core feature** of 여행 가계부 (ask about your spending in natural language). Keep it the most prominent feature (`.highlight` block in the Product section).
- Contact: nespot2@sitrip.co.kr
- Page copy is Korean; keep the tone short and plain.
