# pd-baseball
Pure Data code for baseball project

## Theory of Operation
| Physical Event                     | uC event           | uC sends to Pd | Pd Action                                                      |
| ------                             | ------             | ------         | ------                                                         |
| ---                                | ---                | ---            | ambient background noise ("get your hotdogs here!") |
| human touches button to start game | LEDs flash         | B              | louder crowd noise (they're getting excited), current score moves to recent score list, score shows 0, maybe flashes? |
| ---                                | one light stays on | C, constant update of timing | ball hitting wooden bat, crowd noise continues |
| human touches correct light        | ---                | D              | loud cheering. Maybe the score flashes on Pd? |
| human touches incorrect light      | ---                | ---            | |
| timeout (10 sec no activity)       | ---                | T              | return to start |

## Fonts to check out
 * [DSEG](https://www.keshikan.net/fonts-e.html)

## Sound archive
 * https://www.youtube.com/watch?v=WZaBgnm8FpA

## Thoughts on sound
 * we NEED the charge sound and the marching modulation organ sound!
 