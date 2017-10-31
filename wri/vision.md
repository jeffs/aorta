# Aorta

Project Aorta comprises technology and documentation to support creators of
Accessibility-Oriented Real-Time Applications.  For example, an MMORPG built on
Aorta might allow players to interact, and even participate in the same
campaign, through widely disparate interfaces:  One player might use an AR or
VR headset like Hololens or Oculus Rift, another an audio-only device like
Amazon Echo, a third a primarily textual system like SMS or Slack, and a fourth
a traditional desktop computer.

Naively constructed multi-user applications sacrifice either the richness of
some interfaces, or the feeling of a shared experience.  For example, consider
two users, Alice and Bob: Alice sits at a desktop PC with a high-end graphics
card and broadband Internet access, while Bob has a text-only device with an
unreliable network.  If an application is built with only the latter device in
mind, then the user interface must be limited to text, and will feel
unnecessarily restrictive to Alice.  Conversely, if the interface relies on the
full feature set of the PC, then Bob is excluded.

The premise of Aorta is that the experience of users connected through
disparate technology can be shared, without being identical.  Wherever an
interface must degrade, it should do so gracefully.  As an example, let us
return to our two users, who are playing an online game together.  As the
heroes enter a dank chamber in a monster-infested dungeon, Alice's PC shows a
three-dimensional representation of the chamber, including artwork and sound
effects; whereas Bob receives an atmospheric description in prose.  While Bob
reads, Alice's avatar explores the chamber in response to joystick input.

Suddenly, a monster attacks!  Alice sees the monster, and immediately begins
attacking, parrying, and casting spells.  Each attack either strikes or misses
the monster, depending on the Alice's dexterity with the joystick.  Meanwhile,
Bob is notified -- "A MONSTER ATTACKS!" -- and replies with the instruction
"LAUNCH CROSSBOW BOLT."  Virtual dice are rolled, causing both Bob and the
monster to sustain randomly determined damage.  Bob is notified: "BOLT STRIKES
MONSTER for 27 DAMAGE (73 LIFE POINTS REMAINING).  MONSTER BITES BOB FOR 18
DAMAGE (82 LIFE POINTS REMAINING)." The interaction of Bob's avatar with the
monster is rendered for Alice along with simulated battle to keep the action
lively:  Not only is the crossbow carefully leveled and aimed, but a series of
blows and parries is also generated.  Specifics of the combat are not important
to the game, so long as they entertain Alice, and eventually result in the
correct outcome, as determined by the dice rolled for Bob.  Every few seconds,
or perhaps only after the battle, the interaction of Alice with the monster is
summarized to Bob: "ALICE HAS SUSTAINED 42 DAMAGE AND HAS 58 LIFE POINTS
REMAINING."

Such interactions are possible, but require thoughtful design to separate
aspects of the user experience that should be fundamentally shared from those
that are interface-specific.  Aorta provides not only technical integrations
with various devices and platforms, but tooling and guidelines to underpin
scaleable, real-time systems to which the most diverse possible user base
enjoys first-class access.
