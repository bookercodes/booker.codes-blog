---
title: Bind ESC to FN on your Vortex Pok3r
description: Bind ESC to FN on your Vortex Pok3r
date: 2020-11-16
layout: layouts/post.njk
---

If like me, you relish the idea of using HJKL for your arrows, you’ll need to map FN to a key on the left-hand side of your keyboard - that is unless you have salad fingers.

The left-hand side of your keyboard has 4 prime candidates for FN - namely, ESC, CAPS, R_CTRL, and R_ALT. 

Of these 4 candidates, CAPS is easiest to bind FN to - all you need to do is flip switch 3 ON. This will bind CAPS to FN on *all* layers - nice and easy. 

With that said, I am special and want to use ESC as my special FN key. If you want to do the same, you'll need something of a Konami code. At least, reading the [manual](http://www.vortexgear.tw/db/upload/webdata4/6vortex_20166523361966663.pdf), there’s only a hint about how to do this.

My saving grace was [this post](https://www.reddit.com/r/MechanicalKeyboards/comments/35uy60/guide_howto_program_your_pok3r_programming_layers/) on Reddit but I hope I can make things a little clearer yet.

## How to bind ESC to FN

Normally when binding keys, the spacebar LED indicates the current state. The Pok3r doesn't offer any documentation and it doesn’t offer any feedback when binding the FN key either, making it easy to mess up. Not trying to brag, but it only took me one attempt to fuck up all my previous binds. Oh well.

In this how-to, I am going to embrace the fact that you’ll probably mess up and ask that you reset your Pok3r from the beginning. It might be that you can skip step 1 as long as you read the others carefully.

Leggo!

1. Reset your Pok3r by pressing and holding R_ALT + L_ALT for 5 seconds
2. You can only bind FN for one layer at a time, so pick layer 1, 2, 3, or 4. Even though switch 3 binds CAPS to FN on the default layer, it is otherwise impossible to rebind FN on the default layer - just thought I'd let you know!
3. If like me, you need to bind CAPS to ESC, do that first 
	1. Press FN + R_CONTROL
	2. Press CAPS
	3. Press ESC
	4. Press PN
	5. Press FN + R_CONTROL
	6. Unless you're an absolute mad lad, use [Keyboard Tester](https://www.keyboardtester.com/tester.html) to test CAPS is now registering ESC
4. Unplug your Pok3r and flip switch 4 ON to temporarily enter _FN/PN BINDING MODE_. The only way to leave this mode is to turn switch 4 OFF (you don't want it ON all the time like you might switch 3 - I found this counterintuitive)  
5. Plug your Pok3r back in. Your keyboard is now in a special _FN/PN BINDING MODE_ where you can't type - only bind FN and PN
6. When the Pok3r wakes up in _FN/PN PROGRAMMING MODE_, it will anticipate you to bind either FN or PN
7. To do this, press FN once then ESC (or the key you want to bind FN to) once
8. Press PN once then PN once 
9. Flip switch 4 OFF to exit _FN/PN PROGRAMMING MODE_ (no need to unplug this time)

ESC should now be your FN key. Sick mate.