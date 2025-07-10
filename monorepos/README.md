
# Where My Monorepos Go?

Welcome! 👋  
If you're looking for the example projects from the course, you're in the right place—but the structure has changed a bit to make things easier.

## 📁 Where Are the Lesson Projects?

All the **lesson folders have been moved to Git branches**.  
Inside each branch, the lesson folder is now located **in the root of the project**, instead of being nested inside a `monorepos/` folder.

This change makes it:
- ✅ Easier to switch between lessons
- ✅ Simpler to manage dependencies
- ✅ Cleaner to run and test each project independently

You no longer need to browse folders manually or dig through subdirectories. Just switch to a branch, and the project for that lesson will be ready in your workspace.

## 🧭 How to Access a Lesson

Each Git branch matches a specific lesson. To open one:

### 1. List Available Branches

In your terminal, run:

```bash
git branch -r
````

You'll see something like:

```
origin/01_01_Creating-your-first-monorepo
origin/01_02_Setting-up-config-files
origin/01_03_Adding-a-new-project
...
```

### 2. Switch to a Branch

To work on a lesson, switch to the corresponding branch:

```bash
git checkout <branch-name>
```

_Example:_

```bash
git checkout 01_02_Setting-up-config-files
```

---

## 🔄 Want the Original Version?

To see the starting point or the original monorepo structure, switch back to the `main` branch:

```bash
git checkout main
```

---

## 💡 Useful Tips

- Make sure you’ve cloned the repository first:
    
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
    
- If you’re switching branches for the first time, you may need to fetch them:
    
    ```bash
    git fetch --all
    ```
    
- After switching, don’t forget to install dependencies:
    
    ```bash
    npm install
    ```