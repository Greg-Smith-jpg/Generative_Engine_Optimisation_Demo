STUDENT TECH CLUB — GEO LAB (STUDENT TEMPLATE)

IMPORTANT: Do not upload all folders at once. Work through the stages.

STAGE 1: BASIC WEBSITE
1. Choose a UNIQUE club name (e.g. Kiwi Code Corner, Campus AI Circle).
2. In all 4 HTML files, replace YOUR CLUB NAME in the title, header and footer.
3. Replace CHANGE-ME-STUDENT-ID in ai-tools.html with a unique, non-sensitive phrase (not your real student ID).
4. Edit the descriptions and text to make your website different from classmates'.
5. Create a PUBLIC GitHub repository with your own unique repository name.
6. Upload only the CONTENTS of starter/ to the repository root: index.html, coding.html, ai-tools.html, events.html, style.css.
7. Settings > Pages > Deploy from a branch > main > /(root).
8. Confirm all 4 pages load and links work.
9. In a fresh AI conversation, compare direct URL retrieval with searching by topic without a URL. Record evidence. Search results can vary.

STAGE 2: SITEMAP
1. Edit step2_sitemap/sitemap.xml; replace YOUR-USERNAME and YOUR-REPO with your GitHub account and repo.
2. Upload sitemap.xml to the repository root (not the folder).
3. Confirm https://YOUR-USERNAME.github.io/YOUR-REPO/sitemap.xml loads.
4. Use Google Search Console URL-prefix property for your full project URL; verify ownership; submit sitemap.xml.
5. Check Live URL Test, Indexing status and sitemap status separately. They are not the same.

STAGE 3: ROBOTS
1. Study step3_robots/robots.txt and optionally upload it for comparison.
2. IMPORTANT: GitHub Pages project sites use a subpath; /YOUR-REPO/robots.txt is NOT an effective robots.txt for the host. The effective file must be at https://YOUR-USERNAME.github.io/robots.txt, which requires control of the root user site or a custom domain.
3. Do not claim uploading the project file changes crawler permissions.

STAGE 4: SCHEMA.ORG
1. Open the example snippets in step4_schema/.
2. Replace placeholders and paste the WebSite script inside index.html <head>.
3. Paste the WebPage script inside ai-tools.html <head>.
4. Commit and test each exact URL at https://validator.schema.org/ .
5. A valid Schema.org result does not prove Google indexing or AI recommendations.

STUDENT CHECKLIST
[ ] Unique website name
[ ] Unique GitHub repository name
[ ] All <title> values updated
[ ] All <meta name="description"> values reviewed
[ ] All visible club names updated
[ ] Unique non-sensitive verification phrase
[ ] All sitemap URLs updated
[ ] All Schema.org names and URLs updated
[ ] Four pages and navigation links tested
[ ] Screenshot of direct-URL AI test and independent search test
[ ] Screenshots of Search Console and Schema Validator

TEACHER NOTE
Google indexing may take days/weeks and is not guaranteed. The AI may access a given URL even when it cannot independently find it in search. Do not treat one before/after result as proof that Schema.org or sitemap caused a ranking change.
