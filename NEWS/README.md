# MonsterDesire News

The announcement shown in the game's main menu (the free and the Patreon version show the same one). The game downloads it on every launch; changes reach players within about 5 minutes.

- `news.txt` : settings + the text of the three cards
- `image1.jpg` : top card (free version), `image2.jpg` / `image3.jpg` : bottom card rows (Patreon)
- Images: JPG, 812x560 (aspect 1.45, the slot crops anything wider or taller), under 300 KB each

## news.txt
General settings at the top:

| Setting | Meaning |
|---|---|
| `show: yes/no` | `no` hides the announcement |
| `itch:` | itch.io page of the game (the itch.io badge opens it; empty = the default page) |
| `patreon:` | Patreon page (empty = the default page) |

Then one section per card, starting with `=== 1 ===`, `=== 2 ===`, `=== 3 ===`.
With all three sections the Patreon perks scroll in a ribbon at the bottom of the Patreon card. Leave out `=== 3 ===`
(and its text) to show the Patreon perks panel in the third row instead. Inside a section, everything above the `---` line is settings, everything below it is the text:

| Setting | Meaning |
|---|---|
| `subtitle:` | small pink line above the title |
| `title:` | title |
| `image:` | file name of the image in this folder |

Text: an empty line starts a new paragraph, consecutive lines stay in the same paragraph, a line starting with `- ` is a bullet point.

If the download fails, the game shows the last announcement it downloaded, or nothing if there is none.