[ludum-dare](ludum-dare.md)
# mission statement!!!!
our purpose in joinging ludum dare, in order of importance, is....
1. FINISH SOMETHING. just create ANY kind of game that is ACTUALLY PLAYABLE by OTHER PEOPLE and available to them online!!! prioritize "complete enough to more or less be played" over "good" or even enjoyable... 
	- primary goal is literally just "can be experienced as a functional, 'complete' game with a start and end"; second goal is to accurately express my thoughts/feelings, third goal is that people might actually enjoy playing it, and fourth goal is for it be considered "good"
	- the main reason behind this goal is to gain experience with those later parts of the creative/development process that we don't usually get around to! (and maybe learn how we feel about finishing projects and whether maybe it DOES feel good or worthwhile after all.) secondary reasons are to finally have something to share with people when they ask "what kind of art do you make" or to put in a portfolio (??? ew it sounds so gross to even say, lmao), and to express my particular feelings about these themes (the "i'm not ready for it to end yet" feelings, the value of fleeting moments) because maybe they can inspire someone, and to [[build-in-public|build in public]] for similar reasons of maybe it can inspire another person to make something even cooler.
2. practice/learn javascript
3. to a lesser extent, learn about game and software development in general - try to take notes afterward about lessons you learned from the experience
4. participate in the community, share ideas, give and get feedback
5. make something i feel proud of and feel like i can show off

## rules
- dont take it too seriously!!! we are here to fuck around and fuck up and just see what happens
- real life and friends come first. don't pass up special things just to work on this. there will always be more game jams and you can always jsut submit a worse/smaller game.
- sleep is sorta negotiable as long as you have a plan for catching up afterward. meds and food are NOT negotiable.
 
# brainstorm 
### phase 1
- just use plain javascript and canvas, don't worry about webgl or phaser or frameworks or anything
- using magic to keep a day/vacation/etc from ending..???, i guess this could be the potion thingy!! you use your time to gather ingredients to make more delay-time potions, but its imopotant that you also collect something else so that it doesnt feel completely futile or pointless..... every time you go ingrdient hunting (atelier style) theres a random cahnce to find some ssouvenier that adds to your collection? or you get a snapshot/journal entry of some fun experience (e.g. with friends) that you had that day? .... ok ok this sounds really cute actually.!!!! i am.. feeling better about this one than the cat one, maybe, yeah......!!!
- a pretty good solution about making it not depressing: the inevitable thing isn't the goal of the game but it make lore sense for it to be the intended outcome; you want it to happen, but just not QUITE yet, not until seomtrhing else happens first.  examples of that feeling:  not wanting a good book to end yet; finishing a good meal; if you like your school, graduation; kids growing up or whatver, suppopsedly;


### phase 2
-   ui should look like a journal??
-   game starts with x days left in your trip
-   each day starts with a day planner interface for choosing what to do (go out looking for ingredients)
-   another screen for making potions/spells - maybe the end of each day, or maybe it's one of the daily activities you can choose in the planner
-   like atelier, you pick a location and then it shows you several different spots where you can click, and each one has different possible random events/gives you a random number of some material
-   maybe one nature scene (trees, flowers, herbs, stream.... but can i avoid it looking exactly like atelier annie www... some cute fluffy moss.. maybe a cute fluffy critter as well...!) and one urban scene (maybe like a boardwalk?? or smth with ocean visible at the side. defintely a cafe and maybe also a street vendor food stall thing... maybe a magical supply shop too)
-   goal of the game is fill up a scrapbook or list of journal entries - each one is either a souvenier you collect, a photo, or a written journal entry. when you finish the game it shows you an overview of your scrapbook. important that this can persist between replays!!
-   literally jsut dont even bother thinking about the time paradox logic lmao were just gonna ignore that shit
-   some incremental mechanics would be neat, e.g. growing a plant in your room instead of just picking leaves... ok wait no a Number Go Up thing doesnt really work for that
-   the effectiveness of your spell depends on the quality of the ingredients you colected; weaker ingredients will extend the timer only 1 day, better ones for longer
-   the final day AKA end of the game will alawys present the player one last chance to cast a spell with just Whatever They've Got On Hand
-   are there other potions/spells to make besdies the time one???
-   limited number of clicks you can make in the explore scenes each day?? maybe the measure for this is a 'where is the sun' meter like in pikmin and it moves a certain amount on each interaction. 
-   there's not really multiple endings. no matter what happens, your trip ends the same way. it's just about how amny experiences you get the cahnce to see--progress is measured just by how much of your journal you filled up. (might actually measure this in metaphorical journal pages and say "i filled x% of my journal" in the ending screen?)
- more of a "time bubble" spell or something than a "rewind"--like, you're sort of creating days that shouldn't exist where the world is inherently slow and quiet and peaceful, instead of going BACK over days that already happened. kind of like a temporal safe space/safe haven.

