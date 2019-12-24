# Hunter



The below *Shots* macros will :
* Not interput Rapid Shot 
* Will prioty target the mouse over target
* If no mouse over it will hit the players target
* The key benfit here is that you never drop the main target.

## Aimed Shot
```
#showtooltip Aimed Shot
/petattack
/startattack
/use Claw(Basic Attack)
/use Bite(Basic Attack)
/use Smack(Basic Attack)
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] Aimed Shot [nochanneling:Rapid Fire] Aimed Shot
```

## Steady Shot
```
#showtooltip Steady Shot
/petattack
/startattack
/use Claw(Basic Attack)
/use Bite(Basic Attack)
/use Smack(Basic Attack)
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] Steady Shot [nochanneling:Rapid Fire] Steady Shot
```

## Multi-Shot
```
#showtooltip Multi-Shot
/petattack
/startattack
/use Claw(Basic Attack)
/use Bite(Basic Attack)
/use Smack(Basic Attack)
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] Multi-Shot [nochanneling:Rapid Fire] Multi-Shot
```

## Arcane Shot
```
#showtooltip Arcane Shot
/petattack
/startattack
/use Claw(Basic Attack)
/use Bite(Basic Attack)
/use Smack(Basic Attack)
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] Arcane Shot [nochanneling:Rapid Fire] Arcane Shot
```

## Rapid Fire
```
#showtooltip Rapid Fire
/petattack
/startattack
/use Claw(Basic Attack)
/use Bite(Basic Attack)
/use Smack(Basic Attack)
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] Rapid Fire [nochanneling:Rapid Fire] Rapid Fire
```

## Counter Shot
```
#showtooltip Counter Shot
/petattack
/startattack
/use Claw(Basic Attack)
/use Bite(Basic Attack)
/use Smack(Basic Attack)
/use [@mouseover,harm,nodead] Counter Shot; Counter Shot
```
Note: This shot will interupt Rapid Shot

## True Shot
```
#showtooltip Trueshot
/use [nochanneling:Rapid Fire] Trueshot
```

## Double Tap
```
#showtooltip Double Tap
/use [nochanneling:Rapid Fire] Double Tap
```

## Tar Trap
```
#showtooltip Tar Trap
/cast [@cursor] Tar Trap
```

## Freezing Trap
```
#showtooltip Freezing Trap
/cast [@cursor] Freezing Trap
```

## Flare
```
#showtooltip Flare
/cast [@cursor] Flare
```

## Light's Judgment(Racial)
```
#showtooltip
/cast [nochanneling:Rapid Fire] Light's Judgment(Racial)
```

## Cancel Aspect of the Turtle
```
/cancelaura Aspect of the Turtle
```
Note : I like to have this on a seconday key so i can spam Aspect of the Turtle



## One Button Pet (Still buggy when the pet is going into Combat)
```
#showtooltip
/petfollow [nocombat]
/petattack [@pettarget,noexists]target
/petfollow [@pettarget,exists]
/petattack [@mouseover,harm,nodead]
```

## Pet Dispell
```
#showtooltip
/petpassive
/petattack
/use [pet:Machine]Nether Shock(Special Ability)
/use [pet:Stag]Nature's Grace(Special Ability)
/use [pet:Rupert]Spore Cloud(Special Ability)
/use [pet:Hati]Spirit Shock(Special Ability)
```

## Use Extra Action Buttion & Cancel Slow Fall
```
/click ExtraActionButton1
/cancelaura slow fall
```
Usefull for Mecha 

