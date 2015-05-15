# Good Button
Good Button is a button created with Sassy goodness that actually looks like a button. It's flat(ish), but still has those subtle gradients, inner-shadows, and drop shadows that give a button its buttonness. Feed Good Button a few variables and the mixin takes care of the rest. Give it a try to make your button feel like a button.

![a few different good button styles](https://s3.amazonaws.com/f.cl.ly/items/3N2O0Z3s0c2w1E3s1K36/good-buttons.png)

Here are the variables to give your Good Button some style.
```sass
$base-color: #0099ff
$label-color: #fff
$label-font: lucida sans, sans-serif
$label-font-size: 1em
$label-shadow-up: true // only make true for medium to light colored buttons
$label-shadow-down: false // only make true for lightbuttons
```
![good button gif](https://s3.amazonaws.com/f.cl.ly/items/442L1F2d053c31121a3D/Screen%20Recording%202015-05-15%20at%2001.25%20PM.gif)

Add the mixin to your very own button.
```sass
button
  +goodbtn
```


