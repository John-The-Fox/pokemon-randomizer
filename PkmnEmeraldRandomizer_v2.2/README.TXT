POKEMON EMERALD RANDOMIZER!
---------------------------
v. 2.0, programmed by Artemis251
Released: 18 August 2013
Last update: 29 September 2013

Version changes:
----------------
v. 2.2:  - Fixed a glitch involving evolutions from dual-ability pokemon
           to single-ability pokemon
v. 2.1:  - Fixed a glitch in rendering Wally's first battle opponent
v. 2.0:  - Added a whole slew of stuff!

v. 1.0:  - Initial release!



Table of contents:
------------------

 1) What the randomizer does
 2) How to use it
   *) !! A WARNING! !!
 3) Starter pokemon options
 4) Wild pokemon options
    *) What is an encounter slot?
 5) Trainer Pokemon options
 6) Pokemon Modifcation Options:
 7) Palette Options:
 8) Base Game Options:
 9) Create ROM Info Docs
10) Quick Settings
11) FAQs/Why the heck won't this work?!
12) If you find a bug...
13) Special Thanks
14) Final comments




1) What the randomizer does:
----------------------------
      This program will modify (to your specification, of course) a Pokemon
    Emerald game file. The list of things it can modify can be summed up as:

       - Starter Pokemon & their items
       - Wild Pokemon, including event Pokemon
       - All other in-game Pokemon, including trades and prizes
       - Trainer Pokemon
       - Trainer titles (like 'Lass' or 'Pokemaniac')
       - Items found on the map, including hidden items
       - TM attacks
       - Pokemon-TM compatability
       - Pokemon themselves, including types, stats, palettes, abilities,
           wild hold items, and movesets
       - Redefining certain evolutions so trading is not required
       - Changing some core game things, like stacking TMs in groups of 90,
           starting with the National Pokedex, or modifying store stocks.

      Unfortunately, this program is a little too specific to apply to other
    games, even within Gen III. If you want to try a different randomized
    version, I suggest trying one of the following:

      -- Red/Blue:
           My own Red/Blue randomizer:
              http://artemis251.fobby.net/downloads/redblue/
      -- Pretty much any other:
           The Universal Pokemon Game Randomizer:
              http://pokehacks.dabomstew.com/randomizer/



2) How to use it:
-----------------
      You may not have seen a '.jar' file before. Basically, it's the same as an
    '.exe. file, only it requires Java to run. If you don't have java, it's simple
    enough to get Java Run-Time installed -- just visit the following link:

	http://java.com/download 

    After downloading, you should be able to open the file by double-clicking
    it (just like an .exe file). If Java is having some weird errors and not
    bringing the program up right, it's likely some issue with your Java version
    or your Operating System that I can't really fix. Look around the internet for
    a solution or try using a different computer.

      As for the program itself, it should be easy enough to understand. First,
    load your game ROM with the Open dialog. Things should be automatically read
    (the starter pokemon, at least). Everything else should be fairly intuitive:
    select what modifications you want and save the file. That's all! There's no
    patching or anything required, so just start the game up and enjoy!

  ==== !!!!! A MINOR WARNING, HOWEVER: !!!!! =======================================
  |                                                                                |
  |    Use of the program may overwrite your ROM! So, if you want to save a fresh  |
  | version of the game to re-randomize later (or just play the vanilla game), you |
  | ought to make a backup copy before using this program or use the 'Save As'     |
  | option in the menu. For convenience, the large 'Save' button on the program    |
  | interface also Saves As instead of overwrites the base game.                   |
  ==================================================================================


