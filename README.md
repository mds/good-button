# good-button
Good button is a button that actually looks like a button. It's flat-ish, but still has those subtle gradients, inner-shadows, and drop shadows that give a button is buttonness. Feed Good Button one hex code (and a few other variables if you'd like) and the mixin does the rest for creating the gradients, hover state, and hit state. Give it a try to make your button feel like a button.

![good button gif](https://s3.amazonaws.com/f.cl.ly/items/442L1F2d053c31121a3D/Screen%20Recording%202015-05-15%20at%2001.25%20PM.gif)

Here are the variable to give your Good Button some style.
```
$base-color: #0099ff
$label-color: #fff
$label-font: lucida sans, sans-serif
$label-font-size: 1em
$label-shadow-up: true // only make true for medium to light colored buttons
$label-shadow-down: false // only make true for lightbuttons
```

Add the mixin to your very own button.
```
button
  +goodbtn
```


