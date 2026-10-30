# MOET MOOC – Interactive English Self-Study Activities

A collection of interactive learning resources developed for the **Independent English Learning in the Digital Age** MOOC.

These activities support learners in developing independent English learning strategies through practical, self-directed tasks. They complement the MOOC content and are designed to be accessible, easy to use, and suitable for learners with approximately CEFR A2 English proficiency.

## Activities

| File | Activity | Purpose |
|---|---|---|
| `index.html` | Self-Study Plan Worksheet | Helps learners identify priorities, set goals, assess available resources, and develop a realistic English learning routine. |
| `speaking-partner.html` | AI Speaking Partner | Supports learners in preparing for and practising spoken English using structured activities and AI-assisted learning strategies. |
| `writing-workspace.html` | Writing Workspace | Provides a structured environment for independent English writing practice. |

Additional activities may be added as the MOOC develops.

## Access the activities

Activities are published through GitHub Pages and can be accessed directly in a web browser.

**Published website:**  
https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/

**Individual activity links:**

- Self-Study Plan Worksheet: https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/
- AI Speaking Partner: https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/speaking-partner.html
- Writing Workspace: https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/writing-workspace.html

Where supported, activities can also be downloaded as standalone HTML files and opened locally in a browser.

Learners should access activities through the links provided in their MOOC lessons.

## Design principles

Activities are developed with the following principles:

- **Independent learning:** Learners can complete activities without direct teacher supervision.
- **Accessible language:** Instructions use clear, concise English, generally targeting CEFR A2 or simpler.
- **Mobile-first:** Activities are designed for use on phones, tablets, and computers.
- **Low-bandwidth access:** Standalone HTML files minimise dependencies and support use in contexts with limited connectivity.
- **Bilingual support:** English/Vietnamese guidance is included where appropriate.
- **Practical outputs:** Where relevant, learners can download or save their work for later reference.
- **Accessible design:** WCAG 2.2 AA is a development target, although formal accessibility certification has not been completed.
- **Institutional consistency:** Materials follow RMIT visual branding principles where appropriate.

Features and offline functionality may vary between activities.

## Repository structure

The repository currently contains:

| File | Purpose |
|---|---|
| `index.html` | Self-study planning worksheet, including CSS and JavaScript |
| `speaking-partner.html` | Speaking practice activity |
| `writing-workspace.html` | Writing practice activity |
| `README.md` | Project overview, access links, and maintenance instructions |
| `LICENSE.md` | Rights and licensing information pending institutional confirmation |
| `.gitignore` | Excludes specified local and temporary files from version control |

Activities are generally developed as standalone HTML files with embedded CSS and JavaScript to simplify hosting, distribution and maintenance.

## Maintaining and updating activities

### Editing an existing activity

1. Open the relevant `.html` file in Visual Studio Code.
2. Make the required changes.
3. Test the activity locally in a browser, including on mobile where possible.
4. Upload or commit the updated file to the GitHub repository.
5. Check that the published GitHub Pages version has updated correctly.
6. Test key interactions, including navigation, language switching, downloads and any activity-specific functionality.

### Adding a new activity

1. Create a standalone HTML file with a descriptive filename.
2. Test the activity locally before publishing.
3. Upload the file to the repository.
4. Confirm that it is accessible through GitHub Pages.
5. Add the activity and its URL to the **Activities** and **Access the activities** sections of this README.
6. Add the activity URL to the appropriate MOOC lesson.

Existing filenames should be preserved where possible, as changing them may break links already published in the MOOC.

## Data, privacy and learner safety

These resources are intended to support independent learning while minimising unnecessary collection of personal information.

- Activities should not require learners to create accounts or provide personally identifiable information unless explicitly approved.
- Locally saved files remain on learners' devices unless they choose to share or upload them elsewhere.
- Learners should avoid entering sensitive personal information into activities or external AI services.
- AI-generated responses and feedback should be treated critically and checked where appropriate.
- GitHub may collect standard website access information under its own policies.
- Learner responses, completed worksheets and progress files must not be uploaded to this public repository.

Activities involving external AI tools or services may have additional privacy and connectivity considerations.

## GitHub Pages publishing

This repository uses GitHub Pages to make HTML activities accessible through public URLs.

To review or configure publishing:

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the `main` branch and `/(root)` folder.
4. Save the configuration.
5. Confirm that GitHub Pages is publishing the latest repository files.

New HTML files can normally be accessed using:

`https://OWNER.github.io/REPOSITORY/FILENAME.html`

For example:

`https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/speaking-partner.html`

**Important:** If repository ownership or the repository name changes, review and update GitHub Pages links in this README and across the MOOC. GitHub Pages URLs do not automatically redirect following repository transfers.

## Ownership and licensing

These resources have been developed in connection with RMIT Vietnam's contribution to the MOET MOOC initiative.

**Licence selection remains subject to institutional review.**

Public access to the repository or activities does not automatically grant permission to copy, modify, republish or redistribute the materials.

Refer to [LICENSE.md](https://github.com/RMITPathways/Ind-Eng-Lear-Dig-Age/blob/main/LICENSE.md) for the current rights notice.

Before introducing an open-source licence, confirm the appropriate ownership and licensing arrangements with RMIT or the relevant rights holder.
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
