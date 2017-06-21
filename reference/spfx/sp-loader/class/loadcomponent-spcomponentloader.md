# loadComponent(manifest)
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Loads a component from a manifest.

**Signature:** _public static loadComponent < TComponent >(manifest: IClientSideComponentManifest): [Promise](../../web-apis/class/promise.md)<TComponent>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<TComponent>



A promise containing the loaded module.

#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `manifest`    | `IClientSideComponentManifest` | Manifest of the module to load. |

