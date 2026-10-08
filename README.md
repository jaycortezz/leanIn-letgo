# Lean In & Let Go

A redesign of [leaninandletgo.com](https://www.leaninandletgo.com): same content, new warm, sun-faded boutique look (terracotta, pink, cream, a yellow accent, film grain, arch-shaped photos).

Plain static HTML/CSS, no build step. Open `index.html` or serve the folder:

```sh
python3 -m http.server 8000
```

| Page | File | Old URL |
| --- | --- | --- |
| Home | `index.html` | `/` |
| About | `about.html` | `/services` |
| Approach | `approach.html` | `/fees` |
| Services | `services.html` | `/our-approach` |
| Contact | `contact.html` | `/cotact` |

The contact form opens the visitor's email app with the message filled in. To receive submissions directly, point the form at a service such as Formspree or Netlify Forms.
