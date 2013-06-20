

Ah, who doesn't remember the endless hours wasted playing Pokémon games on a Game Boy during long car rides? I sure do. Pokémon had an interesting battle system, and one of the nice mechanics was the type system.

For this challenge, you'll be writing a function, `type_effect` , that takes two string arguments -- the offending move's name and the defending Pokémon's name -- and returns a multiplier like `2.0` or `0.25` .

Generally, you take the offending move's type, look up the multipliers for all the defending Pokémon's types in the type chart, and multiply them together. As an example, we'll run through the calculations for `type_effect("Ice Beam", "Dragonite")` .

(Optionally, use `enum` s instead of strings, like `type_effect(M_ICE_BEAM, P_DRAGONITE)` ).

- [Ice Beam](http://bulbapedia.bulbagarden.net/wiki/Ice_Beam_(move)) is an Ice move.
- [Dragonite](http://bulbapedia.bulbagarden.net/wiki/Dragonite_(Pok%C3%A9mon)) has multiple types, Dragon and Flying.
- According to the [type chart](http://bulbapedia.bulbagarden.net/wiki/Type_chart), Ice vs. Dragon has a 2.0× bonus, and Ice vs. Flying has a 2.0× bonus, too. Multiplying these together, you get 4.0×, so return `4.0` .

Obviously, this challenge is all about collecting the data you need yourself and manipulating it, so **don't steal each others' representations** of the Type array, Pokémon's types, etc!

