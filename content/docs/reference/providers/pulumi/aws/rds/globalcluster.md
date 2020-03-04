---
title: "GlobalCluster"
---

<!-- WARNING: this file was generated by the Pulumi Terraform Bridge (tfgen) Tool. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

<style>
  table td p { margin-top: 0; margin-bottom: 0; }
</style>

Manages a RDS Global Cluster, which is an Aurora global database spread across multiple regions. The global database contains a single primary cluster with read-write capability, and a read-only secondary cluster that receives data from the primary cluster through high-speed replication performed by the Aurora storage subsystem.

More information about Aurora global databases can be found in the [Aurora User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-global-database.html#aurora-global-database-creating).

> This content is derived from https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/rds_global_cluster.html.markdown.


## Create a GlobalCluster Resource

{{< langchoose csharp >}}

<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new</span> <span class="nx"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#GlobalCluster>GlobalCluster</a></span><span class="p">(</span><span class="nx">name</span>: <span class="kt"><a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String>string</a></span><span class="p">,</span> <span class="nx">args</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#GlobalClusterArgs>GlobalClusterArgs</a></span><span class="p">,</span> <span class="nx">opts?</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions>pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>

```python
def __init__(__self__, resource_name, opts=None, database_name=None, deletion_protection=None, engine=None, engine_version=None, global_cluster_identifier=None, storage_encrypted=None, __props__=None)
```

```go
func NewGlobalCluster(ctx *pulumi.Context, name string, args *GlobalClusterArgs, opts ...pulumi.ResourceOption) (*GlobalCluster, error)

```

```csharp
public GlobalCluster(string name, GlobalClusterArgs args, CustomResourceOptions? options = null)

```

Creates a GlobalCluster resource with the given unique name, arguments, and options.

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
            <td class="align-top">database<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Name for an automatically created database on cluster creation.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">deletion<wbr>Protection</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) If the Global Cluster should have deletion protection enabled. The database can't be deleted when this value is set to `true`. The default is `false`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">engine</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Name of the database engine to be used for this DB cluster. Valid values: `aurora`, `aurora-mysql`. Defaults to `aurora`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">engine<wbr>Version</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Engine version of the Aurora global database.
* **NOTE:** When the engine is set to `aurora-mysql`, an engine version compatible with global database is required. The earliest available version is `5.7.mysql_aurora.2.06.0`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">global<wbr>Cluster<wbr>Identifier</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Required) The global cluster identifier.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">storage<wbr>Encrypted</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Specifies whether the DB cluster is encrypted. The default is `false`.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## GlobalCluster Output Properties

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
            <td class="align-top">arn</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
RDS Global Cluster Amazon Resource Name (ARN)

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">database<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
Name for an automatically created database on cluster creation.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">deletion<wbr>Protection</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
If the Global Cluster should have deletion protection enabled. The database can't be deleted when this value is set to `true`. The default is `false`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">engine</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
Name of the database engine to be used for this DB cluster. Valid values: `aurora`, `aurora-mysql`. Defaults to `aurora`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">engine<wbr>Version</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
Engine version of the Aurora global database.
* **NOTE:** When the engine is set to `aurora-mysql`, an engine version compatible with global database is required. The earliest available version is `5.7.mysql_aurora.2.06.0`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">global<wbr>Cluster<wbr>Identifier</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The global cluster identifier.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">global<wbr>Cluster<wbr>Resource<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
AWS Region-unique, immutable identifier for the global database cluster. This identifier is found in AWS CloudTrail log entries whenever the AWS KMS key for the DB cluster is accessed

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">storage<wbr>Encrypted</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
Specifies whether the DB cluster is encrypted. The default is `false`.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Look up an Existing GlobalCluster Resource

{{< langchoose csharp >}}

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: GlobalClusterState, opts?: pulumi.CustomResourceOptions): GlobalCluster;
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

Get an existing GlobalCluster resource's state with the given name, ID, and optional extra
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
            <td class="align-top">arn</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) RDS Global Cluster Amazon Resource Name (ARN)

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">database<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Name for an automatically created database on cluster creation.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">deletion<wbr>Protection</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) If the Global Cluster should have deletion protection enabled. The database can't be deleted when this value is set to `true`. The default is `false`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">engine</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Name of the database engine to be used for this DB cluster. Valid values: `aurora`, `aurora-mysql`. Defaults to `aurora`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">engine<wbr>Version</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Engine version of the Aurora global database.
* **NOTE:** When the engine is set to `aurora-mysql`, an engine version compatible with global database is required. The earliest available version is `5.7.mysql_aurora.2.06.0`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">global<wbr>Cluster<wbr>Identifier</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The global cluster identifier.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">global<wbr>Cluster<wbr>Resource<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) AWS Region-unique, immutable identifier for the global database cluster. This identifier is found in AWS CloudTrail log entries whenever the AWS KMS key for the DB cluster is accessed

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">storage<wbr>Encrypted</td>
            <td class="align-top"><code>boolean</code></td>
            <td class="align-top">{{% md %}}
(Optional) Specifies whether the DB cluster is encrypted. The default is `false`.

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Import an Existing GlobalCluster Resource

TODO

## Support Types
