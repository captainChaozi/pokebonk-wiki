# Charizard's dual type in PokéBonk: why Rock hits for ×1.8

Source: [Charizard (#006) on the PokéBonk wiki](https://pokebonk.info/pokedex/charizard/) · Chart: [PokéBonk type chart](https://pokebonk.info/tools/type-chart/) · Wiki: [PokéBonk fan wiki](https://pokebonk.info/)

Charizard is Fire / Flying, the last stage of Charmander → Charmeleon → Charizard. Its defensive table is a good example of how PokéBonk's dual-type maths works.

## The rule

Single-type values: super effective ×1.35, resisted ×0.8, immune ×0.5. For a dual type, the two values **multiply**, and the result is **capped between ×0.4 and ×1.8**.

## Charizard's damage taken, worked out

| Attacking type | vs Fire | vs Flying | Product | Shown |
|---|---|---|---|---|
| Rock | ×1.35 | ×1.35 | 1.8225 | **×1.8** (cap) |
| Water | ×1.35 | ×1.0 | 1.35 | ×1.35 |
| Electric | ×1.0 | ×1.35 | 1.35 | ×1.35 |
| Ice | ×0.8 | ×1.35 | 1.08 | ×1.08 |
| Ground | ×1.35 | ×0.5 | 0.675 | ×0.675 |
| Bug | ×0.8 | ×0.8 | 0.64 | ×0.64 |
| Grass | ×0.8 | ×0.8 | 0.64 | ×0.64 |
| Fighting, Steel, Fire, Fairy | | | | ×0.8 |

## Takeaways

- **Rock is the only ×1.8 threat.** Without the cap it would be slightly higher.
- **Ice is only a small weakness** (×1.08) because Fire resists what Flying fears.
- **Ground is a resistance**, not a weakness: Flying's ×0.5 outweighs Fire's ×1.35.

## Offence

Fire attacks hit Bug, Steel, Grass and Ice for ×1.35; Flying attacks hit Fighting, Bug and Grass for ×1.35. Bug and Grass are covered twice.

Remember that PokéBonk uses its own stats and level-based evolution. The wiki does not list main-series base stats.

---
Maintained by the PokéBonk fan wiki editor. Unofficial; not affiliated with Nintendo, The Pokémon Company or the PokéBonk developer.
