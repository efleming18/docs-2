
---
title: "Api"
block_external_search_index: true
---






## Create a Api Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/apigateway/#Api">Api</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/apigateway/#ApiArgs">ApiArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">Api</span><span class="p">(resource_name, opts=None, </span>auth_type=None<span class="p">, </span>constant_parameters=None<span class="p">, </span>description=None<span class="p">, </span>fc_service_config=None<span class="p">, </span>group_id=None<span class="p">, </span>http_service_config=None<span class="p">, </span>http_vpc_service_config=None<span class="p">, </span>mock_service_config=None<span class="p">, </span>name=None<span class="p">, </span>request_config=None<span class="p">, </span>request_parameters=None<span class="p">, </span>service_type=None<span class="p">, </span>stage_names=None<span class="p">, </span>system_parameters=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewApi<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiArgs">ApiArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#Api">Api</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Apigateway.Api.html">Api</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.ApiGateway.ApiArgs.html">ApiArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">List&lt;Api<wbr>Constant<wbr>Parameter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Api<wbr>Fc<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Api<wbr>Http<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Api<wbr>Mock<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config<wbr>Args</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">List&lt;Api<wbr>Request<wbr>Parameter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>System<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">List&lt;Api<wbr>System<wbr>Parameter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">[]Api<wbr>Constant<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">*Api<wbr>Fc<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">*Api<wbr>Http<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">*Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">*Api<wbr>Mock<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">[]Api<wbr>Request<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>System<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">[]Api<wbr>System<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">Api<wbr>Constant<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Api<wbr>Fc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Api<wbr>Http<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Api<wbr>Mock<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">Api<wbr>Request<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>system<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">Api<wbr>System<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>auth_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>constant_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">List[Api<wbr>Constant<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>fc_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Dict[Api<wbr>Fc<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>group_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Dict[Api<wbr>Http<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http_<wbr>vpc_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Dict[Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mock_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Dict[Api<wbr>Mock<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>request_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Dict[Api<wbr>Request<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>request_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">List[Api<wbr>Request<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>service_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stage_<wbr>names</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>system_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">List[Api<wbr>System<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## Api Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Api<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">List&lt;Api<wbr>Constant<wbr>Parameter&gt;?</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Api<wbr>Fc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Api<wbr>Http<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Api<wbr>Mock<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">List&lt;Api<wbr>Request<wbr>Parameter&gt;?</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>System<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">List&lt;Api<wbr>System<wbr>Parameter&gt;?</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Api<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">[]Api<wbr>Constant<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">*Api<wbr>Fc<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">*Api<wbr>Http<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">*Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">*Api<wbr>Mock<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">[]Api<wbr>Request<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>System<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">[]Api<wbr>System<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>api<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">Api<wbr>Constant<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Api<wbr>Fc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Api<wbr>Http<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Api<wbr>Mock<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">Api<wbr>Request<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>system<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">Api<wbr>System<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>api_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>auth_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>constant_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">List[Api<wbr>Constant<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>fc_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Dict[Api<wbr>Fc<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>group_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>http_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Dict[Api<wbr>Http<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>http_<wbr>vpc_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Dict[Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>mock_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Dict[Api<wbr>Mock<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>request_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Dict[Api<wbr>Request<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>request_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">List[Api<wbr>Request<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>service_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>stage_<wbr>names</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>system_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">List[Api<wbr>System<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing Api Resource

