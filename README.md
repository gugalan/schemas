# GU Schemas

This directory contains JSON Schema definitions generated from TypeScript interfaces defined in the GU backend codebase. These schemas are used for validating data structures and ensuring type safety across different parts of the application.

## Generating Schemas

To generate the JSON Schemas, run the following script from the `backend` directory:

```bashts
ts-node _scripts/gen-schemas.ts
```

This script will read the TypeScript interfaces and output the corresponding JSON Schema files into this directory.