# General

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

## Use Extra Action Buttion & Cancel Slow Fall
```
/click ExtraActionButton1
/dismount [mounted]
/cancelaura slow fall
```

# MM

The below *Shots* macros will :
* Not interpret Rapid Shot
* Will priority target the mouseover target
* If no mouseover, the players target will be attacked
* The key benefit is that you never drop the main target

## Aimed Shot
```
#showtooltip Aimed Shot
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] [nochanneling:Rapid Fire] Aimed Shot
```

## Steady Shot
```
#showtooltip Steady Shot
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] [nochanneling:Rapid Fire] Steady Shot
```

## Multi-Shot
```
#showtooltip Multi-Shot
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] [nochanneling:Rapid Fire] Multi-Shot
```

## Arcane Shot
```
#showtooltip Arcane Shot
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] [nochanneling:Rapid Fire] Arcane Shot
```

## Rapid Fire
```
#showtooltip Rapid Fire
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead,nochanneling:Rapid Fire] [nochanneling:Rapid Fire] Rapid Fire
```

## Counter Shot
```
#showtooltip Counter Shot
/stopcasting
/use [@mouseover,harm,nodead] Counter Shot [] Counter Shot
```

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
# SV

### Serpent Sting
```
#showtooltip Serpent Sting
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead] [] Serpent Sting
```

## Carve
```
#showtooltip Carve
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead] [] Carve
```

## Harpoon
```
#showtooltip Harpoon
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead] [] Harpoon
```

## Kill Command
```
#showtooltip Kill Command
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead][@pettarget,exists] [] Kill Command
```

## Mongoose Bite
```
#showtooltip Mongoose Bite
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead] [] Mongoose Bite
```

## Wildfire Bomb
```
#showtooltip Wildfire Bomb
/startattack
/petattack [@pettarget,noexists]target
/use [@mouseover,harm,nodead] [] Wildfire Bomb
```

## Muzzle
```
#showtooltip
/stopcasting
/use [@mouseover,harm,nodead] [] Muzzle
```



# Pet

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


