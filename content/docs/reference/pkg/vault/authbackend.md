
---
title: "AuthBackend"
block_external_search_index: true
---



{{% examples %}}
## Example Usage
{{% example %}}

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as vault from "@pulumi/vault";

const example = new vault.AuthBackend("example", {
    tune: {
        listingVisibility: "unauth",
        maxLeaseTtl: "90000s",
    },
    type: "github",
});
```

{{% /example %}}
{{% /examples %}}



## Create a AuthBackend Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/#AuthBackend">AuthBackend</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/#AuthBackendArgs">AuthBackendArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">AuthBackend</span><span class="p">(resource_name, opts=None, </span>default_lease_ttl_seconds=None<span class="p">, </span>description=None<span class="p">, </span>listing_visibility=None<span class="p">, </span>local=None<span class="p">, </span>max_lease_ttl_seconds=None<span class="p">, </span>path=None<span class="p">, </span>tune=None<span class="p">, </span>type=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewAuthBackend<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/?tab=doc#AuthBackendArgs">AuthBackendArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/?tab=doc#AuthBackend">AuthBackend</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.AuthBackend.html">AuthBackend</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.AuthBackendArgs.html">AuthBackendArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Default<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Max<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Auth<wbr>Backend<wbr>Tune<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Default<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Max<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Auth<wbr>Backend<wbr>Tune</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>default<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>max<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Auth<wbr>Backend<wbr>Tune</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>default_<wbr>lease_<wbr>ttl_<wbr>seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>listing_<wbr>visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>max_<wbr>lease_<wbr>ttl_<wbr>seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Dict[Auth<wbr>Backend<wbr>Tune]</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## AuthBackend Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing AuthBackend Resource

Get an existing AuthBackend resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/#AuthBackendState">AuthBackendState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/#AuthBackend">AuthBackend</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>accessor=None<span class="p">, </span>default_lease_ttl_seconds=None<span class="p">, </span>description=None<span class="p">, </span>listing_visibility=None<span class="p">, </span>local=None<span class="p">, </span>max_lease_ttl_seconds=None<span class="p">, </span>path=None<span class="p">, </span>tune=None<span class="p">, </span>type=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetAuthBackend<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/?tab=doc#AuthBackendState">AuthBackendState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/?tab=doc#AuthBackend">AuthBackend</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.AuthBackend.html">AuthBackend</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault..AuthBackendState.html">AuthBackendState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Default<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Max<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Auth<wbr>Backend<wbr>Tune<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Default<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>Max<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Auth<wbr>Backend<wbr>Tune</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>default<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>max<wbr>Lease<wbr>Ttl<wbr>Seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Auth<wbr>Backend<wbr>Tune</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>accessor</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The accessor for this auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>default_<wbr>lease_<wbr>ttl_<wbr>seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.default_lease_ttl` if you are using Vault provider version >= 1.8) The default lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A description of the auth method
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>listing_<wbr>visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>local</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Specifies if the auth method is local only.
{{% /md %}}</dd>

    <dt class="property-optional property-deprecated"
            title="Optional, Deprecated">
        <span>max_<wbr>lease_<wbr>ttl_<wbr>seconds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}(Optional; Deprecated, use `tune.max_lease_ttl` if you are using Vault provider version >= 1.8) The maximum lease duration in seconds.
{{% /md %}}<p class="property-message">Deprecated: {{% md %}}Use the tune configuration block to avoid forcing creation of new resource on an update{{% /md %}}</p></dd>

    <dt class="property-optional"
            title="Optional">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The path to mount the auth method — this defaults to the name of the type
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tune</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#authbackendtune">Dict[Auth<wbr>Backend<wbr>Tune]</a></span>
    </dt>
    <dd>{{% md %}}Extra configuration block. Structure is documented below.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the auth method type
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Auth<wbr>Backend<wbr>Tune</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#AuthBackendTune">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#AuthBackendTune">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/?tab=doc#AuthBackendTuneArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/?tab=doc#AuthBackendTuneOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Allowed<wbr>Response<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and allowing
a plugin to include them in the response.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Audit<wbr>Non<wbr>Hmac<wbr>Request<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the request data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Audit<wbr>Non<wbr>Hmac<wbr>Response<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the response data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Default<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the default time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the maximum time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Passthrough<wbr>Request<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and
pass from the request to the backend.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Token<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the type of tokens that should be returned by
the mount. Valid values are "default-service", "default-batch", "service", "batch".
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Allowed<wbr>Response<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and allowing
a plugin to include them in the response.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Audit<wbr>Non<wbr>Hmac<wbr>Request<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the request data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Audit<wbr>Non<wbr>Hmac<wbr>Response<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the response data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Default<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the default time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the maximum time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Passthrough<wbr>Request<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and
pass from the request to the backend.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Token<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the type of tokens that should be returned by
the mount. Valid values are "default-service", "default-batch", "service", "batch".
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>allowed<wbr>Response<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and allowing
a plugin to include them in the response.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>audit<wbr>Non<wbr>Hmac<wbr>Request<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the request data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>audit<wbr>Non<wbr>Hmac<wbr>Response<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the response data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>default<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the default time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>listing<wbr>Visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the maximum time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>passthrough<wbr>Request<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and
pass from the request to the backend.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>token<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Specifies the type of tokens that should be returned by
the mount. Valid values are "default-service", "default-batch", "service", "batch".
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>allowed<wbr>Response<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and allowing
a plugin to include them in the response.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>audit<wbr>Non<wbr>Hmac<wbr>Request<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the request data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>audit<wbr>Non<wbr>Hmac<wbr>Response<wbr>Keys</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}Specifies the list of keys that will
not be HMAC'd by audit devices in the response data object.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>default<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies the default time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>listing_<wbr>visibility</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies whether to show this mount in
the UI-specific listing endpoint. Valid values are "unauth" or "hidden".
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Lease<wbr>Ttl</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies the maximum time-to-live.
If set, this overrides the global default.
Must be a valid [duration string](https://golang.org/pkg/time/#ParseDuration)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>passthrough<wbr>Request<wbr>Headers</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}List of headers to whitelist and
pass from the request to the backend.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>token_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Specifies the type of tokens that should be returned by
the mount. Valid values are "default-service", "default-batch", "service", "batch".
{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-vault">https://github.com/pulumi/pulumi-vault</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    <dt>Notes</dt>
	<dd>This Pulumi package is based on the [`vault` Terraform Provider](https://github.com/terraform-providers/terraform-provider-vault).</dd>
</dl>
