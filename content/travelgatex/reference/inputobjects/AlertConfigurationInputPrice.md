{
  "title": "AlertConfigurationInputPrice",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "Int!",
      "name": "periodicity",
      "url": "/travelgatex/reference/scalars/int",
      "description": "Frequency of time in minutes in which the alert will be reviewed",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "window",
      "url": "/travelgatex/reference/scalars/int",
      "description": "The time frame in minutes",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "timesToAlert",
      "url": "/travelgatex/reference/scalars/int",
      "description": "The number of times the alert must be triggered in order to notify",
      "args": null
    },
    {
      "typeString": "Int",
      "name": "timesToRecovery",
      "url": "/travelgatex/reference/scalars/int",
      "description": "The number of times the alert must be recovered in order to notify",
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "noRecoveries",
      "url": "/travelgatex/reference/scalars/boolean",
      "description": "To allow recoveries notifications",
      "args": null
    },
    {
      "typeString": "Boolean!",
      "name": "stateChangesOnly",
      "url": "/travelgatex/reference/scalars/boolean",
      "description": "To allow notifications only if the status change",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "minNumberRequests",
      "url": "/travelgatex/reference/scalars/int",
      "description": "defines the minimum number of requests must be in the window time frame to check the alert.",
      "args": null
    },
    {
      "typeString": "Int!",
      "name": "percentageToAlert",
      "url": "/travelgatex/reference/scalars/int",
      "description": "Defines the minimum percentage to consider alert in status ALERTING.",
      "args": null
    },
    {
      "typeString": "[EmailInput]!",
      "name": "email",
      "url": "/travelgatex/reference/inputobjects/emailinput",
      "description": "Email addresses to send notifications",
      "args": null
    },
    {
      "typeString": "[AlertObjectInput!]",
      "name": "supplier",
      "url": "/travelgatex/reference/inputobjects/alertobjectinput",
      "description": "Possibility to filter traffic by suppliers",
      "args": null
    },
    {
      "typeString": "[AlertObjectInput!]",
      "name": "client",
      "url": "/travelgatex/reference/inputobjects/alertobjectinput",
      "description": "Possibility to filter traffic by clients",
      "args": null
    },
    {
      "typeString": "[AlertGroupInput!]",
      "name": "group",
      "url": "/travelgatex/reference/inputobjects/alertgroupinput",
      "description": "Must filter traffic by group. Only PRODUCT group type is allowed",
      "args": null
    },
    {
      "typeString": "[AlertObjectInput!]",
      "name": "access",
      "url": "/travelgatex/reference/inputobjects/alertobjectinput",
      "description": "Possibility to filter traffic by accesses",
      "args": null
    },
    {
      "typeString": "[AlertObjectInput!]",
      "name": "operation",
      "url": "/travelgatex/reference/inputobjects/alertobjectinput",
      "description": "Possibility to filter traffic by operations",
      "args": null
    },
    {
      "typeString": "[AlertObjectInput!]",
      "name": "api",
      "url": "/travelgatex/reference/inputobjects/alertobjectinput",
      "description": "Possibility to filter traffic by apis",
      "args": null
    },
    {
      "typeString": "[AlertGroupsInsights!]",
      "name": "groupBy",
      "url": "/travelgatex/reference/enums/alertgroupsinsights",
      "description": "Possibility to group by traffic and calculate its parameters separately",
      "args": null
    },
    {
      "typeString": "AlertPriceInput!",
      "name": "price",
      "url": "/travelgatex/reference/inputobjects/alertpriceinput",
      "description": "Price values",
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "AlertInput",
      "description": "Alert information. Only one configuration has to be set at once.",
      "url": "/travelgatex/reference/inputobjects/alertinput"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "AlertConfigurationInputPrice",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}
