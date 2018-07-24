# learn-web-tech
A plan for teaching / learning web technologies and react.js.

# Resources
- https://developer.mozilla.org/
- https://www.w3schools.com/
- https://reactjs.org

# Tools
- Your favorite browser
- Visual Studio Code
- Git
- Node.js
- NPM

# Simple applications for practice
- Calculator
  - Expression input
  - Digit buttons
  - Operations buttons (+, -, *, /, =)
- Chat
  - Message input
  - Send button
  - Chat log
- Notes
  - Note input
  - Add note button
  - Notes list
  - Remove note button
  - Reorder note
- Timer / Countdown
  - Time display / input
  - Start button
  - Stop button
  - Reset button
- Data table
  - Inserting
  - Editing
  - Removing
  - Pagination
  - Searching
  - Sorting
  - Reordering
  - Spoilers
- Color picker
  - Color palette
  - Color values slider
  - RGB display
  - HSL display
- Calendar
  - Year view
  - Month view
  - Date display
  - Date navigation
  - Event creation
- Clock
  - Digital mode
  - Analogic mode
  - Alarm
  - World time display
  - Date display
- Weather app
  - Location selection
  - Time selection
  - Open service data fetch
  - Weather description
  - Temperature display
  - Wind speed display
  - Humidity display
- Tic-Tac-Toe game
  - Grid display
  - XO set
  - Game reset button
  - Win message

----------

# 1. HTML
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML
## 1.1 General description
- What is HTML? - Hyper Text Markup Language
- Simple HTML document
- What is a tag?
- What is an attribute?
## 1.2 History of HTML
- 1.0 - 1993 (first draft 1991)
- 2.0 - 1995
- 3.2 - 1997 - first W3C standard (3.0 was proposed but did not succeeded)
- 4.0 - 1997 - 1998
- 4.01 - 1999
- XHTML - 2000
- 5.0 - 2014 (first draft 2008)
- 5.1 - 2016
- 5.2 - 2017
- Future
## 1.3 Main tags
- &#60;html&#62;&#60;/html&#62;
- &#60;head&#62;&#60;/head&#62;
- &#60;body&#62;&#60;/body&#62;
## 1.4 Metadata
- &#60;title&#62;&#60;/title&#62;
- &#60;meta&#62;&#60;/meta&#62;
- &#60;link&#62;&#60;/link&#62;
## 1.5 Global attributes
- class
- id
- style
- title
## 1.6 Block elements
## 1.7 Inline elements
## 1.8 Document sections
- &#60;header&#62;&#60;/header&#62;
- &#60;nav&#62;&#60;/nav&#62;
- &#60;main&#62;&#60;/main&#62;
- &#60;aside&#62;&#60;/aside&#62;
- &#60;footer&#62;&#60;/footer&#62;
- &#60;section&#62;&#60;/section&#62;
- &#60;article&#62;&#60;/article&#62;
- &#60;div&#62;&#60;/div&#62;
## 1.9 Hyperlinks
- download
- href
- target
## 1.10 Forms
- &#60;form&#62;&#60;/form&#62;
- &#60;input&#62;&#60;/input&#62;
- &#60;button&#62;&#60;/button&#62;
- &#60;select&#62;&#60;/select&#62;
- &#60;option&#62;&#60;/option&#62;
- &#60;textarea&#62;&#60;/textarea&#62;
- action
- enctype
- method
- name
- target
- type
## 1.11 Images
- alt
- height
- src
- width
## 1.12 Tables
- &#60;table&#62;&#60;/table&#62;
- &#60;thead&#62;&#60;/thead&#62;
- &#60;tbody&#62;&#60;/tbody&#62;
- &#60;tfoot&#62;&#60;/tfoot&#62;
- &#60;tr&#62;&#60;/tr&#62;
- &#60;th&#62;&#60;/th&#62;
- &#60;td&#62;&#60;/td&#62;
- colspan
- rowspan
## 1.13 Lists
- &#60;ul&#62;&#60;/ul&#62;
- &#60;ol&#62;&#60;/ol&#62;
- &#60;li&#62;&#60;/li&#62;
## 1.14 Headings &#60;h*&#62; &#60;/h*&#62;
## 1.15 Multimedia and embedding
- &#60;iframe&#62;&#60;/ifram&#62;
- &#60;video&#62;&#60;/video&#62;
- &#60;audio&#62;&#60;/audio&#62;
- &#60;embed&#62;&#60;/embed&#62;
- &#60;object&#62;&#60;/object&#62;
## 1.16 Comments
----------

