# RYZE Digital Reusable GitHub Workflows

## Usage

Add the following to your workflow YAML and replace `NAME-OF-WORKFLOW` with the actual name of the workflow to be used.

```yml
jobs:
  NAME-OF-WORKFLOW:
    uses: ryze-digital/reusable-workflows/.github/workflows/NAME-OF-WORKFLOW.yml@main
```

See [/.github/workflows](.github/workflows) for all available workflows.
Checkout [calling a reusable workflow](https://docs.github.com/en/actions/using-workflows/reusing-workflows#calling-a-reusable-workflow) to find out more about reusable workflows in general.
