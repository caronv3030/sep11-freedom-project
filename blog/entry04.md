# Entry 4
##### 3/22/25

### Context
---
I'm using my tool to help me use it in my freedom project of a garden game with my teamates, Kiara and Robert. We all have different tools but we are going to mange to combine al out tools together and make a amazing game. My tool is [Kaboom](https://kaboomjs.com/doc/setup) and my parther's tools are very cool and unique. We have a plan on how we would want the game to work but it's not the best right now since we are slowly working on it and slowly building the game slowly and slowly. However, over time we talked about the inputted in the game and the ones that we didn't want. Which had made the work easier for us to work on into building our ***Freedom Project*** with great confidence.

Recently, we have talked to each other about what's the next steps to take after what we are done with what parts we are working for each part that we assigned together to work on. Kiara had also worked on the background and it was a animation background and I was working on our average and basic background but with her having a animated background, we would both combined how we can input them together. Since the background is done for me, I would work on the level on the games using my tool of Kaboom, I used this [Youtube video](https://www.youtube.com/watch?v=wZpbTR7pYR0), that had helped me majorly of how it is suppose to become for my future game.

### Example Code of the Level for the Gardening game
---

```JS
export class Level {
  drawWaves(type, anim) {
    let offset = -100
    for (let i = 0; i < 21; i++) {
      add([sprite(type, { anim }), pos(offset, 600), scale(4), fixed()])
      offset += 64
    }
  }

  drawMapLayout(levelLayout, mappings) {
    const layerSettings = {
      tileWidth: 16,
      tileHeight: 12,
      tiles: mappings,
    }

    this.map = []
    for (const layerLayout of levelLayout) {
      this.map.push(addLevel(layerLayout, layerSettings))
    }

    for (const layer of this.map) {
      layer.use(scale(4))
    }
  }

  drawBackground(bgSpriteName) {
    add([sprite(bgSpriteName), fixed(), scale(4)])
  }
}
```

### Engineering Design Process (EDP)
---
I would say that we are still on the second stage, but slowly moving towards the third once we are able to discuss on how we are going to be able to combine our tools together since it seems that it may be a hard struggle for us but nothing in life will come easy. I will still be tinkering with [Kaboom](https://kaboomjs.com) while using replit for now. But hopefully by next time, I'll be able to be on the third stage of the process slowly building the process of a great gardening game. But now I'm taking bigger steps like the levels in the game.

### Skills
---
### Distractions 

I can get distracted by little things which made me lose my focus on what I would need to get done really quickly which is pretty annoying but I would still be mangeable to get my work done when I don't look on my phone or anything else but just working and working with my headphones in with some classic jazz music.

---

## Takeaways

We had communicated and as we should, and now after communicating, I feel like now I can take bigger steps into the project to making it slowly better and better. In the future, hopefully I would be half-way done with my level if I can and being able to combine all our work together. 



[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
