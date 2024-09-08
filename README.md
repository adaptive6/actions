# Adaptive6 Actions

Prevent waste in pull requests (PRs) by identifying unnecessary changes and ensuring efficient code reviews. Help developers avoid wasteful changes in PRs by analyzing modified files, executing a scan, and annotating results in the PR.

### Inputs

- `a6p-api-token`: Token for Adaptive6 API (required)
- `github-token`: GitHub token (required)

### Usage

To use this action in your workflow, add the following step:

```yaml
- name: Adaptive6 Prevent Waste
  uses: adaptive6/actions/preventive@main
  with:
    a6p-api-token: ${{ secrets.A6P_API_TOKEN }}
    github-token: ${{ secrets.GITHUB_TOKEN }}
```