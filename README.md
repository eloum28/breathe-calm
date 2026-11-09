# Breathe Calm

A responsive static guided-breathing app with a photorealistic seated person, a large second-by-second countdown, adjustable inhale/exhale pacing, and controls for Start, Pause, Resume, and Reset.

## Use

Open `index.html` in a browser or host the repository as a static site. Keep the `assets/` folder beside `index.html`. No build, packages, API keys, database, or backend are required.

## Features

- Photorealistic AI-generated figure with subtle chest displacement synchronized to the breathing timer
- Inhale/exhale countdown and session-progress indicator
- Start, Pause, Resume, and Reset
- Preset rhythms (4/6, 4/4, 3/5) and custom duration sliders
- Timed sessions (2, 5, or 10 minutes) and unlimited mode
- Optional breath-change chime
- Light/dark theme, mobile-friendly layout, and reduced-motion support
- Locally saved preferences and daily session count

## Deploy on Vercel (GitHub)

1. Push these files to a public GitHub repository named `eloum28/breathe-calm` on the `main` branch.
2. In the [Vercel dashboard](https://vercel.com/new), choose **Add New → Project** and import `eloum28/breathe-calm`.
3. Set **Framework Preset** to **Other**, **Root Directory** to `./`, and leave **Build Command** blank. Set **Output Directory** to `.` if asked.
4. Click **Deploy**. Subsequent pushes to `main` will automatically update the production deployment when the Git repository is connected.

Vercel may generate a unique project hostname; verify the actual deployment URL in the Vercel dashboard rather than assuming one.

## Safety

Breathe gently and comfortably. Stop if you feel dizzy, short of breath, or uncomfortable. This is a relaxation guide, not medical treatment.

## Visual asset

`assets/breathing-man-reference.png` was generated with the built-in image generation tool. It is a synthetic photographic image, not footage of a real breathing instructor. The app animates a small region of the chest; pause and reduced-motion settings stop that movement.
