# VFSO Website

Source for the website of the **Vertical Farming Student Organization at UC San Diego (VFSO)**, an interdisciplinary, student-led organization dedicated to the research, design, construction, and operation of a vertical farming system on campus.

**Live site:** https://site-tau-blue-79.vercel.app

## Get involved

- Discord: https://discord.gg/M6tk7K2BP
- Instagram: [@vfsoatucsd](https://www.instagram.com/vfsoatucsd/)
- Email: vfsoatucsd@gmail.com
- Meetings: Tuesdays, 5–6 PM, Climate Action Lab, Ridge Walk Academic Complex (Sixth College)

## Repository contents

| Path | What it is |
| --- | --- |
| `site/` | The website: plain HTML, CSS, and JavaScript with no build step |
| `site/images/` | Leadership headshots |
| `UPDATED_V2 VFSO Constitution .docx` | The organization's constitution |
| `UCSD Center For Student Involvement - Student Organization Registration.pdf` | VFSO's CSI registration listing |

## Run locally

```bash
python3 -m http.server 4173 --directory site
```

Then open http://localhost:4173.

## Deploy

The site is deployed on [Vercel](https://vercel.com) from the `site/` directory:

```bash
cd site
npx vercel deploy --prod
```

## Contributing

Pull requests are welcome. Keep content accurate to official VFSO sources: please don't add events, partners, or accomplishments that the organization hasn't confirmed.

## License

The website source code (`site/*.html`, `site/*.css`, `site/*.js`, `site/favicon.svg`) is released under the [MIT License](LICENSE).

The headshots in `site/images/` belong to the people pictured and are **not** covered by the MIT License. The constitution and CSI registration documents are included for reference only. VFSO is a registered student organization and is not an official unit of UC San Diego.