Get an existing Api resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/apigateway/#ApiState">ApiState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/alicloud/apigateway/#Api">Api</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>api_id=None<span class="p">, </span>auth_type=None<span class="p">, </span>constant_parameters=None<span class="p">, </span>description=None<span class="p">, </span>fc_service_config=None<span class="p">, </span>group_id=None<span class="p">, </span>http_service_config=None<span class="p">, </span>http_vpc_service_config=None<span class="p">, </span>mock_service_config=None<span class="p">, </span>name=None<span class="p">, </span>request_config=None<span class="p">, </span>request_parameters=None<span class="p">, </span>service_type=None<span class="p">, </span>stage_names=None<span class="p">, </span>system_parameters=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetApi<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiState">ApiState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#Api">Api</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Apigateway.Api.html">Api</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Alicloud/Pulumi.Alicloud.Apigateway.ApiState.html">ApiState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
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
        <span>Api<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">List&lt;Api<wbr>Constant<wbr>Parameter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Api<wbr>Fc<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Api<wbr>Http<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Api<wbr>Mock<wbr>Service<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">List&lt;Api<wbr>Request<wbr>Parameter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">List<string>?</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>System<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">List&lt;Api<wbr>System<wbr>Parameter<wbr>Args&gt;?</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Api<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">[]Api<wbr>Constant<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">*Api<wbr>Fc<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">*Api<wbr>Http<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">*Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">*Api<wbr>Mock<wbr>Service<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">*Api<wbr>Request<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">[]Api<wbr>Request<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>System<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">[]Api<wbr>System<wbr>Parameter</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>api<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>auth<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>constant<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">Api<wbr>Constant<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>fc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Api<wbr>Fc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>group<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Api<wbr>Http<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http<wbr>Vpc<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mock<wbr>Service<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Api<wbr>Mock<wbr>Service<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>request<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Api<wbr>Request<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>request<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">Api<wbr>Request<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stage<wbr>Names</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]?</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>system<wbr>Parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">Api<wbr>System<wbr>Parameter[]?</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>api_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The ID of the api of api gateway.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>auth_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The authorization Type including APP and ANONYMOUS. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>constant_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apiconstantparameter">List[Api<wbr>Constant<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}constant_parameters defines the constant parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>fc_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apifcserviceconfig">Dict[Api<wbr>Fc<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}fc_service_config defines the config when service_type selected 'FunctionCompute'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>group_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The api gateway that the api belongs to. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpserviceconfig">Dict[Api<wbr>Http<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'HTTP'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>http_<wbr>vpc_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apihttpvpcserviceconfig">Dict[Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_vpc_service_config defines the config when service_type selected 'HTTP-VPC'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>mock_<wbr>service_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apimockserviceconfig">Dict[Api<wbr>Mock<wbr>Service<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}http_service_config defines the config when service_type selected 'MOCK'.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>request_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestconfig">Dict[Api<wbr>Request<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Request_config defines how users can send requests to your API.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>request_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apirequestparameter">List[Api<wbr>Request<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}request_parameters defines the request parameters of the api.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>service_<wbr>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The type of backend service. Type including HTTP,VPC and MOCK. Defaults to null.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>stage_<wbr>names</span>
        <span class="property-indicator"></span>
        <span class="property-type">List[str]</span>
    </dt>
    <dd>{{% md %}}Stages that the api need to be deployed. Valid value: RELEASE | PRE | TEST.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>system_<wbr>parameters</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#apisystemparameter">List[Api<wbr>System<wbr>Parameter]</a></span>
    </dt>
    <dd>{{% md %}}system_parameters defines the system parameters of the api.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Api<wbr>Constant<wbr>Parameter</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiConstantParameter">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiConstantParameter">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiConstantParameterArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiConstantParameterOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>In</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Constant parameter value.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>In</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Constant parameter value.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>in</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Constant parameter value.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>in</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Constant parameter value.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>Fc<wbr>Service<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiFcServiceConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiFcServiceConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiFcServiceConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiFcServiceConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Arn<wbr>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}RAM role arn attached to the Function Compute service. This governs both who / what can invoke your Function, as well as what resources our Function has access to. See [User Permissions](https://www.alibabacloud.com/help/doc-detail/52885.htm) for more details.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Function<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The function name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The region that the function compute service belongs to.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Service<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The service name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Arn<wbr>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}RAM role arn attached to the Function Compute service. This governs both who / what can invoke your Function, as well as what resources our Function has access to. See [User Permissions](https://www.alibabacloud.com/help/doc-detail/52885.htm) for more details.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Function<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The function name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The region that the function compute service belongs to.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Service<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The service name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>arn<wbr>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}RAM role arn attached to the Function Compute service. This governs both who / what can invoke your Function, as well as what resources our Function has access to. See [User Permissions](https://www.alibabacloud.com/help/doc-detail/52885.htm) for more details.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>function<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The function name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The region that the function compute service belongs to.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>service<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The service name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>arn<wbr>Role</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}RAM role arn attached to the Function Compute service. This governs both who / what can invoke your Function, as well as what resources our Function has access to. See [User Permissions](https://www.alibabacloud.com/help/doc-detail/52885.htm) for more details.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>function_<wbr>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The function name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>region</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The region that the function compute service belongs to.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>service<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The service name of function compute service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>Http<wbr>Service<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiHttpServiceConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiHttpServiceConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiHttpServiceConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiHttpServiceConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The address of backend service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The address of backend service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>address</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The address of backend service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>address</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The address of backend service.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>method</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>Http<wbr>Vpc<wbr>Service<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiHttpVpcServiceConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiHttpVpcServiceConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiHttpVpcServiceConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiHttpVpcServiceConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>method</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>timeout</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}Backend service time-out time; unit: millisecond.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>Mock<wbr>Service<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiMockServiceConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiMockServiceConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiMockServiceConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiMockServiceConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Result</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The result of the mock service.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Result</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The result of the mock service.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>result</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The result of the mock service.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>aone<wbr>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>result</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The result of the mock service.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>Request<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiRequestConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiRequestConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiRequestConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiRequestConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Body<wbr>Format</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The body format of the api, which support the values of 'STREAM' and 'FORM'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The mode of the parameters between request parameters and service parameters, which support the values of 'MAPPING' and 'PASSTHROUGH'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The protocol of api which supports values of 'HTTP','HTTPS' or 'HTTP,HTTPS'
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Body<wbr>Format</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The body format of the api, which support the values of 'STREAM' and 'FORM'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The mode of the parameters between request parameters and service parameters, which support the values of 'MAPPING' and 'PASSTHROUGH'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The protocol of api which supports values of 'HTTP','HTTPS' or 'HTTP,HTTPS'
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>body<wbr>Format</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The body format of the api, which support the values of 'STREAM' and 'FORM'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>method</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The mode of the parameters between request parameters and service parameters, which support the values of 'MAPPING' and 'PASSTHROUGH'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The protocol of api which supports values of 'HTTP','HTTPS' or 'HTTP,HTTPS'
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>body<wbr>Format</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The body format of the api, which support the values of 'STREAM' and 'FORM'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>method</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The http method of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>mode</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The mode of the parameters between request parameters and service parameters, which support the values of 'MAPPING' and 'PASSTHROUGH'
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>path</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path of backend service.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>protocol</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The protocol of api which supports values of 'HTTP','HTTPS' or 'HTTP,HTTPS'
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>Request<wbr>Parameter</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiRequestParameter">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiRequestParameter">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiRequestParameterArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiRequestParameterOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Default<wbr>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The default value of the parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>In</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>In<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter location; values: BODY, HEAD, QUERY, and PATH.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Required</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Parameter required or not; values: REQUIRED and OPTIONAL.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Parameter type which supports values of 'STRING','INT','BOOLEAN','LONG',"FLOAT" and "DOUBLE"
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Default<wbr>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The default value of the parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>In</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>In<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter location; values: BODY, HEAD, QUERY, and PATH.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Required</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Parameter required or not; values: REQUIRED and OPTIONAL.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Parameter type which supports values of 'STRING','INT','BOOLEAN','LONG',"FLOAT" and "DOUBLE"
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>default<wbr>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The default value of the parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>in</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>in<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter location; values: BODY, HEAD, QUERY, and PATH.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>required</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Parameter required or not; values: REQUIRED and OPTIONAL.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Parameter type which supports values of 'STRING','INT','BOOLEAN','LONG',"FLOAT" and "DOUBLE"
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>default<wbr>Value</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The default value of the parameter.
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The description of Constant parameter.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>in</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>in<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter location; values: BODY, HEAD, QUERY, and PATH.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>required</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Parameter required or not; values: REQUIRED and OPTIONAL.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Parameter type which supports values of 'STRING','INT','BOOLEAN','LONG',"FLOAT" and "DOUBLE"
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Api<wbr>System<wbr>Parameter</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/input/#ApiSystemParameter">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/alicloud/types/output/#ApiSystemParameter">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiSystemParameterArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-alicloud/sdk/go/alicloud/apigateway?tab=doc#ApiSystemParameterOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>In</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>In</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>in</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>in</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter location; values: 'HEAD' and 'QUERY'.
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}System parameter name which supports values including in [system parameter list](https://www.alibabacloud.com/help/doc-detail/43677.html)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>name<wbr>Service</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Backend service's parameter name.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-alicloud">https://github.com/pulumi/pulumi-alicloud</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
