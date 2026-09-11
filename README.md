# Send It — putting the mock-up on your Android phone

Everything in this folder is the app. There is no build step, no Node, no install.
Five files: the game, an offline cache, a description file and three icons.

---

## The quickest route: GitHub Pages

You need a free GitHub account. About ten minutes, once.

1. Go to **github.com**, click **New repository**. Call it `send-it`.
   Set it to **Public**. Tick nothing else. Create it.

2. On the empty repository page click **uploading an existing file**.
   Drag in **all the files from this folder**: `index.html`, `sw.js`,
   `manifest.json`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`,
   `apple-touch-icon.png`. Click **Commit changes**.

3. Go to **Settings**, then **Pages** in the left sidebar.
   Under *Branch*, choose **main** and **/ (root)**. Click **Save**.

4. Wait a minute, then refresh. GitHub shows your address, in the form
   `https://YOURNAME.github.io/send-it/`

5. On your phone, open **Chrome** and go to that address.
   The game loads.

6. Chrome menu (three dots), then **Add to Home screen** or **Install app**.
   Confirm.

You now have an icon on your home screen. Tapping it opens the game full screen,
with no browser bar, and it works **with no signal**, on the train or in a cellar bar.

Share that same address with your friends and they can install it too.

---

## Updating it later

When I give you a new `index.html`:

1. Upload the new file to the same repository, replacing the old one.
2. **Also** open `sw.js` and change `sendit-v1` to `sendit-v2`.
   Without this your phone keeps serving the copy it already cached and you
   will swear nothing changed.
3. On the phone, close the app fully and reopen it twice. The first open
   fetches the new version, the second shows it.

---

## If you would rather not use GitHub

**Netlify Drop** — go to `app.netlify.com/drop` and drag this whole folder onto
the page. It gives you an address immediately. Free, and you can claim it with an
account later if you want to keep it.

Either way you need a real web address, not a file on the phone. Android will
open an HTML file from your Downloads folder, but it will not let you install it
to the home screen or run it offline, which are the two things worth having.

---

## What each file does

| File | What it is for |
|---|---|
| `index.html` | The whole game. Rules, board, art, everything. |
| `manifest.json` | Tells Android the name, the icon and that it should open full screen. |
| `sw.js` | Keeps a copy on the phone so it runs offline. |
| `icon-*.png` | The home screen icon. The maskable one is for phones that crop icons into circles or squircles. |

---

## Worth knowing before the pub

- **The game does not save yet.** Closing the app loses the current climb.
  Worth adding before you rely on it for a long session.
- **Hot seat needs one phone passed around.** A tablet is far better than a phone
  for four players, the board is easier to read.
- Landscape suits the wider routes, portrait suits the tall ones.
