# Snowflake Terraform Sample

Minimales Terraform-Projekt für Snowflake mit Service User Authentication.

## Setup

1. **Service User** `TERRAFORM_SVC` muss in Snowflake existieren
2. **RSA Key Pair** unter `~/.ssh/snowflake_tf_snow_key.p8`

## Verwendung

```bash
# Provider herunterladen
terraform init

# Verbindung testen
terraform plan

# Ressourcen anwenden
terraform apply
```

## Konfiguration

- **Organization**: sfseeurope
- **Account**: mgreil_aws1  
- **User**: TERRAFORM_SVC
- **Authentication**: RSA Key Pair (SNOWFLAKE_JWT)
