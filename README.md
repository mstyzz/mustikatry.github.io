# Mustika Razali — Creative Screen Portfolio

## Publish on GitHub Pages
1. Extract this ZIP on your computer.
2. Open your existing GitHub repository (username.github.io).
3. In Code > Add file > Upload files, drag the CONTENTS of the extracted mustika-portfolio folder into GitHub, not the outer folder. Keep the projects folder and other folders intact. Commit changes. Replace old index.html if prompted.
4. Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Open your published URL when GitHub finishes deployment.

## Preview locally
Open index.html in your browser. Navigation, project filters, separate project pages, reel selection and activity scrolling work without a server.

## Add personal images
Save JPG files under images/ with these exact names (lowercase):
- profile.jpg, about.jpg
- penang-hill.jpg, television.jpg, mprc.jpg, radio.jpg, short-film.jpg, fyp-documentary.jpg, fyp-podcast.jpg
- For each project, optional BTS pictures: penang-hill-bts-1.jpg through penang-hill-bts-3.jpg (same naming pattern for other project slugs).
- activity-purnama.jpg, activity-forum.jpg, activity-write-it-right.jpg, activity-netball.jpg, activity-baktisiswa.jpg, activity-tapem.jpg, activity-handball.jpg, activity-townhall.jpg, activity-riuh.jpg

## Add media and resume
- Put MP4 videos in videos/, audio in audio/, then edit the matching file field in script.js (e.g. file:'videos/short-film.mp4'). Leave type:'audio' for audio files; use type:'video' for MP4. Keep files small enough for GitHub or adapt the player for external hosting.
- Put CV at documents/resume.pdf; change resumeReady:false to resumeReady:true in script.js.
- Add confirmed professional email and LinkedIn URL in the contact object in script.js.
- Update unknown Coolblog employment dates and Riuh Festival date in index.html.
- Project descriptions are editable in projects/*.html. Add specific challenges, techniques, software and verified results as you confirm them.
- Only publish media you have permission to share; GitHub Pages is public. Avoid personal details you do not want public.

No actual portrait, project media, contact links or CV were provided in this build, so labelled placeholders are intentional.


## Premium edition
The concept-*.jpg images are cropped from the approved generated design mockup and are illustrative only, including the portrait. Upload actual photos using the original filenames listed above; the fallback is automatically replaced. Remove the design preview note once all illustrative images have been replaced. Video and audio remain unavailable until configured in script.js.
