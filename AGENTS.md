# Website instructions

- Preserve the user’s résumé wording and keyword-style role descriptions. Make only minor grammar corrections unless asked for a rewrite.
- The user’s name is Huikang Jiang / 姜惠康. Keep Simin Chen in English.
- Publication author names are italicized without bold emphasis. Mark equal contribution with `*`: the first two SIGIL authors and the first three SteerScope authors. Do not add an explanatory equal-contribution note.
- Use the user's own square crop without further image edits. Display it with square corners. Preserve the photo unless the user asks to change it.
- Keep this a simple static GitHub Pages website. No framework or build step is needed.
- Text links inherit the surrounding text color and use underlines, including on hover, except the three lab names: keep those clickable without underlines. Keep the navigation buttons monochrome with their existing pill styling.
- Keep the English page in `index.html` and the Chinese page in `zh/index.html` consistent. The language switch belongs alongside GitHub, LinkedIn, and CV. Keep the email address as plain text in the introduction, without an email button. Keep paper titles, lab/company names, Simin Chen, and unverified award names in English.
- Education comes before Experience. Keep linked advisor credits in the corresponding lab experience entries, rather than the introduction or paper entries. The header's secondary line shows only the name in the other language, without the sophomore/university tagline.
- In lab experience entries, place the advisor line closer to the description below than to the heading above.
- After changing `styles.css`, update the stylesheet URL's `v` query parameter in both HTML pages to the first 12 characters of the file's SHA-256 hash so browsers fetch the new styles.
- The website’s CV button links to the Chinese-first bilingual PDF. Keep both PDF files working at their existing paths when updating them.
- After each completed edit, validate the result, commit the task-related files, and push the current branch. The user has authorized this workflow.
- Do not change paper status or add biographical claims without evidence from the user or the résumé.
