If you have never made a game for blind gamers before, you may feel overwhelmed and confused about where to start. Here's some information that might be useful.

# TL;dr

- Blind gamers generally use a screen reader, such as NVDA (on Windows) or Orca (on Linux) to game. These read the contents of the screen aloud, getting text and working out structure and order based on the document structure or accessibility APIs.
- There's no one right way to do things: there are many different kinds of vision impairment that may change how a gamer interacts with a game, and there are different approaches to making a game accessible.
- Turning off your monitor and playing your game with no display is a good way to test it if you are developing a game for total vision loss.
- Ask for feedback from blind gamers early and often. Our [Discord server](https://discord.gg/Zd6B7vYBDx) has a channel to facilitate this.

# Blind Inclusivity 101

While blind players have their own preferences, you can generally make your game more accessible and inclusive to them, by adding the following. These are ordered roughly from best to worst:

- **Screen-Reader Integration:** Being able to send text-to-speech messages directly to their screen readers is a big win. This respects user preferences in terms of voice choice and playback speed, is a familiar interface, and allows for advanced features such as rewinding and fast-forwarding.
- **Text to Speech:** Your game engine of choice may have text-to-speech capabilities (e.g. Godot). In this case, best practices include allowing users to select their choice of voice and playback speed.
- **Additional and Spatial Audio:** Audio-only games are a genre in of themselves, and designing a game around audio is one way of making a game that is accessible to blind gamers. If your game engine of choice supports it, consider playing audio in 2D, relative to the player: e.g. things on the left of the player sound mostly/entirely from the left speaker, and ditto for things on the right side.
