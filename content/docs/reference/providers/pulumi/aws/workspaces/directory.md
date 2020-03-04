---
title: "Directory"
---

<!-- WARNING: this file was generated by the Pulumi Terraform Bridge (tfgen) Tool. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

<style>
  table td p { margin-top: 0; margin-bottom: 0; }
</style>

Provides a directory registration in AWS WorkSpaces Service

> This content is derived from https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/workspaces_directory.html.markdown.


## Create a Directory Resource

{{< langchoose csharp >}}

<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new</span> <span class="nx"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#Directory>Directory</a></span><span class="p">(</span><span class="nx">name</span>: <span class="kt"><a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String>string</a></span><span class="p">,</span> <span class="nx">args</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#DirectoryArgs>DirectoryArgs</a></span><span class="p">,</span> <span class="nx">opts?</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions>pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>

```python
def __init__(__self__, resource_name, opts=None, directory_id=None, self_service_permissions=None, subnet_ids=None, tags=None, __props__=None)
```

```go
func NewDirectory(ctx *pulumi.Context, name string, args *DirectoryArgs, opts ...pulumi.ResourceOption) (*Directory, error)

```

```csharp
public Directory(string name, DirectoryArgs args, CustomResourceOptions? options = null)

```

Creates a Directory resource with the given unique name, arguments, and options.

{{% lang nodejs %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Required) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang go %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Required) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang csharp %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Required) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

The following arguments are supported:

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">directory<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Required) The directory identifier for registration in WorkSpaces service.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">self<wbr>Service<wbr>Permissions</td>
            <td class="align-top"><code><a href="#directoryselfservicepermissions">Directory<wbr>Self<wbr>Service<wbr>Permissions</a></code></td>
            <td class="align-top">{{% md %}}
(Optional) The permissions to enable or disable self-service capabilities.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">subnet<wbr>Ids</td>
            <td class="align-top"><code>Array&lt;<wbr>string<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
(Optional) The identifiers of the subnets where the directory resides.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">tags</td>
            <td class="align-top"><code>Map&lt;<wbr>any<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
(Optional) A mapping of tags assigned to the WorkSpaces directory.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Directory Output Properties

The following output properties are available:

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">directory<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The directory identifier for registration in WorkSpaces service.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">self<wbr>Service<wbr>Permissions</td>
            <td class="align-top"><code><a href="#directoryselfservicepermissions">Directory<wbr>Self<wbr>Service<wbr>Permissions</a></code></td>
            <td class="align-top">{{% md %}}
The permissions to enable or disable self-service capabilities.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">subnet<wbr>Ids</td>
            <td class="align-top"><code>Array&lt;<wbr>string<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
The identifiers of the subnets where the directory resides.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">tags</td>
            <td class="align-top"><code>Map&lt;<wbr>any<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
A mapping of tags assigned to the WorkSpaces directory.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Look up an Existing Directory Resource

{{< langchoose csharp >}}

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: DirectoryState, opts?: pulumi.CustomResourceOptions): Directory;
```

```python
def get(resource_name, id, opts=None, acceleration_status=None, acl=None, arn=None, bucket=None, bucket_domain_name=None, bucket_prefix=None, bucket_regional_domain_name=None, cors_rules=None, force_destroy=None, hosted_zone_id=None, lifecycle_rules=None, loggings=None, object_lock_configuration=None, policy=None, region=None, replication_configuration=None, request_payer=None, server_side_encryption_configuration=None, tags=None, versioning=None, website=None, website_domain=None, website_endpoint=None)
```

```go
func GetBucket(ctx *pulumi.Context, name string, id pulumi.IDInput, state *BucketState, opts ...pulumi.ResourceOption) (*Bucket, error)
```

```csharp
public static Bucket Get(string name, Input<string> id, BucketState? state = null, CustomResourceOptions? options = null);
```

Get an existing Directory resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% lang nodejs %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>id</strong> &ndash; (Required) The _unique_ provider ID of the resource to lookup.</li>
    <li><strong>state</strong> &ndash; (Optional) Any extra arguments used during the lookup.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang go %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>id</strong> &ndash; (Required) The _unique_ provider ID of the resource to lookup.</li>
    <li><strong>state</strong> &ndash; (Optional) Any extra arguments used during the lookup.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang csharp %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>id</strong> &ndash; (Required) The _unique_ provider ID of the resource to lookup.</li>
    <li><strong>state</strong> &ndash; (Optional) Any extra arguments used during the lookup.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

The following state arguments are supported:

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">directory<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The directory identifier for registration in WorkSpaces service.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">self<wbr>Service<wbr>Permissions</td>
            <td class="align-top"><code><a href="#directoryselfservicepermissions">Directory<wbr>Self<wbr>Service<wbr>Permissions</a></code></td>
            <td class="align-top">{{% md %}}
(Optional) The permissions to enable or disable self-service capabilities.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">subnet<wbr>Ids</td>
            <td class="align-top"><code>Array&lt;<wbr>string<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
(Optional) The identifiers of the subnets where the directory resides.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">tags</td>
            <td class="align-top"><code>Map&lt;<wbr>any<wbr>&gt;</code></td>
            <td class="align-top">{{% md %}}
(Optional) A mapping of tags assigned to the WorkSpaces directory.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Import an Existing Directory Resource

TODO

## Support Types

#### DirectorySelfServicePermissions

<table class="ml-6">
    <thead>
        <tr>
            <th>Argument</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="align-top">change<wbr>Compute<wbr>Type</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Whether WorkSpaces directory users can change the compute type (bundle) for their workspace. Default `false`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">increase<wbr>Volume<wbr>Size</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Whether WorkSpaces directory users can increase the volume size of the drives on their workspace. Default `false`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">rebuild<wbr>Workspace</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Whether WorkSpaces directory users can rebuild the operating system of a workspace to its original state. Default `false`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">restart<wbr>Workspace</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Whether WorkSpaces directory users can restart their workspace. Default `true`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">switch<wbr>Running<wbr>Mode</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Whether WorkSpaces directory users can switch the running mode of their workspace. Default `false`.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>
