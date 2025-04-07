# Epiverse team member offboarding checklist

## On packages or repos that you maintain

- Do you want to stay maintainer on packages you may currently be maintaining?

  *Being the maintainer on an R package hosted on CRAN requires at least to be able to quickly respond to CRAN requests (usual timeline of ~2 weeks), or risk package archival.
  Ideally, maintainers should also help with review of PRs from other authors or external contributors and address bug reports in a timely manner.*

  *Link to see packages maintained on CRAN by a given email address: <https://cran.r-project.org/web/checks/check_results_hugo_at_data.org.html>

  - [ ] If you want to stay maintainer, ensure the email address used to in the dedicated field in `DESCRIPTION` will still be valid after your departure (check institution policy regarding alumni email address).
        Make a CRAN release using the new email address before leaving. You will need to send a confirmation email from your old email address.
  - [ ] If you want to hand over maintainership, coordinate with a new maintainer and add them to `DESCRIPTION`.
        Make a CRAN release with the new maintainer before leaving. You will need to send a confirmation email from your old email address.

- Review and triage (close, complete or hand over):

  *No work should be left in an unclear pending state. Everything should be
  reviewed and either resolved, closed, or handed over.*

  - [ ] issues (e.g., https://github.com/epiverse-trace/linelist/issues)
  - [ ] pull requests (e.g., https://github.com/epiverse-trace/linelist/pulls)
  - [ ] branches (e.g., https://github.com/epiverse-trace/linelist/branches)
  - [ ] TODO comments in the codebase (https://github.com/search?q=org%3Aepiverse-trace+%2F%23+todo%2F&type=code)

- [ ] A design vignette ([template](https://github.com/epiverse-trace/packagetemplate/blob/main/vignettes/design-principles.Rmd)) is present, describing for posterity some issues you discovered the hard way or design decisions you took after long considerations.
  This will prevent future maintainers from making the same mistake as you did.

## Across all repos in the organization

- [ ] Ensure all local changes are pushed to GitHub
- [ ] Review all existing branches you own and triage them
- [ ] Review issues assigned to you across the organization (e.g., https://github.com/search?q=org%3Aepiverse-trace+assignee%3ABisaloo&type=issues)
- [ ] Submit all records you own on Zenodo to the Epiverse-TRACE Zenodo organization (https://zenodo.org/account/settings/github/)