3) Starter pokemon options:
---------------------------
    When you load the ROM, the 3 current starters should show. From here, simply
    use the dropdown boxes to choose your starter pokemon. If you'd rather be
    surprised at what you get, there is an option for a randomly selected starter.

    To further define what the Random option here does, there are two checkboxes
    located in the area as well, 'Basic Pokemon Only' and 'Prevent Legendaries'.
    They do exactly what they say when choosing your random starters. (For those
    who haven't played the card game, Basic pokemon and unevolved, base form
    pokemon like Bulbasaur, Onix, and Eevee.)

    For convenience, the button at the bottom sets all starter choices to Random.

    Finally, you may choose an item for your starter to hold when you receive it.
    No matter which starter you choose, it will be holding the item you select.
    Note that some items won't transfer to your item pack correctly, like most
    Key Items. Try sticking with things pokemon can normally hold. Additionally,
    items appear in game-index order. If you can't find something, try clicking the
    box and typing the item you want. It may pop up if you type fast enough.
      One last thing: there are several '???????' items as choices. This is because
    there are a bunch of item slots that aren't used. If you select these, you'll
    likely get either nothing or some garbage item that can't be used. I'd advise
    against selecting these.



4) Wild pokemon options:
------------------------
      First, I feel I ought to define something:

  ==== !!!!! WHAT THE JONES IS AN ENCOUNTER SLOT? !!!!! ==========================
  |                                                                              |
  |   A quick definition: Encounter slots are the way the game stores wild       |
  | pokemon data. Each area has a finite number of encounter slots. Each slot    |
  | holds a pokemon found on that map, and each slot has a different rarity.     |
  |   As such, you will NOT find all 151 pokemon on one route! Chances are,      |
  | you'll find 10 or so on the highest randomization setting.                   |
  ================================================================================

    That said, there are 4 options for how the wild pokemon are changed. Note that
    just the pokemon are changed, NOT their levels. From top to bottom, the options
    range from least randomized to most randomized:

      - Unchanged:
            Pokemon encounter slots do not change.
      - Global 1-1 Substitutions:
            All pokemon of the same species change to pokemon of another, random
            species in all locations. For example, all Zubats throughout the caves
            of Hoenn will all become the same alternate pokemon.
      - Area-Unique 1-1 Substitutions:
            All pokemon of the same species within each location change to another,
            random species. This differs from the above by shifting the pokemon
            outside the area. For example, all Zubats in one cave turn into one
            random pokemon, while Zubats in every other cave are different pokemon.
              Note that many-leveled areas (places with several floors, etc.) count
            each area as a separate map. Thus, caves with 3 floors all normally
            sporting Zubats will have a different pokemon substitution for Zubat
            for each floor.
      - Completely Random:
            Every encounter slot is a different pokemon. This gets pretty crazy,
            as some routes may hold over 30 pokemon depending on whether they
            have grass, surf, fishing, or rock smash encounter slots.

    Also note that the pokedex automatically updates the ranges for each pokemon.
    This makes it really easy to find where certain pokemon live. However, you won't
    have the national Pokedex right away unless you turn that option on in the
    'Base Game Options' section. Without it, you'll have to wait to beat the Elite
    Four before you can search for non-Hoenn pokemon.

    There are more fine-grained options to tweak these chocies to your preference.
    Depending on your randomization choice, not all may be available, as some of
    the options don't make sense with some choices.

      - Randomize Unique Pokemon
            Special pokemon that appear on the map get randomized with this. This
            includes all legendaries (Regi trio, Kyogr, etc.), roaming pokemon
            (Latias, Latios), scripted battles (Kecleon, Electrode, etc.), and
            gift pokemon (Beldum, Castform, etc.). The overworld sprites won't
            change to match the pokemon, but some of the in-game text may.
            For story purposes, I stayed away from swapping out the text for the
            main trio of Groudon, Kyogre, and Rayquaza. They'll still be mentioned
            by Teams Aqua and Magma.
              If you chose this option, you may also choose its sub-option,
            'Uniques are Legendary'. This ensures all unique pokemon are
            legendaries. This goes well with the below option, 'Prevent Wild
            Legendaries'. Note that there are JUST enough uniques to cover them
            all without traveling to any special islands. (If you do go to said
            islands, though, the uniques like Mew and Ho-oh are randomized, too.)
              As a final note, if you choose 'Ensure All Pokemon Appear' (see
            below) alongside the 'Uniques are Legendary', Latias and Latios will
            always be 2 non-hoenn legendaries. This lets you fill the Hoenn dex,
            granting you the ability to unlock Prof. Birch's final gift --
            normally one of the three Johto starters. Here, though, they'll be
            replaced with the Latios replacement, the Latias replacement, and
            a random legendary, allowing you to get all 493 pokemon on one game.
      - Ensure All Pokemon Appear
            With this chosen, the randomizer will do its best to let you find
            all 493 pokemon in your game. Note that evolution may be required
            depending on other options chosen. Note further that 'Global
            Substitutions' will NEVER allow you to get all 493 pokemon merely
            because there aren't enough substitutions to allow this. It will, at
            least, ensure each substitution is something unique to get you as
            many pokemon as it can.
              For the completionist's sake, some special areas are marked to
            ensure pokemon within them are not the only place those pokemon
            can be found. This includes the Safari Zone, the Cave of Origin,
            and Mirage Tower. This was done to the Safari Zone because getting
            stuck snaring a legendary with Safari Balls is tedious and lame.
            The others are areas that cannot be returned to later in the game.
      - Keep Evolution Forms Intact
            This is a neat option that keeps the evolution form for any pokemon
            replacement the same as the original pokemon's form. Thus, Basic
            pokemon are replaced by Basic Pokemon, and evolved pokemon are
            replaced by evolved pokemon. Note that an evolution may make Stage 1
            OR Stage 2 pokemon replacements. This might be coded differently in
            a future update, but for now any evolution stage will be replaced by
            a random evolution stage.
      - Prevent Wild Legendaries
            When this is chosen, all legendaries are removed from the wild. This
            does not take effect for Unique or Traded pokemon, however.
      - Randomize Trade Pokemon
            As the name implies, thee 3-4 trades in the game are randomized.
            Both the pokemon wanted and the pokemon up for trade are changed.
            The received pokemon's nickname and held item will be randomized,
            too!

      Whew! Sorry that got kind of verbose, but I want you all to be aware of
      everything happened under the hood, so to speak!


