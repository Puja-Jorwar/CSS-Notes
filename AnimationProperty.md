##Animation
==> It is Shorthand CSS property.
==> The process of animating the html element from one state to multiple state with a transition effect.
==> Animation is depends on keyframes and every keyframe will be provided from 0% to 100%.
==> Animation key frame are represented in CSS file by using "@keyframes" annotation and followed by that we have to pass the animation name.
==> keyframes need not to start with 0% and need not to end with 100%.
==> 0% can be translated to and 100% can be translated to 
==>  animation key frames counts depends on element's state count.
==> the below syntax will explain the element which is having 3 state animation.
"@keyframes animationName{
first frame 
0%{
css-property: css-property-value;
}
second-frame
50%{
css-property: css-property-value;
}
last frame
100%{
css-property: css-property-value;
}
}"

==> Whenever developer wants to animate the element only between two state that time only we have to go for below syntax.
"@keyframes twoStateAnimationEffect{
first frame
from{
css-property: css-property-value;
}
last frame
to{
css-property: css-property-value;
} "

==> animation shorthand property has 8 specific property.
==> 1] animation-name
==> 2] animation-duration
==> 3] animation-timing-function
==> 4] animation-delay
==> 5] animation-iteration-count
==> 6] animation-direction
==> 7] animation-fil-mode
==> 8] animation-play-state

==> 1] animation-name:
-------It is specific property of animation shorthand property.
-------It is used for provide animation name.
-------Animation name is one of the identifier so animation name casing should be return in camel casing.





















