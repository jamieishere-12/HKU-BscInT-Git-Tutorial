# HKU BscInT Git & GitHub Tutorial

Welcome! Follow these steps to practice branching, committing, and pushing your code.

## Step-by-Step Instructions

1. **Clone the repository** to your laptop:
   ```bash
   git clone https://github.com/kennethcptang/HKU-BscInT-Git-Tutorial.git
   cd HKU-BscInT-Git-Tutorial
   ```

2. **Create your own branch** (use your name or HKU UID):
   ```bash
   git checkout -b student-yourname
   ```

3. **Make your change:**
   - Open `index.html` in your code editor.
   - Add a new `<li>Your Name - Hello World!</li>` line inside the `<ul>` list.
   - Save the file.

4. **Stage and commit your work:**
   ```bash
   git add index.html
   git commit -m "Add YourName to attendance list"
   ```

5. **Push your branch to GitHub:**
   ```bash
   git push -u origin student-yourname
   ```

6. **Open a Pull Request:**
   - Go back to this GitHub page in your browser.
   - Click **Compare & pull request** to submit your branch!

