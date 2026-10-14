# MOET MOOC – Self-Study Plan Worksheet

An interactive English self-study planning worksheet for learners taking the **Independent Learning in the Digital Age** MOOC.

The worksheet helps learners choose an English learning priority, describe what they need to do, set a short-term goal, check their available time and support, and review whether their goal is realistic.

## Open the activity

Once GitHub Pages is enabled, share the published **website URL** with learners, not the GitHub repository URL.

The site address will usually look like:

`https://YOUR-USERNAME.github.io/moet-self-study-plan/`

Replace `YOUR-USERNAME` with your GitHub username and adjust the repository name if different.

The activity also works offline: download `index.html` and open it in a browser.

## Learner instructions

1. Open the worksheet link.
2. Complete questions **1 and 2**.
3. Select **Save my progress** to download a `.json` progress file.
4. Return to the MOOC and complete the next lesson about making goals specific.
5. Open the worksheet again, then choose the saved `.json` file using **Returning to your worksheet?**
6. Complete questions **3–5**.
7. Choose **Download my answers** to save a readable `.txt` summary, or **Print / save as PDF**.

**Important:** Answers are not saved automatically. Learners should keep their downloaded progress files to continue later. The `.txt` summary cannot be reimported to edit answers; use the `.json` file for that.

## Publish with GitHub Pages (repository owner)

1. Sign in to GitHub and create a **public** repository called `moet-self-study-plan` (or another name).
2. Upload the four files from this package into the **top level** of the repository. Make sure the HTML file is named `index.html`.
3. Open the repository's **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Set the branch to **main**, folder to **/(root)**, and select **Save**.
6. When publication finishes, open the URL shown on the Pages settings screen.
7. Test the link on a phone and computer, especially save, restore, language switching, and download.
8. Paste the **published Pages URL** into the MOET MOOC platform as the student hyperlink.

GitHub Pages publication is not always immediate. Refresh the Pages settings screen if the URL has not appeared yet.

## Update the worksheet

1. Open `index.html` in Visual Studio Code.
2. Edit and test it in a local browser.
3. On GitHub, open `index.html`, choose **Edit** (pencil icon), paste the updated code, and commit the change — or upload the edited file to replace the existing one.
4. Allow the Pages site time to update, then test the published link.

Changes to the worksheet's saved-progress structure should preserve compatibility with older `.json` files where possible.

## Accessibility and design

- Mobile-first and responsive.
- Designed for short instructions and approximately CEFR A2 English.
- English/Vietnamese interface toggle.
- Uses RMIT primary colours and an offline-safe system font.
- No external packages, account, internet connection, or server calls are needed to run the activity itself.
- WCAG 2.2 AA is a design target, **not a certification**; formal accessibility testing has not been completed.

## Privacy and data

- This static activity does **not** send learners' worksheet answers to GitHub or the MOOC.
- Save/restore files and answer summaries are created on the learner's device.
- GitHub may still collect standard website access data under its own policies.
- Do **not** upload learners' completed answer files or progress files into this public repository.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The interactive worksheet and all CSS/JavaScript |
| `README.md` | Project overview and setup instructions |
| `LICENSE.md` | Temporary rights notice while licensing permission is confirmed |
| `.gitignore` | Prevents accidental commits of local files and saved learner work |

## Ownership and licensing

**Licence selection is pending institutional review.** Do not assume the public repository or GitHub Pages link grants permission to copy, modify, or redistribute the code or materials. See [LICENSE.md](LICENSE.md).

Before adding an open-source licence, confirm with RMIT or the appropriate rights holder who owns the course materials and which licence (if any) is authorised.
