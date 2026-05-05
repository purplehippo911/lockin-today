# Lock In Now - A focus app with todos, pomodoro timer and focus music

## Downloading/Building

### Step 1 -- Requirements and setup

Check out the links here to download:

- [Rust](https://rustup.rs)
- [Deno](https://deno.land/#installation)
- [Git]


```
git clone https://github.com/purplehippo911/pomodoro-app.git

```

Now go into the newly made directory before you run the other commands.

On LINUX it is:

```
cd pomodoro-app
```

### Step 2 -- installing Tauri-cli

Install tauri-cli

```
# Either this way
cargo install tauri-cli

# or this way
npm install -g @tauri/apps/cli

```

### Step 3 -- Finally building the project

```
# Either this way
deno task build

# or this way
cargo tauri build

```

### Step 4 -- Find the executable file
go under `src-tauri/target/release` and run the executable app either by running it in the terminal or by clicking on it when you're inside your file manager app.

-----
[Delta wave with Brown Noise by PureBinaural at pixabay.com](https://pixabay.com/music/ambient-purebinaural-25-hz-delta-binaural-beats-with-brown-noise-484855/)
[Beta Waves Meditation Flute (short) by Siarhei_korbut](https://pixabay.com/music/meditationspiritual-beta-waves-meditation-flute-short-386121/)
[Binaural Beta waves by Mr Washingt0n](https://pixabay.com/music/ambient-binaural-beta-waves-491929/)
[alarm clock sound effect by gecop at freesound.org](https://freesound.org/people/gecop/sounds/522119/)

Made with Tauri, Vue and Typescript
