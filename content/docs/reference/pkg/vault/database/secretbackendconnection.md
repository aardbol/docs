
---
title: "SecretBackendConnection"
block_external_search_index: true
---






## Create a SecretBackendConnection Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/database/#SecretBackendConnection">SecretBackendConnection</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/database/#SecretBackendConnectionArgs">SecretBackendConnectionArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">SecretBackendConnection</span><span class="p">(resource_name, opts=None, </span>allowed_roles=None<span class="p">, </span>backend=None<span class="p">, </span>cassandra=None<span class="p">, </span>data=None<span class="p">, </span>elasticsearch=None<span class="p">, </span>hana=None<span class="p">, </span>mongodb=None<span class="p">, </span>mssql=None<span class="p">, </span>mysql=None<span class="p">, </span>mysql_aurora=None<span class="p">, </span>mysql_legacy=None<span class="p">, </span>mysql_rds=None<span class="p">, </span>name=None<span class="p">, </span>oracle=None<span class="p">, </span>postgresql=None<span class="p">, </span>root_rotation_statements=None<span class="p">, </span>verify_connection=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewSecretBackendConnection<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionArgs">SecretBackendConnectionArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnection">SecretBackendConnection</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.Database.SecretBackendConnection.html">SecretBackendConnection</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.Database.SecretBackendConnectionArgs.html">SecretBackendConnectionArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allowed<wbr>Roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Secret<wbr>Backend<wbr>Connection<wbr>Cassandra<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary&lt;string, object&gt;</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Secret<wbr>Backend<wbr>Connection<wbr>Hana<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Secret<wbr>Backend<wbr>Connection<wbr>Mongodb<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Secret<wbr>Backend<wbr>Connection<wbr>Mssql<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Secret<wbr>Backend<wbr>Connection<wbr>Oracle<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Secret<wbr>Backend<wbr>Connection<wbr>Postgresql<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Root<wbr>Rotation<wbr>Statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Verify<wbr>Connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allowed<wbr>Roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Secret<wbr>Backend<wbr>Connection<wbr>Cassandra</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Secret<wbr>Backend<wbr>Connection<wbr>Hana</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Secret<wbr>Backend<wbr>Connection<wbr>Mongodb</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Secret<wbr>Backend<wbr>Connection<wbr>Mssql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Secret<wbr>Backend<wbr>Connection<wbr>Mysql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Secret<wbr>Backend<wbr>Connection<wbr>Oracle</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Secret<wbr>Backend<wbr>Connection<wbr>Postgresql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Root<wbr>Rotation<wbr>Statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Verify<wbr>Connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allowed<wbr>Roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Secret<wbr>Backend<wbr>Connection<wbr>Cassandra</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Secret<wbr>Backend<wbr>Connection<wbr>Hana</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Secret<wbr>Backend<wbr>Connection<wbr>Mongodb</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Secret<wbr>Backend<wbr>Connection<wbr>Mssql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Secret<wbr>Backend<wbr>Connection<wbr>Mysql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql<wbr>Aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql<wbr>Legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql<wbr>Rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Secret<wbr>Backend<wbr>Connection<wbr>Oracle</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Secret<wbr>Backend<wbr>Connection<wbr>Postgresql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>root<wbr>Rotation<wbr>Statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>verify<wbr>Connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allowed_<wbr>roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Cassandra]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Hana]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mongodb]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mssql]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql_<wbr>aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql_<wbr>legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql_<wbr>rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Oracle]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Postgresql]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>root_<wbr>rotation_<wbr>statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>verify_<wbr>connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Look up an Existing SecretBackendConnection Resource

