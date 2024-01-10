# CHANGELOG - 10xCSS

__Legend__

```
  ❖ = demo.10xCSS.com
  ★ = sponsor.10xCSS.com
```
<!-- 
  __`new`__ - New component/style
  __`add`__ - Add style/property to existing
  __`fix`__ - Corrections made
  __`del`__ - Style/property removed or deprecated
  __`mod`__ - Modifications or updates to existing
 -->


__TOC__

<!-- MDTOC auto="2" levels="1,2" -->

- [v0.0.3](#v003) _[in-progress]_
- [v0.0.2](#v002) _`BREAKING` LoaderBall_
- [v0.0.1](#v001)

<!-- /MDTOC -->

--- 

<br />



## v0.0.3

> __[in-progress]__ <br/>
> DEMO: [d003.10xCSS.com](https://d003.10xCSS.com) <br/>
> SPONSOR: [s003.10xCSS.com](https://s003.10xCSS.com) <br/>


### Components
- ★ __`new`__ [Pattern Graph Paper](https://sponsor.10xCSS.com/dashboard/presets?cid=PatternGraphPaper) - Graph paper pattern
- ★ __`new`__ [Pattern Waves Rippled](https://sponsor.10xCSS.com/dashboard/view?cid=PatternWavesRippled&uid=PatternWavesRippled__default) - Pattern of waves rippled
- ★ __`new`__ [Pattern Circle Howling](https://sponsor.10xCSS.com/dashboard/view?cid=PatternCircleHowling&uid=PatternCircleHowling__default) - Pattern of circles howling
- __`add`__ [Modern Font Stacks](https://github.com/system-fonts/modern-font-stacks) - `transition`, `old-style`, `humanist`, `geometric`, `classical`, `neo-gro`, `mono-slab`, `industrial`, `round-sans`, `slab-serif`, `antique`, `didone`, `hand`


### Styles
- ❖ __`new`__ [LoaderBall__zerostyle](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__zerostyle) - An initial zero/blank style for the #cssexp series
- ★ __`new`__ [PatternGraphPaper__default](https://sponsor.10xCSS.com/dashboard/view?cid=PatternGraphPaper&uid=PatternGraphPaper__default) - A graph paper pattern
- ★ __`new`__ [PatternGraphPaper__pressf](https://sponsor.10xCSS.com/dashboard/view?cid=PatternGraphPaper&uid=PatternGraphPaper__pressf) - To pay respects to graph paper
- ★ __`new`__ [PatternGraphPaper__tictactoe](https://sponsor.10xCSS.com/dashboard/view?cid=PatternGraphPaper&uid=PatternGraphPaper__tictactoe) - No description needed
- ★ __`new`__ [PatternWavesRippled__default](https://sponsor.10xCSS.com/dashboard/view?cid=PatternWavesRippled&uid=PatternWavesRippled__default) - A WavesRippled pattern
- ★ __`new`__ [PatternWavesRippled__art](https://sponsor.10xCSS.com/dashboard/view?cid=PatternWavesRippled&uid=PatternWavesRippled__art) - A artful WavesRippled pattern
- ★ __`new`__ [PatternWavesRippled__artempty](https://sponsor.10xCSS.com/dashboard/view?cid=PatternWavesRippled&uid=PatternWavesRippled__artempty) - Does artful WavesRippled pattern look better empty?
- ★ __`new`__ [PatternCircleHowling__default](https://sponsor.10xCSS.com/dashboard/view?cid=PatternCircleHowling&uid=PatternCircleHowling__default) - A pattern of circles howling
- ★ __`new`__ [PatternCircleHowling__flipped](https://sponsor.10xCSS.com/dashboard/view?cid=PatternCircleHowling&uid=PatternCircleHowling__flipped) - The pattern flipped around
- ★ __`new`__ [PatternCircleHowling__groovyvanity](https://sponsor.10xCSS.com/dashboard/view?cid=PatternCircleHowling&uid=PatternCircleHowling__groovyvanity) - A vanity mirror shape of groovy-ness


_-----------------------------------------------------------------------------_

### Documentation
- ❖ Note the version number link on the bottom-left SideNav to open the [CHANGELOG](https://github.com/10xCSS/CHANGELOG) version

### Features
- __`new`__ Select widget [transform-origin](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-origin)
- __`new`__ Zoom component for share.10xCSS.com, enhancing mobile and general aesthetics

### Fixes
- Incorrect initial background on share.10xCSS.com clone/create style

### Refactor
- ❖ Replace title ` | ` with ` / ` for schema unification
- Update share.10xCSS.com mobile styles


<br />
<br />


## v0.0.2

> __2024-01-06__ <br/>
> DEMO: [d002.10xCSS.com](https://d002.10xCSS.com) <br/>
> SPONSOR: [s002.10xCSS.com](https://s002.10xCSS.com)


### BREAKING
- ❖ [LoaderBall](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall) - Updated naming schema, and  move from/to properties into own groups 
  + __`removed`__
    - `ball-border-radius-min` → does more harm than good with `scale-x`
    - `ball-border-radius-min` → does more harm than good with `scale-x`
  + __`renamed`__
    - `ball-size` → `base-ball-size`
    - `ball-rotate` → `base-bounce-rotation`
    - `ball-bounceY` → `base-bounce-y`
    - `shadow-width` → `base-shadow-height`
    - `shadow-scaleX` → `shadow-from-to-from-scale-x`
    - `shadow-scaleXMin` → `shadow-from-to-to-scale-x`
    - `shadow-background`
      + `shadow-from-to-from-background`
      + `shadow-from-to-to-background`

_-----------------------------------------------------------------------------_

### Components
- ❖ __`add`__ [LoaderBall](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall) - [@keyframes](https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes) property to toggle between @keyframes from/to and percentage-based rules

### Styles
- ❖ __`del`__ [LoaderBall__imnotsure](https://d001.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__imnotsure)
- ❖ __`new`__ [LoaderBall__default](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__default) - The default LoaderBall style
- ❖ __`new`__ [LoaderBall__defaultreverse](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__defaultreverse) - The default LoaderBall style, but in reverse
- ❖ __`new`__ [LoaderBall__defaultinverted](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__defaultinverted) - The default LoaderBall style, but inverted
- ❖ __`new`__ [LoaderBall__almost](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__almost) - A loader animation that almost rotates
- ❖ __`new`__ [LoaderBall__alternate](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__alternate) - LoaderBall style that alternates rotate fall direction
- ❖ __`new`__ [LoaderBall__ballin](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__ballin) - A proper bouncing ball, that’s ballin
- ❖ __`new`__ [LoaderBall__chatty](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__chatty) - A chat-bubble loader, response notification, or just on-hold animation
- ❖ __`new`__ [LoaderBall__cosmopolitan](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__cosmopolitan) - A cosmopolitan, presumably enjoyed on your yacht out at sea
- ❖ __`new`__ [LoaderBall__fromto](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__fromto) - A Flip Cup loader to demonstrate from/to @keyframes
- ❖ __`new`__ [LoaderBall__onceasquare](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__onceasquare) - Always a square, fitting squarely inside the mold
- ❖ __`new`__ [LoaderBall__paused](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__paused) - A paused loader style (may appear incorrectly in the dashboard preview)
- ❖ __`new`__ [LoaderBall__romancandle](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__romancandle) - A roman candle firework-like style
- ❖ __`new`__ [LoaderBall__spinningcircle](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__spinningcircle) - A simple, bounce-free spinning circle loader
- ❖ __`new`__ [LoaderBall__spinningdashes](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__spinningdashes) - A simple loader with bounce-free spinning dashes
- ❖ __`new`__ [LoaderBall__spinningdots](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__spinningdots) - A simple loader with bounce-free spinning dots
- ❖ __`new`__ [LoaderBall__spinningfast](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall&uid=LoaderBall__spinningfast) - A fast loader guaranteed to boost your JS app's speed by 1000hp


_-----------------------------------------------------------------------------_

### Documentation
- ❖ Make note of the dated walk-through video

### Features
- ★ Static demo/sponsor application links
- Include share URL in CSS meta comment `share: <url>`
- Include 10xCSS app version in CSS meta comment `ver: d0.0.2`

### Fixes
- Hashing function that invalidated share images when nothing had changed on reload
- Limit `cubic-bezier` functions to 4 decimal places
- Animation Bezier widget custom ease button overlap

### Refactor
- ★ Remove SideNav logos
- Use single-value notation for `border-radius` when all values are the same

<br />
<br />


## v0.0.1

> __2024-01-02__ <br/>
> DEMO: [d001.10xCSS.com](https://d001.10xCSS.com) <br/>
> SPONSOR: [s001.10xCSS.com](https://s001.10xCSS.com)


### Components
- ★ __`new`__ [TwoDivs](https://sponsor.10xCSS.com/dashboard/presets?cid=TwoDivs) - similar to [ASimpleBox](https://demo.10xCSS.com/dashboard/presets?cid=ASimpleBox) but features two `div` elements
- ❖ __`fix`__ [LoaderBall](https://demo.10xCSS.com/dashboard/presets?cid=LoaderBall) - added missing `box-sizing` property

### Styles
- ★ __`new`__ [TwoDivs/Default](https://sponsor.10xCSS.com/dashboard/presets?cid=TwoDivs&uid=TwoDivs__default) style


_-----------------------------------------------------------------------------_


### Features
- Current version of the application displayed at the bottom of SideNav, linked & labeled as `vX.X.X`
  + ❖ Links to CHANGELOG 
  + ★ Links to static version of the app for reference, stability, and consistency

### Init
  - [github.com/10xCSS/CHANGELOG](https://github.com/10xCSS/CHANGELOG)
  - ★ [sponsor.10xCSS.com](https://sponsor.10xCSS.com)
  - ★ [github.com/10xCSS/sponsor](https://github.com/10xCSS/sponsor)


