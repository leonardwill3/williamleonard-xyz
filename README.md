# williamleonard.xyz

Personal site. Single `index.html` file — no build step, no dependencies.

## How to edit

Tell Claude what you want changed in plain English. Examples:
- "Change my tagline to 'Investor and writer based in Atlanta'"
- "Add a new writing: 'Title' linking to https://..."
- "Remove the Morgan Stanley entry from Work"
- "Make the background pure white instead of off-white"

Claude edits `index.html` directly.

## How to deploy changes

After Claude edits the file, push to your Git repo. Vercel will redeploy automatically (takes ~10 seconds).

If you don't want to use Git, you can drag-and-drop the file into the Vercel dashboard each time.

## Structure

Everything lives in `index.html`:
- HTML content (top section)
- CSS styles (in the `<style>` block at the top)
- A tiny script at the bottom that auto-updates the copyright year