5) Trainer Pokemon options:
---------------------------
    Surprise, surprise, this changes the pokemon of trainers across Hoenn.
    This includes all rematches against the same NPC. As before, levels did not
    change, though some other things may if you look through the special detailed
    option underneath the main choices. All trainers keep the number of pokemon
    they originally had as well.
      For Gym Leaders and Elite Four, though, I made sure their pokemon are all in
    their final evolution form. Gotta keep those guys and gals strong!

      - Unchanged:
            Trainer pokemon do not change.
      - Global 1-1 Substitutions:
            All trainer pokemon of the same species change to pokemon of another,
            random species across Hoenn. For example, all Trainers with Poochyena
            will instead have the same alternate pokemon.
      - Completely Random:
            Each trainer will have random pokemon in their team.

    As before, there are more detailed options below:

      - Randomize Trainer Class Names
            Trainer class names, like LASS, AROMA LADY, or GENTLEMAN get
            randomized to one of 5 different names (like SASSY LASSY, SMELLOMANCER,
            or HABERDASHER).
      - Randomize Trainer Held Items
            Some trainers' pokemon hold items. This options changes their items to
            a random, useful-for-battle item. When I say 'useful for battle', I mean
            things like Leftovers, certain berries, or Focus Bands. Things like
            pokeballs, X-Speed, or TMs won't be included.
      - Randomize Trainer Use Items
            Some trainers have a stock of items to use (like the Elite Four and
            their maddening supply of Full Restores). This options changes those
            items to other, useful battle items. Think things like Lava Cookies,
            X-Attack, or any potion/status restoration item.
      - Rivals Keep First Pokemon
            This option ensures both May/Brendan and Wally keep their first pokemon.
            Their partner will evolve as you meet them throughout the story. Just
            note that May/Brendan's pokemon may not reach its full potential. This
            is normal, as they never do in Emerald in the first place (i.e., their
            starter never reaches Stage 2). Wally's may only evolve after a few
            rematches, too.
      - Prevent Trainer Legendaries
            Easy enough, no trainers will have legendary pokemon. The list of
            legends is pretty standard.
      - Include Battle Frontier
            This option will randomize the trainers' pokemon in the Battle Frontier.
            Note that because of this, you may not see the normal trend of evolution
            forms. Thus, the first trainers may have Stage 1 and Stage 2 pokemon
            instead of just Basic forms, and those appearing later may have unevolved
            pokemon. The only exceptions are the Frontier Brains, whom should all
            have fully evolved pokemon no matter what.
            


