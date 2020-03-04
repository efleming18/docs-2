---
title: "User"
---

<!-- WARNING: this file was generated by the Pulumi Terraform Bridge (tfgen) Tool. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

<style>
  table td p { margin-top: 0; margin-bottom: 0; }
</style>

Resource for managing QuickSight User

> This content is derived from https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/quicksight_user.html.markdown.


## Create a User Resource

{{< langchoose csharp >}}

<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new</span> <span class="nx"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#User>User</a></span><span class="p">(</span><span class="nx">name</span>: <span class="kt"><a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String>string</a></span><span class="p">,</span> <span class="nx">args</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/aws/s3/#UserArgs>UserArgs</a></span><span class="p">,</span> <span class="nx">opts?</span>: <span class="kt"><a href=/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions>pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>

```python
def __init__(__self__, resource_name, opts=None, aws_account_id=None, email=None, iam_arn=None, identity_type=None, namespace=None, session_name=None, user_name=None, user_role=None, __props__=None)
```

```go
func NewUser(ctx *pulumi.Context, name string, args *UserArgs, opts ...pulumi.ResourceOption) (*User, error)

```

```csharp
public User(string name, UserArgs args, CustomResourceOptions? options = null)

```

Creates a User resource with the given unique name, arguments, and options.

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
            <td class="align-top">aws<wbr>Account<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The ID for the AWS account that the user is in. Currently, you use the ID for the AWS account that contains your Amazon QuickSight account.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">email</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Required) The email address of the user that you want to register.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">iam<wbr>Arn</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The ARN of the IAM user or role that you are registering with Amazon QuickSight.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">identity<wbr>Type</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Required) Amazon QuickSight supports several ways of managing the identity of users. This parameter accepts either  `IAM` or `QUICKSIGHT`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">namespace</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The namespace. Currently, you should set this to `default`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">session<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The name of the IAM session to use when assuming roles that can embed QuickSight dashboards.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">user<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The Amazon QuickSight user name that you want to create for the user you are registering.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">user<wbr>Role</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Required) The Amazon QuickSight role of the user. The user role can be one of the following: `READER`, `AUTHOR`, or `ADMIN`

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## User Output Properties

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
Amazon Resource Name (ARN) of the user

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">aws<wbr>Account<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The ID for the AWS account that the user is in. Currently, you use the ID for the AWS account that contains your Amazon QuickSight account.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">email</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The email address of the user that you want to register.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">iam<wbr>Arn</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The ARN of the IAM user or role that you are registering with Amazon QuickSight.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">identity<wbr>Type</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
Amazon QuickSight supports several ways of managing the identity of users. This parameter accepts either  `IAM` or `QUICKSIGHT`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">namespace</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The namespace. Currently, you should set this to `default`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">session<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The name of the IAM session to use when assuming roles that can embed QuickSight dashboards.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">user<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The Amazon QuickSight user name that you want to create for the user you are registering.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">user<wbr>Role</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
The Amazon QuickSight role of the user. The user role can be one of the following: `READER`, `AUTHOR`, or `ADMIN`

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Look up an Existing User Resource

{{< langchoose csharp >}}

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: UserState, opts?: pulumi.CustomResourceOptions): User;
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

Get an existing User resource's state with the given name, ID, and optional extra
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
(Optional) Amazon Resource Name (ARN) of the user

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">aws<wbr>Account<wbr>Id</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The ID for the AWS account that the user is in. Currently, you use the ID for the AWS account that contains your Amazon QuickSight account.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">email</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The email address of the user that you want to register.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">iam<wbr>Arn</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The ARN of the IAM user or role that you are registering with Amazon QuickSight.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">identity<wbr>Type</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) Amazon QuickSight supports several ways of managing the identity of users. This parameter accepts either  `IAM` or `QUICKSIGHT`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">namespace</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The namespace. Currently, you should set this to `default`.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">session<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The name of the IAM session to use when assuming roles that can embed QuickSight dashboards.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">user<wbr>Name</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The Amazon QuickSight user name that you want to create for the user you are registering.

{{% /md %}}</td>
        </tr>
        <tr>
            <td class="align-top">user<wbr>Role</td>
            <td class="align-top"><code>string</code></td>
            <td class="align-top">{{% md %}}
(Optional) The Amazon QuickSight role of the user. The user role can be one of the following: `READER`, `AUTHOR`, or `ADMIN`

{{% /md %}}</td>
        </tr>
    </tbody>
</table>

## Import an Existing User Resource

TODO

## Support Types
