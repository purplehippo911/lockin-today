# Lock In Today 

A focus app with todos, pomodoro timer and focus music

## Web version 
[lockin-today webapp](https://pomodoro-app.7c7a4f33-a16b-46f1-98bb-da21899751a8.workers.dev/)

## ARCH LINUX -- Download through AUR



```
sudo pacman -S webkit2gtk-4.1 gtk3
git clone https://aur.archlinux.org/lockin-today-git.git
cd lockin-today
mkpkg -si
```

## Downloading for every other platform 

### Step 1 -- Requirements and setup

Check out the links here to download:

- [Rust](https://rustup.rs)
- [Deno](https://deno.land/#installation)
- Git


### Step 2 -- Cloning repository

```
git clone https://github.com/purplehippo911/lockin-today.git

```

Now go into the newly made directory before you run the other commands.

On LINUX it is:

```
cd lockin-today 
```

## Step 3 -- Building the project

Installing the packages:

```
deno install
```

Finally building it:

```
deno task build
```

### Step 5 -- Find the executable file

The name of the executable file should be `lockin-today` under `src/target/release`

Run that file

-----

## Attribution

Thanks to the creators of these assets, that I used for this project

[Delta wave with Brown Noise by PureBinaural at pixabay.com](https://pixabay.com/music/ambient-purebinaural-25-hz-delta-binaural-beats-with-brown-noise-484855/)

[Beta Waves Meditation Flute (short) by Siarhei_korbut](https://pixabay.com/music/meditationspiritual-beta-waves-meditation-flute-short-386121/)

[Binaural Beta waves by Mr Washingt0n](https://pixabay.com/music/ambient-binaural-beta-waves-491929/)

[alarm clock sound effect by gecop at freesound.org](https://freesound.org/people/gecop/sounds/522119/)

Made with Tauri, Vue and Typescript
