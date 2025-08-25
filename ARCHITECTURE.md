# Project Architecture: Astro-Snippets

This document describes the architecture of the **Astro-Snippets** project. Below, the folder and file structure is detailed, along with a conceptual map to facilitate understanding.

## Project Structure

```plaintext
/home/bastndev/Documents/bastndev/VScode/Astro-Snippets/
├── src/
│   ├── components/       # Reusable application components
│   ├── layouts/          # Base layouts for pages
│   ├── pages/            # Main project pages
│   ├── styles/           # Global and specific style files
│   └── utils/            # Utilities and helper functions
├── public/               # Static files (images, fonts, etc.)
├── tests/                # Unit and integration tests
├── .astro/               # Astro-specific configuration
├── package.json          # Project dependencies and scripts
├── README.md             # Main project documentation
└── ARCHITECTURE.md       # Architecture document (this file)
```

## Conceptual Map

```plaintext
[Start]
    |
    v
[Components] ---> [Layouts] ---> [Pages]
    |                   |               |
    v                   v               v
[Styles]         [Utilities]     [Tests]
    |
    v
[Static Files]
```

This conceptual map shows how the different parts of the project are connected and how they flow together.

## Folder Descriptions

- **src/components/**: Contains reusable components like buttons, headers, etc.
- **src/layouts/**: Base layouts applied to pages.
- **src/pages/**: Contains the main project pages.
- **src/styles/**: CSS files or preprocessors like SCSS.
- **src/utils/**: Helper functions like date handling, validations, etc.
- **public/**: Static files that do not require processing.
- **tests/**: Tests to ensure code quality.

## Notes

- Ensure to maintain a modular structure to facilitate maintenance.
- Document each component and function to improve collaboration.

