# Codezen Regmi's Vlog

Live at **https://codezenblog.github.io/**

Anyone can read it. Only you can post, because only you can change this repo.

---

## ✍️ Write a new post (3 minutes, works on your phone)

**1. Open this link** (bookmark it, it's your "New post" button):

👉 [**New post**](https://github.com/codezenblog/codezenblog.github.io/new/main/_posts?filename=YYYY-MM-DD-my-title.md&value=---%0Atitle%3A%20Write%20your%20title%20here%0Adescription%3A%20One%20sentence%20about%20this%20post.%20This%20shows%20on%20Google.%0Atags%3A%20%5Blife%5D%0A%23%20youtube%3A%20PASTE_VIDEO_ID_HERE%0A---%0A%0AStart%20writing%20here.%0A%0A%23%23%20A%20heading%20if%20you%20want%20one%0A%0AMore%20writing.%0A)

It opens GitHub with the template already filled in.

**2. Change the file name at the top.** Replace `YYYY-MM-DD` with today's date and `my-title` with a few words, using dashes and no spaces:

```
2026-10-21-how-i-got-my-first-100-users.md
```

**3. Change the top part (between the `---` lines):**

| Line | What to write |
|---|---|
| `title:` | The headline. Make it something people would search for. |
| `description:` | One sentence. Google shows it under your title. |
| `tags:` | A few words like `[creovel, ai, life]`. |
| `# youtube:` | Only for a video: remove the `#` and paste the video ID. |

**4. Write your post below the second `---`.**

**5. Click "Commit changes…" (green), then "Commit changes" again in the pop-up.**

About 1 minute later it's live on the homepage. Done.

---

## 📝 Formatting cheat sheet

```markdown
## Big heading
### Smaller heading

**bold**   *italic*

[link text](https://creovel.com)

- bullet point
- another one

1. numbered
2. list

> a quote

![photo description](/assets/images/my-photo.jpg)
```

Leave an **empty line between paragraphs**, otherwise they join into one.

Click the **Preview** tab in the GitHub editor to see how it looks before you commit.

---

## 🎥 Add a YouTube video

From a link like `https://www.youtube.com/watch?v=abc123XYZ`, the ID is the part after `v=`: **`abc123XYZ`**.
For a link like `https://youtu.be/abc123XYZ`, it's the part after the `/`.

In the top part of your post:

```
youtube: abc123XYZ
```

The video shows at the top of the post, and the homepage marks it as **Video**.

---

## 📸 Add photos

1. Open [assets/images → Upload](https://github.com/codezenblog/codezenblog.github.io/upload/main/assets/images) and drag in your photo.
2. Use simple names like `creovel-launch.jpg` (no spaces). Then commit.
3. In your post: `![Creovel launch day](/assets/images/creovel-launch.jpg)`

To use a photo as the post's cover and share image, add this to the top part: `image: /assets/images/creovel-launch.jpg`

---

## ✏️ Edit or delete a post

Go to [_posts](https://github.com/codezenblog/codezenblog.github.io/tree/main/_posts) and open the post.

- **Edit:** pencil icon ✏️, change it, commit.
- **Delete:** `⋯` menu → **Delete file**, commit.
- **Hide without deleting:** add `published: false` to the top part.

---

## 🔍 Google (indexing)

**You don't need to do anything for each post.** Every new post is added to `sitemap.xml` automatically, and Google already knows about the sitemap through Search Console. It checks back on its own and finds new posts, usually within a few days.

To get a post found faster (optional), open [Search Console](https://search.google.com/search-console), paste the post's link into the top search bar, and click **Request indexing**.

Tips that help posts rank:
- Write a clear `title` and `description` every time.
- Post regularly.
- Share each post on Instagram and LinkedIn. Links from other sites help Google find and trust you.

---

## ❗ Post not showing up?

Check these, in order:

1. **File name.** It must look exactly like `2026-10-21-some-title.md`: a real date, dashes, and `.md` at the end. `YYYY-MM-DD` left in the name means the post is ignored.
2. **Date in the future?** Posts dated later than today stay hidden until that day.
3. **The `---` lines.** The top part needs a `---` line before it and a `---` line after it.
4. **Did it build?** Open [Actions](https://github.com/codezenblog/codezenblog.github.io/actions). A green ✓ means live, a red ✗ means something in the post broke the build. Click it to see what.
5. **Still old?** Wait a minute and refresh. Your browser may be showing the old page.
