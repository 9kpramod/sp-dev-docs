# get(url,configuration,options)
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Calls fetch(), but sets the method to 'GET'.

**Signature:** _public get(url: string, configuration: [GraphHttpClientConfiguration](../../sp-http/class/graphhttpclientconfiguration.md),
    options?: [IGraphHttpClientOptions](../../sp-http/interface/igraphhttpclientoptions.md)): [Promise](../../web-apis/class/promise.md)<GraphHttpClientResponse>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<GraphHttpClientResponse>



a promise that will return the result

#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `url`    | `string` | the URL to fetch |
| `configuration`    | [`GraphHttpClientConfiguration`](../../sp-http/class/graphhttpclientconfiguration.md) | determines the default behavior of GraphHttpClient; normally this should be the latest version number from GraphHttpClientConfigurations |
| `options`    | [`IGraphHttpClientOptions`](../../sp-http/interface/igraphhttpclientoptions.md) | _Optional._ additional options that affect the request |

