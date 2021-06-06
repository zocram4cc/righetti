# Righetti
## Righetti - Gameplay patch for PES21

Righetti is the gameplay patch specifically developed for and by [the 4chan Cup](https://implyingrigged.info) for its use in Pro Evolution Soccer 2021, to attempt to fix its lack of entertainment value when watched in coach mode, by editing a legacy file Konami includes in all of its games in data pack 18 which allows the user to tweak a number of gameplay constants loaded at match time. Its name is a very unsubtle nod at the nationality of the original developer.

**Note:** You can contribute to the patch's development, but please, upload any changes\forks in BIN, CPK and text form *at the same time*. Don't make the documentation drift from the actual binary. Thank you.

**Current patch notes:**
- Significantly reduced or zeroed all wait times, making the game feel a lot snappier.
- Reduced the maximum pass distances for long lobbed passes both in play and on goal kicks to curb some of the persistent long ball issues.
- Expanded all angles and ranges for short passing options across the board, giving the AI more options.
- Made the defense a lot pressier than stock, and it should now stay around the midfield line when attacking on FLP, giving more passing options. (see team/basePosition)
- Significantly heightened the AI's ability to see potential throughball targets (see team/lineBreak)
- Made the attacking AI more capable of taking more chances, but without being laser precise. (see team/spaceRun)
- Slightly nerfed the defence's marking abilities.
- Slightly nerfed the keepers.
- About a million more minor changes across the board. For further detail, feel free to browse the data or ask any question to what does what to me or Neon63. More help is always welcome.

**Known bugs:**
- Maybe an overreliance on "sieges" - AKA bunching up at the edge of the box. It's a tendency for 21 to do this, but 0.04 seems to have heightened it a little

### How do I read this shit
The text files follow this format:
```bash
STOCK VALUE   PATCHED VALUE //variable description
```

## TODO:
- Wait for feedback after Summer and see what's to be changed.
