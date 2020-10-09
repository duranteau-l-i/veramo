## API Report File for "daf-rest"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { IAgentPlugin } from 'daf-core';
import { IAgentPluginSchema } from 'daf-core';
import { IPluginMethodMap } from 'daf-core';
import { OpenAPIV3 } from 'openapi-types';

// @public (undocumented)
export class AgentRestClient implements IAgentPlugin {
    constructor(options: {
        url: string;
        enabledMethods: string[];
        headers?: Record<string, string>;
        extraMethods?: Array<string>;
    });
    // (undocumented)
    readonly methods: IPluginMethodMap;
    // (undocumented)
    readonly schema: IAgentPluginSchema;
    }

// @public (undocumented)
export const openApiSchema: OpenAPIV3.Document;

// @public (undocumented)
export const supportedMethods: string[];


```