6) Pokemon Modifcation Options:
-------------------------------
    Options here will help you change the base pokemon information. Things like
    types, abilities, movesets, and more are at your control!

      - Switch Pokemon Stats Around
            This option will randomly switch around pokemno base stats. Note that
            this doesn't mean that they'll be changed -- if a pokemon has stats
            of 50, 70, 100, 80, 100, and 65, those 6 values will remain the same
            but be assigned to different stats. So, if in that example, the 65
            base value was in Attack, it may be assigned to Special Defense after
            a randomization. So don't expect Magikarp to become as powerful as
            Salamence!
      - Randomize Pokemon Types
            All pokemon types will get mixed around with this option. I ran the
            stats on Gen 3 pokemon for this and came up with a few notable numbers
            for type chances. To mimic those finding exactly, I set the chance for
            a dual-type pokemon to be 47%. For evolutions, there's a 21% chance for
            single-type pokemon to gain a new type. Finally, I ensured all evolutions
            carry their types over. Thus, you needn't worry about your dragon-type
            suddenly becoming a flying-type.
      - Randomize Pokemon Abilities
            Pokemon abilities will become randomized, with a few exceptions. Pokemon
            may be assigned any ability except for two: Forecast and Wonder Guard.
            Forecast on any pokemon besides Castform does nothing, so I made Castform
            have a 100% chance to have that ability. Likewise, Shedinja has a 100%
            chance at Wonder Guard. It's not much, but it'll help him survive with
            that crummy base stat of 1.
      - Randomize Wild Held Items
            Wild pokemon will have a random shot at holding a holdable item with this
            checked. Each pokemon has 2 item slots they may be holding an item in.
            Each slot gets a 25% chance to activate, and evolutions will inherit the
            items from their lower forms.
      - Randomize TM/Tutor Attacks
            TMs and Move Tutor moves will be randomly reassigned with this checked.
            There are a few attacks that won't ever show up, though:
                - All HM moves
                - Swallow/Spit Up/Stockpile
                - Struggle
      - Randomize TM/Tutor Compatability
            The list of TMs a pokemon can learn gets randomized. Each pokemon has a
            50% chance to be able to learn a given TM/HM/Move Tutor move. If a
            pokemon can learn the move, rest assured that its evolutions can, too.
            If fact, evolved forms have a second shot to be able to learn any missed
            TMs at the same 50% chance.
               As a side note, I've kept Mew's unique ability to learn all TMs, HMs,
            and Move Tutor moves unchanged. It should still be able to learn all
            attacks.
      - Randomize Pokemon Movesets
            Pokemon mobesets are given the switcheroo. Attacks known between
            evolution forms should stay the same, though: Poochyena and Mightyena's
            Howl will both be replaced by the same move, for example.
            There are a few attacks that won't ever show up, though:
                - All HM moves
                - Swallow/Spit Up/Stockpile
                - Struggle
      - Ensure L:1 Attacks Do Damage
            Ever randomize a game, choose a starter, and find out they only know a
            non-damaging or suicidal attack? Choose this option to remedy that pain.
            It will swap the first damaging move in a pokemon's moveset with the
            first attack it can learn. If the pokemon doesn't learn any damaging
            attacks, the first attack will become Tackle.
              Note that 'damaging' here is mostly focused on the ability to do
            damage. This includes things like Focus Punch, but not Transform.
      - Metronome Hyperdrive!
            Choosing this option will really put some randomness into your game.
            It grants all pokemon the move Metronome as their first attack and ups
            Metronome's PP to 40.