# 2. CSS
https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS
## 2.1 General description
- What is CSS? - Cascading Style Sheets
- Simple style sheet
- How CSS works with HTML
- What is a rule?
- What is a selector?
## 2.2 History of CSS
- Release 1996 (first proposal 1994)
- Level 2 - 1998
- Level 2.1 - 2004 - 2011
- Level 3 - 2011 - 2012 (first draft 1999)
- Level 4 - 2007 - ...
- Future
## 2.3 Syntax
- Property
- Value
## 2.4 Selectors
- Simple selectors
  - Type selectors
  - Class selectors
  - Id selectors
  - Universal selector "\*"
- Attribute selectors
  - Attribute presence
  - Attribute substring
- Pseudo-selectors
  - :not()
  - :first-child()
  - :last-child()
  - :nth-child()
  - :nth-last-child()
  - :hover
- Pseudo-elements
  - ::after
  - ::before
- Combinators
  - Descendant selector
  - Child selector
  - Adjacent sibling selector
  - General sibling selector
- Multiple selectors
## 2.5 Cascade
- Source order
- Specificity
- Importance
## 2.6 Units
- absolute length units
  - pixels (px)
  - points (pt)
  - millimeters (mm)
  - centimeters (cm)
- relative length units
  - percentage (%)
  - vh
  - vw
  - vmin
  - vmax
  - em
  - rem
- unitless values
## 2.7 Colors
- RGB
- HSL
- RGBA
- HSLA
## 2.8 Box model
- width
- height
- padding
- border
- margin
- box-sizing
## 2.9 Box styling
- Background
  - color
  - image
  - position
  - repeat
  - size
- Border
  - color
  - style
  - width
  - radius
  - image
## 2.10 Text styling
- Color
- Font
  - family
  - size
  - style
  - weight
  - transform
  - decoration
- Alignment
- Line Height
- Spacing
  - letter spacing
  - word spacing
## 2.11 Layout
- Normal flow
- display property
- position property
- Flexbox
- Grid
- table layout
- floats
----------

# 3. JS
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction
http://javascript.info/
## 3.1 General description
- What is JS? - JavaScript
- Simple JS script
- How JS works with HTML and CSS?
- Language philosophy
## 3.2 History of JS
- ES1 - 1997 (first implementation 1995)
- ES2 - 1998
- ES3 - 1999
- ES4 - 1999 - 2008 (never released)
- ES5 - 2009
- ES6/2015
- ES2016
- ES2017
- ES2018
- ES.NEXT
## 3.3 Grammar and types
- Comments
  - Single-line comment
  - Multi-line comment
- Variable and constant declarations
- Data types
  - Boolean
  - Number
  - String
  - Undefined
  - Symbol
  - Object
  - Function
- Literals
  - Array literals
  - Boolean literals
  - Floating-point literals
  - Integers
  - Object literals
  - RegExp literals
  - String literals
## 3.4 Control flow and error handling
- Block statement
- Conditional statements
  - if...else statement
  - switch statement
- Exception handling statements
  - throw statement
  - try...catch statement
- Promises
## 3.5 Loops and iteration
- for statement
- do...while statement
- while statement
- labeled statement
- break statement
- continue statement
- for...in statement
- for...of statement
## 3.6 Functions
- Defining functions
  - Function declarations
  - Function expressions
  - Arrow functions
- Calling functions
- Function anatomy
## 3.7 Expressions and operators
- Operators
  - Assignment operators
  - Comparison operators
  - Arithmetic operators
  - Bitwise operators
  - Logical operators
  - String operators
  - Conditional (ternary) operator
  - Comma operator
  - Unary operators
  - Relational operators
- Operator precedence
- Expressions
  - Primary expressions
  - Left-hand-side expressions
## 3.8 Numbers and dates
- Numbers
  - Decimal numbers
  - Binary numbers
  - Octal numbers
  - Hexadecimal numbers
  - Exponentiation
- Number object
- Math object
- Date object
## 3.9 Text formatting
- Strings
- Template literals
## 3.10 Regular Expressions
## 3.11 Indexed collections
- Array
- Typed Arrays
## 3.12 Keyed collections
- Map
- WeakMap
- Set
- WeakSet
## 3.13 Objects
- object initializers
- properties and methods
- getters and setters
- deleting properties
- comparing objects
- Object.assign()
- Object.create()
- Object.defineProperty()
- Object.defineProperties()
- Object.freeze()
- Object.seal()
- Object.entries()
- Object.keys()
- Objet.values()
## 3.15 Classes
- constructor
- properties and methods
- getters and setters
- inheritance
- static
- future proposals
## 3.14 JSON
## 3.16 Iterators and generators
## 3.17 Meta programming
- Proxy
- Reflexion
----------

