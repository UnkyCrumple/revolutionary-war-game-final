# Revolutionary Soldier: A Survival Story

A history game for grades 4-6. Students choose a soldier, then survive 10 real battles of the American Revolution
(Lexington & Concord through Yorktown) using decisions, dice, maps, quizzes, journal entries, and a final reflection.

The whole game is ONE file: `index.html`. No installs, no libraries, no internet needed once it loads.

## Test it on your computer
Double-click `index.html`. It opens in your browser and works right away.

## Put it on GitHub Pages (free hosting)
1. Sign in at github.com and click **New repository**. Name it (for example `revolutionary-soldier`), set it to **Public**, and click **Create repository**.
2. Click **uploading an existing file**, drag in `index.html` (and this README if you like), then click **Commit changes**.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait 1-2 minutes. Your game will be at `https://YOUR-USERNAME.github.io/revolutionary-soldier/`. Share that link with students.

To update the game later, upload a new `index.html` to the repository and commit; the site refreshes in a minute or two.

## How students turn in work
At the end, students can **Download results (.txt)**, **Print / Save as PDF**, or **Copy results**. Progress also auto-saves in the browser on the same computer.

## Customizing
Open `index.html` in a text editor and search for:
- `const BATTLES` - all battle text, choices, quizzes
- `const ATTRIBUTES` / `const SUPPLIES` - skills and supplies and their bonuses
- `const REFLECTIONS` - final reflection questions
- `NEED_ADJUST` - make the dice easier (higher number) or harder (lower number)
