# Overview

```
Module Name: Welect Bidder Adapter
Module Type: Welect Adapter
Maintainer: dev@welect.de
```

# Description

## Parameters

- `placementId` (required): The unique identifier for the placement.
- `cattax` (optional): Specifies the category taxonomy identifier. Example: `'iab2'`.
- `cat` (optional): An array of category IDs. Example: `['1', '321', 'v9i3On']`.

Module that connects to Welect's demand sources

# Test Parameters
```
var adUnits = [
  {
    bidder: 'welect',
    params: {
      placementId: 'exampleId',
      cattax: 'iab2', // Optional: Category taxonomy identifier
      cat: ['1', '321', 'v9i3On'] // Optional: Array of category IDs
    },
    sizes: [[640, 360]],
    mediaTypes: {
      video: {
        context: 'instream',
        playerSize: [640, 480]
      }
    },
  };
];
```