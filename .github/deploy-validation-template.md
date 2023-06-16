---
title: Deployment validation required on {{ env.TERRAFORM_ENV }} for layer {{ env.TERRAFORM_LAYER }}
assignees: DidelotK
labels: release
---
Please approve or deny the deployment on {{ env.TERRAFORM_ENV }} for layer {{ env.TERRAFORM_LAYER }}

Plan was made in workflow ({{ env.WORKFLOW }}) on run ({{ env.WORFLOW_RUN_ID }} | {{ env.WORKFLOW_RUN_NUMBER }})

Tfplan result :
```
{{ env.TF_PLAN }}
```

Respond "yes" to continue workflow or "no" to cancel.

Date : {{ date | date('dddd, MMMM Do') }}
