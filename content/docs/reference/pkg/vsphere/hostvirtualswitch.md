
---
title: "HostVirtualSwitch"
block_external_search_index: true
---






## Create a HostVirtualSwitch Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vsphere/#HostVirtualSwitch">HostVirtualSwitch</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vsphere/#HostVirtualSwitchArgs">HostVirtualSwitchArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">HostVirtualSwitch</span><span class="p">(resource_name, opts=None, </span>active_nics=None<span class="p">, </span>allow_forged_transmits=None<span class="p">, </span>allow_mac_changes=None<span class="p">, </span>allow_promiscuous=None<span class="p">, </span>beacon_interval=None<span class="p">, </span>check_beacon=None<span class="p">, </span>failback=None<span class="p">, </span>host_system_id=None<span class="p">, </span>link_discovery_operation=None<span class="p">, </span>link_discovery_protocol=None<span class="p">, </span>mtu=None<span class="p">, </span>name=None<span class="p">, </span>network_adapters=None<span class="p">, </span>notify_switches=None<span class="p">, </span>number_of_ports=None<span class="p">, </span>shaping_average_bandwidth=None<span class="p">, </span>shaping_burst_size=None<span class="p">, </span>shaping_enabled=None<span class="p">, </span>shaping_peak_bandwidth=None<span class="p">, </span>standby_nics=None<span class="p">, </span>teaming_policy=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewHostVirtualSwitch<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vsphere/sdk/v2/go/vsphere/?tab=doc#HostVirtualSwitchArgs">HostVirtualSwitchArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vsphere/sdk/v2/go/vsphere/?tab=doc#HostVirtualSwitch">HostVirtualSwitch</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vsphere/Pulumi.Vsphere.HostVirtualSwitch.html">HostVirtualSwitch</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vsphere/Pulumi.VSphere.HostVirtualSwitchArgs.html">HostVirtualSwitchArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Active<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>System<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Network<wbr>Adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Standby<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Forged<wbr>Transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Mac<wbr>Changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Beacon<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Check<wbr>Beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notify<wbr>Switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Number<wbr>Of<wbr>Ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Average<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Burst<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Peak<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Teaming<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Active<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host<wbr>System<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Network<wbr>Adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Standby<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Forged<wbr>Transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Mac<wbr>Changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Beacon<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Check<wbr>Beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notify<wbr>Switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Number<wbr>Of<wbr>Ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Average<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Burst<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Peak<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Teaming<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>active<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host<wbr>System<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>network<wbr>Adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>standby<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow<wbr>Forged<wbr>Transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow<wbr>Mac<wbr>Changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow<wbr>Promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>beacon<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>check<wbr>Beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link<wbr>Discovery<wbr>Operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link<wbr>Discovery<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notify<wbr>Switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>number<wbr>Of<wbr>Ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Average<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Burst<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Peak<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>teaming<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>active_<wbr>nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host_<wbr>system_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>network_<wbr>adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>standby_<wbr>nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow_<wbr>forged_<wbr>transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow_<wbr>mac_<wbr>changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow_<wbr>promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>beacon_<wbr>interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>check_<wbr>beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link_<wbr>discovery_<wbr>operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link_<wbr>discovery_<wbr>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notify_<wbr>switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>number_<wbr>of_<wbr>ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>average_<wbr>bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>burst_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>peak_<wbr>bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>teaming_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Look up an Existing HostVirtualSwitch Resource

