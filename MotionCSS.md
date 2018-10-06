# Motion with CSS

## Transition

* transition describes how a property should display change when given a different value
* transition is about going from one value to another
* transition: property duration (delay - function)
* list of transitionable [list](goo.gl/Ttk1S2)
* use millisecond for duration
* all transition can be written in one line 
* transition: color 2s, transform 1s 500ms
* 250-300ms sweet spot for animation
* ease-in, ease-out, ease-in-out, linear, steps, cubic-bezier (cubic-bezier.com)

## Animation

* animation: $name $duration $timingFunction $delay $iteration-count
* animation-fill-mode: forwards, backwards, none, both
* animation-play-state: runing, paused
* animation-direction: alternate, reverse, alternate-reverse
* why animation: looping, self-starting, Repeating, Animating, Grouping

## Types of Animation

* stateful animation: change in task flow location, where you have been, where you are now
* supplemental animation: change in information, what is possible for users, important detailes taht should be overlooked
* causal effect: client is the cause, hover effect
* Decorative Animation

## Ways of triggering state

* Browser events
  * loading
  * scrolling
* Human events
  * Hovering
  * Clicking
* Timed events
  * Timeouts
  * choreography

## Libraries

* Skrollr
* Waypoints

## JS animation

* event listeners
* animationend, animastionstart, animationiteration, transitionend

## Best to use

* scale() instead of with or height
* translate() instead of position
* opacity instead of z-index or visibility hidden

## Will-Change

* translateZ(0); translateZ hack
* will-change

## chrome tools

* animation
* rendering
* Timeline