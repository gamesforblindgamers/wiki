These may represent the subjective opinion or preference of a single blind player, or they may be more generalizable.

# Screen Readers and Text-to-Speech (TTS)

## Q: Do you have opinions on games with their own audio or text-to-speech instead of screen reader compatibility?
A: This is pretty subjective, but I believe for most, including me, screen reader compatibility would be great. If your game uses the operating system's TTS, it would help if you expose controls for speech rate, changing the voice, and a game-global key (mostly ctrl) that silences speech when pressed. For completely self-voiced games (e.g., using prerecorded speech), it's usually not that great because then you are limited by the speed and quality of the prerecorded lines.

## Q: Which screen readers should I support? NVDA, or JAWS? I heard JAWS is more widely used.

A: NVDA is not as uncommon as you might think! In fact, it is more popular than JAWS, especially among gamers. JAWS is mainly prevalent in workspaces due to contracts, and many people don't even like how it's imposed on them by their bosses. NVDA, on the other hand, is seen as less formal, and the company behind JAWS tends to shout "use me" louder at employers.

Additionally, many daily JAWS users even have NVDA as a backup, and use it as their screen reader for gaming. This is because JAWS does some keyhook magic that requires custom scripts for proper gaming, unlike the more straightforward NVDA.

Supporting NVDA might be the option to support the majority of gamers.

# Game Mechanics and Genre-Specific Questions


## Q: How do I make a 3D game, such as a walking simulator, navigatble to blind players?
A: Audio games often use an "audio camera" system, where you hold down a key and can explore around your character (in the audio field) with the normal navigation keys. And if you have a goal, add some unique auditory sound for the target. 

Adding a text description of where you are, as well as clear distinct wall and foot step sounds, also helps.

As for notifying about surroundings, there are a few options:

- For example, have a set of keys that "look" at an angle. Use the K key to look left and the L key to look right. Each time the user presses either K or L, you cycle between objects within the view range in that direction (use raycasting or something).
- Or you can have things play a looping sound, positioned where they are relative to the player in terms of volume (e.g. louder if closer). They're audible, and you can move into them and interact.
- Alternatively, you can have a key that triggers a list displaying everything on the map and its coordinates/position/direction.
- Another option is to have some sort of sonar that constantly scans around or in front of the player and announces anything new you can interact with, and so on.

## Q: Are turn-based games particularly popular with blind gamers?
A: There is nothing especially popular about turn-baste games, but we play them if we like them, just like any other games.

## Q: What reading speed do you prefer for in-game text? For example: tutorials, item or effect descriptions, menus, etc.
A: This is very subjective, and I highly recommend that you don't assume anything. Provide a way to change the speech rate (Every speech synthesis API I know of will let you do that) or interface with screen readers directly. As for content that needs a natural voice, like cut-scenes and whatnot, then there's nothing special you should keep in mind about the speed there. It should just flow with your story and theme.

## Q: How do you prefer lists? For like an inventory. Something more cursor based, where you go down individually, pages where each page is spoken out, or something in the middle?
A: Cursor-based navigation with the arrow keys would be easy to implement and straightforward to use. Think of pressing up/down arrows or tab/shift tab to browse the items. Whenever you press these keys and the focused item changes, the newly focused item is spoken out. If there are any more details about the item, have a key to announce it. Like a key for a description of the item, a key to use it or drop it, etc.

Having a hole page of items spoken out would probably be confusing. It's easier to just brows to your selected item than hearing a hole list of items spoken out just to know what you have.

# Other

## Q: What type of keyboard do you use?
A: I just use my laptop's internal keyboard. But if you mean blind people in general, then, well, it's mostly not limited to a single keyboard. Everyone uses the keyboard they like, just like sighted people.

## Q: Do you usually have a sighted person help you when setting up new games?
A: It depends on how accessible the game is. If the game is accessible enough (hopefully), I wouldn't have to. But if it needs sighted help to set it up, it's probably not playable for me anyway, so I wouldn't bother.

## Q: how is the experience of browsing the internet in general?
A: It depends on the website. Most sites are accessible enough; some exceptionally stand out.