7) Palette Options:
--------------------------
    Ever wanted to see some interesting palette swaps of existing pokemon? Do shiny
    colors make pokemon more likely to be on your team? Try these options to swap
    the hues of pokemon to newer, potentially sweeter colors!
      Note that though you may read about limited color selections, I've added quite
    a few tricks to keep colors different and unique. Colors have a random chance to
    be lighter or darker than their base color, and each time a color is chosen it
    is tweaked a bit before application. This way, the same red can become multiple
    different hues for each choice. Plus, the shade count makes a difference in how
    the colors change from palette slot to palette slot.

      - Unchanged:
            No changes to the palette will be performed.
      - Use Type-based Colors:
            A pokemon's main type (and secondary type, if applicable) will determine
            the colors chosen. For this option, each type has 3 colors assigned to
            it. Colors will be randomly selected from the pool of colors until
            either the color pool is empty (i.e. all colors have been used once) or
            the number of colors used by the pokemon is exhausted. In the case of
            the pool being used up, additional colors are chosen at random.
              The reason for this option is to allow a quick gauge of what a
            potentially unknown pokemon's type is during type randomizations. Because
            of this, I tried making the color groups make as much sense as I could
            while retaining a decent rainbow of colors overall. If you'd like to know
            which colors are assigned to which types, view the added PNG image that
            comes with this program.
      - Use Random Colors:
            Colors are chosen randomly out of the large group of type colors.
            
    The extra options help you fine tune your primary choice:

      - Randomize Primary Colors Only
            Only the main color of each pokemon will be randomized. This color can be
            quite different from pokemon to pokemon, so expect mixed amounts of color
            changes. This option is great for keeping things a little more controlled
            color-wise.
      - Single Family Palette
            When this option is checked, pokemon evolutionary lines will retain the
            same palette substitutions 100% of the time. If it's left unchecked,
            pokemon have a 20% chance to get a new palette when they evolve.
      - Make Shinies Normal Colors
            Shiny pokemon will have their palettes changed to the palettes of
            whatever the current norm is. I say this instead of 'normal colors'
            because it will simply copy whatever the base colors in the ROM are.
            This means that if you load a ROM with randomized palettes, the 'normal
            colors' will be whatever randomized palettes were on the base ROM. If
            you use a fresh ROM, you can expect the normal pokemon colors, though
            (Bulbasaur being blue and green, Charmander being orange, etc.).
            


