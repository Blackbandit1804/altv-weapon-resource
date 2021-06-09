# altv-weapon-resource

# How to add Weapons?

1.  Download [OpenIV](https://openiv.com/)
2.  Open OpenIV
3.  Tools -> Search (STRG + F3)
4.  Search for your weapon name (weapon_combatshotgun)
5.  Put the meta in your resource
6.  Edit `stream.cfg` add your weapon in meta
7.  Edit your weapons meta with these values to disable headshot

```xml
<MinHeadShotDistanceAI value="-1000.000000" />
<MaxHeadShotDistanceAI value="-1000.000000" />
<HeadShotDamageModifierAI value="0.000000" />
<MinHeadShotDistancePlayer value="-40.000000" />
<MaxHeadShotDistancePlayer value="-40.000000" />
<HeadShotDamageModifierPlayer value="0.000000" />
```

8. Edit `WeaponFlags` and remove `AllowCloseQuarterKills`
