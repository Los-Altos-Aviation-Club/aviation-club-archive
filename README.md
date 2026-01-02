# Aviation Project Archive Documentation

Welcome to the **AviationProjectArchive** repository. This archive serves as the centralized storage for all project-related updates, media, and descriptions for the LAHS Aviation Website.

## Repository Structure

The archive follows a strict hierarchical structure to ensure consistency and ease of parsing by the main website.

### Folder Structure
All project updates are stored within the `projects` directory:

`/projects/[slug]/YYYY-MM-DD-Update-Title/`

- **`[slug]`**: The unique identifier for the project (e.g., `drone-project`).
- **`YYYY-MM-DD-Update-Title`**: A folder representing a specific update.
    - `YYYY-MM-DD`: The date of the update.
    - `Update-Title`: A short, hyphenated title for the update.

### File Requirements
Each update folder must contain the following:

1.  **`desc.txt`**: A plain text file containing the description of the update. This file should only contain text and will be rendered as the body of the update post.
2.  **Media Files**: Any associated media for the update. Supported formats include:
    - **Images**: `.jpg`, `.jpeg`, `.png`, `.webp`
    - **Video**: `.mp4`
    - **Other**: `.pdf` (if applicable)

## Global Metadata

The root of the repository contains a `metadata.json` file. This file acts as the registry for all projects and their respective metadata, allowing the website to discover and display projects dynamically.

### `metadata.json` Format
The file should maintain an array or object mapping of project slugs to their high-level details (e.g., project name, status, thumbnail).

## Contribution Workflow

1.  Navigate to the relevant project folder in `/projects/`.
2.  Create a new folder following the `YYYY-MM-DD-Update-Title` format.
3.  Add the `desc.txt` file and any media assets.
4.  Commit and push the changes to the repository.
