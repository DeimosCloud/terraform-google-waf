# Terraform WAF GCP
A terraform module to setup WAF/CloudArmor on GCP


## Usage

```hcl

# Cloud Armor and WAF Rules
module "cloud-armor" {
  source = "git@gitlab.com:deimosdev/tooling/terraform-modules/gcp/terraform-gcp-waf.git"
}
```

## Contributing

Report issues/questions/feature requests on in the issues section.

Full contributing guidelines are covered [here](CONTRIBUTING.md).

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| google | n/a |

## Inputs

No input.

## Outputs

No output.

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
