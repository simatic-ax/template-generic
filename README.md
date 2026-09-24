# Template for SIMATIC AX Generic Projects

## Description

This repository provides a generic APAX template for the SIMATIC AX GitHub Community. Use it when your contribution does not fit one of the more specific template types and you need a minimal starting point with the required project metadata and documentation placeholders.

## Repository Type

This repository is an APAX template package of type `generic`.

The root repository contains the template definition. The content in `template/` is what users receive when they create a project from this template.

## Create a Project from This Template

Create a new project with APAX:

```bash
apax create @simatic-ax/generic --registry https://npm.pkg.github.com
```

If authentication for the GitHub package registry is not configured yet, log in first and then rerun the command.

## What the Template Contains

The generated project is intentionally small and contains the basic files contributors are expected to adapt:

```text
template/
  apax.yml
  CODEOWNERS
  LICENSE.md
  README.md
  renovate.json
  docs/
```

Purpose of the included files:

- `apax.yml`: package metadata such as name, description, repository URL, registry configuration, and shipped files.
- `README.md`: onboarding document for users of the generated project.
- `docs/template.md`: placeholder for additional project-specific documentation.
- `CODEOWNERS`: ownership information for reviews and maintenance.
- `renovate.json`: dependency update configuration.
- `LICENSE.md`: legal terms for the repository content.

## Expected Customization After Creation

After creating a project from this template, update at least the following:

- package name, description, and repository URL in `apax.yml`
- project description and usage instructions in `README.md`
- additional documentation in `docs/`
- ownership information in `CODEOWNERS`

Remove placeholder text before publishing or requesting review.

## Maintainer Review Checklist

Before releasing a project based on this template, verify the following:

- [ ] OSS clearing completed
- [ ] Patent clearing completed
- [ ] ECC classification completed
- [ ] `LICENSE.md` is unchanged and up to date
- [ ] `CODEOWNERS` reflects the responsible maintainers
- [ ] `README.md` explains purpose, setup, and usage
- [ ] placeholder values in `apax.yml` and documentation were replaced
- [ ] the repository was reviewed through a pull request

## Learn More

See the [SIMATIC AX documentation on custom templates](https://console.simatic-ax.siemens.io/docs/apax/templates).


## Contribution

Thanks for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section or, even better, is free to propose any changes to this repository using a pull request.

## License and Legal information

Please read the [Legal information](LICENSE.md)