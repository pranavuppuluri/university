# University

Coursework, intern tasks and practice projects from 2023, collected into one
place. Previously these were sixteen separate repositories; they are archived
here as folders so the work is kept without sixteen entries standing in for it.

Nothing here is maintained. It is a record.

## What's in it

### Web fundamentals

| Folder | What it is |
| --- | --- |
| `assignment1/` | Four CSS exercises — `csstask1`…`csstask4.html` |
| `assignment2/` | A static multi-page site with image assets |
| `tasks1/` | A single CSS exercise |
| `taskDemo/` | Early HTML/CSS task pages |

### React

Most of these started from Create React App, which is why several still carry
its default README.

| Folder | What it is |
| --- | --- |
| `React_Calculator-main/` | Calculator |
| `React_Age_Calculator-main/` | Age calculator |
| `React_Color_Picker-main/` | Colour picker |
| `React-tasks/` | A single-page task list |
| `API-main/` | Fetching and rendering from a public API |
| `Intern_React_Task-1-main/` | Internship task |
| `projectfrontend/` | Front end for a larger project |
| `trail/` | Practice app |
| `PortFolio-main/` | Portfolio site — most of its content is in `src/data/constants.js` |

### Backend and other

| Folder | What it is |
| --- | --- |
| `crudproject/` | Node + Express CRUD app — `controller/`, `model/`, `index.js` |
| `dice/` | Android dice roller in Kotlin, Gradle build |
| `SI-GuidedProject-580176-1695307239/` | SmartInternz guided project — a login page |

### University projects (2024)

Course projects and lab notebooks from 2024, in `university-projects/`. Each
folder has its own README. Datasets are not included.

| Folder | What it is |
| --- | --- |
| `arsenic-detection-swin/` | Swin transformer for arsenic detection, with CeiT, CaiT, DeiT, T2T and TnT comparisons |
| `speech-language-processing/` | Text classification comparison, BERT fine tuning, sentiment analysis, Watson speech to text |
| `medicine-side-effects/` | Side effects lookup over a medicine dataset, with architecture doc |
| `pose-estimation/` | OpenPose script and SimplePose training on COCO keypoints |
| `object-detection/` | YOLOv8 training and a CBAM attention CNN for drone images |

## Running demos

Five of these are served from this repository's GitHub Pages site:

**https://pranavuppuluri.github.io/university/**

| Demo | Source |
| --- | --- |
| [CSS exercises](https://pranavuppuluri.github.io/university/demos/assignment1/) | `projects/assignment1` |
| [JavaScript exercises](https://pranavuppuluri.github.io/university/demos/assignment2/) | `projects/assignment2` |
| [Task list](https://pranavuppuluri.github.io/university/demos/react-tasks/) | `projects/React-tasks` |
| [Internship task](https://pranavuppuluri.github.io/university/demos/intern-task-1/) | `projects/Intern_React_Task-1-main` |
| [Colour picker](https://pranavuppuluri.github.io/university/demos/color-picker/) | `projects/React_Color_Picker-main` |

The two React apps are built from source into `demos/`, with `homepage` set to
`.` so their assets resolve under the subpath. The other three are plain HTML and
are served as they are.

> These previously had their own repositories and their own Pages sites at
> `pranavuppuluri.github.io/<name>/`. Those URLs no longer resolve — the demos
> moved here.

## Notes on the archive

- Folders are **snapshots of the final state**, not full git histories. Each was
  its own repository with its own history before being collected here.
- `loginpage` was an empty repository and is not included.
- Two folders shipped a `.zip` duplicating source that sat beside it; those were
  dropped. `SI-GuidedProject-…` contained **only** a zip, so it was unpacked.
- `package-lock.json` files are kept as they were. They account for most of the
  repository size.
