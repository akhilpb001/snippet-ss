# snippet-ss
A generic set of stylesheet classes - In css, less & scss formats


## Installation

`npm install --save snippet-ss`

- All the styles are originally scripted in less, its then transpiled into css and scss by the build command
- All the transpiled scripts will be committed for ease at the user end

## Demo page / tests

`npm test`
- The demo page (tests/index.html) must be built, and opened in your default browser.

## Transpiling less to css & scss

 `npm run build`

#### Only to css

  `npm run build:css`

#### Only to scss

  `npm run build:scss`


## Available style files, and classes in them
_Parameterised mixins would be available only in less & scss_

##### 1. reset - _Eric Meyer’s CSS Reset V2.0_

##### 2. no
  - .no-mouse [alias - no-pointer]
  - .no-select
  - .no-display
  - .no-visible
  - .no-active
  - .no-margin
  - .no-padding
  - .no-border
  - .no-wrap

##### 3. effects
_The glow is appended onto existing box-shadow value_
  - .outer-glow(@color)
  - .inner-glow(@color)
  - .shadow(@color)
  - .left-shadow(@color)
  - .right-shadow(@color)
  - .white-outer-glow
  - .white-inner-glow
  - .dark-shadow
  - .dark-left-shadow
  - .dark-right-shadow
  - .glass

##### 4. background
_Default background color is grey, you can change that in less using background-color or other related property. Also the pattern is appended onto existing patterns_
  - .noise-bg
  - .dotted-bg
  - .checker-bg
  - .diagonal-stripes-bg

##### 5. fix
  - .clear-fix

##### 6. force-use
  - .force-gpu - Just to force hardware acceleration for the element
  - .force-scrollbar - _To replace OSx Lion’s hidden scroll-bar behavior. So that a scroll-bar is displayed whenever scrolling is possible. Supported only by WebKit._

##### 7. x-browser - Some functions for making cross browser compatibility easy
  - .opacity(@opacity)
    - @opacity must be a value from 0 to 1
    - _Previously it was under functions file_

##### 8. fonts
  - .serif-georgia
  - .serif-times
  - .serif-palatino
  - .san-helvetica
  - .san-verdana
  - .san-arial
  - .san-comic
  - .san-impact
  - .san-lucida
  - .san-tahoma
  - .san-trebuchet
  - .mono-courier
  - .mono-lucida
