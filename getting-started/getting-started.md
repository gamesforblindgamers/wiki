If you never made a game for blind gamers before, you may feel overwhelmed and confused about where to start. Here's some information that might be useful.

# TL;dr

- Blind gamers generally use a screen reader, such as NVDA (on Windows) or Orca (on Linux) to game. These read out the contents of various things.
- Turning off your monitor and playing your game blind is a good test.
- Blind gamers encompass a huge range of sight levels (yes, really) and preferences. There's no one "right" way to do things.
- Ask for feedback early and often. Our [Discord server](https://discord.gg/Zd6B7vYBDx) has a channel to facilitate this.

# Blind Inclusivity 101

While blind players have their own preferences, you can generally make your game more accessible and inclusive to them, by adding the following. These are ordered roughly from best to worst:

- **Screen-Reader Integration:** Being able to send text-to-speech messages directly to their screen readers is a big win. It uses their preferences in terms of voice choice and playback speed, it's familiar to them, and it allows advanced features such as rewinding and fast-forwarding.
- **Text to Speech:** Your game engine of choice may have text-to-speech capabilities (e.g. Godot). In this case, best practices include allowing users to select their choice of voice and playback speed.
- **Additional and Spatial Audio:** Depending on your game, you may just need spatial audio! If your game engine of choice supports it, consider playing audio in 2D, relative to the player: e.g. things on the left of the player sound mostly/entirely from the left speaker, and ditto for things on the right side.