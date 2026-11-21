# Contributing to the Guitalculator

Thanks for helping. A few things make it easier to work together.

## How the project is laid out

- The whole app is one file. **`index.html`** is the current version, and the HTML, styles and scripts are all inside it.
- There's no build step and nothing to install. Open the file in a browser to run it.
- `The Guitalculator vNN.html` files are older versions, kept for reference. Don't edit them.

## Reporting problems

Please use the [issue forms](../../issues/new/choose). The most useful reports include:

- which tab you were on (Dimensions, Saddle, Wired!, and so on);
- what you entered;
- what the app showed and what you expected;
- for wiring, the switch and pickups you used, and your source for the expected result (a maker's diagram, or what you measured with a meter).

## Changing the code

1. Fork the repo, or ask to be added as a collaborator.
2. Edit `index.html` on a branch.
3. Open the file in a browser and check the tab you changed. Also check that the other tabs still load, and that the browser console shows no errors.
4. Open a pull request saying what you changed and why. If a figure or formula comes from a book, maker or other source, say which one.

## Ground rules

- **Accuracy over features.** Numbers in this app end up as cuts in real instruments. Don't change a formula or figure without a source.
- **Keep it in one file** that works offline and sends nothing anywhere.
- **Don't add copyrighted material**, such as scanned book pages or makers' diagram artwork. Link to the source instead.
