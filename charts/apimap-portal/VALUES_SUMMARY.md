# Apimap.io : Portal

## Configuration

The following tables list the configurable parameters of the Apimap.io Portal chart and their default values.

### URLs

| Parameter                         | Description                          | Default                                   | Required |
| --------------------------------- | ------------------------------------ | ----------------------------------------- | -------- |
| urls.api                          | URL to the API services              | Empty | Required |
| urls.developer                    | URL to the Developer Portal          | Empty | Required |

### Branding

| Parameter                         | Description                          | Default                                   | Required |
| --------------------------------- | ------------------------------------ | ----------------------------------------- | -------- |
| branding.title                    | Page title shown to the users on the first page | "Apimap.io" | Required |
| branding.support                  | A short descriptive text giving the users a link to where they can get support from the organization implementing Apimap. | "Visit https://github.com/apimap to ask questions and contribute to the project"  | Required |

### Exposure

| Parameter                         | Description                          | Default                                   | Required |
| --------------------------------- | ------------------------------------ | ----------------------------------------- | -------- |
| exposure.nodeport.enabled         | Enable the use of nodeport           | false                                     | Required |
| exposure.ingress.enabled          | Enable the use of ingress            | false                                     | Required |
| exposure.ingress.host             | Hostname / domain name that the service should respond to | ""                   | Required | 

### Content

| Parameter             | Description                                                     | Default                                   | Required  |
|-----------------------|-----------------------------------------------------------------| ----------------------------------------- |-----------|
| content.options       | Name of configmap that contanis the metadata and search options | | Required  |
