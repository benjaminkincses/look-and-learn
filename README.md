# Look & Learn

[![Made with pollinations.ai](https://raw.githubusercontent.com/pollinations/pollinations/main/packages/ui/src/brand/badge-made-with.svg)](https://pollinations.ai/?ref=badge)

Point your camera at anything and learn what you see.

Open the app, start the camera or upload a photo, tap "What is this?", and get a short lesson: what the object, plant, animal, place or thing is, three quick facts, and one small detail to look closer at.

Live app: https://benjaminkincses.github.io/look-and-learn/

## How it works

- One static page, no build step, no server.
- Sign in with Pollinations using the `<polli-connect>` button. Your own balance pays for each look. No key pasting, no app key in the page.
- Photos are resized in the browser and sent to the `openai/gpt-5.4-nano` vision model on `gen.pollinations.ai`. Nothing is stored.
- Three bundled samples with ready answers work without sign-in or a camera.

## Run it locally

Serve the folder with any static server, for example:

```
npx serve .
```

Camera access needs HTTPS or localhost.

## Sample photo credits

From Wikimedia Commons:

- Sunflower: "Sunflower sky backdrop" by Fir0002, GFDL 1.2
- Red fox: "Alaska Red Fox (Vulpes vulpes)" by Gregory "Slobirdr" Smith, CC BY-SA 2.0
- Lighthouse: "Leuchtturm in Westerheversand crop" by Marco Leiter, CC BY-SA 4.0

## License

MIT
