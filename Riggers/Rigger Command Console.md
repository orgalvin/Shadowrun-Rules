[[Riggers]]

A rigger command console, or RCC, is like a deck for controlling
drones (or other vehicles and devices). It’s about
the size of a briefcase. It can act like a commlink and
has all the features of a commlink in addition to the cool
drone stuff. The main purpose of the RCC is to create
a PAN with your drones. This gives the standard master-
slave benefits (see PANs and WANs, p. 233), but the
RCC comes with some extra features.

![[Rigger Command Console.png]]

##### NOISE REDUCTION & SHARING
Along with all the standard features of a commlink, rigger
command consoles have Noise Reduction and Sharing
ratings that you set when you boot the console. The
Noise reduction rating is straight-up Noise Reduction (p.
230), which is cumulative with other forms of Noise Reduction.
The Sharing rating is the number of autosofts
you can run on the RCC that simultaneously run on all
slaved drones at the same time. One caveat: if a drone is
running any of its own autosofts, it cannot benefit from
the RCC’s autosofts.
	The total of both ratings cannot exceed the device
rating of the RCC. You can adjust the values of these two
special ratings with a Change Device Mode action (p. 163).
Yeah, that means if your RCC has a Device Rating of 1 it can
only have one or the other feature running at a time.

##### DATA PROCESSING & FIREWALL
Rigger command consoles have the familiar Data Processing
and Firewall ratings from both commlinks and
cyberdecks, but they lean toward commlinks in their
functionality since they are not designed for versatility
and cannot be readjusted on the fly. Data Processing
is used to determine Initiative when running in VR and
acts as the Limit for all Command tests performed on
the RCC. Firewall is used to defend against unwanted
wireless intrusion onto the entire slaved drone network.

##### GROUP COMMANDAND JUMPING AROUND
Your RCC manages several parallel connections at
once, so you can give a command to one, all, or some
of your slaved drones with the same Simple Action. This
multi-connection also lets you jump from one slaved
drone to another without first jumping out of the drone
you’re leaving. Commands issued from your RCC are
acted on during the drone’s Action Phase, not yours.
Drones receiving multiple contradicting commands
on the same control levels (see Control Override, p.
265) before they have a chance to enact those commands
on their Action Phase fail to perform any of them
and instead send an error message back to the users attempting
to issue the commands.

##### PANS & WANS (RIGGER STYLE)
If you want extra protection for your drones and the ability
to command them all at once, you can slave them to
your RCC. Your RCC can handle up to (Device Rating x 3)
slaved drones, becoming the master device on that network.
The group of your slaved drones plus your master
RCC is called a personal area network, or PAN.
Whenever a slaved device is called on to make a defense
test, it uses either its own or its master’s Rating
for each Rating in the test. For example, if your slaved
rotodrone is the target of a hacker’s Brute Force action,
it could use your Willpower in place of its Device Rating,
and your RCC’s Firewall in place of its own Rating, assuming
that either or both of these Ratings improve on
what it already has.
	The same rules for marks on slaved devices apply in
the RCC-drone relationship as in other Matrix couplings.
Most important to you are that if you get a mark on a
slave, you also get a mark on the master, and that if an
attacker has a direct connection, your drone can’t use you
for help. For more details, see PANs and WANs, p. 233.
	There are also wide area networks, or WANs, with
multiple devices slaved to a host. This is the world of
that special kind of rigger, the security spider. They slave
their RCC to the building’s host and connect to the entire
security system, including all of its slaved drones. When
you’re inside a host, your effective “physical distance” to
drones slaved to that host becomes zero, even if you’re
on the other side of the world. The spider-rigger is often
teamed up with a spider-decker to help against hacking
intrusions on the security system.

##### ELECTRONIC WARFARE FOR RIGGERS
No one likes getting jammed out of controlling their
own stuff. Yeah, the dog-brain pilot takes over, but who
wants that thing running the show?
If you’re using an RCC, you can compensate for noise
on the fly. Take a Complex Action and make an Electronic
Warfare + Logic [Data Processing] test. The hits from
this test act as Noise reduction (cumulative with all other
Noise reduction) for the rest of the current Combat Turn.
You can turn the tables on an enemy rigger or hacker
by using a jammer (p. 441). Some rigging purists say that
using jamming in a rigger duel is dirty pool, but sometimes
it’s just what you need to save your keister.

##### GETTING HACKED
Rigger command consoles and vehicles, including
drones, are frequent targets of enemy deckers trying
to get the upper hand on an opponent. Riggers aren’t
deckers, but they aren’t completely inept in the world
of electronic warfare. Here are a few important Matrix
Actions riggers need to know about.
When you know there’s a Matrix attack coming, you
can use the Full Matrix Defense action to bolster your
cyberdefenses. This option slows you down a bit, but it’s
often better than losing control of your RCC or a precious
drone.
	Sometimes it’s better to lose a drone for a few seconds
than to have it turned against you or sent careening
into the nearest dense object. You can use the Reboot
Device action to cut off an enemy hack before it
gets too far. This take a little time, as your drone won’t
come back online until the end of the following Combat
Turn, so be aware of the drone’s environment when you
perform this trick. A hard reboot won’t automatically result
in drone wreckage if you’re careful. An aerial drone
that can glide on its wings or on autorotation for a few
seconds will be fine when it comes back up, and surface
drones should be okay as long as they’re not going too
fast. If you’re flying a vectored thrust drone, you should
probably land it before you do this trick.

##### GETTING DUMPED
No, we don’t mean the “let’s be friends” conversation—
we’ve all been there, chummer—we mean getting booted out of something you’ve jumped into. Riggers can be forcefully ejected from their jumped-in vehicles
in three nasty ways. First, if the vehicle is destroyed or
bricked, you’re dumped. Second, if you’re using a commlink
or RCC and it gets destroyed or bricked, dump
city. Third, if you’re plugged into something with a universal
connector and your cable gets yanked from either
end (ouch), you get dumped.
In all three cases, a dumped rigger suffers [[Matrix Damage#Dumpshock]]
(p. 229) and loses control of the vehicle (natch). Vehicles
with a Pilot Rating will return to autopilot control at the
beginning of the next Combat Turn. Vehicles are uncontrolled
(see Control Vehicle, p. 203) until someone else
takes control.

##### RIGGER CYBERPROGRAMS
Riggers can utilize a number of cyberprograms that deckers
usually use. Programs purchased for use on an RCC cannot be used in
a cyberdeck and vice versa. As with decks, RCCs cannot run more than
one type of program of the same type, even if you rename it. Here’s a
list of handy programs for the savvy rigger and their basic function.
See [[Programs]] for more detail.
- Encryption: +1 Firewall
- Signal Scrub: Rating 2 noise reduction
- Toolbox: + 1 Data Processing
- Virtual Machine: 2 extra program slots; take 1 extra box of
unresisted Matrix damage when attacked
- Armor: +2 dice pool modifier to resist Matrix damage
- Biofeedback Filter: +2 dice pool modifier to resist biofeedback
damage
- Guard: Reduce extra damage from marks by 1 DV per mark
- Shell: +1 dice pool modifier against Matrix and biofeedback
damage, cumulative with other programs
- Sneak: +2 dice pool modifier to defend against Trace User
actions
- Wrapper: Allows you to defy Matrix iconography rules