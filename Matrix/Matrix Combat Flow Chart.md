# Connecting to the Matrix
## How are you connecting?
| Connection   | Initiative          | Dice Pool Penalty     | Biofeedback |
|--------------|---------------------|-----------------------|-------------|
| AR           | React. + Int. + 1d6 | Potential -2 Penalty  | None        |
| Cold Sim VR  | DP + Int. + 3d6     | No Penalty            | Stun Dmg    |
| Hot Sim VR   | DP + Int. + 4d6     | +2 for Matrix Actions | Physical Dmg |


NEXT: [[Matrix Combat Flow Chart#Connection to target]]

# Connection to target
## Direct
Go to [[Matrix Combat Flow Chart#Running silently]]

## Indirect

|     | Initiative          |
|--------------|---------------------|
| On public grid? | React. + Int. + 1d6 | 
| Cold Sim VR    | DP + Int. + 3d6     | 
| Hot Sim VR   | DP + Int. + 4d6     | 
* On the public grid?
	* Yes: -2 to Dice Pool
	* No: No Dice Penalty
* On same grid as target?
	* Yes: No Dice Penalty
	* No: -2 to Dice Pool
* No, but in same host as target: No Dice Penalty
### Next action
* [[Matrix Actions#GRID HOP COMPLEX ACTION|Hop to another grid]]
	* [[Matrix Combat Flow Chart#How are you connecting]]
* [[Matrix Actions#HACK ON THE FLY COMPLEX ACTION|Hack on the fly]] / [[Matrix Actions#BRUTE FORCE COMPLEX ACTION|Brute force]]
	* Increases [[Overwatch Score|grid overwatch score]]
	* [[Matrix Combat Flow Chart#How are you connecting]]
* Continue
	* [[Matrix Combat Flow Chart#Running silently]]

## Running silently?
* Yes: -2 to Dice pool
* No: No Dice Penalty

NEXT: [[Matrix Combat Flow Chart#Calculate Noise]]

# Calculate Noise
**Calculate Noise: Spam/Static**
* Direct Connection: No penalty
* City Downtown/Abandoned Building: -1 to Dice Pool
* Sprawl Downtown/Barrens: -2 to Dice Pool
* Major Event/Weather/Rural/Underground: -3 to Dice Pool
* Commerical Area/Wilderness/Storm: -4 to Dice Pool
* Commercial Sprawl Area/Remote Areas: -5  to Dice Pool
* Massive Gathering/Widespread Emergency/Remote, Enclosed Place: -6 to Dice Pool

**Calculate Noise: Distance**
* Direct Connection/Within 100 meters: No penalty
* (100m-1000m]: -1 to Dice Pool
* (1km-10km]: -3 to Dice Pool
* (10km-100km]: -5 to Dice Pool
* (100km-inf): -8 to Dice Pool

NEXT: [[Matrix Combat Flow Chart#Target spotted]]

# Target spotted?
* Spotted target/Connected directly to target?
	* Yes:
		* [[Matrix Combat Flow Chart#Destroy Attack target]]
		--OR--
		* 
	* No: Use [[Matrix Actions#MATRIX PERCEPTION COMPLEX ACTION|Matrix perception]] until you spot target

# Destroy/Attack target
 Increases [[Overwatch Score|grid overwatch score]]

Available actions:
* [[Matrix Actions#DATA SPIKE COMPLEX ACTION]]

When done:

# Matrix shenanigans
Use [[Matrix Actions#HACK ON THE FLY COMPLEX ACTION|Hack on the fly]] / [[Matrix Actions#BRUTE FORCE COMPLEX ACTION|Brute force]] to [[MARK]] the target the required amount of times

Increases [[Overwatch Score|grid overwatch score]]

Available actions:
* [[Matrix Actions#CONTROL DEVICE VARIABLE ACTION|Control device]] (Variable MARKs required)
* [[Matrix Actions#CRACK FILE COMPLEX ACTION|Crack file]] (1)
* [[Matrix Actions#CRASH PROGRAM COMPLEX ACTION|Crash program]] (1)
* [[Matrix Actions#EDIT FILE COMPLEX ACTION|Edit file]] (1)
	* Might also by good to [[Matrix Actions#DISARM DATA BOMB COMPLEX ACTION]] if editing a file with a data bomb
* [[Matrix Actions#ENTER EXIT HOST COMPLEX ACTION|Enter/Exit Host]] (1)
* [[Matrix Actions#FORMAT DEVICE COMPLEX ACTION|Format device]] (3)
* [[Matrix Actions#REBOOT DEVICE COMPLEX ACTION|Reboot device]] (3)
* [[Matrix Actions#SET DATA BOMB COMPLEX ACTION|Set data bomb]] (1)
* [[Matrix Actions#SNOOP COMPLEX ACTION|Snoop]] (1)
* [[Matrix Actions#SPOOF COMMAND COMPLEX ACTION|Spoof command]] (1)
* [[Matrix Actions#TRACE ICON COMPLEX ACTION|Trace icon]] (2)

When done:

# Other situations
## Need to hide/Deal with Overwatch
* [[Matrix Actions#CHECK OVERWATCH SCORE SIMPLE ACTION]]
* [[Matrix Actions#CHANGE ICON SIMPLE ACTION]]
* [[Matrix Actions#ERASE MARK COMPLEX ACTION]]
* [[Matrix Actions#FULL MATRIX DEFENSE INTERRUPT ACTION]]
* [[Matrix Actions#HIDE COMPLEX ACTION]]

## Leaving matrix
* When done: [[Matrix Actions#JACK OUT SIMPLE ACTION|Jack out]] or [[Matrix Actions#SWITCH INTERFACE MODE SIMPLE ACTION]]







1a) If the target of a PC hack is something they can see in the real world, like a gate, a security camera, or an NPC’s weapon or commlink, the PC usually doesn’t need to perform a Matrix Perception test to find it. 1b) If the PCs’ target cannot be seen in real life and is not inside a host, a Matrix Perception test is needed to spot it (see Matrix Perception sidebar, p. 33). 1c) If the target is inside a host, the PC must first enter the host to hack it (see Getting Around in the Matrix sidebar, p. 25). Once the PCs are inside, a Matrix Perception test will help them find their target. 2) Next, depending on what the hacker wants to do with the target, they need to place between 1 and 3 marks on it (see Marks and the Matrix, p. 34). 3) When there is opposition, hackers must decide whether to be sneaky or to go on the attack (see Cybercombat, p. 35). If there is IC present, use the Patrol IC sidebar (p. 44) to see how often to roll to see if the hacker is spotted. If they are spotted, introduce additional IC at the beginning of every Combat Turn. If needed, stats for a typical enemy Spider (see Security Spiders sidebar p. 44) can be found on p. 104, Data Trails. 4) After these preliminary consi




##### RECKLESS HACKING 
A wiz hacker can shave time off hacking a device, but it isn’t for the faint of heart. Hackers can inflict one or more –5 dice pool penalties to a single Matrix Action. For each such penalty taken, you may perform that action as if you had 1 mark beyond the amount you already have. This may be used up to 3 times on a single Matrix action, so an action requiring 3 marks would be a –15 dice pool penalty. Critical glitches on any reckless hacking attempt should cause immediate rebooting of whatever device the hacker is using, with all associated difficulties. Any and all resulting dumpshock should be Physical damage, regardless of the mode being used to hack. 





[[Matrix]]

[[Matrix Perception]]
[[Non-Hacker actions]]
```toc

```

Matrix actions are special because certain modifiers apply to them, such as [[Noise]] and [[Overwatch Score]]

![[Matrix Actions.png]]

![[Matrix Actions Cont.png]]

##### BRUTE FORCE (COMPLEX ACTION)
Marks Required: none 
Test: Cybercombat + Logic [Attack] v. Willpower + Firewall 
You can use this action to mark a target without obtaining the normal permissions you need. This is the action for hackers emphasizing their Attack over their [[Matrix Attributes#Sleaze|Sleaze]], making it related to [[#HACK ON THE FLY COMPLEX ACTION|Hack on the Fly]]. If you succeed in this action, you place one [[mark]] on it. You can have up to a maximum of three [[mark|marks]] per icon. If you wish, you may also inflict 1 DV of [[Matrix damage]] to the target for every two full net hits, if the target can take [[Matrix damage]], which is resisted with the target’s Device Rating + Firewall. Before rolling, you can declare that you are trying to place more than one [[mark]]. If you try for two [[mark|marks]] in one shot, you take a –4 dice pool penalty on the attempt. If you try for three [[mark|marks]] in a single swipe, you take a –10 dice pool penalty. You can also use this action to hop to a grid for which you don’t have legitimate access. The defense dice pool in this case is 4 dice for a local grid or 6 dice for a global grid. If you succeed, instead of putting a [[mark]] on the grid, you hop to that grid immediately. Using Brute Force to hop grids successfully doesn’t alert the grid or its demiGOD the way most successful Attack actions do. 

##### CALIBRATION (SIMPLE ACTION) 
Marks required: One per persona 
Test: Electronic Warfare + Logic [Data Processing] 
You can increase the current Initiative Score of a number of personas on whom you have marks by 1 for every 2 hits. The number of personas affected cannot exceed your Data Processing. The Initiative Score then decreases each Combat Turn as normal. 

##### CHANGE ICON (SIMPLE ACTION)
Marks Required: Owner 
Test: none (Data Processing action) 
You change the target’s icon to one that you have a copy of or have designed yourself. Changing an icon doesn’t change the results of a Matrix Perception action, but might fool personas who don’t take the time to inspect your new look. You can target your own icon, if you like. 

##### CHECK OVERWATCH SCORE (SIMPLE ACTION)
Marks Required: none 
Test: Electronic Warfare + Logic [Sleaze] v. 6 dice 
You find out how close the grid is to converging on you. Checking the OS is a [[Matrix Attributes#Sleaze|Sleaze]] action, so the defense against it will add to your OS. If you succeed, the gamemaster tells you what your OS was when you started the action, then adds the hits from the defending dice pool. 

##### CONTROL DEVICE (VARIABLE ACTION) 
Marks Required: varies 
Test: (as action) [Data Processing (or special)] v. (as action) or Electronic Warfare + Intuition [Sleaze] v. Intuition + Firewall 
You perform an action through a device you control (or at least control sufficiently), using your commlink or deck like a remote control or video-game controller. The dice pool of any test you make using this action uses the rating of the appropriate skill and attribute you would use if you were performing the action normally. For example, firing a drone-mounted weapon at a target requires a Gunnery + Agility test, and using a remote underwater welder calls for a Nautical Mechanic + Logic test. All actions you take while controlling a device use either the normal limit for that action or your Data Processing rating, whichever is lower. If there is no test associated with the action you want the device to perform (such as unlocking a maglock or ejecting a clip from a pistol), you must succeed in an Electronic Warfare + Intuition [Sleaze] v. Intuition + Firewall test to perform the action. You can use this action to control multiple devices at once. If you are the owner of all devices being commanded and they are all being commanded to do exactly the same thing, taking this action costs nothing extra. Otherwise, you must split your dice pool into a number of groups equal to the number of devices you want to control with a single action. The type of action this is (i.e., Free, Simple, Standard, and Complex) is the same as the type of action attempted with the device, and it requires 1 mark for Free Actions, 2 marks for Simple Actions, and 3 marks for Standard or Complex Actions. This action is a [[Matrix Attributes#Sleaze|Sleaze]] action whenever you use your [[Matrix Attributes#Sleaze|Sleaze]] as a limit in the test, which incurs the same risk of Overwatch Score and consequences of failure as all [[Matrix Attributes#Sleaze|Sleaze]] actions. 

##### CRACK FILE (COMPLEX ACTION) 
Marks Required: 1 
Test: Hacking + Logic [Attack] v. Protection Rating x 2 
You remove the protection from a file, making it readable. This action doesn’t need to be performed on a file that isn’t protected, of course. 

##### CRASH PROGRAM (COMPLEX ACTION) 
Marks Required: 1 
Test: Cybercombat + Logic [Attack] v. Intuition + Firewall 
You overload part of your target’s memory and scramble one of its running programs. You need to specify which program you’re trying to crash; you can learn what your target is running either with a [[Matrix Perception]] action or by observing the program in action. If you succeed, the program is scrambled: it ends and cannot be restarted until the device it was running on is rebooted.

##### DATA SPIKE (COMPLEX ACTION)
Marks Required: none 
Test: Cybercombat + Logic [Attack] v. Intuition + Firewall 
You send harmful instructions to a persona or device, causing Matrix damage to the target. Your attack has a Damage Value equal to your Attack rating, with one additional box of damage per net hit, and two additional boxes of damage for each mark you have on the target. This damage is [[Matrix damage]] (p. 228), resisted with the target’s Device Rating + Firewall. 

##### DENIAL OF SERVICE (SIMPLE ACTION) 
Marks required: See description 
Test: Cybercombat + Logic [Attack] v. Willpower + Firewall 
A decker or technomancer may target a wirelessly active device or PAN. Make a Computer + Intuition [Data processing] Test opposed by Willpower + Firewall, and apply the number of net hits x 2 as a negative dice pool modifier to all tests made with that device until the beginning of the next Combat Turn. For every mark the decker or technomancer has on an enemy PAN, they may apply this effect to two additional devices slaved to the PAN. 

##### DISARM DATA BOMB (COMPLEX ACTION)
Marks Required: none 
Test: Software + Intuition [Firewall] v. Data Bomb Rating x 2 
You attempt to disarm a [[#SET DATA BOMB COMPLEX ACTION|Data Bomb]] that you have detected (usually as the result of a [[Matrix Perception]] action). If you score any net hits, the Data Bomb is removed and deleted. If not, the Data Bomb activates, causing its damage and possibly destroying any file to which it was attached (assuming it was set to destroy the file). 

##### EDIT FILE (COMPLEX ACTION) 
Marks Required: 1 
Test: Computer + Logic [Data Processing] v. Intuition + Firewall 
Edit File allows you to create, change, copy, delete, or protect any kind of file. The defender against this test is either the host holding the file or the owner of the file (if it’s not on a host). Each action is enough to alter one detail of a file—a short paragraph of text, a single detail of an image, or two or three seconds of video or audio (you and your gamemaster can work out what exactly “one detail” means). Your gamemaster may impose penalties on the test if your edit is particularly intricate or tricky. If you want to perform a continuous edit, such as removing your teammates from a video feed, you need to perform this action once per Combat Turn for as long as you want to keep the edit going. If you use this action to copy a file, you are the new file’s owner. If the file you want to copy has protection on it, this action automatically fails. If the file has a Data Bomb, the Data Bomb goes off on you (so try to remember to scan files before you open them). You can also use this action to set protection on a file if you’re its owner. To protect a file, make a Simple Computer + Logic [Data Processing] test. The number of hits you get becomes the rating of the protected file. A protected file cannot be read, changed, deleted, or copied until its protection is broken. 

##### ENTER/EXIT HOST (COMPLEX ACTION)
Marks Required: 1 
Test: n/a 
You enter a host that you have a mark on and your icon appears there, or you leave a host you’re already in. There is no test for this action: a host allows anyone to enter if they’ve got a mark, and anyone inside can exit. The host might not be so welcoming once you’re inside, of course, and some IC has the ability to keep you trapped in a host until you can break out. When you leave a host, you return to the grid from which you entered. 

##### ERASE MARK (COMPLEX ACTION)
Marks Required: special 
Test: Computer + Logic [Attack] v. Willpower + Firewall 
You eradicate a mark that has been placed on your persona or on another icon. To perform this action, you need three marks on the icon from which you are erasing a mark. You do not, however, need a mark on the icon that placed the mark in the first place. You can try to erase two marks in the same action at a –4 dice pool penalty, and three marks in one go at a –10 dice pool penalty; if you go for more than one mark, all of the marks must be on the same icon and from the same icon. You can’t use this action to change the target’s owner. For example, an IC program has marked both you and your buddy. You roll your Computer + Logic (with your Attack program rating as the limit), opposed by the IC’s rating (standing in for Willpower) + Firewall to erase its mark on your icon. You need three marks on your buddy’s icon to erase the IC’s marks on him, but he isn’t the sharing type, so he’s on his own for now. 

##### ERASE MATRIX SIGNATURE (COMPLEX ACTION) 
Marks Required: none 
Test: Computer + Resonance [Attack] v. (Signature Rating) x 2 You eradicate a Matrix signature that has been left by a Resonance being, such as a technomancer or a sprite. If successful, the signature dissipates. You need to have a Resonance rating to attempt this action; unlike other actions that need Resonance, this one’s a real Matrix Action, and an Attack one to boot, so you risk Matrix damage and Overwatch Score when you use it. 

##### FORMAT DEVICE (COMPLEX ACTION) 
Marks Required: 3 
Test: Computer + Logic [Sleaze] v. Willpower + Firewall
You rewrite the boot code for the device. The next time it would reboot, it instead shuts down for good, or until its software can be replaced (an Extended Software + Logic [Mental] (12, 1 hour) Test). A device that has been shut down in this fashion loses all of its wireless modifiers but can still be used as a normal mechanism (a door with a manual handle can be opened, a gun with a trigger can be fired, etc.) and cannot be accessed from the Matrix.

##### FULL MATRIX DEFENSE (INTERRUPT ACTION) 
Marks Required: Owner
Test: none (Firewall action) 
This allows you to defend against Attack actions, and may be taken at any time. Whenever you make a defense test against a Matrix Action, add your Willpower to the dice pool (or add it again if it’s already in there). When you take this action, your Initiative Score is reduced by 10, but the effects last for the rest of the Combat Turn. 

##### GARBAGE IN/GARBAGE OUT (COMPLEX ACTION)
Marks Required: 3
Test: Software + Logic [Sleaze] vs. Logic + Firewall

This allows a decker to “cross the wires” of a single device, confusing its input and output commands.Only a single input can be changed to correspond to a single output—devices can’t be reprogrammed whole- sale or made to act in a manner outside of their original design through Garbage In/Garbage Out. For example, a smartgun-enabled firearm could be reprogrammed so that every time the fire command is given (through either pulling the trigger or DNI), the clip—or even the magazine—ejects. An elevator could be reprogrammed to go to the 23rd floor instead of the lobby, but a decker can’t override its basic safety protocols since that would require multiple commands. Gamemasters have final say in what can and cannot be reprogrammed, but the rule of thumb should be “a single keystroke” of activity or the inversion of a binary relationship—the “friend or foe” recognition program in a smart safety system, for example. Rebooting the device restores the code to its proper state.

##### GRID HOP (COMPLEX ACTION)
Marks Required: none
Test: none (Data Processing action) 
You hop to another grid—for example, you might jump from the public grid to Seattle’s Emerald City local grid. To do this, you must have access to your destination grid. If you do not have access, you can use Brute Force or Hack on the Fly to hop to another grid illegally. If you’re inside a host, you need to leave the host before you can hop to another grid. 

##### HACK ON THE FLY (COMPLEX ACTION)
Marks Required: none
Test: Hacking + Logic [Sleaze] v. Intuition + Firewall 
You can use this action to mark a target without getting the normal permissions. This is the action for hackers emphasizing their [[Matrix Attributes#Sleaze|Sleaze]] over their Attack, making it an analog to Brute Force. When targeting an icon, you put one mark on it, up to a maximum of three marks per icon. Additionally, every two full net hits counts as one hit on a Matrix Perception Test, so you can get some info along with your mark. Before rolling, you can declare that you are trying for more than one mark. If you try for two marks in one shot, you take a –4 dice pool penalty on the attempt. If you try for three marks in one go, you take a –10 dice pool penalty. You can also use this action to hop to a grid for which you don’t have legitimate access. The defense dice pool in this case is 4 dice for a local grid or 6 dice for a global grid. If you succeed, instead of putting a mark on the grid, you hop to that grid immediately. Using  [[#HACK ON THE FLY COMPLEX ACTION|Hack on the Fly]] to hop grids unsuccessfully doesn’t alert the grid or its demiGOD the way most unsuccessful [[Matrix Attributes#Sleaze|Sleaze]] actions do. 

##### HAYWIRE (COMPLEX ACTION) 
Marks required: None 
Test: Cybercombat + Logic [Attack] v. Willpower + Firewall 
Target must be a persona not running in VR. Haywire disables all of the target’s PAN-related functions. Physical devices still function, so smartguns can still fire and chemsuits still offer protection, but without wireless or PAN functions. This effect lasts until the target succeeds an extended Computer + Logic [Data Processing] (Hacker’s Net Hits, Simple Action) test with a threshold equal to the net hits from the attacker’s roll; each attempt takes a simple action. The target may simply reset their device and reboot it with a Complex Action; the device will be back online at the end of the following Combat Turn, which takes one minute. Glitching the test to fix the device adds an additional net hit to the attacker’s roll. A critical glitch causes all the devices on the PAN to require an OS reinstall. This takes multiple hours and a connection to a persona-enabled device. 

##### HIDE (COMPLEX ACTION) 
Marks Required: 0 
Test: Electronic Warfare + Intuition [Sleaze] v. Intuition + Data Processing You’ll probably be spotted by another icon, even if you’re running silent. You can use this action to make a target lose you. If you succeed, the target stops spotting you and needs to perform a new Matrix Perception action against you if it wants to find you again. You can’t hide from an icon that has a mark on you, so you’ll need to clear those before you can try this action. 

##### I AM THE FIREWALL (COMPLEX ACTION/INTERRUPT [–5 INITIATIVE SCORE]) 
Marks required: None 
Test: Computer + Intuition [Data Processing] 
I Am the Firewall allows the hacker to give a Defense test bonus to all allies with access to an AR feed from the user. The number of bonus dice is equal to the number of hits on a Computer + Intuition [Data Processing] Test. This bonus lasts until the beginning of the hacker’s next Initiative Pass. The hacker can only share their feed with a number of users equal to or less than their Data Processing attribute. When you take this action as an Interrupt Action, your Initiative Score is reduced by 5. 

##### INTERVENE (INTERRUPT ACTION [–5 INITIATIVE SCORE]) 
Marks required: None 
Test: Computer + Intuition [Data Processing] 
This allows the hacker to give an immediate defense bonus to the owner of a device slaved to the hacker’s PAN. This action can be taken only if the device making the attack is wirelessly enabled and the hacker is aware of it. When you take this action, your Initiative Score is reduced by 5. Roll your Computer + Intuition [Data Processing], adding the number of hits to your ally’s Defense test. This bonus applies only to the current Defense test—it cannot be carried over to any other Combat Turn or Initiative Pass. 

##### INVITE MARK (SIMPLE ACTION)
Marks Required: Owner
Test: none (Data Processing action) 
If you’re the owner of a device, file, persona, host, or IC program, you can offer other icons the opportunity to put a mark on your device, file, etc. When you make the offer, you choose the number of marks allowed, their duration, and how long the offer stands. The invitee can then mark your icon with a Free Action. You may revoke your offer at any time before the mark is placed, but once another icon has a mark, you need to either use the Erase Mark action or reboot your device to remove it before the duration you chose expires. 

##### JACK OUT (SIMPLE ACTION)
Marks Required: Owner 
Test: Hardware + Willpower [Firewall] v. Logic + Attack
This jacks you out of the Matrix and reboots the device you are using. You suffer dumpshock if you were in VR. The defense pool only applies if you’ve been linklocked (p. 229) by someone; the test is against the icon that locked your link. If more than one persona has you link-locked, you need to beat each of them individually: use a single roll and compare your hits to rolls from each opponent who had established a link-lock. You can only jack out yourself. You can’t dump other people except by beating them into submission through Matrix damage. 

##### JAM SIGNALS (COMPLEX ACTION) 
Marks Required: Owner 
Test: Electronic Warfare + Logic [Attack] 
This action turns the wireless device you are using into a local jammer. As long as you do not use the device for any further Matrix actions, the device adds any hits you get on the test to the noise rating for all Matrix actions conducted by or targeting any devices within 100 meters. If you want selective jamming or directional jamming, buy a jammer—that’s what they’re for.

##### JUMP INTO RIGGED DEVICE (COMPLEX ACTION) 
Marks Required: 3 
Test: Electronic Warfare + Logic [Data Processing] v. Willpower + Firewall
You jump into a device that has a rigger adaptation, usually a vehicle or a drone. There’s a list of things you need to have in order to jump into a device: you have to have three marks on the device you want to jump into, you have to be in VR, the device you want to jump into has to have a rigger adaptation, and you have to have a control rig. If you are the device’s owner, or the device’s owner has given you permission to jump into the device, you don’t need to make a test. In the Matrix, the icon of the device you jumped into becomes part of your persona. If someone else is already jumped into the device, you cannot attempt this action until he or she vacates. 

##### MASQUERADE (COMPLEX ACTION) 
Marks required: 2/2 
Test: Hacking + Intuition [Sleaze] v. Logic + Firewall 
This action allows a hacker to impersonate a persona on the Matrix. Since persona data is updated in real time, this action requires 2 marks on one target (the persona being impersonated) and 2 marks on a second target (the icon you are trying to fool). For every net hit scored on a Hacking + Intuition [Sleaze] v. Logic + Firewall against the second target, you have convinced them you are target one for one minute. This can be used to impersonate someone online, intercept their calls, use their social media, rummage through their email history, or other creative mischief, but processes like changing device owners or perform ing major financial actions (like bank transfers) have too many double-checks for Masquerade to work. If the persona you’re impersonating logs off, those marks are immediately lost, and the disguise drops. While masquerading, you are never considered the owner with regard to any of the impersonated persona’s devices. 

##### MATRIX PERCEPTION (COMPLEX ACTION)
Marks Required: none
Test: Computer + Intuition [Data Processing] (v. Logic + [[Matrix Attributes#Sleaze|Sleaze]])
This versatile and important action is used both for finding icons in the Matrix and for analyzing Matrix objects. When you use this action to analyze a Matrix object or scan the vicinity for silent-running icons, you make a Simple Test and your hits determine how much info you get. For each net hit scored, you can ask for one piece of information about the object—this could be type, a rating, how many marks it has on it, any files it may be carrying, which grid it is using, whether any silent running icons are in the area, or any other pertinent Matrix information. You learn one fact per net hit. If you get a list of marks, you can only recognize marks you have seen before or marks left by personas that you have marks on yourself. Otherwise you only get a count. If you’re trying to spot an icon that is farther than 100 meters away, this is a Simple Test: the first hit lets you spot the target, and any additional hits can be used to get more information about it as mentioned above. If you’re looking for an icon that is running silent (after you’ve determined that it’s present), the test becomes an Opposed Test, with the target defending with Logic + [[Matrix Attributes#Sleaze|Sleaze]]. Net hits are used just like you would for spotting distant targets, with the first one for spotting the target and the rest for analysis. 

##### MATRIX SEARCH (SPECIAL ACTION)
Action: special Marks Required: n/a
Test: Simple Computer + Intuition [Data Processing]
You search the Matrix for information about a topic. The time it takes and the threshold of the test depend on the general availability of the information in question and the area being searched, respectively. Any hits above and beyond the threshold can be used to reduce the search time. Divide the base time by the net hits to determine the reduction. If you fail this test, you still spend the full base time looking. Some information is protected and kept secret, stored in a host that is not publicly accessible. Finding this information usually requires you to find and enter the hosts in which the data is hidden. You can then make a Matrix Search within the host, using a base time of 1 minute (regardless of the kind of information you’re looking for). This only works if the information is at least occasionally accessed by the legitimate users of the host. If the information is archived, you’ll need to dig deeper into the host for that information, a dangerous process that is detailed in the forthcoming Matrix sourcebook. 

##### POPUP (SIMPLE ACTION) 
Marks required: 1 
Test: Hacking + Logic [Sleaze] or Cybercombat + Logic [Attack] v. Willpower + Firewall
Target must be a persona not running in VR. If the target has wireless-enabled AR, they are flooded with Matrix spam, taking a penalty to all actions equal to [net hits] until the start of the attacker’s next Combat Turn. If the attacker uses Cybercombat + Logic, the attack also deals Matrix damage equal to net hits. If the attacker uses Hacking + Logic, they may immediately act as if the net hits on the attack were net hits on a Matrix Perception test, and they gain any relevant information. 

##### REBOOT DEVICE (COMPLEX ACTION)
Marks Required: 3 
Test: Computer + Logic [Data Processing] v. Willpower + Firewall 
The device on which this action is performed shuts down and immediately reboots. The device comes back online at the end of the following Combat Turn. The device ceases electronic functions and disappears from the Matrix until its reboot time is over. When you reboot the device your persona is on, your OS is reset to zero and all of your marks, as well as the ones others may have put on your icon, are erased. If you’re in VR when you reboot, you suffer from dumpshock (see p. 229). When you come back online, your icon can be on any grid to which you have legitimate access, or the public grid if you have no other grid access. When you perform this action, you can choose a delay of any amount of time between the time the device shuts down and the time it comes back online. Anyone with physical access to the device can override this delay by hitting the power button, which starts the boot process and brings the device online at the end of the following Combat Turn. This action only works on devices. It doesn’t work on hosts, living beings (like technomancers, although they can “reboot” themselves, p. 251), or Resonance constructs (like sprites), and the only persona it works on is your own. If you’re the owner of the device you’re rebooting, you don’t have to make a test. You can’t use this action on a device that is link-locked (p. 229). 

##### SEND MESSAGE (SIMPLE ACTION)
Marks Required: n/a (or 1)
Test: none (Data Processing action) 
You send a text or audio message the length of a short sentence, an image, or a file via the Matrix to a user whose commcode you have. If you’re using the Matrix through a DNI, even if you’re in AR, you can send longer and more complicated messages, about a paragraph worth of text. You can also use this action to open a live feed to one or more recipients, using any digital recording devices you have. 

##### SET DATA BOMB (COMPLEX ACTION) 
Marks Required: 1 
Test: Software + Logic [Sleaze] v. (Device Rating x 2)
You set a Data Bomb in a file. When you do, choose the rating of the Data Bomb, up to the net hits on your test. You also need to choose whether or not the Data Bomb will delete the file to which it is attached when activated, and you need to program the passcode required to deactivate it. A file can only have one Data Bomb on it at a time. The Data Bomb is triggered when someone attempts to read, edit, copy, protect, delete, or put another Data Bomb on the file without using the already-in-place Data Bomb’s passcode. When a Data Bomb goes off, it causes (Rating)D6 Matrix Damage (resisted normally) to the icon that tripped it, deletes the file (if it was set that way), and then is itself deleted. If the passcode is used, the Data Bomb doesn’t activate. Instead, it remains attached to the file, waiting for the next guy. A Data Bomb can be detected using Matrix Perception. If it’s detected, it can be defused with the Disarm Data Bomb action; a disarmed Data Bomb is deleted. Damn. 

##### SNOOP (COMPLEX ACTION)
Marks Required: 1
Test: Electronic Warfare + Intuition [Sleaze] v. Logic + Firewall
This action lets you intercept Matrix traffic sent to and from your target for as long as you have the target marked. You can listen to, view, or read this data live, or you can save it for later playback/viewing if you have something to store it on (your deck will do). 

#####  SQUELCH (SIMPLE ACTION) 
Marks required: None 
Test: Electronic Warfare + Logic [Attack] v. Sleaze + Intuition
A successful Squelch test prevents the target device from calling or sending messages for a number of minutes equal to the net hits scored. 

##### SPOOF COMMAND (COMPLEX ACTION) 
Marks Required: 1 (see description) 
Test: Hacking + Intuition [Sleaze] v. Logic + Firewall 
You spoof a device’s owner’s identity, making the device think that your command is a legitimate one from its owner. You need one mark on the icon you are imitating; you do not need a mark on the target. The opposing dice roll is still based on the target, though. This trick only works on devices and agents, not IC, sprites, hosts, personas, or any other icons. 

##### SUBVERT INFRASTRUCTURE (COMPLEX ACTION)
Marks required: 1 
Test: Electronic Warfare + Intuition [Sleaze] v. Intuition + Firewall 
This action allows a decker or technomancer to slightly alter the operation of multiple physical devices so they respond to the hacker’s commands. If the hacker has at least 1 mark on the host, a successful Electronic Warfare + Intuition [Sleaze] v. Intuition + Firewall Test allows them to control one similar simple device (traffic lights, vending machines, home appliances, desk lamps, etc., at gamemaster discretion) slaved to that host for every net hit. This action cannot be used to make an attack. The hacker can sustain controlling these devices as a Complex Action each Combat Turn. 

##### SWITCH INTERFACE MODE (SIMPLE ACTION)
Marks Required: Owner
Test: none (Data Processing action) 
You switch your perception from AR to VR or vice versa. Switching to VR causes your body to go limp, so don’t do it somewhere dangerous. If you switch from VR to AR, you lose the bonus Initiative Dice from VR (Changing Initiative, p. 160). If you’re link-locked (p. 229), you cannot switch interface modes. You can only do this to yourself; you can’t switch other people’s interface mode. 

##### TAG (SIMPLE ACTION) 
Marks required: None 
Test: Computer + Logic [Data Processing] v. Sleaze + Intuition
The hacker may “tag” a number of targets on a single PAN, equal to their net hits, within their line of sight. They can then relay those tags wirelessly to allies. Tagging a target negates up to 2 dice in penalties from Visibility and Light/Glare to any affected ranged attack rolls allies may be making against that target, including blind-fire due to invisibility or shooting through cover. Allies who can see a tag may also take one additional Take Aim Action against that target as a Free Action on each Initiative Pass. Tags may be sustained by spending a Simple Action to refresh the tags each Combat Turn. When using a PI-Tac, the hacker may add the PI-Tac’s level to the number of targets they may tag. Note: In order for allies to receive this bonus, they must have the ability to see AROs.

##### TRACE ICON (COMPLEX ACTION)
Marks Required: 2
Test: Computer + Intuition [Data Processing] v. Willpower + [[Matrix Attributes#Sleaze|Sleaze]] 
You find the physical location of a device or persona in the Matrix. After succeeding with this action, you know the target’s location for as long as you have at least one mark on the target. This doesn’t work on hosts because they generally have no physical location, or IC programs because they are confined to their hosts.

##### TRACKBACK (SPECIAL ACTION)
Marks Required: Owner
Test: Extended Computer + Intuition [Data Processing]
(special, 30 minutes) Test
This test is only possible on grids, not inside a host. The datastreams that connect marks to their owners are barely visible wisps of information. Calibrating your
filters to see them and not the billions of overlapping datastreams is a painstakingly laborious task. Once a mark has been detected on a device (see Matrix Percep-
tion, p. 241, SR5), that device’s owner can try to follow the datastream back the mark’s owner. The number of hits required is equal to 10 + the Sleaze rating of the
persona who marked the device. If the Sleaze rating changes during the search, the number of hits required changes as well. If the persona that placed the mark is
running silent, the trail will end in its vicinity, effectively letting the tracker know that a silent icon is nearby.

##### WATCHDOG (COMPLEX ACTION) 
Marks required: None 
Test: Electronic Warfare + Logic [Sleaze] v. Logic + Firewall 
Target must be a persona or device. If successful, place one mark on the target. The user is now aware of the Matrix actions the target is going to use before they use them, and they may attempt to stop them. A Watchdog mark allows the hacker to use Haywire or Popup as Interrupt Actions (for –10 initiative) or Squelch as an Interrupt Action (for –5 initiative) against the target with the Watchdog mark. This ability lasts as long as the target is marked by the user.