#### scrapbook entries to collect....!
-   a few photos of shenanigans with friends (ok ok just one i guess lol)
-   flowers, herbs
-   a seashell from a visit to the beach
-   picture of cute food or cafe drink
-   something like a feather?? (or maybe thats jsut an ingredient)
-   stickerrrrrr
-   dryadella?!! [but that would be so sad to pluck www and hard to draw....] but drawing issues aside, maybe it coudl jsut be ascrapbook memory that you saw one and sketched it (and thats special because in this world its a literal dryad/living creature, or just a flower that more literally looks nymph-shaped)  
    
#### spell/potion ingredients:
-   definitely a few different kinds of flower/ herb/ leaf/ plant: 
-   feathers froma  certain bird, maybe a raven but probably i want sometihng more whimsical
-   some kind of stone, maybe from a river, or maybe like a special-shaped stone? (maybe one of the less obvious things to find--maybe you need to go somewhere that you run nto another character and they give it to you) or like yuo can get the low level version from the stream but the best one you need to get froma  friend. the stone with a hole in it thing???
-   maybe there's some plant which you can choose to either like just pick the leaves as they are but they're not fully mature, or you can take a whole little sprout/seedling home and take care of it, which will give you better leaves (choice is jsut what you click on in the collecting scene)
-   lol maybe there's a bunny or soemthing int he scne but if you click on it it jsut tells you that it hopped away www liker you cant actually colelct anything from it, and if ytou need something like rabbit fur or whiskers ro something then you actually need to click somewhere else to look for them

# design spec
## concept
> it's your last week away from the magic academy on study abroad, but you're not ready to go home just yet. collect materials to cast a spell that will let you sneak a few extra days into the calendar and make a few more memories before it's time to go. 

most important things to express to the player:
- sense of wonder and exploration
- appreciation for fleeting moments and small simple joys

