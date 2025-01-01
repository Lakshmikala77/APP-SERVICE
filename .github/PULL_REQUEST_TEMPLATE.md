# Description
please provide the details for the deployment variables below::


<!-- ## Environment Tags
| Environment | Variable | Value |
|-------------|----------|-------|
| DEV         | VAR_1    | ${{ env.DEV_VAR_1 }} |
| STAGE       | VAR_2    | ${{ env.STG_VAR_2 }} |
| PROD        | VAR_3    | ${{ env.PROD_VAR_3 }} | -->




# Deployment Configuration

## Instructions:
- Please enter the image tag values for the environments and regions below.
- If a value is not provided, the default from the repository variables will be used.

### Environment Tags
| Environment | Region | Image Tag Value |
|-------------|--------|-----------------|
| DEV         | US     | `<Enter value>` |
| DEV         | EU     | `<Enter value>` |
| DEV         | AP     | `<Enter value>` |
| STG         | US     | `<Enter value>` |
| STG         | EU     | `<Enter value>` |
| STG         | AP     | `<Enter value>` |
| PREPROD     | US     | `<Enter value>` |
| PREPROD     | EU     | `<Enter value>` |
| PREPROD     | AP     | `<Enter value>` |
| PROD        | US     | `<Enter value>` |
| PROD        | EU     | `<Enter value>` |
| PROD        | AP     | `<Enter value>` |

## Example
```markdown
DEV - US: image-tag-dev-us
STG - EU: image-tag-stg-eu
PROD - AP: image-tag-prod-ap


