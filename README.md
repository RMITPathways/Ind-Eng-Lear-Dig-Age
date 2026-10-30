# MOET MOOC – Interactive English Self-Study Activities

A collection of interactive learning resources developed for the **Independent English Learning in the Digital Age** MOOC.

These activities support learners in developing independent English learning strategies through practical, self-directed tasks. They complement the MOOC content and are designed to be accessible, easy to use, and suitable for learners with approximately CEFR A2 English proficiency.

## Activities

| File | Activity | Purpose |
|---|---|---|
| `index.html` | Self-Study Plan Worksheet | Helps learners identify priorities, set goals, assess available resources, and develop a realistic English learning routine. |
| `speaking-partner.html` | AI Speaking Partner | Supports learners in preparing for and practising spoken English using structured activities and AI-assisted learning strategies. |
| `writing-workspace.html` | Writing Workspace | Provides a structured environment for independent English writing practice. |
| `my-plan.html` | My Self-Study Plan | Helps learners consolidate their learning goals, strategies and weekly routines into a practical plan, including responsible AI use, progress checks and opportunities to review and adjust their approach. |

Additional activities may be added as the MOOC develops.

## Access the activities

Activities are published through GitHub Pages and can be accessed directly in a web browser.

**Published website:**  
https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/

**Individual activity links:**

- **Self-Study Plan Worksheet:** https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/
- **AI Speaking Partner:** https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/speaking-partner.html
- **Writing Workspace:** https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/writing-workspace.html
- **My Self-Study Plan:** https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/my-plan.html

Where supported, activities can also be downloaded as standalone HTML files and opened locally in a browser.

Learners should access activities through the links provided in their MOOC lessons.

## Design principles

Activities are developed with the following principles:

- **Independent learning:** Learners can complete activities without direct teacher supervision.
- **Accessible language:** Instructions use clear, concise English, generally targeting CEFR A2 or simpler.
- **Mobile-first:** Activities are designed for use on phones, tablets and computers.
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
| `index.html` | Interactive self-study planning worksheet, including CSS and JavaScript |
| `speaking-partner.html` | Speaking practice activity |
| `writing-workspace.html` | Independent writing practice activity |
| `my-plan.html` | Consolidated self-study plan builder, including weekly routines, AI use and progress review |
| `README.md` | Project overview, access links and maintenance instructions |
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

### Maintaining learner progress compatibility

Some activities allow learners to save their work and return to it later.

When updating these activities:

- Preserve compatibility with existing saved-progress files where possible.
- Check that previously saved responses can still be restored.
- Test downloaded outputs and printing functionality.
- Avoid changing file formats or saved-data structures without checking the impact on learners.

For the original Self-Study Plan Worksheet, learners use a `.json` file to save and restore editable progress. Downloaded `.txt` summaries cannot be reimported to continue editing.

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

`https://rmitpathways.github.io/Ind-Eng-Lear-Dig-Age/my-plan.html`

GitHub Pages publication is not always immediate. After committing changes, allow time for deployment and refresh the published activity to confirm the update.

**Important:** If repository ownership or the repository name changes, review and update GitHub Pages links in this README and across the MOOC. GitHub Pages URLs do not automatically redirect following repository transfers.

## Ownership and licensing

These resources have been developed in connection with RMIT Vietnam's contribution to the MOET MOOC initiative.

**Licence selection remains subject to institutional review.**

Public access to the repository or activities does not automatically grant permission to copy, modify, republish or redistribute the materials.

Refer to [LICENSE.md](https://github.com/RMITPathways/Ind-Eng-Lear-Dig-Age/blob/main/LICENSE.md) for the current rights notice.

Before introducing an open-source licence, confirm the appropriate ownership and licensing arrangements with RMIT or the relevant rights holder.
