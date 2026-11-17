# GRPS School Needs & Title I Planning

Guides a school through its Comprehensive Needs Assessment (CNA) and into a Title I Targeted Assistance or Schoolwide plan, connected to MICIP.

**Live site:** https://melatkins2-ops.github.io/grps-cna/

## What's here

- `index.html`: the whole planning tool (Start → Connect needs to Title I → Build the plan → Review and export, plus a compliance crosswalk and a completed CNA example)
- `QA_REPORT.txt`: earlier QA notes

## Good to know

- Work in progress is saved in the browser on the device being used (local storage). It does not sync between devices or people; export to keep a copy.

## Updating the site

Edit the files on a branch and open a pull request. GitHub Pages publishes `main` automatically, usually within a minute or two of a merge.

## Automated site check

Every pull request and every push to `main` runs **Site check** (`.github/workflows/site-check.yml`). It opens the site in a headless browser at desktop (1366px) and phone (390px) widths and fails if the page throws a JavaScript error, a local file or image is missing, or the page scrolls sideways. See the Actions tab for results.

Maintained by GRPS Community & Student Affairs.