Get an existing HostVirtualSwitch resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vsphere/#HostVirtualSwitchState">HostVirtualSwitchState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/vsphere/#HostVirtualSwitch">HostVirtualSwitch</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>active_nics=None<span class="p">, </span>allow_forged_transmits=None<span class="p">, </span>allow_mac_changes=None<span class="p">, </span>allow_promiscuous=None<span class="p">, </span>beacon_interval=None<span class="p">, </span>check_beacon=None<span class="p">, </span>failback=None<span class="p">, </span>host_system_id=None<span class="p">, </span>link_discovery_operation=None<span class="p">, </span>link_discovery_protocol=None<span class="p">, </span>mtu=None<span class="p">, </span>name=None<span class="p">, </span>network_adapters=None<span class="p">, </span>notify_switches=None<span class="p">, </span>number_of_ports=None<span class="p">, </span>shaping_average_bandwidth=None<span class="p">, </span>shaping_burst_size=None<span class="p">, </span>shaping_enabled=None<span class="p">, </span>shaping_peak_bandwidth=None<span class="p">, </span>standby_nics=None<span class="p">, </span>teaming_policy=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetHostVirtualSwitch<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vsphere/sdk/v2/go/vsphere/?tab=doc#HostVirtualSwitchState">HostVirtualSwitchState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-vsphere/sdk/v2/go/vsphere/?tab=doc#HostVirtualSwitch">HostVirtualSwitch</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vsphere/Pulumi.Vsphere.HostVirtualSwitch.html">HostVirtualSwitch</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Vsphere/Pulumi.Vsphere..HostVirtualSwitchState.html">HostVirtualSwitchState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Active<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Forged<wbr>Transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Mac<wbr>Changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Beacon<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Check<wbr>Beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Host<wbr>System<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notify<wbr>Switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Number<wbr>Of<wbr>Ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Average<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Burst<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">bool</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Peak<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">int</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Standby<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Teaming<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Active<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Forged<wbr>Transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Mac<wbr>Changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Allow<wbr>Promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Beacon<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Check<wbr>Beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Host<wbr>System<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Link<wbr>Discovery<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Network<wbr>Adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Notify<wbr>Switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Number<wbr>Of<wbr>Ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Average<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Burst<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#boolean">bool</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Shaping<wbr>Peak<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#integer">int</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Standby<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Teaming<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>active<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow<wbr>Forged<wbr>Transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow<wbr>Mac<wbr>Changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow<wbr>Promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>beacon<wbr>Interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>check<wbr>Beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>host<wbr>System<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link<wbr>Discovery<wbr>Operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link<wbr>Discovery<wbr>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network<wbr>Adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notify<wbr>Switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>number<wbr>Of<wbr>Ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Average<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Burst<wbr>Size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/boolean">boolean</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping<wbr>Peak<wbr>Bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/integer">number</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>standby<wbr>Nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>teaming<wbr>Policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>active_<wbr>nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The list of active network adapters used for load
balancing.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow_<wbr>forged_<wbr>transmits</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the virtual
network adapter is allowed to send network traffic with a different MAC
address than that of its own. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow_<wbr>mac_<wbr>changes</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Controls whether or not the Media Access
Control (MAC) address can be changed. Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>allow_<wbr>promiscuous</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable promiscuous mode on the network. This
flag indicates whether or not all traffic is seen on a given port. Default:
`false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>beacon_<wbr>interval</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The interval, in seconds, that a NIC beacon
packet is sent out. This can be used with `check_beacon` to
offer link failure capability beyond link status only. Default: `1`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>check_<wbr>beacon</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Enable beacon probing - this requires that the
`beacon_interval` option has been set in the bridge
options. If this is set to `false`, only link status is used to check for
failed NICs.  Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>failback</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will re-activate
failed interfaces higher in precedence when they come back up.  Default:
`true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>host_<wbr>system_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The [managed object ID][docs-about-morefs] of
the host to set the virtual switch up on. Forces a new resource if changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link_<wbr>discovery_<wbr>operation</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Whether to `advertise` or `listen`
for link discovery traffic. Default: `listen`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>link_<wbr>discovery_<wbr>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The discovery protocol type.  Valid
types are `cpd` and `lldp`. Default: `cdp`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mtu</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum transmission unit (MTU) for the virtual
switch. Default: `1500`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The name of the virtual switch. Forces a new resource if
changed.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>network_<wbr>adapters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The network interfaces to bind to the bridge.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>notify_<wbr>switches</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}If set to `true`, the teaming policy will
notify the broadcast network of a NIC failover, triggering cache updates.
Default: `true`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>number_<wbr>of_<wbr>ports</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The number of ports to create with this
virtual switch. Default: `128`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>average_<wbr>bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The average bandwidth in bits per
second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>burst_<wbr>size</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The maximum burst size allowed in bytes if
shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>enabled</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">bool</a></span>
    </dt>
    <dd>{{% md %}}Set to `true` to enable the traffic shaper for
ports managed by this virtual switch. Default: `false`.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>shaping_<wbr>peak_<wbr>bandwidth</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">float</a></span>
    </dt>
    <dd>{{% md %}}The peak bandwidth during bursts in
bits per second if traffic shaping is enabled. Default: `0`
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>standby_<wbr>nics</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">List[str]</a></span>
    </dt>
    <dd>{{% md %}}The list of standby network adapters used for
failover.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>teaming_<wbr>policy</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The network adapter teaming policy. Can be one
of `loadbalance_ip`, `loadbalance_srcmac`, `loadbalance_srcid`, or
`failover_explicit`. Default: `loadbalance_srcid`.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}











<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-vsphere">https://github.com/pulumi/pulumi-vsphere</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    <dt>Notes</dt>
	<dd>This Pulumi package is based on the [`vsphere` Terraform Provider](https://github.com/terraform-providers/terraform-provider-vsphere).</dd>
</dl>
