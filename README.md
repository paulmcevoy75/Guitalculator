# The Guitalculator

**Open the app: https://paulmcevoy75.github.io/Guitalculator/**. It runs in your browser, there's nothing to install, and nothing you enter leaves your computer.

The goal of the project is a desktop app that luthiers can use for common calculations.

Currently it's an HTML program that I started a while ago, but it may be that HTML is absolutely wrong for this. It's entirely vibe coded on Claude so far.

## What it does

1. **Nut and saddle compensation** for all manner of fretted instruments, with several formulas for nut compensation.
2. **String spacing** for all manner of instruments.
3. **A unit converter** for measurements. It's also a place where you can store measurements you use often.
4. **Wired!: a guitar wiring designer.**
   - You lay out pickups, switches, pots and the output jack, and wire what each switch position should do.
   - The app works out which lug every wire goes on and checks every switch setting.
   - It draws a lug-to-lug wiring diagram in the pickups' real lead colours, a build sheet, and a tone graph for each setting.

## Files

- **`index.html`**: the current version (this is what the link above opens).
- **`The Guitalculator vNN.html`**: earlier versions, kept for reference. To use one offline, download it and open it in a browser.

## Helping out

Feedback is very welcome, especially from people who build and wire guitars.

- **Found something wrong?** [Report a bug](../../issues/new?template=bug.yml). A wrong number or a wiring diagram that doesn't match what you got on the bench is exactly what I want to hear about.
- **Have an idea?** [Suggest a feature](../../issues/new?template=idea.yml).
- **Want to change the code?** See [CONTRIBUTING.md](CONTRIBUTING.md).
