<!-- # Description
please provide the details for the deployment variables below::


<!-- ## Environment Tags
| Environment | Variable | Value |
|-------------|----------|-------|
| DEV         | VAR_1    | ${{ env.DEV_VAR_1 }} |
| STAGE       | VAR_2    | ${{ env.STG_VAR_2 }} |
| PROD        | VAR_3    | ${{ env.PROD_VAR_3 }} | 




<!-- # Deployment Configuration

## Instructions:
#- Please enter the image tag values for the environments and regions below.
#- If a value is not provided, the default from the repository variables will be used.

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
#```markdown
#DEV - US: image-tag-dev-us
#STG - EU: image-tag-stg-eu
#PROD - AP: image-tag-prod-ap --> -->


## Description

#Please fill in the below details to trigger a deployment.

## Deploy to below environment

#- [ ] PR1
#- [ ] PR2
#- [ ] PR3
#- [ ] PR4
#- [ ] PR5
#- [ ] Dev

## Deploy to below Regions

#- [ ] US
#- [ ] EU
#- [ ] AP


## Deploy the below subgraphs

#- [ ] RecommendationGraph
#- [ ] SearchGraph
#- [ ] Other subgraph etc


## Tags to deploy for each subgraph. Latest tag will be considered for each subgraph as default.
-->
#Recommendation Graph : tag = latest TAG
## Deployment Configuration

### Select Environments for Deployment
- [ ] DEV
- [ ] STAGING
- [ ] PREPROD
- [ ] PROD

### Image Tags per Region

#### DEV Environment
- US: `<enter image tag here>`  
- EU: `<enter image tag here>`  
- AP: `<enter image tag here>`  

#### STAGING Environment
- US: `<enter image tag here>`  
- EU: `<enter image tag here>`  
- AP: `<enter image tag here>`  

#### PREPROD Environment
- US: `<enter image tag here>`  
- EU: `<enter image tag here>`  
- AP: `<enter image tag here>`  

#### PROD Environment
- US: `<enter image tag here>`  
- EU: `<enter image tag here>`  
- AP: `<enter image tag here>`  

---


















Other subgraphs etc: tag = latest TAG
