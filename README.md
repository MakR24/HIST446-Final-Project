# HIST 446 Final Projects

This repository holds everyone's final project for HIST 446, *The Past as Data*. Each of you works in your own copy (a fork), and you receive new files from me the same way you do in `HIST446-Worksheets`.

## What's in here

```
HIST446-Final-Project/
├── README.md                    ← this file
├── HIST446-Final-Project.Rproj  ← open this to start working
├── .gitignore                   ← one file for the whole class (don't edit it)
├── Anglin_Workspace.qmd        
├── Cole_Workspace.qmd
├── Huneryager_Workspace.qmd
├── Matney_Workspace.qmd
├── Ramon_Workspace.qmd
├── Rojas_Workspace.qmd
├── Tan_Workspace.qmd 
├── Tanglertpaibul_Workspace.qmd  
├── data/                         
│   ├── anglin/                  
│   ├── cole/
│   ├── huneryager/
│   ├── matney/
│   ├── ramon/
│   ├── rojas/
│   ├── tan/
│   ├── tanglertbaipul/           
└── output/                       
    ├── anglin/                  
    ├── cole/                     
    └── ...
```

- **`Lastname_Workspace.qmd`** is your workspace: it walks you through the first steps to get started with data processing for your project, with code to run and space for your answers. If I make more files for you later, they'll follow the same pattern (`Lastname_Topic.qmd`).
- **`data/lastname/`** holds your datasets: the sources you download, and every dataset you make from them by cleaning, processing or counting.
- **`output/lastname/`** holds what you make to show: charts, maps, and your writing.

Keep the `.qmd` files at the top level, where they are. Their code looks for `data/` and `output/` starting from the folder the file is in, so moving a file into a folder breaks its paths.

## 1. Fork and clone this repository

1. At the top right of this page, click **Fork**. This makes your own copy of the repository under your GitHub account.
2. On your fork's page, click the green **Code** button, then **Open with GitHub Desktop**.
3. When GitHub Desktop asks where to put the folder, choose `Desktop/HIST-446/`, beside your `HIST446-Worksheets/` folder.
4. GitHub Desktop will ask how you plan to use the fork. Choose **To contribute to the parent repository**. This is what lets you receive my new files later.

## 2. Open the project

Open the folder and double-click **`HIST446-Final-Project.Rproj`**. RStudio opens with the project's folder as its starting point, which is what makes the paths in your workspace work. From now on, always open your workspace this way rather than opening the `.qmd` file directly.

Then open your own `Lastname_Workspace.qmd` from RStudio's **Files** pane and start with its Section 0.

## 3. Whose files are whose

You're welcome to read your classmates' workspaces: you might learn something from their methods. But **only edit your own files**: your workspace, and your folders in `data/` and `output/`. If you change someone else's file it could cause a conflict during your next update.

## 4. The `.gitignore` file

The `.gitignore` tells Git which files to leave off GitHub: sources we're not allowed to share (Freedom on the Move, IPUMS, musem pictures, oral histories), large files anyone can download again, and private notes. There's one for the whole class, so it lists things that each of you has and should not be public.

**Don't edit it.** I update it when needed. If you have something that should stay off GitHub and isn't covered, email me and I'll add it.

## 5. Save your work to GitHub

When you've made progress:

1. Save and **Render** your workspace in RStudio.
2. In **GitHub Desktop**, look at the list of changed files on the left. Everything there will go to GitHub, so check that nothing private or restricted is on it.
3. Write a short summary message for every commit (for example, "Section 5: geocoded places") and click **Commit to main**.
4. Click **Push origin**.

## 6. Getting my updates

When I announce new files for you, or an update to the `.gitignore`:

1. Open **GitHub Desktop** and make sure `HIST446-Final-Project` is selected at the top left.
2. Click **Fetch origin**.
3. Go to **Branch → Update from upstream/main**.
4. Click **Push origin** to bring your copy on GitHub up to date too.

**Your own work is safe.** This only adds my new files and changes. Everything you have written stays exactly as it was.
