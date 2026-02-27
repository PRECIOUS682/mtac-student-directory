# Mauke Tech Academy - Kau Mapu 2026

Student directory for the Mauke Tech Academy 2026 cohort. Each student adds themselves by contributing a pull request.

## How to Add Yourself

### 1. Fork this repo

Click the **Fork** button at the top-right of this page to create your own copy.

### 2. Clone your fork

```bash
git clone https://github.com/YOUR-USERNAME/mtac-student-directory.git
cd mtac-student-directory
```

(Replace `YOUR-USERNAME` with your GitHub username.)

### 3. Add your photo

Put your photo in the `images/` folder. Name it with your name in lowercase, using dashes instead of spaces:

```
images/jane-doe.jpg
```

Keep it reasonably sized (under 1MB). Square photos work best.

### 4. Add your card to `index.html`

Open `index.html` and find the template block near the bottom (look for `START COPY` / `END COPY`).

Copy the template and paste it **below** the `<!-- ADD YOUR CARD BELOW THIS LINE -->` comment. Then fill in your details:

```html
<a href="https://your-website.com" class="student-card">
    <img
        src="images/jane-doe.jpg"
        alt="Photo of Jane Doe"
        class="student-photo"
    >
    <p class="student-name">Jane Doe</p>
</a>
```

- **href** - link to your website (use `#` if you don't have one)
- **src** - path to your photo in the `images/` folder
- **alt** - "Photo of Your Name"
- **student-name** - your name

### 5. Commit and push

```bash
git add images/your-name.jpg index.html
git commit -m "Add Jane Doe to student directory"
git push
```

### 6. Open a Pull Request

Go to your fork on GitHub and click **"Contribute" > "Open pull request"**.

Give it a title like "Add Jane Doe" and submit it. Your instructor will review and merge it!
