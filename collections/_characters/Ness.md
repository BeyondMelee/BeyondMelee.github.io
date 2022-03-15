---
layout: character
title: ness
image: ness.png
name: Ness
over: Write gibberish here
---

## Ness Vanilla > Demo 2 CL

### Attributes:

Initial walk velocity 0.08 > 0.12

Max Walk Velocity 0.84 > 1

Dash initial velocity 1.3 > 1.45

Run terminal velocity 1.4 > 1.55

double jump momentum (0x54) .8 > 1

Ground to air jump multipler 0.8 > 0.9

Int Hori jump vel 1 > 1.05

Max Sh Hori Vel: 1.3 > 1.35

Max air hori speed 0.93 > 1

Shield size 13.75 > 15

Int Ver Jump Vel 2.5 > 2.8

Int SH Vert Vel 1.5 > 1.6

Term Vel 1.83 > 1.86

Fast fall term Vel 2.2 > 2.4

### Jab 1:

Cancellable in to jab 2 f5 > f4

IASA 20 > 18

### Jab 2:

First active frame 3 > 2

Cancellable in to jab 3 f6 > f5

Damage 2 > 3

IASA 20 > 18

### Jab 3:

First active frame 6 > 4

Damage 4 > 6

IASA 30 > 28

### grab:

active frames 8-9 > 7-8

### Utilt:

Made arms also invincible

Damage 7 > 10

KBG 120 > 115

Angle 96 > 90

IASA 32 > 30

### Ftilt:

up/side/down dmg 12/11/10 > 12/12/12

### Fsmash:

dmg 18/20/22/24 > 20/22/22/24

IASA 50 > 45

### Usmash:

size 600 > 900

Damage 9/6 > 13

Angle 70 > 85

BKB 80/60 > 40

KBG 80/45 > 90

IASA 49 > 40

### Dsmash:

size 600 > 900

Damage 11/7 > 12

Angle 70 > 35

kbg 80/60 > 85

bkb 70/70 > 35

IASA 59 > 48

### Uthrow:

Sped up 1.25x

angle 90 > 90

BKB 105 > 90

KBG 40 > 55

### Fthrow:

BKB 120 > 100

KBG 10 > 25

### Dthrow:

Sped up 1.5

### Nair: 

Strong hit:

Damage 11 > 13

Weak hit:

DMG 8 > 9

KBG 100 > 80

landing lag 22 > 15

first active frame 5 > 4

IASA 36 > 31

Total frames 39 > 35

### Uair:

First active frame 8 > 6

DMG 13 > 14

BKB 13 > 10

KBG 109 > 110

landing lag 18 > 16

### Dair:

First active frame 20 > 15

KBG 70 > 75

BKB 90 > 80

IASA 60 > 39

Total frames 59 > 49

### Bair:

First active frame 10 > 8

Added a super sweet spot that does 17% + 15 extra kbg + 5 extra bkb, electric sound effect

bkb 16 > 20

Angle 361 > 40

### Fair:

First active frame 8 > 7

weak hit:

all weak hits sped up 

dmg 3/2 > 3

shield damage 1 > 4

Final hit:

dmg 5 > 7

angle 361 > 40

shield damage 1 > 6

hitbox size 1700/1000 > 1780/1200

### Dash attack:

First active frame 8 > 6

First and second hitbox each linger for one more frame

Last hitbox starts one frame earlier

### up b:

Start up(air):

Total frames 20 > 15

After hit:

Strong hit:

DMG 25 > 18

BKB 60 > 40

Mid hit:

DMG 20 > 16

BKB 45 > 35

Total frames:

70 > 60

Landing lag:

24 > 18

### Neutral b:

Reworked entirely

//-----notes:
min charge time (0xC, second ???? in crazy hand) 30 > 18
ness neutral b end animation time sped up 2x (FSMs)
-----Hitbox: 
size 2,150 > 4,200
Shield damage 0 > 14
-----Attributes:
- (min chage time?) 30 > (?)19(?)
Cooldown after releasing Pk Flash (0x4) 25 > 1
- 10
- (min chage time?) 30 > (?)19(?)
- 2
Aerial vertical momentum on charge (0x14) 0.017 > .5
- 0.6
Landing Lag (0x1c) 30 > 1
Projectile Lifetime 120 > 22
- 100
- 0.3
- 1.7
Pk Flash Horizontal momentum 3 > 30
Max rising height 1.2 > 2.8
Control sensitivity 0.01 > 0.08
Gravity 0.02
- 2
- 2
Detonation timer 20 > 5
Base damage 2.125
Hitbox size multiplier smaller = bigger 100 > 75
Int hitbox size multiplier 0.3 > 0.18
Hitbox growth multiplier 1.7 > 1
- 1
Damage multiplier 0.35 > 1

### side b:

start up 20 > 10 (FSM's)

endlag 50 > 40 (70 frames total vs 50 frames total)

Damage per hit of pillar 2 > 3

Spark hitbox size 700 > 900

Attributes:

landing lag 30 > 12

Spark lifetime 20 > 35

Pillar lifetime 100 > 10

Angle in air (radians) -0.663 > -0.4

Angle on ground (radians) -0.063 > -0.03

### Down b:

All animations sped up

Hitbox:

dmg 6

angle 361

has a ground hitbox :D

Attributes:

Frames down b is held after releasing b 30 > 4
//???? 4
Momentum preservation? 8
Momentum preservatoin? 2 > 10
???? 4 > 6 (i think it's the amount of frames before it starts falling again)
???? something with horizontal momentum 2 > 0.65
fall speed 0.02666666666 

FSM'd SpecialLwStart and Hold *3 (starts on frame 8) <old
FSM'd SpecialLwEnd 1.375? (Frame 23 IASA) <old
