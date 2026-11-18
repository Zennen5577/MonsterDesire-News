# MonsterDesire News

The announcement shown in the game's main menu. The game downloads it on every launch changes reach players in about a minute.


## news.txt
Everything above the `---` line is settings, everything below it is the text.

| Setting | Meaning |
|---|---|
| `show: yes/no` | `no` hides the announcement |
| `title:` | title |
| `subtitle:` | subtitle |
| `image:` | file name of the image in the same folder (leave empty for no image) |

Text: an empty line starts a new paragraph, consecutive lines stay in the same paragraph, a line starting with `- ` is a bullet point.
TextMeshPro tags work: `<b>bold</b>`, `<i>italic</i>`, `<color=#FF78B8>color</color>`.

If the download fails, the game shows the last announcement it downloaded, or nothing if there is none.
