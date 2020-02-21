# Use TypeScript everywhere (without compilation step)

> 🎒 this article uses following library versions:

```json
{
  "@types/react": "16.x.x",
  "@types/react-dom": "16.x.x",
  "typescript": "3.x.x",
  "react": "16.5.2",
  "react-dom": "16.5.2"
}
```

> 🎮 [source code can be found on my github profile](https://github.com/Hotell/blogposts/tree/master/{date}/{title})

---

## {Subtitle}

---

<!-- Main -->

### Outline

1. we use typescript - everything should be typed

- node scripts
- configs (webpack/linters/jest)

2. How do you use TypeScript for these things

- typescript run via ts-node
- compile tsc to js, then run vanilla JS
- vanilla JS with JSDoc and @ts-check

  2.1 describe all of those options + drawbacks

3. mitigating all previous issues

- `@babel/register`
- module structure
- configuration
- `__dirname` issues and solutions
- don't use for production code !

4. So how do you type-check within pipeline ?

- `tsc` on commit
- `tsc` on CI

<!-- /Main -->

<!-- Footer -->

As always, don't hesitate to ping me if you have any questions here or on Twitter (my handle [@martin_hotell](https://twitter.com/martin_hotell)) and besides that, happy type checking folks and 'till next time! Cheers! 🖖 🌊 🏄

<!-- /Footer -->

---