8) Base Game Options:
--------------------------
    Options here change core game attributes or randomize things that don't have
    anything to do with pokemon or trainers directly. These can make your playthrough
    more fun or your randomization options a little more balanced and completable.

      - Redefine Trade Evolutions
            All trade evolutions are redefined to allow one single game to attain
            the forms normally requiring link cable trades. The following
            evolutionary means are changed:

                * No item	Level 36
                * Metal Coat	Level 40
                * King's Rock	Moon Stone
                * Dragon Scale	Level 42
                * Upgrade	Level 32
                * DeepSeaTooth	Low personality (like Wurmple -> Cascoon)
                * DeepSeaScale	High personality (like Wurmple -> Silcoon)

            Of course, if you'd rather evolve them normally through trading, you
            can still do that. I just added a secondary method on top of the existing
            definitions.
      - Make Scales and Stones Buyable
            Since items may be randomized (see below), some rather important items
            may end up being scarce. To address this issue, you can choose this
            option to modify stores in two towns to sell items allowing evolution
            and move relearning. Evolution stones and Heart Scales can be bought in
            Fallarbor Town. Just note that since Moon Stones are not meant to be
            bought, they'll appear free. You'll only be able to buy one at a time
            and you won't be able to sell or drop them, I believe.
      - Randomize Pickup Items
            This option will switch around the items that a pokemon with the Pickup
            ability can gain at the end of battle. The chances remain unchanged --
            only the items are randomized. The items on this list can be viewed if
            you create the ROM info docs.
      - Randomize Field Items
            Both pokeballs that appear on the overworld map and hidden items will
            change when this option is selected. Only non-key items will be changed,
            so don't worry about getting stuck because you couldn't find a plot-
            important item. Additionally, mail won't be changed, so don't expect
            great items in the Trick House.
              The algorithm should ensure one of each item gets put in the world,
            so you're sure to find all 50 TMs, the Master Ball, and a bunch of other
            useful stuff. After each main item is accounted for, items are selected
            at random. As a bonus, there's a special Key Item that you can only find
            when this option is selected, though you won't be able to use it without
            an activation code....
      - TMs Come in Stacks of 90
            All TM item balls will give you 90 of the TM when found. Note that this
            only applies to item balls -- gifted TMs from trainers or TMs bought from
            stores will still be in quantities of 1. I chose 90 instead of 99 because
            you'll be prevented from picking an item ball up if you can't get the
            full quantity. Thus, if you got a TM from a gym leader and then found
            the item ball for that TM, you'd have to get rid of the one you had
            before picking the ball up. (And in Emerald, you can't just toss TMs...)
              Note that hidden item TM substitutions will only come in groups of 1.
            This is because invisible items can only be picked up one at a time, and
            only one item can be retrieved every time a map is loaded. You'd have to
            do a lot of traveling to pick up all 90 that way!
      - Start with the National Pokedex
            You'll be given the National Pokedex at the start of the game instead
            of the Hoenn pokedex. When you beat the game, Prof. Birch will still
            seem to give you the National Dex, though.


9) Create ROM Info Docs:
------------------------
    Once you load a ROM, you can use this option to gather a bunch of data about it.
    When you click the button, it will prompt you for the filename and location
    to save the file. Once done, open it with any program that can read .txt files.

  ==== !!!!! NOTE !!!!! ==========================================================
  |                                                                              |
  |   Until you save your ROM, none of your randomization options will show up   |
  | in the resultant info document. So, to get the ROM changes, go through your  |
  | options, save your ROM, and THEN print the docs.                             |
  ================================================================================

    The sections that get written to the document are the following:

      - Pokemon Info List
            A list of base stats, Effort Points (EPs), Types, Abilities, and Held
            Items for each pokemon in the game.
      - TM List
            A list of TM moves.
      - TM/HM Compatability List
            A list of which TMs and HMs a pokemon can learn. An 'X' means a pokemon
            can learn the attack, and a '-' means they can't. Unfortunately, Move
            Tutor move compatability is not included.
      - Lati@s choices
            The pokemon replacements for the roamable Latios and Latias you get to
            choose after beating the Elite Four for the first time. Normally, your
            options are RED and BLUE, meaning Latias and Latios, respectively.
            When you randomize event pokemon, these options will become new
            adjectives. Check this to see what pokemon coincide with which option.
      - Pickup Items
            The chart of items a pokemon with the Pickup ability can retrieve.
            


10) Quick Settings:
------------------
    Too lazy to fill out all those options? Click one of these to auto-fill
    everything for you!

      - Low
            Changes a lot of options, but doesn't make anything too crazy.
      - Medium
            A bit of this, a bit of that. Good for a decent challenge and fun
            playthrough.
      - High
            Only for die-hard fans. Be prepared for a lot of random fun!
      - Arty's Choice
            The program creator's option choices. Somewhere between Medium and High.
      - Random
            Not enough randomization for you? Then randomize your randomization
            choices with this! Every checkbox has a 50% shot at being checked and
            every bubble has an equal chance of being selected!
      - Clear All
            Remove all chosen options and default back to a clean ROM's starters.


