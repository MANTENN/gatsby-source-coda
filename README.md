# gatsby-source-coda
Source plugin for pulling data (including images) into Gatsby from Coda.io

## Getting started

Include the plugin in gatsby-config.js
```javascript
    {
      resolve: `gatsby-source-coda`,
      options: {
        apiToken: '',
        docId: '',
        tableIdOrName: '',
        useColumnNames: '',
      },
    },
```

All of the options are required for the plugin to work. 
