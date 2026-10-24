# Hello, I'm Abi. I'm made of Milk probably.

I am literally a slacker bum in sch and somehow still tired. Genuinely rethinking my life choices... CUTELY THO OwO??? >///<

I literally don't even do anything productive, my LinkedIn is basically empty, my GitHub is just full of random stuff and still I am somehow tired. I don't know why man, I really don't. Studies not good, code not good, just dumb ideas in my head bouncing around, going weeeee. Man I don't know where I'm goin with life, and that's just inspiration for more code.

Year 2 at Singapore Polytechnic. Programmer-for-fun (masochist, you can tell). Chronic notebook filler. I get really charmed by an idea - indoctrinated rather..., scribble increasingly unhinged diagrams about it for weeks, go on seventeen tangents, and then one day it just... becomes code. No plan. Just vibes and probably the SG haze making me high.

I kinda enjoy this, I guess. The part where nothing works, the part where it finally does, the weird detour where you end up learning something completely unrelated and get haunted about that instead.

---

## What I Actually Do

I tinker. Mostly just basic software, embedded systems, weird side projects, the occasional thing with no reason to exist. I'm doing computer engineering at SP and struggling with half of it, which is fine - I learn a lot more from just building things than I ever do from sitting in a lecture.

I should say upfront: I'm not a good coder - horrid if anything really. I take forever to start things, I get distracted constantly, I do weird stuff with projects for reasons I can't fully explain, and anything GUI or frontend-adjacent defeats me completely. Math too - I feel bad for my SP lecturers at this point for having to mark my abysmal math. My brain is kind of like a GPU - terrible single-core performance, somehow parallelised for no good reason. You'd watch me try to do something simple and think I was struggling. I am. I just also happen to have six other things running in the background. I am constantly over stimulated as fuck. (•_•)

It's fine. I like it here. Kinda... Maybe... I dunno.

### Linux on my Mac

**MSL** (Mac Subsystem for Linux) exists because I moved from my Surface Laptop 3 to a MacBook and missed WSL way too much. It runs real Linux distros on Apple silicon, in lightweight VMs on Apple's own Virtualization framework. Type `msl` and you're in a shell about a second later, with your Mac home folder already there. Linux apps open as actual Mac windows with their own Dock tiles, because I ended up writing my own X11 server in Swift (mslgd) to make that happen. Plus a whole Finder-style file manager, 12 distros, snapshots, a sandbox... it's been over a year and it's still held together by stubbornness ヽ(・∀・)ﾉ

### Terminal things

**ytcui** started as a "what if I just..." and turned into a full C++ ncurses YouTube client: search, play through mpv, playlists, vim keybinds, 18 colour themes and coloured thumbnails right in the terminal. Runs on Linux, macOS, the BSDs and WSL. It got away from me a little (•̀ω•́ )ゝ

**ytcui-dl** is the YouTube client underneath it, rewritten from scratch as a header-only C++17 library. No libcurl, no JSON library, no yt-dlp: its own little HTTP client and JSON scanner, a 240 KB binary, parallel resumable downloads, and video and audio fetched separately and muxed, so it goes past the old 360p ceiling all the way up to 8K. YouTube keeps changing things under it, so it's a never-ending game of catch-up (¬_¬)

**OneInstallSystem (OIS)** is the installer I got tired of rewriting for every project. Pure POSIX `sh`. Drop it into a repo, set one line in a config file, and your users get `sh install.sh`, a real uninstaller and `myapp --update` straight from GitHub releases, with checksums and instant rollback. It speaks 13 package managers, from apt and pacman to Homebrew, MacPorts and the BSDs. ytcui installs through it.

### Study things

**PaperNotes** is the study app I built for my own semester, and then it got a bit out of hand. It opens a folder of notes, slides, PDFs and past papers and turns it into a place to actually study: proper Markdown with maths and chemistry, a PDF reader you can write on, flashcards with spaced repetition, sticky notes, a Pomodoro timer, a music player, 15 themes, and Claude beside your notes if you want it. Your files stay plain files in your own folder. For Windows (｀・ω・´)ゞ

---

## How I Work

### Parallel development

I can't iterate linearly - my brain refuses. I'll run a few versions of a feature at the same time, let them evolve separately, then see what survives. Borrowed the idea from my plant hobby, honestly. Selective breeding but for code. Only the fittest (or most interesting) makes it through (´･ᴗ･ ` )

### Documentation-heavy

I rewrite READMEs and comments more than I write actual code some weeks. I'll spend an hour getting a single sentence right. This produces a suspicious contribution graph. It is what it is.

### On AI

I use AI the way I use documentation - to learn things I don't know yet. MIDI internals, how a garbage collector actually works, untangling complex merges. The ideas, the directions, the weird lil projects are mine. I mention it because transparency is just more comfortable (・‿・) I'm not the best coder, and I won't pretend to be. I use AI all the time to learn and to help clean up the messy code I write. That said, I don't believe in fully offloading a project to AI. I'm transparent about it because, honestly, I don't think it's right to pretend AI-generated work is entirely my own. XP

---

## Outside of Code

Plants. I grow things, make terrariums, think about small ecosystems a lot. It probably bleeds into how I think about projects - slow growth, careful iteration, things dying quietly and being replaced by something better.

Also: drawing, painting, woodworking, repairing old laptops and phones, and music - I love music deeply and I am completely hopeless at it and those two facts coexist peacefully.

And as you may be able to tell from my commit history... I need a bloody job. Bwahhh...

---

## Repos - Idk, whatever I thought I'd put here for fun :3

### [MSL](https://github.com/MilkmanAbi/MSL)
Mac Subsystem for Linux. Real Linux on Apple silicon, WSL style, with Linux apps as real Mac windows. Swift, its own X11 server, and a [121-article guide](https://milkmanabi.github.io/MSL-Wiki/) because I can't stop writing docs.

### [ytcui](https://github.com/MilkmanAbi/ytcui)
Terminal YouTube client. C++, ncurses, mpv, 18 themes, playlists, coloured thumbnails. Got a little out of hand :3

### [ytcui-dl](https://github.com/MilkmanAbi/ytcui-dl)
Header-only C++17 YouTube client. No libcurl, no JSON library, no yt-dlp. Parallel resumable downloads, up to 8K.

### [OneInstallSystem](https://github.com/MilkmanAbi/OneInstallSystem)
Drop-in installer, updater and uninstaller in pure POSIX sh. One config line, 13 package managers, Linux, macOS and the BSDs.

### [PaperNotes](https://github.com/MilkmanAbi/PaperNotes)
Study app for Windows. Notes, slides, PDFs and past papers in one place, with flashcards, stickies, Pomodoro and an optional Claude sidekick.

---

If you're here, (￣▽￣)  Hallo, hallo, hallo! GitHub ya!
