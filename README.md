# Jiahui Zeng's personal website

Academic homepage of **Jiahui Zeng (曾家辉)**, a Ph.D. student at the University of Liverpool researching robotics foundation models and dexterous manipulation for industrial tasks.

Website: [garrithm.github.io](https://garrithm.github.io/)

## Update the website

Edit `index.html` and preview locally first. Publish to `main` only after the changes are approved. The page uses responsive CSS, Jiahui Zeng's portrait in `assets/jiahui-zeng-portrait.png`, and local organization logos in `assets/logos/`. Keep the `assets/` directory alongside `index.html` when copying or publishing the site. There is no build step and no external asset dependency.

- Introduction: `.hero-copy`
- Research: `#research`; ongoing project summaries: `#ongoing-research` (industrial connector insertion, and compressor rotor insertion with shaft diameter measurement). Each research entry displays a title and an expanded introduction, with proposed work described as planned; update both language dictionaries when editing.
- Project experience: `#project-experience`; four bilingual entries cover dual-arm quadruped EOD teleoperation, robotic screwdriving, sheet picking and palletizing, and highway quadruped teleoperation. Each entry shows only its title and an expanded introduction. Named equipment and algorithms are integrated into the introduction; no separate technology tags or technical breakdowns are displayed.
- Education: `#education`; one compact entry per row, with dates alongside school and degree information on larger screens.
- Internships: `#internships`
- Contact: `#contact`
- Appearance: the `<style>` block and CSS custom properties in `:root`
- Languages: the EN / 中文 buttons switch all page content between English and Simplified Chinese. Translations are stored in the inline `messages` object. The selection is remembered locally; `?lang=en` and `?lang=zh` open a specific language.

Education and internship dates, degree subjects, roles, and locations are included. Doctoral studies are shown as Sep 2025–Present. Experience cards show roles, work arrangements, dates and locations without skill tags. The Contact section includes psjzeng8@liverpool.ac.uk and garryz.sep@gmail.com. Lab details and publications can be added when available.

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, and folder **/ (root)**. Future commits to `main` automatically update the website.
