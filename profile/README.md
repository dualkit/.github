<p align="center">
  <a href="https://github.com/dualkit/dualkit"><img src="https://raw.githubusercontent.com/dualkit/dualkit/main/.github/assets/banner.jpg" alt="Dualkit. Build for the Gulf. In both directions. A desert at dusk." width="100%"></a>
</p>

Free, open-source tools for products that ship in Arabic and English.

- **[Skills](https://github.com/dualkit/dualkit/tree/main/plugin/skills)** teach Claude Code and Cursor to get Arabic right: RTL layout, type pairing, Gulf formats and bilingual copy. They are listed in the Claude plugin directory.
- **[Format](https://github.com/dualkit/dualkit/tree/main/packages/format)** handles all six Gulf currencies, Hijri dates, Arabic numerals, phone numbers and IBANs for all six GCC countries, the Emirates ID, the Saudi VAT number and Gulf weekends, with no dependencies.
- **[Starter](https://github.com/dualkit/dualkit/tree/main/packages/starter)** is a bilingual design system to fork, one token file for code and Figma.
- **[Check](https://github.com/dualkit/dualkit/tree/main/packages/cli)** audits any page for Arabic and right-to-left bugs and writes a shareable report: `npx dualkit check <url>`. A GitHub Action runs it on every pull request.
- **[Lint](https://github.com/dualkit/dualkit/tree/main/packages/lint)** reads your CSS, Tailwind classes and Intl calls and flags right-to-left bugs before anything renders, with no browser: `npx dualkit@beta lint .`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dualkit/dualkit/main/.github/assets/check-report-dark.png">
  <img src="https://raw.githubusercontent.com/dualkit/dualkit/main/.github/assets/check-report.png" alt="A Dualkit check report for an Arabic checkout, scored 0 out of 100 with 11 problems and evidence cards for each bug." width="100%">
</picture>

Start at **[dualkit/dualkit](https://github.com/dualkit/dualkit)** or [dualkit.dev](https://dualkit.dev).
