![enter image description here](https://raw.githubusercontent.com/open-saga/.github/main/profile/logo-256.jpg)

# Open Saga

Welcome to the **Open Saga** project! This repository is dedicated to collaboratively creating and managing open-source stories. Below, you'll find the structure and guidelines ensuring consistency, accessibility, and quality across all contributions. You can use the template to start a new project.

## Story repository structure

Each story follows this directory and file structure:

```
https://github.com/open-saga/
├── [StoryName]/
│   ├── [LanguageCode]/
│   │   ├── STORY.md        # Entire story in a single file
│   ├── images/
│   │   ├── example.png     # Related images
│   └── RULES.md            # Story rules
└── ...
```

### Key Points

1. **Languages Directory**:
   - Stories are organized into subdirectories by name.
   - Each language subdirectory (e.g., `en`, `fr`, `es`) contains a `STORY.md` file.

2. **Images Directory**:
   - The `images/` folder stores visuals for the story.
   - Images are included in `STORY.md` using relative paths:
     ```markdown
     ![Description of the image](images/example.png)
     ```

3. **Rules File**:
   - Each story includes a `RULES.md` file defining its core rules.
   - These rules can be updated collaboratively, respecting the story's original vision.

## Contribution Rules

### Story Updates

- Stories are stored in a single `STORY.md` file per language.
- Updates must be reflected across all available languages to maintain consistency.
- Translations must remain faithful to the original content.

### Image Contributions

- Add images to the `images/` folder with filenames indicating their purpose.
- Ensure images adhere to contribution rules and updates apply across translations.

### Rules File Updates

- Proposed changes to `RULES.md` require thorough review to align with the creator's intent.

### General Guidelines

- **Single Source of Truth**: One file per language avoids duplication.
- **Collaboration**: Discuss significant changes via issues or pull requests before making updates.
- **Attribution**: Respect the license and acknowledge contributors.

## Workflow

1. Fork the repository.
2. Create a branch for your updates (e.g., `feature/add-new-chapter`).
3. Ensure updates comply with the outlined structure and rules.
4. Submit a pull request with a detailed description.
5. Collaborate with maintainers for review and merging.

## License

This project is open-source under the [Open Saga License](LICENSE), enabling collaborative storytelling while protecting story integrity and contributions.

---

Thank you for being a part of Open Saga! For questions, suggestions, or feedback, reach out or open an issue.