Get an existing SecretBackendConnection resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/database/#SecretBackendConnectionState">SecretBackendConnectionState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vault/database/#SecretBackendConnection">SecretBackendConnection</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>allowed_roles=None<span class="p">, </span>backend=None<span class="p">, </span>cassandra=None<span class="p">, </span>data=None<span class="p">, </span>elasticsearch=None<span class="p">, </span>hana=None<span class="p">, </span>mongodb=None<span class="p">, </span>mssql=None<span class="p">, </span>mysql=None<span class="p">, </span>mysql_aurora=None<span class="p">, </span>mysql_legacy=None<span class="p">, </span>mysql_rds=None<span class="p">, </span>name=None<span class="p">, </span>oracle=None<span class="p">, </span>postgresql=None<span class="p">, </span>root_rotation_statements=None<span class="p">, </span>verify_connection=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetSecretBackendConnection<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionState">SecretBackendConnectionState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnection">SecretBackendConnection</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.Database.SecretBackendConnection.html">SecretBackendConnection</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vault/Pulumi.Vault.Database.SecretBackendConnectionState.html">SecretBackendConnectionState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Allowed<wbr>Roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Secret<wbr>Backend<wbr>Connection<wbr>Cassandra<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary&lt;string, object&gt;</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Secret<wbr>Backend<wbr>Connection<wbr>Hana<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Secret<wbr>Backend<wbr>Connection<wbr>Mongodb<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Secret<wbr>Backend<wbr>Connection<wbr>Mssql<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Secret<wbr>Backend<wbr>Connection<wbr>Oracle<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Secret<wbr>Backend<wbr>Connection<wbr>Postgresql<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Root<wbr>Rotation<wbr>Statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Verify<wbr>Connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Allowed<wbr>Roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Secret<wbr>Backend<wbr>Connection<wbr>Cassandra</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Data</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Secret<wbr>Backend<wbr>Connection<wbr>Hana</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Secret<wbr>Backend<wbr>Connection<wbr>Mongodb</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Secret<wbr>Backend<wbr>Connection<wbr>Mssql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Secret<wbr>Backend<wbr>Connection<wbr>Mysql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mysql<wbr>Rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Secret<wbr>Backend<wbr>Connection<wbr>Oracle</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Secret<wbr>Backend<wbr>Connection<wbr>Postgresql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Root<wbr>Rotation<wbr>Statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Verify<wbr>Connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>allowed<wbr>Roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Secret<wbr>Backend<wbr>Connection<wbr>Cassandra</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Secret<wbr>Backend<wbr>Connection<wbr>Hana</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Secret<wbr>Backend<wbr>Connection<wbr>Mongodb</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Secret<wbr>Backend<wbr>Connection<wbr>Mssql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Secret<wbr>Backend<wbr>Connection<wbr>Mysql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql<wbr>Aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql<wbr>Legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql<wbr>Rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Secret<wbr>Backend<wbr>Connection<wbr>Oracle</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Secret<wbr>Backend<wbr>Connection<wbr>Postgresql</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>root<wbr>Rotation<wbr>Statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>verify<wbr>Connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>allowed_<wbr>roles</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}A list of roles that are allowed to use this
connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>backend</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The unique name of the Vault mount to configure.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cassandra</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectioncassandra">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Cassandra]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Cassandra connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>data</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}A map of sensitive data to pass to the endpoint. Useful for templated connection strings.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>elasticsearch</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionelasticsearch">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Elasticsearch connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hana</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionhana">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Hana]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for SAP HanaDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mongodb</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmongodb">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mongodb]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MongoDB connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mssql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmssql">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mssql]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MSSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysql">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql_<wbr>aurora</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlaurora">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Aurora MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql_<wbr>legacy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqllegacy">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for legacy MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mysql_<wbr>rds</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionmysqlrds">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for RDS MySQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A unique name to give the database connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>oracle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionoracle">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Oracle]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for Oracle connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>postgresql</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#secretbackendconnectionpostgresql">Dict[Secret<wbr>Backend<wbr>Connection<wbr>Postgresql]</a></span>
    </dt>
    <dd>{{% md %}}A nested block containing configuration options for PostgreSQL connections.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>root_<wbr>rotation_<wbr>statements</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}A list of database statements to be executed to rotate the root user's credentials.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>verify_<wbr>connection</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether the connection should be verified on
