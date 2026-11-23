# 300 Feet — Dhaka Road Run

A self-contained, original browser driving game inspired by Dhaka's 300 Feet Road. It uses hand-drawn Canvas art, HTML, CSS and JavaScript, with no build step or game engine.

## Play and controls

Open `index.html` in a modern browser, or deploy this folder to Netlify Drop.

- **Up / W:** accelerate; **Down / S:** brake; **Left / Right / A / D:** steer.
- On touchscreens, use the four on-screen controls.
- The view stays in third-person so your car remains visible.
- Open the in-game **MENU** at any time to pause and switch between the Chase and Free Drive modes without refreshing.
- The menu shows how many game tabs are open in the same browser using built-in browser presence. It does not count visitors on other devices; that needs a shared online presence backend.
- Use **সোনালি বিকেল / রাতের ড্রাইভ** to switch from golden hour to night.
- The Run is a 90-second trip to Neela Market. It has six cars on a wide, one-way three-lane road. One collision ends the run.
- Free Drive has nine cars, no finish line, and no traffic dialogue bubbles. Police checks happen at 30-second intervals, with a low chance of a chase each time; being caught does not end the drive.
- The player speed is capped at 180 km/h. In The Run, sustained speeding brings a faster police car that can reach 160 km/h. Slowing down makes it catch you.
- The footer meter shows police distance. **ইতিহাস** saves your recent runs on this browser and ranks your local results.

## Radio and sound

- **Radio Foorti 88.0 FM** plays the station's live stream in the browser. The slider changes its volume; the button starts or stops it. The live broadcast needs an internet connection and may be unavailable if the station stream is down.
- The effects button independently controls the synthesized engine, louder police siren, chase-start cue, escape cue, catch cue, and crash sound.
- Police and traffic speech uses the browser's Bengali speech voice when one is installed.

The game illustrations and sound effects are original. The Foorti button plays the broadcaster's live stream from its website; the game does not package or rebroadcast music files.

## Scores and custom address

This project is static, so run history is stored on the current browser only.

