# precommit_demo

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 5.5.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_subnet.subnets](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet) | resource |
| [aws_vpc.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_subnets_azs"></a> [subnets\_azs](#input\_subnets\_azs) | n/a | `list(string)` | n/a | yes |
| <a name="input_subnets_cidr_lists"></a> [subnets\_cidr\_lists](#input\_subnets\_cidr\_lists) | n/a | `list(string)` | n/a | yes |
| <a name="input_subnets_map_public_ip"></a> [subnets\_map\_public\_ip](#input\_subnets\_map\_public\_ip) | n/a | `list(bool)` | n/a | yes |
| <a name="input_subnets_names"></a> [subnets\_names](#input\_subnets\_names) | n/a | `list(string)` | n/a | yes |
| <a name="input_vpc_cidr_block"></a> [vpc\_cidr\_block](#input\_vpc\_cidr\_block) | n/a | `any` | n/a | yes |
| <a name="input_vpc_name"></a> [vpc\_name](#input\_vpc\_name) | n/a | `any` | n/a | yes |

## Outputs

No outputs.
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