main points of value (ie, if i were a player, what would i be expecting to get out of it? what would draw me to this game as opposed to all the others? what can it offer that's somewhat unique?):
- overall vibe/aesthetic/tone conveyed by visuals and writing - could maybe be sort of a cozy comfort game
- theme/message
- cute (hopefully!!) art
- process of exploration and discovery
 - goal of completing a collection

### objective 
- fill up a scrapbook by triggering/collecting a set number of memories or journal entries
- method: collect ingredients -> cast spell -> extend gameplay time
- gameplay is motivated by wanting to discover this world and Have Experiences rather than pursuing an ending
	- ending should show player what percent of the scrapbook they filled and encourage replaying to get different journal entries, but *not* frame 100% journal completion as "winning". 
- *no multiple endings* - the closing text is the same no matter what - you're not trying to change your fate you're just trying to collect experiences along the way. 

### target vibes
- *tone:* bittersweet, but mostly sweet. playful and whimsical with just a hint of hashtag-relatable wistfulness. ideally, could create a very small catharsis around the player thinking about times you had to leave from a trip/special place/part of your life before you felt ready, and wishing you couldve had this "just one more day" chance irl too--not sure yet how to make good on that, current framing maybe leans toward "its depressing to think about how this works out so nicely here but doesnt work in real life" so maybe could benefit from the ending addressing that more and emphasizing that it's not perfect.
	- lighthearted <-- 1 **(2)** 3 4 5 --> serious
	- no true fail/lose state - maybe you can fail to make the big spell but you still gather some memories in your 3 days

#### themes
- it's the little moments that make life special (magical!)
- feelings of wonder at discovery, especially tiny discoveries like One Really Nice Flower
- being a goofus with yr friends; lazy summer days spent just hecking around together
- you can't stay in a special place forever but that's okay, it's enough to just appreciate it as much as possible while it lasts (time is fleeting; your magic lets you shape it into something a little more merciful, but you have to acknowledge that you can never control or outsmart it)
- feelings of safe haven and sanctuary; taking a pause to recharge before carrying on with something hard (knowing it's limited but appreciating it just as much nonetheless)
- maybe the act of playing this game can itself serve as a similar kind of "escapism as restorative sanctuary, just for a little while, but perhaps enough that these tiny moments of happiness can form a source of strength to draw on when life is hard", to stand in for the actual time-slowing magic that we lack in real life. because the one kind of magic we do get in this world is storytelling. (well i mean, that and like, nanotechnology.)

### inspo
- atelier games: general gameplay premise
- little witch academia and kiki's delivery service: aesthetic, vibes of being a witch in training. player here is implied to be a little older though - so maybe a little more like switchcraft's vibes for what the school and friends are like. 
- owl house is minor inspo for "witch in training vibes" and "discovering a magical world"  but the aesthetic and tone here should definitely not be that wacky (?), more soft and ghibli-esque. 
	- but like if we are gonna compare to owl house, this game would fall entirely within luz's ep 1/2 attitude of being enchanted with everything; protag is still very much romanticizing this setting, and the game should portray that perspective as truth, not question it.
- "lofi for witches (only)"
- animal crossing: general atmosphere and emotional experience of playing, relaxed pace, slightly utopian worldview; would love for it to be a game you can go to for comfort in a similar way to how i look to animal crossing for comfort

### 

## world/lore/story
- whimsical but relatable low fantasy
- setting feels like a place you can imagine actually vacationing to, aside from a small few fantastical details here and there (relatable as a romanticization of an irl vacation memory)
## mechanics
### end state
- game ends when there's no more days in your calendar
- *OR* game ends when all memories have been found
- *stretch goal*: something that prevents player from extending time infinitely
### gameplay flow
#### flowchart
[witch game (whimsical.com)](https://whimsical.com/witch-game-7ji4YugZ4A4nVsbZQQdAF6)
![flow](Pasted%20image%2020220402224959.png)
#### description
- intro text
- main gameplay loop
	1. day init
		- decrease number of days left - `days--`
		- reset "times gathered/explored today" or "time of day" variable 
			- `numExploresToday = 0`
		- reset current location variable
	2. where to go today? (pick a location from daily planner) 
		- set a var for current location
		- need to tell player how many days left
	3. gathering (pick a part of the scene to explore)
		- repeats 3-5? times
		- variable scoped to the day checks how many chances are left
			- if chances are used up, progress to end of day scene
				-  `if (numExploresToday > dailyChances) `
			- else, 
		- *stretch goal*: results/available events depend on time of day aka how many times we gathered already today
	4. 
- ending
### progress tracking
- days left (starts at 3, casting spells increases it)
	- the amount increased depends on the quality of spell materials used
- scrapbook (memories collected)
- inventory
- number of exploring/gathering chances left today
	- *stretch goal*: change "number of explores left today" to a daylight / time of day / time until sunset system (like pikmin!)
- player's current location
- *hidden:* total number of days played
	- *stretch goal:* impose some hard limit on this--some function checks each morning whether the total number of days exceeds some limit and triggers an ending scenario if so, regardless of days remaining on calendar
### stuff the player can do
#### gathering resources

#### spells
- just the one for now!!! "time bubble"???
### stretch goals
- minigame/interactive element to cast the spell, like in switchcraft
- more spells
## ui
### screens needed
- day planning: (**mandatory**) first screen when you start each day, lets you choose where to go
	- include **buttons to check inventory and spellbook** (aka list of required materials), unless these are constantly available in the global ui
- maps where you collect resources or have encounters
	- choose exactly where in the area to search/interact by clicking on the map, like in atelier annie or bcm 
		- *how do we make this accessible???*
	- scenes to choose:
		- **mandatory**: a nature/woods/park scene
		- preferred: an urban scene 
		- stretch goal: another naturey gathering scene; school or dorm or bedroom scene
- **mandatory**: cauldron/hearth/altar - screen where you choose your ingredients to use and cast your spell
	- should show spellbook and 
- **mandatory**: inventory
- **mandatory**: spellbook, which is where you see what ingredients you need for the spell
	- ideally should interact with the inventory and show you like "2/3 collected", but can just be plain text if 
### global ui
- things the player should always (be able to) know:
	- how many days are left
	- current inventory
	- ingredients needed for the spell
- hud or menu buttons:
	- days left, maybe shown as "today's date"
	- current location?? probablyt not needed
	- button to check inventory and items needed for spell
	- days played??? probably not global, if even shown at all

## art
### plan
- start by drawing jsut like the FASTEST SHITTIEST POSSIBLE VERSION of everything ASAP.  take pictures with ur phone if needed, crop them to ugly squares if needed, just hurry and get them into the code asap. jsut make sure we have SOMETHING to work with even if its garbage.
	- on second thought, digital drawings will actually be fastter probably--if nothing else, draw them on ur fuckin phone, that still at least exports to psd for transparency
### assets
- [ ] **mandatory:** map of woods gathing place
	- [ ] look up something like "magical looking places" for ref/inspo (and check ur old pinterest!)
- [ ] map of town gathering place
- [ ] daily planner screen (can do procedurally if no time to draw)
	- [ ] ui for spellbook/showing required ingredients and for inventory can possibly just use the same background as day planner menu
	- [ ] ideally, player chooses what to do by clicking what look like doodles in the notebook: one for each explore area, plus inv, spellbook, and/or cauldron?
- [ ] **mandatory:** cauldron/hearth screen
	- [ ] stretch goal: animate the cauldron
- [ ] **mandatory:** scrapbook result screen
	- [ ] compiled image to show at the end, plus sprites for each individual item that can be shown when discovering them
- [ ] **semi-mandatory:** sprites for resources
- [ ] **mandatory:** pick a font!

### design notes
- all sprites (aka anything to be shwon on screen besides full backgrounds) should be displayed with a few pixel thick white border for a sticker-like effect
- no human sprites!! only items

## sound
- ???????

## code implementation
### plan
1. work on core game logic (flow of events, game state)
2. make a super barebones approximation of a ui (like even just plain html buttons), jsut enough to playtest
3. playtest and see how the code is working. if you hit major hair-pulling bugs, consider bailing for renpy/twine
4. if it's working, bring in the most important and non-ui-dependent images (backgrounds and sprites) and the story text
5. pseudo code whatver else of the mvp game logic you feel pretty confident about without having to read a lot about (i.e. don't bother with class constructors and crap for the inventory)
6. do we have mvp yet? if no, it's time to consider switching to renpy or twine. 
7. if yes, then we should be pretty confdient about sticking with js! time to flesh out that pseudocode 
8. fix up the ui and visuals (move from html elements to canvas)
9. now flesh out the rest of the code

### tools/technologies
- vanilla js + html... PROBABLY canvas
	- but it's possible we can get it functional faster using jsut regular html elements (buttons and stuff, text jsut in a plain text element displayed below an image, even a dropdown menu for choosing where to explore) instead of clicking the image
	- 
- honestly you might consider making the art and writing first and saving the code for later so that if you run out of time you can try to make a quick switch back to something more familiar (and tbh better suited to this type of game) like renpy or twine


### function and variable names
```javascript
// constants
const dailyChances = 3 // how many times per day player can gather resources or click a place on a map

// update on each day start
days //how many days left to play

// reset on each day start
numExploresToday // how many times we have clicked a map spot so far today
currentPlace // 

```

# mvp
- intro text
- day planner and combined inventory/spellbook - these can be rendered with code
- one map to explore, 3 clickable areas, each has 1 resource type and 1 possible memory
- 
- ending screen showing the final scrapbook - one of the most important visuals!!
- ending text
- start game > daily planner > explore (gather a few resouces and a chance for a memory) > try to cast > sleep, start new day, repeat those things > hopefully can cast spell now > repeat more days, having more chances to find a memory > 
# next steps to do
## tasks
- [ ] look at examples of javascript point and click games - how do they do inventory? ui?
- [ ] watch videos on the dom, let vs var cs const, on general game design eg game states, etc - while sketching game asset designs (maps, items, ui)
- [ ] start defining the varibles and constants
- [ ] start defiing functions for core game flow/states