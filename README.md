# Sreenath Kyathanahally — Personal Portfolio

AI Innovation Leader specializing in Computer Vision, Generative AI, and Edge AI.

**Live site:** [kspruthviraj.github.io](https://kspruthviraj.github.io)

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, glassmorphism, grid/flexbox, scroll animations
- **Vanilla JS** — IntersectionObserver, requestAnimationFrame-throttled scroll, mobile nav
- **Fonts:** Inter (Google Fonts)
- **Icons:** Font Awesome 6.5 (CDN)
- **Contact:** [Web3Forms](https://web3forms.com) (serverless email)

No build tools, frameworks, or dependencies — single self-contained `index.html`.

## Structure

```
.
├── index.html              # Complete site (HTML + inline CSS/JS)
├── Kyathanahally.pdf       # Downloadable CV
├── assets/img/
│   ├── profile-img2.png    # Hero profile photo
│   └── img_09.avif         # (unused, kept for reference)
├── googlee21c3da747b38fea.html  # Google site verification
└── README.md
```

## Sections

| Section        | Content                                    |
|----------------|--------------------------------------------|
| Hero           | Name, tagline, stats, CV download, GitHub  |
| About          | Professional summary + 4 highlight cards   |
| Skills         | 9 cards (3×3 grid)                         |
| Projects       | 6 cards (3×2 grid)                         |
| Experience     | Timeline with 9 roles                      |
| Education      | 3 degree cards                             |
| Awards         | 7 award cards                              |
| Publications   | Google Scholar link                        |
| Contact        | Info + Web3Forms message form              |

## Local Development

```bash
# Serve locally (any static server works)
python3 -m http.server 8000

# Then open http://localhost:8000
```

## Contact Form Setup

The contact form uses [Web3Forms](https://web3forms.com). To configure:

1. Sign up at [web3forms.com](https://web3forms.com) with your email
2. Copy your access key
3. In `index.html`, replace `YOUR_ACCESS_KEY_HERE` with your actual key

## License

Content © Sreenath Kyathanahally. Template design is original work.
