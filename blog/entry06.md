# Entry 6
##### 5/26/25

### Context
---
I'm using my tool to help me use it in my freedom project of a garden game with my teamates, Kiara and Robert. We all have different tools but we are going to mange to combine al out tools together and make a amazing game. My tool is [Kaboom](https://kaboomjs.com/doc/setup) and my parther's tools are very cool and unique. 

We were able to make our main menu which was using my tool Kaboom for out beyond MVP. It was a lot of struggles and challenges that I was facing which was a lot of trouble and after alot of crashes while working on the main menu, it finally worked on a chromobook and nothing my macbook. It was showing many errors that had to be fixed asap and we did! We were also able to make our game connected since me and kiara had used different tools to make the game combined together. 

But after all the crashes and errors, our game had finally come alive! The game has the main menu, instructions and the main game for our gardening or aka falling fruits! Challenges were faced but we were definitly ready to face them to resolve the problem.

### My Main Main Code
```JS
import kaboom from "https://unpkg.com/kaboom@3000.0.1/dist/kaboom.mjs";

kaboom({
    background: [141, 183, 255],
})

     loadSprite("Menu", "sprites/garden-background (3).png");
            add([
                sprite("Menu"),
                pos(center().sub(0.1, 0)),
                scale(0.9),
                anchor("center"),
            ]);
            add([
                text("Welcome to the Garden!"),
                color(18, 1, 255),
                pos(center().sub(0.5, 100)),
                scale(2.2),
                anchor("center"),
            ]);
            add([
                text("Press Mouse to play!"),
                color(18, 1, 255),
                pos(center().sub(0.5, 0.5)),
                scale(2.2),
                anchor("center"),
            ]);

            onMousePress(() => {
            location = "Instructions.html";

            });

```

### My Instruction Code
```JS
import kaboom from "https://unpkg.com/kaboom@3000.0.1/dist/kaboom.mjs";

kaboom({
	background: [141, 183, 255],
})

     loadSprite("Menu", "sprites/garden-background (3).png");
            add([
                sprite("Menu"),
                pos(center().sub(0.1, 0)),
                scale(0.9),
                anchor("center"),
            ]);
            add([
                text("Instructions!"),
				color(18, 1, 255),
                pos(center().sub(0.5, 100)),
                scale(1.15),
                anchor("center"),
            ]);
            add([
                text("Collect the fruits!"),
				color(18, 1, 255),
                pos(center().sub(0.5, 0.5)),
                scale(1.5),
                anchor("center"),
            ]);
            add([
                text("Avoid the bugs!"),
				color(18, 1, 255),
                pos(center().sub(0.5, -70)),
                scale(1.5),
                anchor("center"),
            ]);
                add([
                text("Use the pattle to move side by side"),
				color(18, 1, 255),
                pos(center().sub(0.5, -150)),
                scale(1.5),
                anchor("center"),
            ]);



            onMousePress(() => {
            location = "mini-game.html";

            });
```
### Engineering Design Process (EDP)
---
We finished 2,3,4,5,and 6. We were brainstorming from the problems of errors and challenges that we were facing while working on the project all together. Hard or easy mistakes, one small mistake can always lead to one big or huge mistake to the game. We planned it all during spring break and worked on it during and after and kept working on our project. We tested and tested to see how it would be an outcome of the game. Soon everything will be done and we will easily move to improving our game for 7 and 8.

### Skills
---
### Distractions 

I can get distracted by little things which made me lose my focus on what I would need to get done really quickly which is pretty annoying but I would still be mangeable to get my work done when I don't look on my phone or anything else but just working and working with my headphones in with some classic jazz music.

---

## Takeaways

We had communicated and as we should, and now after communicating, I feel like now I can take bigger steps into the project to making it slowly better and better. In the future, hopefully I would be half-way done with my level if I can and being able to combine all our work together. 


[Home](../README.md)
