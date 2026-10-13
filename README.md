# AI Disclosure Builder

A draft tool by Dr. Alec Couros for reporting AI use in teaching, learning, and research. Students can create disclosure statements and supporting records. Faculty can set assignment expectations, share assignment links, and disclose their own AI use.

[Use the live tool](https://couros.ca/aidisclosure/)

This is an independent prototype for feedback. It is not approved or endorsed by the University of Regina. Follow your course instructions and applicable institutional guidance.

## Run or host it

The app is a standalone `index.html` with inline CSS, JavaScript, an illustration, and a bundled Word export library. No installation or build step is required. Open the file in a modern browser or serve it from any static web host.

For local development:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`. To deploy through cPanel, upload `index.html` to `public_html/aidisclosure/`. Include the licence files and third-party notices when redistributing the app. GitHub commits do not automatically deploy to couros.ca.

## Data and exports

The tool uses templates and browser JavaScript to create statements. It does not call an AI model or upload answers. It supports optional browser save/resume, plain-text and Word downloads, and PDF through the browser print window. Assignment links contain assignment settings, so share them with that in mind.

The repository contains application files only, with no student answers or saved browser data.

## Open licences

Copyright (c) 2026 Alec Couros.

- **Original software code and technical documentation:** [MIT](LICENSE).
- **Original educational content**, including guidance, prompts, statement templates, and original illustrations: [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE-CONTENT). See the [licence summary](https://creativecommons.org/licenses/by/4.0/).
- **Third-party code and sources:** retain their own terms. The bundled Word export library and dependency notices are documented in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Institutional names, trademarks, and third-party material are outside the original-content grant.

These grants apply to the corresponding parts of the project, including where code and content appear together in `index.html`. The MIT grant does not replace the CC BY 4.0 terms for educational content. User answers and generated documents are not licensed by this repository notice.

Suggested attribution for educational content:

> AI Disclosure Builder by Alec Couros, https://couros.ca/aidisclosure/, licensed under CC BY 4.0, https://creativecommons.org/licenses/by/4.0/. Indicate any changes you make.

Keep the MIT copyright and permission notice when sharing code. For educational content, credit the creator, link to the licence, and indicate changes, without suggesting endorsement.

## Version provenance

`index.html` was downloaded from the live site on 12 October 2026 and verified against the latest staged deployment. Its visible update date is 23 September 2026. The application file is unchanged from that live copy.

SHA-256: `f271956989261948da6ec0142ac769736f544ef348fa905d3825ed631e165e66`

The bundled docx 9.6.1 code was matched against its official npm distribution. Licence texts and dependency notices were added for this GitHub publication.
