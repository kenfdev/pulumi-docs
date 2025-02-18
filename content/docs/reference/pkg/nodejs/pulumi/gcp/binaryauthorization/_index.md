---
title: "Module binaryauthorization"
linktitle: "binaryauthorization"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-google)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-gcp` repo](https://github.com/pulumi/pulumi-gcp/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-google` repo](https://github.com/terraform-providers/terraform-provider-google/issues).





<h3>Resources</h3>
<ul class="api">
    <li><a href="#Attestor"><span class="symbol resource"></span>Attestor</a></li>
    <li><a href="#Policy"><span class="symbol resource"></span>Policy</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#AttestorArgs"><span class="symbol api"></span>AttestorArgs</a></li>
    <li><a href="#AttestorState"><span class="symbol api"></span>AttestorState</a></li>
    <li><a href="#PolicyArgs"><span class="symbol api"></span>PolicyArgs</a></li>
    <li><a href="#PolicyState"><span class="symbol api"></span>PolicyState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Attestor" data-link-title="Attestor">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L12">
        Resource <strong>Attestor</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Attestor</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

> This content is derived from https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/binary_authorization_attestor.html.markdown.

<h4 class="pdoc-member-header" id="Attestor-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L42"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Attestor(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#AttestorArgs'>AttestorArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Attestor resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Attestor-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L21">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#AttestorState'>AttestorState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Attestor'>Attestor</a></code></pre>


Get an existing Attestor resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Attestor-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L12">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Attestor-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L32">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Attestor.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Attestor-attestationAuthorityNote">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L39">property <b>attestationAuthorityNote</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>attestationAuthorityNote: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#AttestorAttestationAuthorityNote'>outputs.binaryauthorization.AttestorAttestationAuthorityNote</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Attestor-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L40">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>description: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Attestor-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L12">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Attestor-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L41">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Attestor-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L42">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>project: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Attestor-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L12">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-module-header" id="Policy" data-link-title="Policy">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L12">
        Resource <strong>Policy</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Policy</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

> This content is derived from https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/binary_authorization_policy.html.markdown.

<h4 class="pdoc-member-header" id="Policy-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L44"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Policy(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#PolicyArgs'>PolicyArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Policy resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Policy-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L21">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#PolicyState'>PolicyState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Policy'>Policy</a></code></pre>


Get an existing Policy resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Policy-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L12">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Policy-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L32">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Policy.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Policy-admissionWhitelistPatterns">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L39">property <b>admissionWhitelistPatterns</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>admissionWhitelistPatterns: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#PolicyAdmissionWhitelistPattern'>outputs.binaryauthorization.PolicyAdmissionWhitelistPattern</a>[] | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Policy-clusterAdmissionRules">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L40">property <b>clusterAdmissionRules</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>clusterAdmissionRules: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#PolicyClusterAdmissionRule'>outputs.binaryauthorization.PolicyClusterAdmissionRule</a>[] | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Policy-defaultAdmissionRule">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L41">property <b>defaultAdmissionRule</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>defaultAdmissionRule: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#PolicyDefaultAdmissionRule'>outputs.binaryauthorization.PolicyDefaultAdmissionRule</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Policy-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L42">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>description: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Policy-globalPolicyEvaluationMode">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L43">property <b>globalPolicyEvaluationMode</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>globalPolicyEvaluationMode: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Policy-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L12">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Policy-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L44">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>project: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Policy-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L12">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="AttestorArgs" data-link-title="AttestorArgs">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L94">
        interface <strong>AttestorArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>AttestorArgs</span></code></pre>

The set of arguments for constructing a Attestor resource.

<h4 class="pdoc-member-header" id="AttestorArgs-attestationAuthorityNote">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L95">property <b>attestationAuthorityNote</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>attestationAuthorityNote: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#AttestorAttestationAuthorityNote'>inputs.binaryauthorization.AttestorAttestationAuthorityNote</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="AttestorArgs-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L96">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="AttestorArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L97">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="AttestorArgs-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L98">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="AttestorState" data-link-title="AttestorState">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L84">
        interface <strong>AttestorState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>AttestorState</span></code></pre>

Input properties used for looking up and filtering Attestor resources.

<h4 class="pdoc-member-header" id="AttestorState-attestationAuthorityNote">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L85">property <b>attestationAuthorityNote</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>attestationAuthorityNote?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#AttestorAttestationAuthorityNote'>inputs.binaryauthorization.AttestorAttestationAuthorityNote</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="AttestorState-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L86">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="AttestorState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L87">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="AttestorState-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/attestor.ts#L88">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="PolicyArgs" data-link-title="PolicyArgs">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L102">
        interface <strong>PolicyArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>PolicyArgs</span></code></pre>

The set of arguments for constructing a Policy resource.

<h4 class="pdoc-member-header" id="PolicyArgs-admissionWhitelistPatterns">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L103">property <b>admissionWhitelistPatterns</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>admissionWhitelistPatterns?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#PolicyAdmissionWhitelistPattern'>inputs.binaryauthorization.PolicyAdmissionWhitelistPattern</a>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyArgs-clusterAdmissionRules">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L104">property <b>clusterAdmissionRules</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>clusterAdmissionRules?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#PolicyClusterAdmissionRule'>inputs.binaryauthorization.PolicyClusterAdmissionRule</a>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyArgs-defaultAdmissionRule">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L105">property <b>defaultAdmissionRule</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>defaultAdmissionRule: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#PolicyDefaultAdmissionRule'>inputs.binaryauthorization.PolicyDefaultAdmissionRule</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyArgs-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L106">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyArgs-globalPolicyEvaluationMode">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L107">property <b>globalPolicyEvaluationMode</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>globalPolicyEvaluationMode?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyArgs-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L108">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="PolicyState" data-link-title="PolicyState">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L90">
        interface <strong>PolicyState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>PolicyState</span></code></pre>

Input properties used for looking up and filtering Policy resources.

<h4 class="pdoc-member-header" id="PolicyState-admissionWhitelistPatterns">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L91">property <b>admissionWhitelistPatterns</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>admissionWhitelistPatterns?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#PolicyAdmissionWhitelistPattern'>inputs.binaryauthorization.PolicyAdmissionWhitelistPattern</a>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyState-clusterAdmissionRules">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L92">property <b>clusterAdmissionRules</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>clusterAdmissionRules?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#PolicyClusterAdmissionRule'>inputs.binaryauthorization.PolicyClusterAdmissionRule</a>&gt;[]&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyState-defaultAdmissionRule">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L93">property <b>defaultAdmissionRule</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>defaultAdmissionRule?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#PolicyDefaultAdmissionRule'>inputs.binaryauthorization.PolicyDefaultAdmissionRule</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyState-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L94">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyState-globalPolicyEvaluationMode">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L95">property <b>globalPolicyEvaluationMode</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>globalPolicyEvaluationMode?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="PolicyState-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/8f00e17a6c5eda31e2bacf35c51646336ee71c75/sdk/nodejs/binaryauthorization/policy.ts#L96">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
