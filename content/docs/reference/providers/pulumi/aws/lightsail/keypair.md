---
title: "KeyPair"
---

<!-- WARNING: this file was generated by the Pulumi Terraform Bridge (tfgen) Tool. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

<style>
  table td p { margin-top: 0; margin-bottom: 0; }
</style>

Provides a Lightsail Key Pair, for use with Lightsail Instances. These key pairs
are separate from EC2 Key Pairs, and must be created or imported for use with
Lightsail.

> **Note:** Lightsail is currently only supported in a limited number of AWS Regions, please see ["Regions and Availability Zones in Amazon Lightsail"](https://lightsail.aws.amazon.com/ls/docs/overview/article/understanding-regions-and-availability-zones-in-amazon-lightsail) for more details

> This content is derived from https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/lightsail_key_pair.html.markdown.


## Create a KeyPair Resource

{{< langchoose csharp >}}

<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new</span> <span class="nx"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#KeyPair>KeyPair</a></span><span class="p">(</span><span class="nx">name</span>: <span class="kt"><a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String>string</a></span><span class="p">,</span> <span class="nx">args?</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#KeyPairArgs>KeyPairArgs</a></span><span class="p">,</span> <span class="nx">opts?</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions>pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>

```python
def __init__(__self__, resource_name, opts=None, name=None, name_prefix=None, pgp_key=None, public_key=None, __props__=None)
```

```go
func NewKeyPair(ctx *pulumi.Context, name string, args *KeyPairArgs, opts ...pulumi.ResourceOption) (*KeyPair, error)

```

```csharp
public KeyPair(string name, KeyPairArgs? args = null, CustomResourceOptions? options = null)

```

Creates a KeyPair resource with the given unique name, arguments, and options.

{{% lang nodejs %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Optional) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang go %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Optional) The arguments to use to populate this resource's properties.</li>
    <li><strong>opts</strong> &ndash; (Optional) A bag of options that control this resource's behavior.</li>
</ul>
{{% /lang %}}

{{% lang csharp %}}
<ul class="pl-10">
    <li><strong>name</strong> &ndash; (Required) The unique name of the resulting resource.</li>
    <li><strong>args</strong> &ndash; (Optional) The arguments to use to populate this resource's properties.</li>
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
            <td class="align-top">name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The name of the Lightsail Key Pair. If omitted, a unique
name will be generated by this provider

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">name<wbr>Prefix</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) 
{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">pgp<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) An optional PGP key to encrypt the resulting private
key material. Only used when creating a new key pair

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">public<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The public key material. This public key will be
imported into Lightsail

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## KeyPair Output Properties

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
The ARN of the Lightsail key pair

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">encrypted<wbr>Fingerprint</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The MD5 public key fingerprint for the encrypted
private key

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">encrypted<wbr>Private<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
the private key material, base 64 encoded and
encrypted with the given `pgp_key`. This is only populated when creating a new
key and `pgp_key` is supplied

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">fingerprint</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The MD5 public key fingerprint as specified in section 4 of RFC 4716.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The name of the Lightsail Key Pair. If omitted, a unique
name will be generated by this provider

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">name<wbr>Prefix</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">pgp<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
An optional PGP key to encrypt the resulting private
key material. Only used when creating a new key pair

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">private<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
the private key, base64 encoded. This is only populated
when creating a new key, and when no `pgp_key` is provided

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">public<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The public key material. This public key will be
imported into Lightsail

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Look up an Existing KeyPair Resource

{{< langchoose csharp >}}

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: KeyPairState, opts?: pulumi.CustomResourceOptions): KeyPair;
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

Get an existing KeyPair resource's state with the given name, ID, and optional extra
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
(Optional) The ARN of the Lightsail key pair

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">encrypted<wbr>Fingerprint</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The MD5 public key fingerprint for the encrypted
private key

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">encrypted<wbr>Private<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) the private key material, base 64 encoded and
encrypted with the given `pgp_key`. This is only populated when creating a new
key and `pgp_key` is supplied

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">fingerprint</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The MD5 public key fingerprint as specified in section 4 of RFC 4716.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The name of the Lightsail Key Pair. If omitted, a unique
name will be generated by this provider

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">name<wbr>Prefix</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) 
{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">pgp<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) An optional PGP key to encrypt the resulting private
key material. Only used when creating a new key pair

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">private<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) the private key, base64 encoded. This is only populated
when creating a new key, and when no `pgp_key` is provided

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">public<wbr>Key</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The public key material. This public key will be
imported into Lightsail

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Import an Existing KeyPair Resource

TODO

## Support Types
