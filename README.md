# css-fundamentals-lab

## git command used in this lab 
Part 1: การเตรียมโปรเจค
git clone https://github.com/Supakan06/web-semantic-lab
git add . 
git commit -m  "init project"
git push

Part 2: index.html
git checkout -b feature/main
git add index.html
git commit -m "create main page"

Part 3: CSS Selectors และ Specificity
git checkout -b feature/css
git add css/styles.css
git commit -m "add basic CSS selectors"

Part 4: Box Model
git add css/styles.css
git commit -m "add box model styles"

Part 5: Flexbox Layout
git add css/styles.css
git commit -m "add flexbox layouts" 

Part 6: merge branch
git checkout main
git merge feature/main
git merge feature/css
git push origin main