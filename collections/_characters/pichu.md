---
layout: character
title: pichu
image: pichu.png
name: Pichu
over: Pichu is a space animal. His shine is like Falco’s but it self damages Pichu. His recovery is weakened to help him fit further in to his spacie archetype.
---

Weight 55 > 67
Walk max velocity 1.24 > 1.45
Run 1.72 > 1.9
Friction 0.01 > 0.095
Jump V Int Velocity 2.6 > 3.3
Ground to air jump momentum mlti 0.8 > 0.9
Jump H Max velocity 1.8 > 1.75
SH V Int Velocity 1.7 > 2.1
DJ momentum 0.8 > 1.1
Gravity .11 > .16
Air Mobility A 0.3 > 0.45
Air Friction 0.01 > 0.015
Fast Fall Term Velocity 2.5 > 3.2
Ledgejump V velocity 2.6 > 3.4
Normal landing lag 2 > 4
Walljump V Velocity 2.6 > 3.1
Ledge grab box vertical scale 6 > 10
Ledge grab box horizontal scale 9 > 11
term velocity 1.9 > 2.9
Max Aerial H Velocity 0.85 > 0.91

Tech rolls fixed to be normal distance
get up rolls fixed to be normal
tech in place fixed to be normal

Down b:
changed to shine
frame 1
dmg 8
angle 85
kbg 65
bkb 75

side b
charging adds damage but not distance
min(aka max) distance is now less than a Fountain platform
does 3% to pichu
base damage 16
angle 40
kbg 100
bkb 20

up b:
first half:
Added a hitbox between frames 13/14
DMG 5
angle 361
bkb 40
kbg 70
goes about half distance, but doesn't do 1% of self damage
second half:
unchanged basically

neutral b:
-5 endlag

ftilt:
hitbox size 1192/1192/766 > 1300/1300/900
damage 7/8/9 > 9/9/9

Utilt:
Damage 6 > 9
KBG 120 > 105
Max offset 1500 > 1300

Dtilt:
iasa 25 (via frame speed modifier, animation is shorter than 25)
Hitbox ID 0: Size 500 > 800
Hitbox ID 2:
Z offset: 900 > 1000
Y offset: 1533 > 500
X offset: -511 > -500
Damage: 7 > 10
BKB: 12 > 22
KBG: 100 > 95
Angle: 35 > 80

dash attack:
angle 361 > 80
IASA 50 > 37

fsmash:
only 2 pre-sparks instead of 6, so three hits total
strong hit comes out frame 22 instead of 34
strong hit lingers
Strong hit buffed from 6% > 12% kb compensated (95bkb 80kbg)
ends on frame 44 instead of 51

usmash:
lingers one more frame
angle 95 > 91
BKB 50/40 > 50/50

Dsmash:
Hitbox size 900/900/900 > 1200/900/1200
angle 160 > 125
kbg 70 > 69
damage 13 > 15

Fair:
active frames 6-16
dmg 11
angle 75
bkb 45
kbg 50
ID 0 size 1400 > 1100
Horizontal offset 5800 > 4500 (ROFLLLLL)
ID 1 Size 1000 > 900
Horizontal offset 4000 > 3800
Graphic pulled in to 5800 > 5100
Landing Lag 23 > 26
anim end 39 > 34
IASA 31
(this move needs a lot of work still, we will see)

Bair completely changed
dmg 15
self damage 2
bkb 10
kbg 90
angle 38° > 35°
31 IASA
37 Animation > 33 total

Dair:
landing hitbox (and landing self damage) removed
active frames 14-26 > 14-20
angle 361 > 270
damage 12 > 14
self damage 1 > 2
BKB 20 > 20
Landing lag 26 > 26
iasa -6 (thus with other FSM's, IASA frame 38)
Y offset 553 > 700
(Bone ID 14 > 15)

uair:
starts frame 5
9 dmg, angle 70, 24 bkb, 120 kbg
IASA 28 > 25
Outer hitbox size 900 > 500

Nair:
hitbox size 1022/1022/1200 > 1150/1150/1300

Jab:
ID 0 Size from 1106 > 1200
(vertical offset increased from 1200>1300 to better jab reset)
ID 1 Size from 681 > 800
7BKB > 12BKB
IASA 22 > 20

Grab:
Size 1200/800 > 1300/850
Dash grab:
Size 1200/800 > 1300/850

Up throw:
kbg 45 > 70
Now Weight Dependent


Bthrow:
angle 135 > 125
bkb 75 > 60
kbg 50 > 65

Dthrow
dmg 5 > 6
angle 80 > 75
kbg 38 > 40
BKB 60 > 65
-6 endlag

uthrow:
angle 90 > 80
bkb 90 > 100
kbg 70 > 85