initial configuration or not.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Secret<wbr>Backend<wbr>Connection<wbr>Cassandra</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionCassandra">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionCassandra">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionCassandraArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionCassandraOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connect<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The number of seconds to use as a connection
timeout.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hosts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The hosts to connect to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Insecure<wbr>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether to skip verification of the server
certificate when using TLS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pem<wbr>Bundle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Concatenated PEM blocks configuring the certificate
chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pem<wbr>Json</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A JSON structure configuring the certificate chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The default port to connect to if no port is specified as
part of the host.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Protocol<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The CQL protocol version to use.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether to use TLS when connecting to Cassandra.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connect<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The number of seconds to use as a connection
timeout.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Hosts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The hosts to connect to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Insecure<wbr>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether to skip verification of the server
certificate when using TLS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pem<wbr>Bundle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Concatenated PEM blocks configuring the certificate
chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pem<wbr>Json</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A JSON structure configuring the certificate chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The default port to connect to if no port is specified as
part of the host.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Protocol<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The CQL protocol version to use.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether to use TLS when connecting to Cassandra.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connect<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The number of seconds to use as a connection
timeout.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hosts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The hosts to connect to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>insecure<wbr>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Whether to skip verification of the server
certificate when using TLS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pem<wbr>Bundle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Concatenated PEM blocks configuring the certificate
chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pem<wbr>Json</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A JSON structure configuring the certificate chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>port</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The default port to connect to if no port is specified as
part of the host.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>protocol<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The CQL protocol version to use.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Whether to use TLS when connecting to Cassandra.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connect<wbr>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The number of seconds to use as a connection
timeout.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>hosts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The hosts to connect to.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>insecure_<wbr>tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether to skip verification of the server
certificate when using TLS.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pem_<wbr>bundle</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Concatenated PEM blocks configuring the certificate
chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pem<wbr>Json</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A JSON structure configuring the certificate chain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>port</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The default port to connect to if no port is specified as
part of the host.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>protocol<wbr>Version</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The CQL protocol version to use.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tls</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Whether to use TLS when connecting to Cassandra.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Elasticsearch</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionElasticsearch">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionElasticsearch">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionElasticsearchArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionElasticsearchOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The URL for Elasticsearch's API. https requires certificate
by trusted CA if used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The URL for Elasticsearch's API. https requires certificate
by trusted CA if used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The URL for Elasticsearch's API. https requires certificate
by trusted CA if used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The password to be used in the connection.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The URL for Elasticsearch's API. https requires certificate
by trusted CA if used.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>username</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The username to be used in the connection.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Hana</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionHana">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionHana">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionHanaArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionHanaOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Mongodb</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionMongodb">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionMongodb">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMongodbArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMongodbOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Mssql</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionMssql">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionMssql">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMssqlArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMssqlOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Mysql</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionMysql">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionMysql">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Aurora</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionMysqlAurora">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionMysqlAurora">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlAuroraArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlAuroraOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Legacy</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionMysqlLegacy">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionMysqlLegacy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlLegacyArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlLegacyOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Mysql<wbr>Rds</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionMysqlRds">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionMysqlRds">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlRdsArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionMysqlRdsOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Oracle</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionOracle">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionOracle">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionOracleArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionOracleOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Secret<wbr>Backend<wbr>Connection<wbr>Postgresql</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/input/#SecretBackendConnectionPostgresql">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/vault/types/output/#SecretBackendConnectionPostgresql">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionPostgresqlArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-vault/sdk/v2/go/vault/database?tab=doc#SecretBackendConnectionPostgresqlOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>connection<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}A URL containing connection information. See
the [Vault
docs](https://www.vaultproject.io/api/secret/databases/oracle.html#sample-payload)
for an example.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Connection<wbr>Lifetime</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of seconds to keep
a connection alive for.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Idle<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of idle connections to
maintain.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>max<wbr>Open<wbr>Connections</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum number of open connections to
use.
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