# 4. Web APIs
https://developer.mozilla.org/en-US/docs/Web/API
## 4.1 Window
- .console
- .document
- .fullScreen
- .history
- .location
- .localStorage
- .name
- .navigator
- .opener
- .parent
- .performance
- .screen
- .status
- .alert()
- .blur()
- .close()
- .confirm()
- .find()
- .focus()
- .getComputedStyle()
- .getSelection()
- .open()
- .moveTo()
- .moveBy()
- .print()
- .prompt()
- .requestAnimationFrame()
- .requestIdleCallback()
- .setTimeout()
- .setInterval()
## 4.2 Console
- .log()
- .error()
- .info()
- .warn()
- .trace()
- .count()
- .group()
- .table()
- .time()
- .clear()
## 4.3 Document
- .body
- .head
- .links
- .forms
- .images
- .scripts
- .styleSheetSets
- .documentElement
- .cookie
- .domain
- .location
- .readyState
- .referrer
- .title
- .activeElement
- .fullscreenElement
- .getElementById()
## 4.4 History
- .length
- .back()
- .forward()
- .go()
- .pushState()
- .replaceState()
## 4.5 Location
- .href
- .protocol
- .host
- .hostname
- .port
- .pathname
- .search
- .hash
- .assign()
- .reload()
- .replace()
## 4.6 Storage
- .length
- .key()
- .getItem()
- .setItem()
- .removeItem()
- .clear()
## 4.7 Navigator
- .appCodeName
- .appName
- .appVersion
- .battery
- .connection
- .geolocation
- .oscpu
- .platform
- .userAgent
- .getUserMedia()
## 4.8 Performance
- .mark()
- .measure()
- .now()
- .getEntries()
- .clearMarks()
- .clearMeasures()
## 4.9 Screen
- .width
- .height
- .left
- .top
- .availWidth
- .availHeight
- .availLeft
- .availTop
- .orientation
- .pixelDepth
## 4.10 EventTarget
- .addEventListener()
- .removeEventListener()
- .dispatchEvent()
## 4.11 Node
- .nodeName
- .nodeType
- .nodeValue
- .childNodes
- .firstChild
- .lastChild
- .nextSibling
- .previousSibling
- .parentNode
- .appendChild()
- .cloneNode()
- .contains()
- .insertBefore()
- .removeChild()
- .replaceChild()
## 4.12 Element
- .tagName
- .attributes
- .classList
- .className
- .clientWidth
- .clientHeight
- .clientLeft
- .clientTop
- .id
- .innerHTML
- .outerHTML
- .scrollWidth
- .scrollHeight
- .scrollLeft
- .scrollTop
- .getAttribute()
- .setAttribute()
- .hasAttribute()
- .closest()
- .getBoundingClientRect()
- .getClientRects()
- .getElementsByClassName()
- .getElementsByTagName()
- .querySelector()
- .querySelectorAll()

##4.13 Concurrency model and Event Loop
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop
- https://youtu.be/8aGhZQkoFbQ
----------

# 5. React
https://reactjs.org/docs/getting-started.html
## 5.1 General description
- What is React and ReactDOM?
- What is JSX?
- What is a component?
- Simples react example
- React philosophy
## 5.2 JSX
- Why using JSX?
- Adding expressions in JSX
- Specifying attirbutes and childrens in JSX
- JSX translation to plain JS
## 5.3 Functional components and class components
## 5.4 Rendering / composing / splitting components
## 5.5 Props and state
- setState()
- forceUpdate()
## 5.6 Lifecycles
- Mounting
  - constructor()
  - static getDerivedStateFromProps()
  - render()
  - componentDidMount()
- Updating
  - static getDerivedStateFromProps()
  - shouldComponentUpdate()
  - render()
  - getSnapshotBeforeUpdate()
  - componentDidUpdate()
- Unmounting
  - componentWillUnmount()
- Error Handling
  - componentDidCatch()
## 5.7 Handling events
- Synthetic events
## 5.8 Multiple children and keys
## 5.9 Forms
- Controlled components
## 5.10 Fragments
## 5.11 Refs
- React.createRef()
- React.forwardRef()
## 5.12 Context
- Provider
- Consumer
## 5.13 Portals
