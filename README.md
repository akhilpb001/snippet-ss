# snippet-ss
A generic set of stylesheet classes - In css, less & scss formats


## Installation

`npm install --save snippet-ss`

- All the styles are originaly scripted in less, its then transpiled into css and scss by the build command
- All the transpiled scripts will be committed for ease at the user end

## Demo page / tests

`npm test`

## Transpiling less to css & scss

 `npm run build`

#### Only to css

  `npm run build:css`

#### Only to scss

  `npm run build:scss`


## Available style files, and classes in them
##### 1. reset - _Eric Meyer’s CSS Reset V2.0_

##### 2. no
  - no-mouse (alias - no-pointer)
  - no-select
  - no-display
  - no-visible
  - no-active
  - no-margin
  - no-padding
  - no-border
  - no-wrap

##### 3. effects
  - noise-bg
  - dotted-bg
  - diagonal-stripes-bg

##### 4. background
  - noise-bg
  - dotted-bg
  - diagonal-stripes-bg

##### 5. functions
  - opacity

##### 6. fix
  - clear-fix

##### 7. force-use
  - force-gpu
  - force-scrollbar - To replace OSx Lion’s hidden scroll-bar behavior. So that a scroll-bar is displayed whenever scrolling is possible. Supported only by webkit.

##### 8. fonts
  - serif-georgia
  - serif-times
  - serif-palatino
  - san-helvetica
  - san-verdana
  - san-arial
  - san-comic
  - san-impact
  - san-lucida
  - san-tahoma
  - san-trebuchet
  - mono-courier
  - mono-lucida