# discord css

my personal QuickCSS for discord. i run it through vencord but it should work anywhere QuickCSS is supported (betterdiscord etc). mostly written for the visual refresh UI, so if you're still on the old layout most of it won't do anything.

this has been cobbled together from a bunch of different places over time: other people's themes, snippets from github and the vencord plugin repo, stuff i found on discord. it is very much not all my code. credit where it's mostly due: the guild bar section comes from scattagain's GuildbarRevert. if any of it looks familiar, it's because it probably is.

## using it

vencord settings -> QuickCSS -> paste in `quickCss.css`. that's it.

note: it imports [GuildbarRevert](https://scattagain.github.io/VencordStuff/css/GuildbarRevert.css) at the top, so you need that to load for the guild bar stuff to look right.

## what it does

- bigger round server icons that squish into squares when you click them
- tones down the border radius on basically everything (4px)
- kills the username gradients and name glow
- hides the gift button in chat
- the friends list side panel is removed entirely (the blur-until-hover version is also in the css, comment out the `display: none` rule for the panel if you'd rather have that)

## warning

discord shuffles their class hashes constantly so things will just randomly break sometimes. i use this myself though so it does get patched whenever something breaks badly enough to annoy me. no guarantees anything here stays working.

## license

CC BY 4.0. short version: do whatever you want with it, just keep the credits intact since a bunch of it isn't mine to begin with. full text in the LICENSE file.

steal whatever you want from it.
