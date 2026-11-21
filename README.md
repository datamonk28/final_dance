# Somewhere, in the Universe of Us

A no-build static website made with HTML, CSS and JavaScript. It can be hosted using GitHub Pages.

## Add your photographs
1. Open the `photos` folder.
2. Add your images. Use simple filenames such as `photo-01.jpg`, `birthday.jpg`, or `first-gift.png`.
3. Open `index.html` and find `const memories = [...]`.
4. Replace the sample image paths, titles, categories and captions with your own.
5. Add or remove entries by copying/removing an object in that array.

Example:
```js
{
  image: "photos/birthday.jpg",
  title: "A birthday to remember",
  category: "Birthdays",
  caption: "Thank you for remembering my day. I will always be grateful for this little moment."
}
```

## Add messages
Find `const messages = [...]` in `index.html` and replace the sample text with the messages you want to preserve. Keep excerpts short and only include messages you have permission to share.

## Change the final note
Search for `Thank you for the gifts` in `index.html` and edit the final gratitude paragraph.

## Preview locally
Double-click `index.html` to open it in your browser. For best results, use a local development server or GitHub Pages.

## Publish with GitHub Pages
1. Create a new GitHub repository. If the site is private, check your GitHub plan and Pages visibility settings; GitHub Pages sites are commonly public even when the repository is private.
2. Upload `index.html`, the `photos` folder and this README.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. Wait for GitHub to publish the site. The Pages URL will appear in Settings → Pages.

## Privacy note
A GitHub Pages website is public on the internet in the usual setup. Do not upload intimate photographs, private messages or identifying information unless you are comfortable with anyone who has the link viewing them. For a genuinely private keepsake, keep it local or use an authenticated private hosting option.
