# Description
please provide the details for the deployment variables below:


<!-- ## Environment Tags
| Environment | Variable | Value |
|-------------|----------|-------|
| DEV         | VAR_1    | ${{ env.DEV_VAR_1 }} |
| STAGE       | VAR_2    | ${{ env.STG_VAR_2 }} |
| PROD        | VAR_3    | ${{ env.PROD_VAR_3 }} | -->




# Pull Request Template

## **Description**
Provide a brief summary of the changes introduced in this PR.

---

## **Related Issue**
Link to the related issue (if any):  
`[Issue Number/Link]`

---

## **Deployment Configuration**
Please provide the image tags for deployment in the respective environments and regions.  

**Fill in the table below** with the image tag values for each combination of environment and region.  
Leave a field blank if deployment is not required for a specific region.

| Environment  | US Region Image Tag | EU Region Image Tag | AP Region Image Tag |
|--------------|----------------------|----------------------|----------------------|
| **Dev**      | `[Input Tag]`        | `[Input Tag]`        | `[Input Tag]`        |
| **Staging**  | `[Input Tag]`        | `[Input Tag]`        | `[Input Tag]`        |
| **Preprod**  | `[Input Tag]`        | `[Input Tag]`        | `[Input Tag]`        |
| **Prod**     | `[Input Tag]`        | `[Input Tag]`        | `[Input Tag]`        |

---

## **Steps to Test**
1. Provide detailed steps to test the changes in this PR.
2. Include any specific setup instructions or test cases.

---

## **Checklist**
- [ ] Verified the image tags for each environment and region.
- [ ] Code changes follow the project's style guide.
- [ ] Relevant tests have been added or updated.
- [ ] Documentation has been updated where necessary.
- [ ] The PR has been reviewed and approved by peers.

---

## **Notes**
1. The provided image tags will be used for deployment. Ensure all values are accurate and correspond to the required version.
2. Any incorrect input may affect deployments in specific environments/regions.

---

### **Instructions for Users**
1. Replace `[Input Tag]` with the appropriate image tag for each environment and region combination.
2. Leave fields blank if deployment is not needed in certain regions.


