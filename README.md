# Dustforce DX Beginner to Intermediate Guide #

*by czyys*

![95.png](Resources/95.png)

<br />

## Table of Contents ##

* [Introduction](#introduction)  
* [Before you begin](#before-you-begin)  
	* [Helpful tools](#helpful-tools)
	* [Keyboard or Controller](#keyboard-or-controller)
	* [Controls scheme](#controls-scheme)
	* [Dustmod settings](#dustmod-settings)
	* [Basics](#basics)
	* [Characters and their differences](#characters-and-their-differences)
	* [General mindset](#general-mindset)
* [Movement](#movement)
	* [Dash to move](#dash-to-move)
	* [How dashing works](#how-dashing-works)
	* [Downdash](#downdash)
	* [Jumping](#jumping)
	* [Walljump](#walljump)
	* [Walldash](#walldash)
	* [Corner boosts](#corner-boosts)
	* [Ceiling run](#ceiling-run)
	* [Ground boosting](#ground-boosting)
	* [Slope boosting](#slope-boosting)
	* [Dash rhythm](#dash-rhythm)
	* [Slant boosting](#slant-tboosting)
	* [Ledge jump](#ledge-jump)
	* [Ledge cancels and Mantles](#ledge-cancels-and-mantles)
	* [Slopejump](#slopejump)
	* [Spikejump](#spikejump)
* [Combat](#combat)
	* [Clearing dust through walls](#clearing-dust-through-walls)
	* [Changing directions of attacks](#changing-directions-of-attacks)
	* [Super attack](#super-attack)
	* [Buffering](#buffering)
	* [Canceling recovery animations of attacks](#canceling-recovery-animations-of-attacks)
* [More advanced stuff](#more-advanced-stuff)
	* [Holding 'left' and 'right' at the same time](#holding-left-and-right-at-the-same-time)
	* [Dashjump](#dashjump)
	* [Mapler slide](#mapler-slide)
	* [Hitrise](#hitrise)
	* [Hitstop](#hitstop)
	* [Jorf](#jorf)
	* [Spikestand](#spikestand)
	* [Clipping](#clipping)
	* [Facing](#facing)
	* [Deadleg](#deadleg)
	* [Super attack cancel](#super-attack-cancel)
	* [Time dilation](#time-dilation)
	* [Left friction](#left-friction)
	* [Iteration order](#iteration-order)
* [Getting better](#getting-better)
	* [Improving ranks](#improving-ranks)
	* [Using editor anywhere](#using-editor-anywhere)
	* [Comparing replays on dustkid.com](#comparing-replays-on-dustkid)
	* [Replay ghosts](#replay-ghosts)
	* [Other resources](#other-resources)
* [Closing words and credits](#closing-words-and-credits)

\
<a name="introduction"/>

## Introduction ##

This guide is made for those only starting or having just started their journey with Dustforce, however I expect even players with the Steam achievement to learn something new by going through it. Players thinking about, or maybe even set on focusing on climbing stock maps’ leaderboards in the long run should find it especially helpful. 

It provides information I wish I knew when I was learning the game myself, so it’s just my own perspective and input on improving your skills. I’m a mostly inactive Dustforce player with a little over 2000 hours of playtime, most of which was spent on playing custom maps, the rest on playing stock maps and making my own customs. I’ve had ideas popping into my head for a guide like this for a long time, in fact my very first custom map was an attempt at a simple tutorial level, which is now hidden on Atlas as it became obsolete with the release of this guide.

\
<a name="before-you-begin"/>

## Before you begin ##

I want to emphasize that you’re not meant to complete this guide in one go, before moving on to playing any nexus maps, especially if it’s just your Dustforce beginnings. This guide covers techniques which some players start learning only after getting SS on most of the stock maps. Go through it at your own tempo, leave it after learning new tech, play some maps then come back later. You can also go through “Movement” and “Combat” sections independently.

<br /> 

<a name="helpful-tools"/>

### Helpful tools ###

* Get Dustmod from http://dustmod.com/. It has many great features some of which are very useful for getting better at the game. If you already completed some stock levels and want to copy over your progress then start Dustmod, when in-game go to Dustmod → Tools → Save → Download. It may mess up info at the bottom about the keys you’ve gotten. As far as I know you can continue playing and everything should end up fine.
* On https://dustkid.com/ you can find information about your Dustforce profile with all the replays you submit. Once you finish playing any level open the site and it should ask about confirming your profile. Another thing worth taking care of right now is enabling watching replays from the dustkid website and for this you need to run dustmod.exe just once as an administrator. After this you have to run it normally.

If you run into any technical difficulties during these two steps ask people from Dustforce community for help over at r/dustforce or in the Dustforce Discord server.

- - - -

<br /> 

<a name="keyboard-or-controller"/>

### Keyboard or Controller ###

Whatever you find more comfortable. There are or were top players using either. Until you become considerably experienced with the game you won’t be able to take advantage of unique differences each offers. 
If you decide to pick keyboard, whether to you use a mechanical one is up to your own preference as well. There are even players who prefer arcade sticks.
I use keyboard - Cougar 200K, although first half of my playtime was mostly on a laptop keyboard.

Whatever you choose it’s very important to make sure your control scheme doesn’t suffer from ghosting (more on that below).

- - - -

<br /> 

<a name="controls-scheme"/>

### Controls scheme ###

Here is a spreadsheet with bindings some players in the community use - https://docs.google.com/spreadsheets/d/1jRj5AwVUZjaTHa-s4hkeCyT0mikM3cAQnAR6-RYr7OA/edit?usp=sharing (for majority of the levels I use 8456 for directions and zxcv for dashing, jumping, light attacks and heavy attacks in that order). 

Controller players using analog stick have to deal with potentially less precise inputs. For keyboard it’s important to note that if your control scheme makes use of your pinky and ring finger, actions dedicated for them will probably be more difficult or taxing to execute. That’s why you can see most players not using pinky for dashing.

Make sure that with your bindings you can comfortably do combinations of non-direction inputs in quick succession, for example dash → jump → light, or jump → dash → 2x light → heavy. One of the reasons I use pinky for dashing, even though many people refrain from it, is that it makes the natural progression of dash → jump → attacks very easy to execute (I do use another finger if the map is heavy on dashing).

Other than that choose whatever feels comfortable. You can always adjust bindings later, when you learn new tech. 

The last important thing is to check if your control scheme is safe from ghosting.

Open this page - https://drakeirving.github.io/MultiKeyDisplay/ and test these keys combinations holding:

* dash + jump + up + left
* dash + jump + up + right
* dash + jump + down + left
* dash + jump + down + right

* light + heavy + up + left
* light + heavy + up + right
* light + heavy + down + left
* light + heavy + down + right

<br />

If all keys lit up for every combination then you’re good to go. If any weren’t possible then you should change your bindings, or in worst case scenario change your keyboard/try a controller.

- - - -

<br /> 

<a name="dustmod-settings"/>

### Dustmod Settings ###


Here are relevant settings I recommend using:

* Display → Overlay → Show Input Display (adjust size and color to your liking) – self-explanatory, works for replays as well.
* Tools → Editor → Editor Anywhere – allows to enter editor mode at any moment with 'tab' key. It’s extremely useful as it allows you to practice levels from wherever you place the player spawn, but more on that later. Though in case you decide to try it out now just remember that **completing a level from start to finish while in editor mode makes your replay invalidate.** If there’s a flag (or any other icon for that matter) in the top right corner your replay won’t validate. Simply exit the level to remove the flag icon.

- - - -

<br /> 

<a name="basics"/>

### Basics ###


If you went through the stock tutorials without carefully reading all the instructions then go back and do it now. They cover only some of the essentials, but it’s necessary to make sure you haven’t missed anything.

One thing they don’t mention is the conditions to get a double S rank when completing a level. You need to: 
* collect all the dust in the level
* clear all enemies
* avoid dropping combo

You can drop combo either by: 
* getting hit, touching spikes, death zones etc.
* collecting dust and failing to collect more in 5 seconds


- - - -

<br /> 

<a name="characters-and-their-differences"/>

### Characters and their differences ###

By this point you should be at least somewhat familiar with Dustman, as he’s the only character available in the tutorials. Dustgirl is very similar to him but Dustkid and Dustworth have some significant differences.

A more detailed breakdown is available here – https://www.dustforce.info/#playable-characters

Generally you can trust the in-game top 10 leaderboards in what character is optimal on each map. Feel free to experiment though and play whatever character feels best to you for a particular map. There are even players who main only one character.


- - - -

<br /> 

<a name="general-mindset"/>

### General mindset ###

In Dustforce your character carries a lot of momentum which can’t be easily redirected just by using direction keys. Most of the actions aren’t instant and instead have windup animations. It’s why most input decisions are commitments and mistakes are hard to correct during a run, especially fast. It definitely takes time to get used to it so don’t be discouraged when your beginnings look a bit shaky.

If you ever find yourself in a situation where you can’t perform some simple technique for no apparent reason, it is most likely you either not being aware of something or just making a mistake. For example, I kept forgetting to hold ‘up’ to wall run.

Lastly, Dustforce doesn’t include any rng elements affecting gameplay, which is one of the reasons why getting better feels satisfying.

\
<a name="movement"/>

## Movement ##

<a name="dash-to-move"/>

### Dash to move ###


Just like it was mentioned in the Beginner Tutorial level, dashing puts you at full running speed (or almost full in case of Dustworth) immediately. Dash whenever you want to start running. When you land on the ground some amount of ground friction is applied to your character, so dash after landing as well.

![1.webp](Resources/1.webp)

Here you can see me lose some speed when I land on each platform.

\
![2.webp](Resources/2.webp)

And here even when I lose speed I’m back to running because I dash right after touching the ground.


- - - -

<br /> 

<a name="how-dashing-works"/>

### How dashing works ###

While we’re on the topic of dashing, it’s good to understand how exactly it works:

* Ground Dashes
	* If your speed is below your normal running speed it immediately puts you at it and locks your momentum for 12/13 frames (There's 60 frames in a second).
	* The same applies if your speed is above it with one important difference – it locks your momentum at your current speed.
	* You can cancel out of it by jumping, wallrunning or attacking.

* Air Dashes
	* Point 1 applies the same.
	* Point 2 is more complicated and I’m not going to get into it in this guide. For now don’t worry about it.
	* You can cancel out of it only by jumping and wallrunning.
	
- - - -

<br /> 

<a name="downdash"/>

### Downdash ###

Stock tutorials fail to mention it but you can perform a technique called downdash in Dustforce. It gives you significant downwards speed if you didn’t have much of it to being with.

There’s one condition for executing it – your character can’t be rising, or to be accurate, can’t be in a state called raise (more on that in the <a href="https://github.com/czyys/dustforceguide#ledge-cancels-and-mantles">Ledge cancels and Mantles</a> section). This also includes hitrise occurring after you hit most enemies (more on that later as well - <a href="https://github.com/czyys/dustforceguide#hitrise">Hitrise</a>). 

Simply hold ‘down’ and press ‘dash’ to perform a downdash.

- - - -

<br /> 

<a name="jumping"/>

### Jumping ###

If you’re not sure, for a normal ground jump there are only two kinds of it – low jump and high jump. If you hold the ‘jump’ key for the entire duration of jump squat animation (which in a usual scenario lasts 8 frames) you’re going to do a high jump. Holding jump any shorter will result in a low jump.

There is no height you can reach in between them by holding the ‘jump’ key shorter/longer like in some other games. And there is only one kind of airjump, you don’t need to hold ‘jump’ after you’ve pressed it.

If sometimes after jumping off a ledge you don’t seem to be able to double-jump, it’s because you pressed ‘jump’ while already being off the ground. You can differentiate normal groundjump from an airjump by the “cloud” below your character the second one produces.

![7.webp](Resources/7.webp)

- - - -

<br /> 

<a name="walljump"/>

### Walljump ###

The important thing to bring up here is that the sprite of your character doesn’t have to be touching the wall to be able to walljump. When you’re close enough to a wall, a jump input is going to magnet your character to it. This is why you sometimes might die to a spiked wall even though you’re not touching it.

![3.webp](Resources/3.webp)

Here’s me walljumping as early as possible.

\
![4.webp](Resources/4.webp)

And here’s how it looks like when the wall has spikes.


You can walljump while holding any directions, although holding the direction towards the wall is going to affect your facing (see <a href="https://github.com/czyys/dustforceguide#facing">Facing</a> section below).

Lastly, your speed after walljumping is always the same, it doesn’t matter if you’re holding the direction key away from the wall.

- - - -

<br /> 

<a name="walldash"/>

### Walldash ###

To perform a walldash you can’t be holding ‘down’ or the direction towards the wall. The magneting works exactly the same for walldashing. Interestingly you can cancel a walldash with a walljump even after you leave the wall but are still within magneting distance.

Make sure to delay jumping after walldashing enough.

![5.webp](Resources/5.webp)

- - - -

<br /> 

<a name="corner-boosts"/>

### Corner boosts ###

![91.png](Resources/91.png)

To go fast through sections like the ones from the image above you do what is called a corner boost. This practice map explains how to do them – dustforce://installPlay/9256/GUIDE1 (**Play using Dustman for all of the practice maps**).

Copy the link into your browser's address bar. If you’re having issues installing the map run dustmod.exe as administrator just once.

Just in case here’s a clip of me doing the first one in slow motion, so you can easily follow the input display.

![6.webp](Resources/6.webp)

- - - -

<br /> 

<a name="ceiling-run"/>

### Ceiling run ###

You may have noticed, that if you ceiling run for too long you start to slow down considerably. That’s because there’s no ceiling friction only for the first 1/3 of a second. After it kicks in you start to slow down and you’re glued to the ceiling (you can’t even downdash) for a short amount of time. It disrupts the flow of the run so make sure to avoid it by releasing the ceiling early enough. 

And here’s another practice map – dustforce://installPlay/9257/GUIDE2

- - - -

<br /> 

<a name="ground-boosting"/>

### Ground boosting ###

It’s one of the core techniques of Dustforce and it refers to boosts started on a flat ground. Whether you’re able to even get a groundboost depends on the angle you hit the ground at. Without going into technical details, you have to make sure your horizontal speed is big enough compared to your falling, vertical speed.

Here’s how you set up groundboosts with each character:

It’s pretty much the same for Dustman and Dustgirl:

Dash → Lowjump quickly followed by Airjump → Downdash → Dash when you hit the ground.

![8.webp](Resources/8.webp)

![9.webp](Resources/9.webp)

\
Inputs for Dustkid are a bit different:

Dash→ Highjump → just before you reach the top of the jump arc Dash -> immediately Jump → Downdash → Dash.

![10.webp](Resources/10.webp)

\
Dustworth does the same inputs as Dustman and Dustgirl, but the setup is considerably more difficult. The window for the downdash is very small, because downdashing at greater height results in angle with the ground being too big for the boost to work. 

![11.webp](Resources/11.webp)

\
You can also of course get ground boosts simply by utilizing the geometry around you, for example by downdashing or simply dropping from a higher platform. For the normal running speed (after you dash from standstill) 5 tiles height is very good to get a boost.

![12.webp](Resources/12.webp)

\
With time you will learn where you can go and where you can’t go for groundboosts.


- - - -

<br /> 

<a name="slope-boosting"/>

### Slope boosting ###

Increasing then keeping your speed after landing on a 45<sup>o</sup> angled ground is called slope boosting. As long as you’re not going backwards you don’t have to worry about the landing angle necessary for the boost to work.

Make sure to also hold ‘down’ until you leave the slope or you’re going to slow down if your dash rhythm isn’t frame perfect.

![27.webp](Resources/27.webp)

<br />

It’s also worth noting that in situations where you can’t get a good slope boost, for example because there’s no way to gain much falling speed and your horizontal speed isn’t big, it’s better to simply slide down the slope.

Sliding down a slope has a relatively low maximum speed, that's why it’s rarely the optimal strat.

- - - -

<br /> 

<a name="dash-rhythm"/>

### Dash Rhythm ###

Speaking of dash rhythm, If you’ve noticed me chaining dashes together in the last ground boosting clip, it’s how you maintain your speed in Dustforce. Pressing ‘dash’ repeatedly at correct intervals to keep as much speed as possible is referred to as dash rhythm. 

Without going into technical details, optimally dashes are inputted in a pattern of 12 and 13 frames intervals. Ideally you want to dash as soon as previous dash ends, this way you keep all of your speed. The bigger the break between dashing the more speed you lose, but if the break is too small you drop the dash entirely.

If it’s just your beginnings with dash rhythm try to focus on making it consistent and not dropping any dashes rather than going for very good intervals. Delaying the dashes for a few frames doesn’t loose that much time if the boost isn’t long and especially when compared to missing a dash.

Try this practice map – dustforce://installPlay/9258/GUIDE3

And if you want, play this custom map – dustforce://installPlay/4999/Slope-Boost-Rhythm

For practicing extended dash rhythm you can consider enabling Boost Trainer which you can find in Dustmod → Tools. What also helps some players is a 275 BPM metronome playing in the background.

- - - -

<br /> 

<a name="slant-tboosting"/>

### Slant Boosting ###

Ground angled at ~26<sup>o</sup> is referred to as a slant and usually you boost off of it while not having much height. For example downdashing directly from a 5 tiles high platform is too much for normal running speed. In the clip below I’m decreasing my height a bit first.

![13.webp](Resources/13.webp)

- - - -

<br /> 

<a name="ledge-jump"/>

### Ledge jump ###

When you ground jump your character enters jump squat animation before leaving the ground. If you’re boosting and press ‘jump’ the squat is going to kill nearly all of your speed. However you can cancel that animation by leaving the ground before it finishes. You’re going to jump at the very edge and your speed is going to be preserved.

Try it in this practice map – dustforce://installPlay/9259/GUIDE4

![14.webp](Resources/14.webp)

Only 2 frames of jumpsquat, normally it takes 8.

- - - -

<br /> 

<a name="ledge-cancels-and-mantles"/>

### Ledge cancels and Mantles ###

Dustforce Helpdesk has a very good video about them - https://www.youtube.com/watch?v=7v9-kxYOg0g

Keep in mind mantles are usually much more difficult to execute than ledge cancels. Try to implement them only after getting some more experience with the general movement.

- - - -

<br /> 

<a name="slopejump"/>

### Slopejump ###

When sliding down a slope you can jump without going through the jump squat animation. It does however still kill pretty much any boost you might have. 

![15.webp](Resources/15.webp)

It’s used really only in top runs where every frame matters and jump squat wastes a few. I’m explaining it in this guide though because you might do it accidentally and wonder if something weird didn’t just happen.

- - - -

<br /> 

<a name="spikejump"/>

### Spikejump ###

Probably the most well known tech which obviously makes use of questionable way the game’s logic works on slopes. It allows you to immediately jump off of slopes (so only ground angled at 45<sup>o</sup>) even if they have spikes. And it’s fairly easy to perform. 

When you’re in the air and don’t have any aircharges left (it’s what you use up when you dash or jump in the air), land on a slope while holding ‘down’ and ‘jump’. If you used your aircharge on an airjump make sure to also release the ‘jump’ key and hold it again. Just like downdashing, spikejumping works only if you’re not rising.

You can control the direction in which you’re going to jump off by holding ‘left’ or ‘right’ or not holding any of them.

Even though it’s called “Spikejump” it works the same way on slopes without spikes.

![16.webp](Resources/16.webp)

\
<a name="combat"/>

## Combat ##

<a name="clearing-dust-through-walls"/>

### Clearing dust through walls ###

In Dustforce you can hit enemies through walls, but with up and down attacks you can also clear dust through walls (ceilings and floors too for that matter). It’s extremely useful so always keep it in mind when figuring out strats for a map. 

Play this practice map to test how it works – dustforce://installPlay/9260/GUIDE5

Try replaying it after clearing all the dust to test different attacks. You’re going to notice that for some geometry up and down attacks aren’t the best option.

- - - -

<br /> 

<a name="changing-directions-of-attacks"/>

### Changing directions of attacks ###

It’s possible to change the direction of your attack after you’ve initiated it but the new direction has to be inputted within a specific window. 

Changing the direction from forward to back:

* light attack has a 2 frames window
* heavy attack has an 8 frames window

Changing vertical direction:

* light attack has a 2 frames window
* heavy attack has a 4 frames window

As you can see redirecting light attacks is very difficult and it’s something only very good players utilize effectively. 

You also have to keep these windows in mind when you start holding the opposite direction but don’t want to reverse your attack. This concerns heavy attacks in particular.

When you want to do a backheavy while moving forward in the air, it’s important to not hold the back direction for too long or you’re going to lose a big chunk of your speed. However if you still have an aircharge, you can dash, then backheavy. It should be much easier to keep your speed this way as dashing locks your momentum for a bit giving you time to input the back direction.

![17.webp](Resources/17.webp)

- - - -

<br /> 

<a name="super-attack"/>

### Super attack ###

Combat Tutorial doesn’t mention that using the super attack gives back your aircharge/s, even if it doesn’t clear anything. It’s also good to know what its range is more or less, for enemies and for dust.

![92.png](Resources/92.png)

Square checks for enemies, circle for dust and dustblocks.

- - - -

<br /> 

<a name="super-attack"/>

### Buffering ###

Buffering refers to pressing or holding down a key to start an action before the condition for its start have been met. Once they’re met the action begins immediately.

In Dustforce you can buffer any action (but not in any situation) not related to dashing. Some examples:

* Holding down ‘jump’ while the windup animation of a heavy attack is still in progress. When it finishes you begin the jump.
* Holding down ‘jump’ when out of aircharges and getting close to a wall. Once you’re close enough you start a walljump.
* Pressing the key for a heavy attack while still doing a light attack.
* Spikejump is a buffered slopejump (unless you press ‘jump’ on the very frame you land on the slope).

Buffering inputs is one of the key aspects of Dustforce as you often find yourself in situations where you have to wait for one action to finish before starting another. It ensures that the next action is going to start immediately, without losing precious time. This doesn’t mean you should buffer every input though. With time and by watching better players you should learn how to make good use of it.

- - - -

<br /> 

<a name="canceling-recovery-animations-of-attacks"/>

### Canceling recovery animations of attacks ###

When you start an attack it goes into its windup animation. After it finishes an enemy gets hit if its hurtbox and hitbox of the attack overlap during that one frame. Then your attack enters the recovery phase during which you can’t start another attack. 

That’s why you often want to cancel that animation and it’s possible to do it with:
* a jump, which can be buffered
* a dash, which has to be timed
* or by grabbing a wall/ceiling, which requires simply holding the right directions.

It gets interesting when you follow up the cancels quickly with another attack. Try this combination:

Jump → Buffer a heavy → During the windup animation buffer another jump and a heavy. 

![18.webp](Resources/18.webp)

\
Dash canceling is the odd one of the group because it requires timing the press of ‘dash’ after the windup has finished. Try doing this:

Dash → Immediately do a heavy attack → Wait for the windup to finish → Press 'dash' → Immediately heavy again.

![19.webp](Resources/19.webp)

\
It’s a very useful technique for dealing with enemies which take more than one heavy attack to clear. However when timing the dash presses you have to take into account hitstop which occurs on each connecting hit (check <a href="https://github.com/czyys/dustforceguide#hitstop">Hitstop</a> section below for more information).

\
<a name="more-advanced-stuff"/>

## More advanced stuff ##

This section covers tech, which for effective use requires being past the beginner phase of playing Dustforce. It also explains some not obviously apparent mechanics and oddities which are worth being aware of.

<br /> 

<a name="holding-left-and-right-at-the-same-time"/>

### Holding ‘left’ and ‘right' at the same time ###

It’s an issue which really can only occur for keyboard players. Sometimes, for example when changing directions the game might misinterpret your intentions and make your character dash the wrong way. It happens when you’re holding both ‘left’ and ‘right’ which game treats as not holding any of them. Because of this your character is going to dash in the direction it was facing before you pressed ‘dash’. For situations like this make sure to release the other direction key early enough.

- - - -

<br /> 

<a name="dashjump"/>

### Dashjump ###

(Not to be confused with the dash-jump mention in the Advanced Tutorial)

Once again here’s Dustforce Helpdesk video explaining all ins and outs of dashjumping - https://www.youtube.com/watch?v=ElrxwX0gtOg

If you’re having trouble getting dashjumps make sure you’re not holding ‘down’ by accident and check again if your keyboard or controller isn’t ghosting.

- - - -

<br /> 

<a name="mapler-slide"/>

### Mapler slide ###

Mapler slide is a technique used to extend the time you ceiling run without friction or simply to get more distance from it. 

You begin the ceiling run holding just ‘up’ then only after a short delay start holding the forward direction key.

Timing on the forward press depends on what you want to use mapler slide for: 
* For keeping speed the optimal delay is 15 frames for non-virtual Dustman, and 10 frames for all the other characters. That’s why from non-virtual characters Dustman is usually the preferred one when maplers are involved. 
* For distance, when you don’t have much speed to begin with, the delay should be longer. 

You can get good at mapler sliding by completing this map – dustforce://installPlay/4970/Mapler-slide-practice

Remember to still hold the forward direction key when slope boosting, then release it and start holding up during the dash.

![20.webp](Resources/20.webp)

- - - -

<br /> 

<a name="hitrise"/>

### Hitrise ###

→ Dustforce Helpdesk video - https://www.youtube.com/watch?v=R_nNLkGVZZU

- - - -

<br /> 

<a name="hitstop"/>

### Hitstop ###

When your attack connects with an enemy the game logic slows down almost to a halt for ~3 frames if it’s a light attack and ~8 frames if it’s a heavy attack. During those frames you can’t do anything besides buffering actions.

Another thing worth mentioning is that when buffering a jump + heavy before an attack is going to hit an enemy it’s important to start holding the heavy attack key only after hitstop has already begun. Otherwise buffering actually loses time rather than saving it.

![21.webp](Resources/21.webp)

- - - -

<br /> 

<a name="jorf"/>

### Jorf ###

You can stand on the corners of spiked tiles.

![93.png](Resources/93.png)

It’s possible to even jump and boost off of jorfs. They’re extremely precise but sometimes they just happen on accident.

- - - -

<br /> 

<a name="spikestand"/>

### Spikestand ###

It’s also possible to stand on the corner of slants. Spikestands are less precise to land than jorfs.

![94.png](Resources/94.png)

- - - -

<br /> 

<a name="clipping"/>

### Clipping ###

And one last time, Dustforce Helpdesk video - https://www.youtube.com/watch?v=W-Zd58F05mU

- - - -

<br /> 

<a name="facing"/>

### Facing ###

The direction your character is facing dictates what direction your attack or dash is going to be when you’re not holding ‘left’ and ‘right’.

You change your facing by:

* Running the other way
* Walljumping (only if not holding the direction towards the wall)
* Corner boosting (the same rule as with walljumping applies) or just ceiling running
* Doing 2 reverse light attacks or a backlight followed by a backheavy

![22.webp](Resources/22.webp)

- - - -

<br /> 

<a name="deadleg"/>

### Deadleg ###

Bottom left half of your character doesn’t have a hurtbox. What this means is that you can safely touch spikes with that part of your character.

![23.webp](Resources/23.webp)

- - - -

<br /> 

<a name="super-attack-cancel"/>

### Super attack cancel ###

If you do a super while grabbing a wall and then release it before the attack is finished, you’re going to cancel the super. It has practical use only in a few custom maps where it’s intended but can sometimes happen on accident.

![24.webp](Resources/24.webp)

- - - -

<br /> 

<a name="time-dilation"/>

### Time dilation ###

Attacking slows down the physics of your character to ~70%. The timer keeps running normally and all enemies behave normally as well. Check this demonstration:

![25.webp](Resources/25.webp)

You can see how long it takes Dustman to fall to the ground without and with some attacks. This is why it’s important to try and use attacks only when they can actually save time.

- - - -

<br /> 

<a name="left-friction"/>

### Left friction ###

Due to a programming mistake friction while going to the left is considerably more harsh than when going to the right. Check how long it takes Dustman to reach each set of white tiles:

![26.webp](Resources/26.webp)

- - - -

<br /> 

<a name="iteration-order"/>

### Iteration order ###

It is possible to clear all enemies and dust and get an A completion rank when finishing a map. It’s pretty complicated, so just know that it happens very rarely. But if it does happen try to do the final attack in a different position, because it might change the iteration order. If it doesn’t help, make sure you are indeed collecting all the dust and try asking people in the community.

\
<a name="getting-better"/>

## Getting better ##

<a name="improving-ranks"/>

### Improving ranks ###

Completing the guide up until this point gives you more than enough knowledge to be able to get better effectively. If you’ve only began playing Dustforce I recommend not focusing on climbing up the leaderboards just yet. First get comfortable with controls and physics of your character by getting SS ranks on some maps in the nexus.

When you start feeling confident try learning and implementing basic techniques like boosting and ledge cancels into your SS runs. At that point, if you’re interested in more than simply beating maps for SS completions, you should be ready to begin focusing on improving your ranks. 

Many players look at their position only on the “Score” (or SS) leaderboards, but I want to bring into your attention the “Time” (or any%) leaderboards as well. The goal is still to beat the map as fast as possible, but here your Completion and Finesse ranks don’t matter (except for when two runs have the same time).

The steps I suggest for improving your runs look like this:

1. Play through a map and figure out what strats you could use.
2. Try getting a clean run with them.
3. Check what rank it gives you and then watch a replay of somebody who is a bit higher on the leaderboard than you.
4. See what they’re doing differently and where they could be saving time.
5. Try to implement those strats into your run.
6. Repeat steps 3-5 until you’re satisfied with your rank.

Better strats alone won’t be enough unless you execute them well, and for this there’s no shortcut. You just have to practice and play the map over and over.

- - - -

<br /> 

<a name="using-editor-anywhere"/>

### Using editor anywhere ###

Thankfully you don’t have to play the entire map if you need to practice just one section.

If the “Editor Anywhere” option is enabled in Dustmod menu, you can press ‘tab’ to open the map you’re currently playing in editor mode. Click on the gargoyle icon to select the “Entities” tab, scroll it down to find the Player 1 spawn and place it where you want to start practicing from (you can pan the camera when holding ‘spacebar’). To change its facing simply press left or right arrow key. Then press ‘tab’ again to switch to playing mode.

- - - -

<br /> 

<a name="comparing-replays-on-dustkid"/>

### Comparing replays on dustkid.com ###

Dustkid.com allows you to compare any two replays of the same map. If you’re logged in (there should be “My Profile” tab visible on the left) you can easily compare your own replays to other runs. 

First open your profile and select any of the maps you’ve already completed. Then click the camera icon to open a replay of some other player you want to compare your run to. Just above the animation showing the run you’re going to find a few comparison options, among which are "Score PB" and "Time PB" (PB standing for Personal Best). 

You can also compare any two runs, not necessarily yours, by clicking the camera icon while holding left shift to mark it as “Sideboard Replay”. Then open another replay and select "Compare with Sideboard Replay". 

- - - -

<br /> 

<a name="replay-ghosts"/>

### Replay ghosts ###

Dustmod includes a feature to watch replay ghosts in-game. Enable “Replay Ghosts” in Dustmod → Tools and start watching any replay. You don’t have to watch it in its entirety, exit the map once it has loaded in. Now select any other replay of this map you’d like to compare it to, or start playing yourself. 

To reset ghosts you have to disable Replay Ghosts and enable it.

- - - -

<br /> 

<a name="other-resources"/>

### Other resources ###

* https://www.youtube.com/channel/UC4H4b4BwJJYmUo_iZwF3WCQ - Dustforce Helpdesk channel has one more video not mentioned here and they may upload something in the future.
* https://www.dustforce.info/ - A Dustforce wiki. It’s still a work-in-progress but it already offers tons of information.
* https://imgur.com/a/jtzG0 – Dustforce Attack Hitbox Sizes and Positions. Although don’t trust the final image as it shows some of the hitboxes incorrectly.
* https://www.reddit.com/r/dustforce/ - Dustforce reddit
* https://discordapp.com/invite/0SkxtG7ddS6n2BCW – Invitation link for Dustforce Discord server

- - - -

<br /> 

<a name="closing-words-and-credits"/>

### Closing words and credits ###

I hope that what I've written here proves to be useful. Have fun dusting and see you on the leaderboards!

Big thank you to Zaandaa for reading through the guide and suggesting some improvements, and indapop for his input on controller related parts.

And lastly, some clips in the guide feature custom maps or just fog triggers made by Linley, Leap, C, Giamma, Dustcreep and Alexspeedy.