11) FAQs/Why the heck won't this work?!:
----------------------------------------
    I've had a lot of mail about the program not working through the years. To
    address this, I added a few features to help troubleshoot.

    First up, when you load a ROM, the program will perform a hash on the file to
    see if it matches the base ROM I used (and the only one I could find at several
    places and dumped from my own game cart). This would be an English-language game
    for the US. I don't know if the UK, Australian, or other English-language ROMs
    work, but I am most certain that foreign-language ROMs won't work. They have
    different addresses than those hard-coded into the program.
      So, if you get a message saying 'The base ROM does not match the target ROM
    this program was intended for!', use that as a warning that you may need to
    acquire a different version of the ROM.

    Secondly, I tried redirecting any output to popup messages when the game is
    being saved. If anything comes up and errors the game out, let me know. You,
    as the program user, should now see what the error is instead of it being hidden.

    Thirdly, I made it so that the program no longer saves blank ROMs if you exit
    without a proper save. This was likely a big factor in a few questions I got.

    Finally, the game now displays a pop-up to tell you that it has successfully
    saved any changes you made. This way, you'll know everything went through as
    expected.

    Q: Does this work on Macs?
    A: Unfortunately, no it does not. I don't have the means to test and troubleshoot
       why, so you Mac users will have to find a PC to save your ROM changes with.
       The ROM ought to play fine on Macs, though, so just transfer your changed game
       once you're done randomizing to play it on your own machine.

    Q: I open the program and nothing lets me choose any options. Why?
    A: You need to load a ROM first. Nothing is available until you do so, and no,
       I will not supply the ROM for you. Dump the game yourself or get it through
       less legal means.

    Q: Why are some options greyed out even after I loaded a ROM?
    A: Those options are only relevant when certain randomization options are
       chosen. They'll become available once you make selections that they pertain
       to.

    Q: I got some message about the base ROM not matching the target ROM. What is
       this?
    A: Your ROM doesn't match the one I used to make this program compatable with.
       Either your ROM isn't a true dump, it's not Pokemon Emerald, or there was
       some weird error with your file. Trying getting it somewhere else.
         Additionally, this may show up if you try re-randmizing an already
       randomized ROM. This is normal -- your game is different than a base ROM
       after being randomized. It should still work if you save new changes, so
       just ignore the message in this case.

    Q: I selected 'Ensure all Pokemon Appear', but I couldn't find them all in the
       wild. What gives?
    A: Depending on your Wild Pokemon randomization options, you won't actually be
       able to find all pokemon in the game. There are 386 total pokemon, and FAR
       less substitutions if you chose 'Global 1-1 Substitutions'. The program did
       its best within these limitations. You can always re-randomize just the
       pokemon to fill your dex, though.

    

12) If you find a bug...:
-------------------------
    Please report it to me! I tried a bunch of different options and fuzz tests.
    Everything seemed fine, but something may have slipped through the cracks. If
    you find something that broke the program, shoot me an E-mail at:
       Artemis251(at)yahoo.com
    with the title mentioning something about the Emerald Randomizer. I'll fix it
    as fast as I can and get back to you (assuming it was actually a bug and not
    misusing the program...).


13) Special Thanks:
-------------------
    Dabomstew - For providing assistance finding both the Obedience Bit for Mew and
                Deoxys and for letting me know how the roamable Latios's bytes were
                set up.

    Many Gen III Tool Creators - They made some sweet tools that saved me tons of
                time locating specific addresses for different things. These
                include the following (look them up and try them out yourself!):
                    - Advance Map
                    - Advance Mart
                    - Advance Starter
                    - Advance Text
                    - Advance Trainer
                    - unLZ-GBA
                    - Universal Pokemon Randomizer
                    - Yet Another Pokemon Editor (YAPE)


14) Final comments:
-------------------
    I think that about wraps it up! Enjoy, and I hope you have a blast rediscovering
    the game, playing through it differently each time! Doing Nuzlocke challenges
    here would be pretty fun, I'd think!

