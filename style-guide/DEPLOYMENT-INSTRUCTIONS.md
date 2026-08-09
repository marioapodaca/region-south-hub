# DEPLOYMENT INSTRUCTIONS — GitHub Pages

## Recommended deployment location
Repository: `marioapodaca/region-south-hub`

The package is designed so the contents of the `style-guide` folder can be placed in a `/style-guide/` folder in that repository.

## Upload
1. Extract the final ZIP file.
2. Open the extracted `style-guide` folder.
3. In the GitHub repository, create or open the repository folder named `style-guide`.
4. Upload **all files and subfolders** from the downloaded `style-guide` folder. Preserve the folder structure exactly.
5. Commit the upload to the repository's publishing branch (normally `main`).

## Turn on GitHub Pages
1. Open the repository on GitHub.
2. Select **Settings**.
3. Select **Pages** under Code and automation.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the publishing branch, normally `main`.
6. Select the repository root folder offered by GitHub for that branch and save.

Because the style guide is stored inside `/style-guide/`, its page will normally be reached under the repository's Pages site at `/style-guide/` after GitHub finishes publishing.

## Verify after publishing
Open the style guide and confirm:
- Home page loads.
- Examples Gallery loads.
- Images and logos load.
- Light/Dark reference image loads.
- Approved example pages load.
- AI instruction files are accessible from the repository.

## Update the AI public links
After the site is live, edit `AI-COPY-PASTE.md` and replace the two placeholder public URLs with the final public URLs for:
- `region-south-style-guide.md`
- `AI-QUICKSTART.md`

## Ongoing maintenance
When standards change:
1. Update the human guide.
2. Update the AI Markdown specification.
3. Update the YAML specification.
4. Update the Prompt Library if user-interaction rules change.
5. Revalidate affected Approved Examples.
6. Increment the appropriate version number.
