# Just Natsuki Unofficial Patch (JNUP)

A fan-made bug fix submod for [Just Natsuki](https://github.com/Just-Natsuki-Team/NatsukiModDev), built in Ren'Py 6.99 and designed to safely and non-invasively repair as many known bugs logged on the official project's GitHub Issues page as I can. Also, I fixed Blackjack's weird forfeit thing.

<img src="https://github.com/Zhaumbie/Just-Natsuki-Unofficial-Patch/blob/main/JNUP-header.png?raw=true">

> [!WARNING]
> **This is an unofficial fan-made submod for Just Natsuki. It is not affiliated with the Just Natsuki team.**  
> The developers are **not responsible for troubleshooting this submod** or problems caused by installing it.  
>
> > This **doesn't touch the persisent file**, but **please still back up your persistent data:** [How to back up your JN persistent file](https://github.com/Just-Natsuki-Team/NatsukiModDev/wiki/04:-FAQ#can-i-back-up-my-save-data--how-do-i-find-my-persistent)

*Seriously please for the love of god it takes like zero effort, just back up your persistent file (it is a really good habit)*

---

## What is this?

Click around in the [official JN Github's Issues page](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues?q=is%3Aissue%20state%3Aopen%20label%3ABug), and you'll see my fingerprints everywhere. I've been pretty busy staying on top of bugs for, oh, six months? Something like that. Well, this file compiles my repairs for every bug I've been able to confirm into one big, non-invasive, safe and effective patch.

Unless the bug was too big, or is too platform-specific—sorta like my [macOS log fixer](https://github.com/Zhaumbie/Fix-Broken-Log-macOS-for-Just-Natsuki). Those get their own submods.

### Features

This is a bug fix patch! It patches these bugs:

- [#980 - Blackjack treats "quitting" like "forfeiting"](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/980)
- [#978 - Shark literature joke repeats the setup wording](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/978)
- [#977 - Game-breaking permission error in the logging path](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/977)
- [#969 - Default music can sound glitchy while custom music doesn't](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/969)
- [#968 - Missing return causes the glasses double intro](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/968)
- [#967 - Glasses greeting double intro](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/967)
- [#963 - Maximizing the window can corrupt textures](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/963)
- [#945 - Typo in event_change_of_atmosphere](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/945)
- [#941 - Empty number boxes can crash the game](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/941)
- [#937 - Linux notifications can crash the game](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/937)
- [#925 - Blocked-screen quit attempts add a false apology](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/925)
- [#919 - Right window weather texture can flicker black](https://github.com/Just-Natsuki-Team/NatsukiModDev/issues/919)

And it fixes them **without touching the persistent file**.

Furthermore, literally every fix this patch enables **can be easily and independently turned off/on**. I did not want to build a big all-or-nothing patch file. Just open the .rpy file with TextEdit, WordPad, or whatever's your text/code editor of choice. if you *just* want the Blackjack fix, or want everything *but* the Blackjack fix... well, there you go!

### ...But why did you build this?

Frankly, I didn't want to. Just Natsuki Team's official Github is very clear that I'm supposed to fork their code and submit a pull request. Very common stuff. Big problem with that: **the only target branch they'll accept seemingly has never existed**, I got no answer when I tried to tell them, and nobody's exactly been picking up the phone since May 2025.

I get it. People get busy, and this is a passion project. So until the folks come back home with the milk, here's my next best option.

___

## Installation

1. Just to beat that dead horse, **back up your persistent data.** [Here's how to back up your JN persistent file.](https://github.com/Just-Natsuki-Team/NatsukiModDev/wiki/04:-FAQ#can-i-back-up-my-save-data--how-do-i-find-my-persistent)

2. Download the latest test build from **Releases**.

3. Copy the latest version of `just_natsuki_unofficial_patch.rpy` into your `game/submods/` folder.

4. If you have an older version, delete it.

5. OPTIONAL: turn off any bug fixes at the top of the file that you want.

6. Launch **Just Natsuki**.

7. Ta-da! It's already working!


## Removal

1. Delete your version of `just_natsuki_unofficial_patch.rpy` from your `game/submods/` folder.

2. There is no step two.

---

## Bug reports

If this file produces a new bug that doesn't exist without it... well then that's no good. Log an Issue telling me:

- what happened
- what you were doing right before it happened
- the traceback, if the game threw one
- your operating system

As usual, if it breaks, bring me your receipts.

---

## Credits

- **Team Salvato** for Doki Doki Literature Club
- The **Just Natsuki Team** for their hard work on this mod
- Espresso. Just... whoever invented espresso shots
