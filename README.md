# Learning [Figma](https://www.figma.com)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

If you can't remember keyboard shortcuts or just want to search available actions, hit <kbd>command</kbd> + <kbd>/</kbd> (mac) **OR** <kbd>Ctrl</kbd> + <kbd>/</kbd> (pc).

Following tutorial: <https://www.youtube.com/watch?v=3q3FV65ZrUs> (But you might want to look at the short [official Figma intro tutorials playlist](https://www.youtube.com/watch?v=Cx2dkpBxst8&list=PLXDU_eVOJTx7QHLShNqIXL1Cgbxj7HlN4&index=1).)

Example Figma interative demo page: <https://www.figma.com/proto/dWPMZc0LYEkG7VB9uqUV6S/Figma-Tutorial?node-id=2%3A2&scaling=scale-down>

<a href="https://www.figma.com/proto/dWPMZc0LYEkG7VB9uqUV6S/Figma-Tutorial?node-id=2%3A2&scaling=scale-down" target="_blank"><img src="https://github.com/hchiam/learning-figma/blob/main/Figma_Tutorial.svg" width="600" alt="Image of Figma Tutorial Demo"/></a>

Example Figma project page: <https://www.figma.com/file/dWPMZc0LYEkG7VB9uqUV6S/Figma-Tutorial?node-id=0%3A1>

Another interactive demo (hover and click): <https://www.figma.com/proto/UTTgyhTIfjDeV5r0MQg0vU/First-Figma-File?node-id=2%3A13&scaling=contain>

And another, newer tutorial: <https://www.youtube.com/watch?v=t-2Gdmx0t08>

Learn Bravo to make native apps from Figma prototypes: <https://github.com/hchiam/learning-bravo-studio>

Note that Figma isn't just collaborative clean drawing or [making component instances update from one place](https://youtu.be/dXQ7IHkTiMM?feature=shared&t=703), it also has interactivity and the [components can be made responsive to frame resizing (constraints)](https://youtu.be/dXQ7IHkTiMM?feature=shared&t=725) and ["Auto Layout", which reminds me of CSS flexbox, but lets components expand/push down with new content like text while preserving a gap between](https://youtu.be/wvFd-z7jSaA?feature=shared&t=443).
- btw: contraints vs auto layout in Figma:
  - constraints: objects respond to parent frame changing
  - auto layout: parent frame responds to child objects changing
- and Figma also has [variables](https://help.figma.com/hc/en-us/articles/14506587589399-Use-variables-in-prototypes) and [conditionals](https://help.figma.com/hc/en-us/articles/15253220891799-Multiple-actions-and-conditionals#h_01H91GHXRHGN8K801ZZCPV99FA)

Tips on Figma components: [tips like how to organize and swap between components - pros/cons of separate state components vs nested (hidden) variations in single master components](https://medium.com/design-with-figma/10-tips-on-using-components-in-figma-c7db9c5e7fe1)
- [Create component > Add variant (default variant will be in top-left)](https://www.youtube.com/watch?v=0XSLMGh8yhM&list=PLXDU_eVOJTx6vqOWJSWH87Zb5-riiG63A&index=7)

**Prototype interaction** info: https://youtu.be/lTIeZ2ahEkQ?feature=shared&t=316
- **Anyone logged in to Figma can add comments** at the **prototype** view link.
- **You can do a usability test with Figma by seeing their interactions with the prototype!** Click on a viewer's avatar to use observation mode on the shared prototype view link.

Example components library (login, then see Assets and search): https://www.figma.com/file/HD9OYLfuDqWgaJ1JfScNZF/Example-Components-Library-(search-the-Assets)?type=design&node-id=0%3A1&mode=design&t=JAlvQci4xpWKErsT-1

"Figma for VS Code" extension so devs can collaborate from VSCode in real time, and get code suggestions based on Figma designs: https://marketplace.visualstudio.com/items?itemName=figma.figma-vscode-extension - NOTE: **in beta as of 2023**

Dev mode Figma to translate design to code faster (**in beta as of 2023**):
  - NON-dev mode (design mode) example: https://www.figma.com/file/UNYqpMVdlSlnjuBO20WRfr/Mobile-Wireframe-UI-Kit-(Community)?type=design&node-id=37-92&mode=design&t=rwE92hE52j9xtQIm-0
  - dev mode example: https://www.figma.com/file/UNYqpMVdlSlnjuBO20WRfr/Mobile-Wireframe-UI-Kit-(Community)?node-id=40%3A191&mode=dev (you need to be logged into Figma) with things like:
  - hover to inspect some things kinda like [DevTools](https://developer.chrome.com/docs/devtools/) or [VisBug](https://github.com/GoogleChromeLabs/ProjectVisBug)
  - click to copy generated code (CSS/HTML/JSX/Tailwind/etc.!) to clipboard
  - click to download icon SVGs

Design system / design tokens:
- [Tokens, variables, and styles - Update: Introduction to design systems](https://www.youtube.com/watch?v=JyCmacSyDY4&list=PLXDU_eVOJTx6vqOWJSWH87Zb5-riiG63A&index=9)
  - create linked style variables that are reusable and inheritable (can be implemented as CSS variables, i.e. CSS custom properties)
  - you can hide primitive values: right click > Edit variables > uncheck "Show in all supported properties" and check "Hide from publishing"
  - variable modes = "table" of alternate values in Figma, e.g. dark mode values LETS YOU SWITCH TO ALL DARK MODE VALUES QUICKLY IN FIGMA!!! Design > Local variables > add a column! Then you can switch to dark mode values of all variables with Design > Layer > Tokens: Dark.
- [open-props figma tokens](https://github.com/hchiam/figma-tokens-sync-example)

## A quick summary of other design tools:

From [Meng To](https://twitter.com/MengTo/status/1109203931580645377):

```text
My thoughts on design tools and why you should pick them.

Figma: collaboration and all-in-one
Sketch: maturity and plugins
Framer: code and advanced prototyping
Studio: free and animation
XD: speed and adobe platform
```

Or if you have more time, read a more involved analysis on [smashingmagazine.com](https://www.smashingmagazine.com/2019/04/sketch-figma-adobe-xd-ui-design-applications).

For creating images like SVGs, I'd use [Photopea](https://github.com/hchiam/learning-photopea)

While Figma is good for collaboration, you might want to consider [Storybook](https://github.com/hchiam/learning-storybook) instead for code and "live" components.

## You might also be interested in:

Lottie files for animations
- https://github.com/hchiam/learning-lottie
- via the [Lottie plugin](https://lottiefiles.com/plugins/figma) for Figma
- You might want to consider [Lottielab](https://www.lottielab.com) with/without Figma to generate [animations with curved paths](https://docs.lottielab.com/editor/canvas/layer-controls-huds/motion-path/curving-a-motion-path)
  - https://www.youtube.com/watch?v=j9KP44kj0gU
  - https://www.youtube.com/watch?v=LooU8K3UgNE
