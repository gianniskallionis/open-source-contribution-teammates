
# Open Source Contribution – TEAMMATES

## About the Project
TEAMMATES is a peer evaluation management system developed by the 
National University of Singapore (NUS), used by hundreds of universities worldwide.

🔗 https://github.com/TEAMMATES/teammates

## Issue
Added expand/collapse all buttons to the **student feedback submission page**, 
mirroring existing functionality from the instructor form.

GitHub Issue: [#13202](https://github.com/TEAMMATES/teammates/issues/13202)  
Pull Request: [#13603](https://github.com/TEAMMATES/teammates/pull/13603)

## What I Implemented
- `expandAllQuestions()` / `collapseAllQuestions()` methods in the TypeScript component
- Conditional buttons in the HTML template (show only when useful)
- 3 unit tests covering expand, collapse, and button visibility

## Tech Stack
| Layer    | Technology              |
|----------|-------------------------|
| Frontend | Angular (TypeScript)    |
| Backend  | Java (Spring Boot)      |
| Database | PostgreSQL              |
| Testing  | TestNG, Selenium (E2E)  |

## Screenshots
**View by Question – Expand All button (all collapsed):**
<img width="839" height="505" alt="image" src="https://github.com/user-attachments/assets/9368db55-a21a-4f22-b746-dddab9c6468e" />

**View by Question – Collapse All button (all expanded):**
<img width="900" height="635" alt="image" src="https://github.com/user-attachments/assets/f76d129c-4001-4701-9b85-7df1c6322e3d" />

**View by Recipients – Collapse All:**
<img width="776" height="556" alt="image" src="https://github.com/user-attachments/assets/7422423f-f9e4-4dcf-bee8-cba111e93a81" />

**View by Recipients – Expand All:**
<img width="863" height="602" alt="image" src="https://github.com/user-attachments/assets/ea88bec2-ab01-4b08-8238-2d882488f1a4" />
