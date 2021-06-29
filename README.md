# React Animations

# ReactTransitionGroup

Exposes simple components useful for defining entering and exiting transitions. React Transition Group is not an animation library like React-Motion, it does not animate styles by itself. Instead it exposes transition stages, manages classes and group elements and manipulates the DOM in useful ways, making the implementation of actual visual transitions much easier.

Installation

npm install react-transition-group --save

# CSS Transitions

CSS transitions allows you to change property values smoothly, over a given duration.

# TransitionGroup

import TransitionGroup from "react-transition-group/TransitionGroup";
use TransitionGroup instead of ul (unordered list component)

TransitionGroup automaticaly sets in property: The special thing about transition group and essentially the only thing it does is it's able to handle multiple items. It determines whenever one element in the list changes if it's removed or added and it will then manually set the in property on the wrapped transition or CSSTransition component so that you don't have to control the "in" property because you of course can't do that, you're handling a dynamic list in the end.

# Alternative libraries:

https://react-move.js.org/#/

https://github.com/chenglou/react-motion

https://reactrouter.com/web/example/animated-transitions
