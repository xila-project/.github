# Xila README writing guide

Use `templates/README.md` as a starting point, not as a requirement to add every heading to every repository. Replace its placeholders and remove the instructional comments and unused sections before publishing a real README.

## Shared frame

Use one H1 containing the repository's light/dark SVG header. Give its image a descriptive alt text so the heading has an accessible name. Do not add a second visible title repeating the header. Follow it with the shared documentation/demo/community links and a short introduction. Keep **Xila** as the public name; `xila-project` is the GitHub organization handle used in URLs.

The graphic sources, repository titles, role summaries and generator belong to `xila-project/brand`. Import the generated SVGs into the consumer repository and record the exact source commit beside them. Both header variants have transparent backgrounds: black artwork for light themes and white artwork for dark themes. Do not bake a hosting platform's surface color into the artwork. Use a light fallback image and descriptive alt text. Rendering must not depend on installed fonts, scripts or image downloads during a consumer build.

Use the shared footer at the end, including the logo design credit to [Martin Legand](https://www.behance.net/martinlegand). Preserve that credit in deployed header asset notes; it credits the logo, not the generated layouts or the Montserrat font. Keep legal statements, license links and attribution repository-specific; the footer deliberately makes no project-wide licensing claim.

This is a source template to copy and adapt. Adding it here does not automatically rewrite consumer READMEs.

## Adapt the body to the reader

Every README should explain what the repository owns, why it is useful, how to take a first step, where to find help and how to contribute. Keep practical instructions ahead of long reference material when restructuring is useful. Preserve the meaning of the repository title in the header and its alt text, and keep useful anchors, badges and cross-repository links.

Do not rename a working section solely to match a placeholder. Existing headings such as `Start here`, `Build and check Core`, `Get the right file`, or `Publishing a version` can fulfil the template's purposes. A large README can retain its detailed technical sections and link to a longer guide for future expansion.

| Repository                | Reader's first step                                      | Body topics to preserve                                                    |
| ------------------------- | -------------------------------------------------------- | -------------------------------------------------------------------------- |
| Core                      | Find a tutorial or check the kernel workspace            | Subsystems, supported targets, build checks, localization and contribution |
| Platforms                 | Select a native, browser or hardware runtime             | Drivers, runtime assembly, seed images and target-specific validation      |
| Applications              | Find an application or build a guest                     | Native/guest boundaries, packaging, ABI and localization                   |
| Package manager           | Use the libraries or desktop CLI                         | Package formats, signing, verification, releases and compatibility         |
| Registry                  | Read or publish package metadata                         | Immutable versions, keys, signatures and publication validation            |
| Workspace                 | Initialize the needed repositories                       | Pinned gitlinks, dependency direction, CI orchestration and integration    |
| Website                   | Find the published docs or run the documentation tooling | Authoring, navigation, reference validation and deployment                 |
| Brand                     | Choose the appropriate artwork                           | Masters, generation, visual guidelines, fonts and provenance               |
| Wasm application template | Create and build a first application                     | Prerequisites, template customization, target and runtime compatibility    |
| Community                 | Discover the project and participation routes            | Organization profile and shared contributor-facing templates               |

## Accuracy and scope

- Verify commands against that repository's current tasks and scripts. Name their working directory and prerequisites when needed.
- Preserve constraints and security assumptions next to the actions they qualify. Never substitute a generic installation recipe for registry, signing or embedded-target instructions.
- Keep repository ownership boundaries explicit. Point to the owning repository rather than copying its maintained instructions.
- Include contribution and help routes appropriate to the repository. Keep maintainer and attribution information where the repository already records it.
- Link the actual local license when present. Do not invent a common license, claim production readiness or create badges for checks that do not exist.
- Keep optional headings only when they contain useful information. A logo repository does not need a software installation section; a metadata index does not need application screenshots.

## Basis

The template uses an original Xila presentation frame and follows the reader-focused principles from [GitHub's README guidance](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) and [Make a README](https://www.makeareadme.com/). These references provide guidance; this is not a verbatim copy of either template.

[Standard Readme](https://github.com/RichardLitt/standard-readme) is another useful reference, especially for libraries. Xila does not claim strict compliance with its required headings or ordering across every repository type.
