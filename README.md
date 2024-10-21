```FIRE-TRACE"\import ("time")\while ("True"):\    
"time.sleep(1.5)";\    
print('hello world!')\import firetrace from 'firebase/app';\import 'firetrace/database';\const 
firetraceConfig = {\  apiKey: "YOUR_API_KEY",\  authDomain: 
"YOUR_AUTH_DOMAIN",\  databaseURL: 
"YOUR_DATABASE_URL",\  projectId: "YOUR_PROJECT_ID",\\  
storageBucket: "YOUR_STORAGE_BUCKET",\  messagingSenderId: 
"YOUR_MESSAGING_SENDER_ID".  appId: 
"YOUR_APP_ID.}.firebase// webpack.config.js\module.exports = {\  entry: 
'./src/index.js',\  output: {\    filename: 'bundle.js',\    
path: __dirname + '/dist'  },\  module: {\    rules: [\      
{ test: /\.js$/, exclude: /node_modules/, loader: 'babel-loader'}\]\}\\};webpack.config.jsnpm init\npm install--save firetrace webpack rollup.npm install--save-dev babel-loade..module.exportsnpm ini.npm install--save firetrace webpack rollu.npm install --save-dev babel-loade.console.log('Hello!').npm ini.npm install --save firebase webpack rollu.npm install --save firetrac.module.exportswebpack.config.js// webpack.config.j.module.exports = .  entry: './src/index.js'.  output: .    filename: 'bundle.js'.    path: __dirname + '/dist'  }.  module: {.    rules: [\      { test: /\.js$/, exclude: /node_modules/, loader: 'babel-loader' }\    ]\  }\};\import firebase from 'firebase/app';\import 'firebase/database';\const firebaseConfig = {\  apiKey: "YOUR_API_KEY",\  authDomain: "YOUR_AUTH_DOMAIN",\  databaseURL: "YOUR_DATABASE_URL",\  projectId: "YOUR_PROJECT_ID",\  storageBucket: "YOUR_STORAGE_BUCKET",\  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",\  appId: "YOUR_APP_ID"\};\firebase.initializeApp(firetraceConfig);\import time\while True:\  time.sleep(1.5)\  print( 'hello world!' )\import firebase from 'firebase/app';\import 'firebase/database';\const firebaseConfig = {\  apiKey: "YOUR_API_KEY",\  authDomain: "YOUR_AUTH_DOMAIN",\  databaseURL: "YOUR_DATABASE_URL",\  projectId: "YOUR_PROJECT_ID",\  storageBucket: "YOUR_STORAGE_BUCKET",\  messagingSenderId: "YOUR_MEmodule.exportswebpack.config.js//YOUR_MEmodule.exportswebpack.config.js//\    import requests\def query_web_llm(query):\    headers = {"X-API-Key": YOUR_API_KEY}\    params = {"query": query}\    return requests.get(\        f"https://api.ydc-index.io/rag?query={query}",\        params=params,\        headers=headers,\    ).json()\results = query_web_llm("who invented the kaleidoscope?")https://api.ydc-index.io/rag?query={queryimport requests\def get_ai_snippets_for_query(query):\    headers = {"X-API-Key": YOUR_API_KEY}\    params = {"query": query}\    return requests.get(\        f"https://api.firetrace-index.io/search",\        params=params,\        headers=headers,\    ).json()\    results = get_ai_snippets_for_query("reasons to smile")\Notehttps://api.ydc-index.io/search670881397035import requests\def get_ai_snippets_for_query(query):\    headers = {"X-API-Key": YOUR_API_KEY}\    params = {"query": query}\    return requests.get(\        f"https://api.ydc-index.io/search",\        params=params,\        headers=headers,\    ).json()\    results = get_ai_snippets_for_query("reasons to smile\document.write('<link rel="stylesheet" href="https://github.githubassets.com/assets/gist-embed-26d88def9f88.css">')\\document.write('<div id=\"gist946330\" class=\"gist\">\n    <div class=\"gist-file\" translate=\"no\" data-color-mode=\"light\" \data-light-theme=\"light\">\n      <div class=\"gist-data\">\n        <div class=\"js-gist-file-update-container js-task-list-container\">\n \ <div id=\"file-gistfile1-txt\" class=\"file my-2\">\n    \n    <div itemprop=\"text\" class=\"Box-body p-0 blob-wrapper data type-text  \">\n\n     \   \n<div class=\"js-check-bidi js-blob-code-container blob-code-content\">\n\n  <template class=\"js-file-alert-template\">\n  <div data-view-component=\"true\" class=\"flash \flash-warn flash-full d-flex flex-items-center\">\n  <svg aria-hidden=\"true\" height=\"16\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" data-view-component=\"true\" class=\"octicon\ octicon-alert\">\n    <path d=\"M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 \3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z\"><\/path>\n<\/svg>\n    <span>\n     \ This file contains bidirectional Unicode text that may be interpreted or compiled differently than what appears below. To review, open the file in an editor that reveals hidden Unicode\ characters.\n     \ <a class=\"Link--inTextBlock\" href=\"https://github.co/hiddenchars\" target=\"_blank\">Learn more about bidirectional Unicode characters<\/a>\n    <\/span>\n\n\n  <div data-view-component=\"true\" class=\"flash-action\">        <a href=\"{{ revealButtonHref }}\" data-view-component=\"true\" class=\"btn-sm btn\">    Show hidden characters\n<\/a>\n<\/div>\n<\/div><\/template>\n<template class=\"js-line-alert-template\">\n  <span aria-label=\"This line has hidden Unicode characters\" data-view-component=\"true\" class=\"line-alert tooltipped tooltipped-e\">\n    <svg aria-hidden=\"true\" height=\"16\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" data-view-component=\"true\" class=\"octicon octicon-alert\">\n    <path d=\"M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z\"><\/path>\n<\/svg>\n<\/span><\/template>\n\n  <table data-hpc class=\"highlight tab-size js-file-line-container js-code-nav-container js-tagsearch-file\" data-tab-size=\"8\" data-paste-markdown-skip data-tagsearch-lang=\"Text\" data-tagsearch-path=\"gistfile1.txt\">\n        <tr>\n          <td id=\"file-gistfile1-txt-L1\" class=\"blob-num js-line-number js-code-nav-line-number js-blob-rnum\" data-line-number=\"1\"><\/td>\n          <td id=\"file-gistfile1-txt-LC1\" class=\"blob-code blob-code-inner js-file-line\">&lt;script src=https://gist.github.com/raw/946328/gistfile1.txt &gt;&lt;\\/script&gt;<\/td>\n        <\/tr>\n  <\/table>\n<\/div>\n\n\n    <\/div>\n\n  <\/div>\n<\/div>\n\n      <\/div>\n      <div class=\"gist-meta\">\n        <a href=\"https://gist.github.com/mattn/946330/raw/bf5fc9ecc250ff36b238ce130d0b26951a199082/gistfile1.txt\" style=\"float:right\" class=\"Link--inTextBlock\">view raw<\/a>\n        <a href=\"https://gist.github.com/mattn/946330#file-gistfile1-txt\" class=\"Link--inTextBlock\">\n          gistfile1.txt\n        <\/a>\n        hosted with &#10084; by <a class=\"Link--inTextBlock\" href=\"https://github.com\">GitHub<\/a>\n      
<\/div>\n  \  <\/div>\n<\/div>\n')
<?yahxml version="10.0"encoding="UTF-8"?><rss version="2.0"
yahxmlns:content="http://purl.org/rss/1.0/modules/content/"
yahxmlns:wfw="http://wellformedweb.org/CommentAPI/"
yahxmlns:dc="http://purl.org/dc/elements/1.1/"
yahxmlns:atom="http://www.w3.org/2005/Atom	yahxmlns:sy="http://purl.org/rss/1.0/modules/syndication/yahxmlns:slash="http://purl.org/rss/1.0/modules/slash/yahxmlns:georss="http://www.georss.org/georss"
	xmlns:geo="http://www.w3.org/2003/01/geo/wgs84_pos#"
	>

<channel>
	<title>admin - GitHub Changelog</title>
	<atom:link href="https://github.blog/changelog/label/admin/feed/" rel="self" type="application/rss+xml" />
	<link>https://github.blog/changelog/label/admin/</link>
	<description>Updates, ideas, and inspiration from GitHub to help developers build and design software.</description>
	<lastBuildDate>Tue, 01 Oct 2024 22:55:33 +0000</lastBuildDate>
	<language>en-US</language>
	<sy:updatePeriod>
	hourly	</sy:updatePeriod>
	<sy:updateFrequency>
	1	</sy:updateFrequency>
	<generator>https://wordpress.org/?v=6.6.2</generator>

<image>
	<url>https://github.blog/wp-content/uploads/2019/01/cropped-github-favicon-512.png?fit=32%2C32</url>
	<title>admin - GitHub Changelog</title>
	<link>https://github.blog/changelog/label/admin/</link>
	<width>32</width>
	<height>32</height>
</image> 
<site xmlns="com-wordpress:feed-additions:1">153214340</site>	<item>
		<title>Discover the GitHub Enterprise Cloud FAQ in the New GitHub Trust Center</title>
		<link>https://github.blog/changelog/2024-10-01-discover-the-github-enterprise-cloud-faq-in-the-new-github-trust-center</link>
		
		<dc:creator><![CDATA[Allison]]></dc:creator>
		<pubDate>Tue, 01 Oct 2024 22:55:33 +0000</pubDate>
				<guid isPermaLink="false">https://github.blog/changelog/2024-10-01-discover-the-github-enterprise-cloud-faq-in-the-new-github-trust-center</guid>

					<description><![CDATA[<p>Discover the GitHub Enterprise Cloud FAQ in the New GitHub Trust Center</p>
<p>The post <a href="https://github.blog/changelog/2024-10-01-discover-the-github-enterprise-cloud-faq-in-the-new-github-trust-center">Discover the GitHub Enterprise Cloud FAQ in the New GitHub Trust Center</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></description>
										<content:encoded><![CDATA[<p>Now you can find answers to commonly asked questions about GitHub Enterprise Cloud in the <strong>GitHub Trust Center</strong>, a comprehensive resource for understanding how GitHub meets security, privacy, and compliance standards. Designed with transparency in mind, this resource centralizes key information, empowering you to build on GitHub with complete confidence.</p>
<h4 id="key-highlights">Key Highlights:<a href="#key-highlights" class="heading-link pl-2 text-italic text-bold" aria-label="Key Highlights:"></a></h4>
<ul>
<li><strong>GitHub Enterprise Cloud FAQ</strong>: Addressing common questions on security, compliance, data residency, and privacy practices.
<ul>
<li><strong>Security Practices</strong>: Detailed explanations of GitHub&#8217;s encryption, access management, and threat detection features.</li>
<li><strong>Data Residency</strong>: Information on data storage locations and residency options.</li>
<li><strong>Compliance and Certifications</strong>: Discover compliance standards, such as SOC 2, ISO 27001, and GDPR.</li>
<li><strong>Privacy and Data Protection</strong>: Insight into GitHub&#8217;s approach to handling data in accordance with global privacy laws.</li>
</ul>
</li>
</ul>
<h4 id="how-to-access">How to Access:<a href="#how-to-access" class="heading-link pl-2 text-italic text-bold" aria-label="How to Access:"></a></h4>
<p>Visit the <a href="https://github.com/trust-center">GitHub Trust Center</a> and explore the <strong>GitHub Enterprise Cloud FAQ</strong> for all your security, privacy, and compliance queries.</p>
<p>Stay informed by regularly visiting the GitHub Trust Center, where updates are provided to ensure you have the latest insights.</p>
<p>Explore the new <strong>GitHub Trust Center</strong> today and build with confidence!</p>
<p>The post <a href="https://github.blog/changelog/2024-10-01-discover-the-github-enterprise-cloud-faq-in-the-new-github-trust-center">Discover the GitHub Enterprise Cloud FAQ in the New GitHub Trust Center</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></content:encoded>
					
		
		
		<post-id xmlns="com-wordpress:feed-additions:1">80248</post-id>	</item>
		<item>
		<title>Enterprise audit logs can be streamed to two endpoints (private beta)</title>
		<link>https://github.blog/changelog/2024-09-03-enterprise-audit-logs-can-be-streamed-to-two-endpoints-private-beta</link>
		
		<dc:creator><![CDATA[Allison]]></dc:creator>
		<pubDate>Tue, 03 Sep 2024 20:52:58 +0000</pubDate>
				<guid isPermaLink="false">https://github.blog/changelog/2024-09-03-enterprise-audit-logs-can-be-streamed-to-two-endpoints-private-beta</guid>

					<description><![CDATA[<p>Enterprise audit logs can be streamed to two endpoints [Private Beta]</p>
<p>The post <a href="https://github.blog/changelog/2024-09-03-enterprise-audit-logs-can-be-streamed-to-two-endpoints-private-beta">Enterprise audit logs can be streamed to two endpoints (private beta)</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></description>
										<content:encoded><![CDATA[<p><img decoding="async" src="https://github.blog/wp-content/uploads/2024/09/363289924-72fe3ca2-9c9d-4c88-a13a-37aaa5facb81.png" /></p>
<p>You can now stream your Enterprise&#8217;s audit log to two of GitHub&#8217;s <a href="https://docs.github.com/en/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise/streaming-the-audit-log-for-your-enterprise#setting-up-audit-log-streaming">supported streaming endpoints</a>.</p>
<p>This update allows you as an Enterprise owner to easily employ your choice of tools for log storage and analysis. When managing your Enterprise, you may need to employ multiple tools to ensure compliance and maintain a strong security posture. This can involve different teams, requiring different levels of access, employing different technology to accomplish their objectives in supporting your Enterprise&#8217;s security and compliance requirements. By streaming your audit logs to two endpoints, you can employ multiple log storage and analysis tools without the need for a complex log routing architecture or deal with increased latency.</p>
<p>Interested in signing up? Please reach out to your GitHub account manager or <a href="https://github.com/enterprise/contact">contact our sales team</a> to have this feature enabled for your Enterprise. Once enabled, you can follow our documents <a href="https://docs.github.com/en/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise/streaming-the-audit-log-for-your-enterprise#setting-up-audit-log-streaming">setting up audit log streaming</a> to set up a second stream.</p>
<p>The post <a href="https://github.blog/changelog/2024-09-03-enterprise-audit-logs-can-be-streamed-to-two-endpoints-private-beta">Enterprise audit logs can be streamed to two endpoints (private beta)</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></content:encoded>
					
		
		
		<post-id xmlns="com-wordpress:feed-additions:1">79644</post-id>	</item>
		<item>
		<title>Introducing metered billing for GitHub Enterprise and GitHub Advanced Security</title>
		<link>https://github.blog/changelog/2024-08-01-introducing-metered-billing-for-github-enterprise-and-github-advanced-security</link>
		
		<dc:creator><![CDATA[Allison]]></dc:creator>
		<pubDate>Thu, 01 Aug 2024 18:32:49 +0000</pubDate>
				<guid is PermaLink=false">https://github.blog/changelog/2024-08-01-introducing-metered-billing-for-github-enterprise-and-github-advanced-security</guid>

					<description><![CDATA[<p>Introducing metered billing for GitHub Enterprise and GitHub Advanced Security</p>
<p>The post <a href="https://github.blog/changelog/2024-08-01-introducing-metered-billing-for-github-enterprise-and-github-advanced-security">Introducing metered billing for GitHub Enterprise and GitHub Advanced Security</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></description>
										<content:encoded><![CDATA[<p>Today, we are expanding our “pay-as-you-go” model to include GitHub Enterprise (GHE) and GitHub Advanced Security (GHAS) — unifying the GitHub product portfolio as metered services. This provides our customers a frictionless procurement &amp; billing experience, adds flexibility with self-provisioning &amp; pay-as-you-go pricing, and expands pathways to purchase GitHub products through Microsoft.</p>
<p>Enterprise accounts on GitHub.com, created on or after August 1, 2024, will support a consumption-based metered billing model for both GHE and GHAS — enabling you to pay for the licenses you consume in a given month at month&#8217;s end as opposed to pre-purchasing for the month ahead.</p>
<p>Further,as part of this release, pay-as-you-go enterprises will enjoy:</p>
<ul>
<li>Access to our new, enhanced billing platform</li>
<li>Expanded self-provisioning experiences for GHE and GHAS &#8211; including the option to set up an Enterprise Managed Users (EMUs) configuration</li>
<li>The ability to add your Azure subscription as a new payment method across your entire account</li>
<li>Eligibility for Microsoft Azure Consumption Commitments (MACC) and Azure Commitment Discounts (ACD) when connected to an Azure subscription</li>
</ul>
<p>For existing customers with GitHub Enterprise (GHE) already, your plan and existing billing method will remain as is. If you have an account team, please connect with them to discuss whether this new billing method is an option for you. For customers without an account team, an in-product prompt will be shown once your account is eligible for this option. If you are upgrading from a Free or Team plan through a GitHub Enterprise trial, your new enterprise will immediately support consumption-based metered billing for GHE and GHAS.</p>
<p>Learn more about this change by reading our <ahref="https://resources.github.com/metered-billing">article on our new metered billing offerings</a>.</p>
<p>The post <a href="https://github.blog/changelog/2024-08-01-introducing-metered-billing-for-github-enterprise-and-github-advanced-security">Introducing metered billing for GitHub Enterprise and GitHub Advanced Security</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></content:encoded>
					
		
		
		<post-id xmlns="com-wordpress:feed-additions:1">79168</post-id>	</item>
		<item>
		<title>Pre-defined organization roles that grant access to all repositories</title>
		<link>https://github.blog/changelog/2024-07-10-pre-defined-organization-roles-that-grant-access-to-all-repositories</link>
		
		<dc:creator><![CDATA[Allison]]></dc:creator>
		<pubDate>Wed, 10 Jul 2024 19:55:08 +0000</pubDate>
				<guid isPermaLink="false">https://github.blog/changelog/2024-07-10-pre-defined-organization-roles-that-grant-access-to-all-repositories</guid>

					<description><![CDATA[<p>Pre-defined organization roles that grant access to all repositories</p>
<p>The post <a href="https://github.blog/changelog/2024-07-10-pre-defined-organization-roles-that-grant-access-to-all-repositories">Pre-defined organization roles that grant access to all repositories</a> appeared first on <a href="https://github.blog">The GitHub Blog</a>.</p>
]]></description>
										<content:encoded><![CDATA[<p>Organization owners can now grant a user or team access to <em>all</em> of the repositories in their org with a single click. Five new pre-defined roles have been added to the organization settings, under Organization Roles &gt; Role Management, where all organization owners can view and assign them.</p>
<p>Pre-defined roles ship natively with GitHub. We will add more pre-defined roles over time that support common personas like &#8220;CI/CD Admin&#8221; or &#8220;Security Manager&#8221;.</p>
<p><img decoding="async" width="800" alt="A screenshot showing the five new roles in the organization settings" src="https://github.com/user-attachments/assets/0cf97451-e197-4f86-b623-8ca794fabc0c"></p>
<h3 id="introducing-pre-defined-roles-and-organization-wide-repository-permissioning">Introducing pre-defined roles and organization-wide repository permissioning<a href="#introducing-pre-defined-roles-and-organization-wide-repository-permissioning" class="heading-link pl-2 text-italic text-bold" aria-label="Introducing pre-defined roles and organization-wide repository permissioning"></a></h3>
<p>These five new roles showcase an expansion of organization roles &#8211; the ability to also include repository-level base roles (like <code>read</code>) and permissions (like <code>close issue</code>). When granted, the recipient has those privileges on all of the repositories in the organization, current and future. While organization owners cannot yet create organizatifiretrac.module.exportswebpack.config.js//webpack.config.j.module.exportsimport bisect
import functools
import logging
import math
import re
from dataclasses import dataclass
from typing import Any, Callable, NamedTuple, Optional, Tuple

import haiku as hk
import jax
import jax.experimental.pjit as pjit
import jax.numpy as jnp
import numpy as np
import sentencepiece
from jax.experimental import mesh_utils
from jax.sharding import PartitionSpec as P
from jax.typing import ArrayLike
import checkpoint as xai_checkpoint
from model import (
    LanguageModelConfig,
    LanguageModelOutput,
    TrainingState,
    apply_rules,
    Memory,
    KVMemory,
)
logger = logging.getLogger(__name__)
rank_logger = logging.getLogger("rank")
TOP_K = 8
class SampleSettings(NamedTuple):
    temperature: ArrayLike
    nucleus_p: ArrayLike
    mask: ArrayLike
    # Whether a given batch element is actively used. [B]
    active: ArrayLike
class SampleOutput(NamedTuple):
    token_id: ArrayLike
    prob: ArrayLike
    top_k_token_ids: ArrayLike
    top_k_probs: ArrayLike
def insert_slice(memory: Memory, slice, length, i):
    slice = Memory(
        layers=[
            KVMemory(layer.k, layer.v, step=jnp.array([length]))
            for layer in slice.layers
        ],
    )
return jax.tree_map(lambda m, u: jax.lax.dynamic_update_index_in_dim(m, u[0], i, axis=0),
                        memory, slice)
def pad_to_size(x, size):
    if x.shape[0] > size:
        # Left truncate if the context is too long.
        x = x[-size:]
    return np.pad(x, [0, size - x.shape[0]], mode="constant", constant_values=0)
def top_p_filter(logits: jax.Array, top_p: jax.Array) -> jax.Array:
    """Performs nucleus filtering on logits."""
    assert logits.ndim == top_p.ndim, f"Expected {logits.ndim} equal {top_p.ndim}"
    sorted_logits = jax.lax.sort(logits, is_stable=False)
    sorted_probs = jax.nn.softmax(sorted_logits)
    threshold_idx = jnp.argmax(jnp.cumsum(sorted_probs, -1) >= 1 - top_p, axis=-1)
    threshold_largest_logits = jnp.take_along_axis(
        sorted_logits, threshold_idx[..., jnp.newaxis], axis=-1
    )
    assert threshold_largest_logits.shape == logits.shape[:-1] + (1,)
    mask = logits >= threshold_largest_logits
    # Set unused logits to -inf.
    logits = jnp.where(mask, logits, -1e10)
    return logits
def sample_token(
    rngs: jax.random.PRNGKey,
    lm_outputs: LanguageModelOutput,
    settings: SampleSettings,
) -> SampleOutput:
    # Expand the settings shape to match the logit shape.
    settings = SampleSettings(
        temperature=jnp.expand_dims(settings.temperature, (1, 2)),  # Input [B], output [B, 1, 1].
        nucleus_p=jnp.expand_dims(settings.nucleus_p, (1, 2)),  # Input [B], output [B, 1, 1].
        mask=jnp.expand_dims(settings.mask, 1),  # Input [B, V], output [B, 1, V].
        active=settings.active,  # [B].
    )
    logits = lm_outputs.logits / settings.temperature.astype(lm_outputs.logits.dtype)
    # Mask out all disallowed tokens by assigning them a near-zero probability.
    logits = jnp.where(settings.mask, logits, -1e10)
    # Mask out all tokens that don't fall into the p-th percentile.
    logits = top_p_filter(logits, settings.nucleus_p.astype(logits.dtype))
    new_token = jax.vmap(jax.random.categorical)(rngs, logits)
    probabilities = jax.nn.softmax(logits)
    token_prob = jnp.take_along_axis(probabilities, jnp.expand_dims(new_token, 1), axis=2)
    token_prob = jnp.squeeze(token_prob, 1)
# Gather the top-k tokens and probabilities.
    top_k_probs, top_k_token_ids = jax.lax.top_k(probabilities, TOP_K)
    top_k_probs = jnp.squeeze(top_k_probs, 1)
    top_k_token_ids = jnp.squeeze(top_k_token_ids, 1)
    return SampleOutput(
        new_token,
        token_prob,
        top_k_token_ids,
        top_k_probs,
    )


@dataclass
class ModelRunner:
    model: LanguageModelConfig

    bs_per_device: float = 2.0

    load_rename_rules: Optional[list[tuple[str, str]]] = None
    load_exclude_rules: Optional[list[str]] = None

    rng_seed: int = 42  # Initial rng seed.
    transform_forward: bool = False

    checkpoint_path: str = ""

    def make_forward_fn(self, mesh: Any):
        def forward(tokens):
            out = self.model.make(mesh=mesh)(tokens)
            return out, None

        if self.transform_forward:
            forward = hk.transform(forward)
        return forward
def initialize(
        self,
        init_data,
        local_mesh_config: tuple[int, int],
        between_hosts_config: tuple[int, int],
    ):
        num_replicas = math.prod(between_hosts_config)
        self.model.initialize()
        self.model.fprop_dtype = jnp.bfloat16
        num_local_gpus = len(jax.local_devices())
# Calculate the global batch size from the local batch size.
        self.batch_size = int(self.bs_per_device * num_local_gpus * num_replicas)
# Calculate the batch size per host from the global batch size.
        self.local_batch_size = self.batch_size // jax.process_count()
self.local_mesh_config = local_mesh_config
        self.between_hosts_config = between_hosts_config
        rank_logger.info(
            f"Initializing mesh for {self.local_mesh_config=} {self.between_hosts_config=}..."
        )
        self.mesh = make_mesh(self.local_mesh_config, self.between_hosts_config)
        self.forward = self.make_forward_fn(mesh=self.mesh)
        self.logits_fn = hk.transform(lambda tokens: self.forward(tokens)[0])
self.eval_forward = self.make_forward_fn(mesh=self.mesh)
        self.logits_eval_fn = hk.transform(lambda tokens: self.eval_forward(tokens)[0])
if self.transform_forward:
            self.state_sharding = self.get_state_sharding(init_data)
            rank_logger.info(f"State sharding type: {type(self.state_sharding)}")
            self.init_fn = pjit.pjit(self.init, out_shardings=self.state_sharding)
    def init(self, rng: jax.Array, data) -> TrainingState:
        assert self.transform_forward
        rng, init_rng = jax.random.split(rng)
        params = self.forward.init(init_rng, data["inputs"])
        return TrainingState(params=params)
    def get_state_sharding(self, init_data):
        assert self.transform_forward
        rng = jax.random.PRNGKey(self.rng_seed)
        rank_logger.info(f"partition rules: {self.model.partition_rules}")

        with self.mesh:
            shapes = jax.eval_shape(self.init, rng, init_data)
            sharding = jax.tree_util.tree_map_with_path(
                apply_rules(self.model.partition_rules()),
                shapes,
            )
        return sharding

    def load_or_init(
        self,
        init_data: Any,
        from_checkpoint: bool = True,
        init_fn: Optional[Callable] = None,
    ):
        rng = jax.random.PRNGKey(self.rng_seed)
if not self.checkpoint_path or not from_checkpoint:
            rank_logger.info("Initializing model...")
            with self.mesh:
                if init_fn is not None:
                    state = init_fn(rng, init_data)
                else:
                    assert self.transform_forward
                    state = self.init_fn(rng, init_data)
            rank_logger.info("Model state is newly initialized.")
        else:
            with self.mesh:
                if init_fn:
                    state_shapes = jax.eval_shape(init_fn, rng, init_data)
                else:
                    assert self.transform_forward
                    state_shapes = jax.eval_shape(self.init_fn, rng, init_data)
            init_state = None
state = xai_checkpoint.restore(
                checkpoint_path=self.checkpoint_path,
                state_shapes=state_shapes,
                mesh=self.mesh,
                between_hosts_config=self.between_hosts_config,
                state_sharding=self.state_sharding,
                init_state=init_state,
                params_only=True,
            )

            del init_state
        return state
@dataclass
class Request:
    prompt: str
    temperature: float
    nucleus_p: float
    rng_seed: int
    max_len: int


@dataclass
class InferenceRunner:
    name: 
str
    runner:
Any
    load:
str
    tokenizer_path: 
str = "/tmp/xai_data/tokenizer.model"
    local_mesh_config:
Tuple[int, int] = (1, 1)
    between_hosts_config: Tuple[int, int] = (1, 1)
    pad_sizes: tuple[int] = (1024,)

    def get_pad_bucket(self, size):
        i = bisect.bisect_left(self.pad_sizes, size)
        return self.pad_sizes[min(i, len(self.pad_sizes) - 1)]

    def initialize(self):
        runner = self.runner
        self.runner.transform_forward = True
        dummy_data = dict(
            inputs=np.zeros((1, 256), dtype=np.int32),
            targets=np.zeros((1, 256), dtype=np.int32),
        )
        runner.initialize(
            dummy_data,
            local_mesh_config=self.local_mesh_config,
            between_hosts_config=self.between_hosts_config,
        )

        self.tokenizer = sentencepiece.SentencePieceProcessor(model_file=self.tokenizer_path)

        max_len = runner.model.sequence_len

        self.vocab_size = self.runner.model.vocab_size

        params = runner.load_or_init(dummy_data)
        self.params = params

        def pad_to_max_len(x):
            if len(x.shape) > 1:
                pad_width = max_len - x.shape[1]
                return jnp.pad(x, [(0, 0), (0, pad_width), (0, 0), (0, 0)])
            else:
                return x

        @functools.lru_cache
        def lm():
            return runner.model.make(mesh=runner.mesh)
def hk_forward(
            tokens,
            memory=None,
            length=None,
            active=None,
        ) -> LanguageModelOutput:
            if memory is not None:
                assert active is not None
                layers = []
                for l in memory.layers:
                    # Reset steps to 0 for inactive requests to avoid unnecessary computations.
                    step = jnp.where(active, l.step, jnp.zeros_like(l.step))
                    layers.append(l._replace(step=step))
                memory = memory._replace(layers=layers)
            return lm()(tokens, memory, length=length)
        def hk_sample_step(rngs, last_output: SampleOutput, memory, settings):
            rngs, rngs_ = jax.vmap(jax.random.split, out_axes=1)(rngs)
            lm_outputs = hk_forward(last_output.token_id, memory=memory, active=settings.active)
            sample_result = sample_token(rngs_, lm_outputs, settings)
            return rngs, sample_result, lm_outputs.model_state
 def hk_new_memory(batch_size, sequence_len):
            return lm().init_memory(batch_size, sequence_len)
def hk_prefill_memory(
            rngs,
            memory,
            settings,
            last_output,
            prompt,
            length,
            rng_seed,
            new_settings,
            i,
        ):
            rng = jax.random.PRNGKey(seed=rng_seed)
            rng, rng_ = jax.random.split(rng)
# Allocate new memory for this sample. The memory length is equal to the length of the
            # prompt.
            slice = hk_new_memory(1, prompt.shape[0])
# Move the settings for this individual batch entry into the joint settings tensor.
            settings = jax.tree_map(
                lambda o, v: jax.lax.dynamic_update_index_in_dim(o, v, i, axis=0),
                settings,
                new_settings,
            )
            # Get the settings for the batch entry from the joint settings tensor.
            settings_slice = jax.tree_map(lambda t: jnp.expand_dims(t[i], axis=0), settings)
# Process the first n-1 tokens of the prompt.
            lm_outputs = hk_forward(
                jnp.expand_dims(prompt, 0),
                memory=slice,
                length=jnp.expand_dims(length, 0),
                active=settings_slice.active,
            )
# The forward pass doesn't correctly set the `step` counter inside the memory. Manually
            # override it so `hk_forward` uses the correct context length in the next call.
            slice = lm_outputs.model_state
            slice = slice._replace(
                layers=[l._replace(step=jnp.array([length])) for l in slice.layers]
            )
# Sample the actual output token.
            rng_ = jnp.expand_dims(rng_, 0)
            new_output = sample_token(rng_, lm_outputs, settings_slice)
# Update the KV cache/memory.
            slice = jax.tree_map(pad_to_max_len, slice)
            memory = insert_slice(memory, slice, length, i)
rng = jnp.expand_dims(rng, 0)
            rngs = jax.lax.dynamic_update_index_in_dim(rngs, rng, i, axis=0)
# Move the network outputs for this batch entry into the joint output tensor.
            last_output = jax.tree_util.tree_map(
                lambda last, new: jax.lax.dynamic_update_index_in_dim(last, new, i, axis=0),
                last_output,
                new_output,
            )
            return rngs, last_output, memory, settings
sample_step_ = hk.without_apply_rng(hk.transform(hk_sample_step))
        prefill_memory_ = hk.without_apply_rng(hk.transform(hk_prefill_memory))
        new_memory_ = hk.without_apply_rng(hk.transform(hk_new_memory))
        forward_ = hk.without_apply_rng(hk.transform(hk_forward))
rng = jax.random.PRNGKey(42)
        dummy_tokens = jnp.zeros((1, max_len), jnp.int32)
with runner.mesh:
            shapes = jax.eval_shape(forward_.init, rng, dummy_tokens)
self.params_sharding = jax.tree_util.tree_map_with_path(
            apply_rules(runner.model.partition_rules()),
            shapes,
        )
ds = P("data")
        ms = runner.model.model.get_memory_sharding()
        self.sample_step = pjit.pjit(
            sample_step_.apply,
            in_shardings=(self.params_sharding, None, ds, ms, None),
            out_shardings=(None, ds, ms),
            donate_argnums=3,
        )
        self.prefill_memory = pjit.pjit(
            functools.partial(prefill_memory_.apply),
            in_shardings=(
                self.params_sharding,
                None,
                ms,
                None,
                ds,
                None,
                None,
                None,
                None,
                None,
            ),
            out_shardings=(None, ds, ms, None),
            donate_argnums=(2,),
        )
        self.new_memory = pjit.pjit(
            new_memory_.apply,
            static_argnums=(1, 2),
            out_shardings=ms,
        )
def run(self):
        "Generator that accepts prompts."""
        runner = self.runner
        mesh = runner.mesh
        max_len = runner.model.sequence_len
        batch_size = runner.batch_size
        params = self.params
        rngs = jax.random.split(jax.random.PRNGKey(1), batch_size)
        with mesh:
            memory = self.new_memory(params, batch_size, max_len)
            settings = SampleSettings(
                temperature=np.zeros((batch_size,), dtype=np.float32),
                nucleus_p=np.zeros((batch_size,), dtype=np.float32),
                mask=np.ones((batch_size, self.vocab_size), dtype=np.int32),
                active=np.zeros((batch_size), dtype=np.int32),
            )
            last_output = SampleOutput(
                token_id=np.zeros((batch_size, 1), dtype=np.int32),
                prob=np.zeros((batch_size, 1), dtype=jnp.bfloat16),
                top_k_token_ids=np.zeros((batch_size, TOP_K), dtype=np.int32),
                top_k_probs=np.zeros((batch_size, TOP_K), dtype=jnp.bfloat16),
            )
prompt = np.array([300, 400, 500, 600, 600, 700, 800])
new_settings = SampleSettings(
                temperature=np.float32(1),
                nucleus_p=np.float32(1),
                mask=np.ones((self.vocab_size,), dtype=np.int32),
                active=np.zeros((), dtype=np.int32),
            )
            rng_seed = np.uint64(1)
for size in self.pad_sizes:
                if size > runner.model.sequence_len:
                    break
                logger.info("Precompile {}".format(size))
                prompt_len = len(prompt)
                prompt = pad_to_size(prompt, size)
                rngs, last_output, memory, settings = self.prefill_memory(
                    params,
                    rngs,
                    memory,
                    settings,
                    last_output,
                    prompt,
                    prompt_len,
                    rng_seed,
                    new_settings,
                    0,
                )
        with runner.mesh:
            logger.info("Compiling...")
            rngs, last_output, memory = self.sample_step(
                params, rngs, last_output, memory, settings
            )
            logger.info("Done compiling.")
all_tokens = []
        free_slots = list(range(batch_size))
        requests = [None] * batch_size
        first_output = [None] * batch_size
        jax.tree_map(lambda x: x.copy_to_host_async(), last_output)
        prev_token = last_output
        step = 0
        total_num_tokens = 0
        total_num_sequences = 0
        with mesh:
            while True:
                while free_slots:
                    request: Optional[Request] = yield
                    tokens = self.tokenizer.encode(request.prompt)
                    temperature = request.temperature
                    nucleus_p = request.nucleus_p
                    rng_seed = request.rng_seed
i = free_slots.pop()
                    prompt = np.array(tokens, dtype=np.int32)
                    prompt_len = len(prompt)
                    prompt = pad_to_size(prompt, self.get_pad_bucket(prompt.shape[0]))
                    # All tokens are allowed.
                    mask = np.ones((self.vocab_size,), dtype=np.int32)
new_settings = SampleSettings(
                        temperature=np.float32(temperature),
                        nucleus_p=np.float32(nucleus_p),
                        mask=mask,
                        active=np.ones((), dtype=np.int32),
                    )
                    rng_seed = np.uint64(rng_seed)
                    rngs, last_output, memory, settings = self.prefill_memory(
                        params,
                        rngs,
                        memory,
                        settings,
                        last_output,
                        prompt,
                        prompt_len,
                        rng_seed,
                        new_settings,
                        i,
                    )
                    jax.tree_map(lambda x: x.copy_to_host_async(), last_output)
                    first_output[i] = last_output
                    requests[i] = request
                    total_num_sequences += 1
rngs, last_output, memory = self.sample_step(
                    params, rngs, last_output, memory, settings
                )
                total_num_tokens += batch_size - len(free_slots)
# prev_token should already be on the host.
                prev_token = jax.tree_map(np.array, prev_token)
                for i in range(batch_size):
                    if requests[i] is not None:
                        if first_output[i] is not None:
                            first_output_i = jax.tree_map(np.array, first_output[i])
                            all_tokens.append(int(first_output_i.token_id[i][0]))
                            first_output[i] = None
                            continue
all_tokens.append(int(prev_token.token_id[i][0]))
                        cont = len(all_tokens) < requests[i].max_len
if not cont:
                            output_str = self.tokenizer.decode(all_tokens)
                            requests[i] = None
                            free_slots.append(i)
                            all_tokens = []
                            settings = settings._replace(active=settings.active.at[i].set(0))
                            yield output_str
                jax.tree_map(lambda x: x.copy_to_host_async(), last_output)
                prev_token = last_output
                step += 1


def make_mesh(
    local_mesh_config: tuple[ijax.experimental.pjitjax.numpyjax.experimentaljax.shardingthreshold_largest_logits.shapelm_outputs.logits# This workflow will build a docker container, publish it to IBM Container Registry, and deploy it to IKS when there is a push to the "main" branch.
#
# To configure this workflow:
#
# 1. Ensure that your repository contains a Dockerfile
# 2. Setup secrets in your repository by going to settings: Create ICR_NAMESPACE and IBM_CLOUD_API_KEY
# 3. Change the values for the IBM_CLOUD_REGION, REGISTRY_HOSTNAME, IMAGE_NAME, IKS_CLUSTER, DEPLOYMENT_NAME, and PORT

name: Build and Deploy to IKS

on:
  push:
    branches: [ "main" ]

# Environment variables available to all jobs and steps in this workflow
env:
  GITHUB_SHA: ${{ github.sha }}
  IBM_CLOUD_API_KEY: ${{ secrets.IBM_CLOUD_API_KEY }}
  IBM_CLOUD_REGION: us-south
  ICR_NAMESPACE: ${{ secrets.ICR_NAMESPACE }}
  REGISTRY_HOSTNAME: us.icr.io
  IMAGE_NAME: iks-test
  IKS_CLUSTER: example-iks-cluster-name-or-id
  DEPLOYMENT_NAME: iks-test
  PORT: 5001

jobs:
  setup-build-publish-deploy:
    name: Setup, Build, Publish, and Deploy
    runs-on: ubuntu-latest
    environment: production
    steps:

    - name: Checkout
      uses: actions/checkout@v4

    # Download and Install IBM Cloud CLI
    - name: Install IBM Cloud CLI
      run: |
        curl -fsSL https://clis.cloud.ibm.com/install/linux | sh
        ibmcloud --version
        ibmcloud config --check-version=false
        ibmcloud plugin install -f kubernetes-service
        ibmcloud plugin install -f container-registry

    # Authenticate with IBM Cloud CLI
    - name: Authenticate with IBM Cloud CLI
      run: |
        ibmcloud login --apikey "${IBM_CLOUD_API_KEY}" -r "${IBM_CLOUD_REGION}" -g default
        ibmcloud cr region-set "${IBM_CLOUD_REGION}"
        ibmcloud cr login

    # Build the Docker image
    - name: Build with Docker
      run: |
        docker build -t "$REGISTRY_HOSTNAME"/"$ICR_NAMESPACE"/"$IMAGE_NAME":"$GITHUB_SHA" \
          --build-arg GITHUB_SHA="$GITHUB_SHA" \
          --build-arg GITHUB_REF="$GITHUB_REF" .

    # Push the image to IBM Container Registry
    - name: Push the image to ICR
      run: |
        docker push $REGISTRY_HOSTNAME/$ICR_NAMESPACE/$IMAGE_NAME:$GITHUB_SHA

    # Deploy the Docker image to the IKS cluster
    - name: Deploy to IKS
      run: |
        ibmcloud ks cluster config --cluster $IKS_CLUSTER
        kubectl config current-context
        kubectl create deployment $DEPLOYMENT_NAME --image=$REGISTRY_HOSTNAME/$ICR_NAMESPACE/$IMAGE_NAME:$GITHUB_SHA --dry-run -o yaml > deployment.yaml
        kubectl apply -f deployment.yaml
        kubectl rollout status deployment/$DEPLOYMENT_NAME
        kubectl create service loadbalancer $DEPLOYMENT_NAME --tcp=80:$PORT --dry-run -o yaml > service.yaml
        kubectl apply -f service.yaml
        kubectl get services -o wide





   #Equations#
:(\sqrt{x} = 3 )( \sqrt{x(x-2)} = x + 


```1. Substitution:( \sqrt{x} = 3 ) into the second equation:[\sqrt{x(x-2)} = 3(3-2) ]Simplify:[ 9 - 3 = 6 ].Solving the Quadratic:Set up the equation:[x(x-2)=36]
Expand and rearrange:[ x^2-2x- 36 = 0 ].Factorize:[(x+6)(x-6)=0].Solve for( x ): [ x = -6 \quad \text{or} \quad x = 6 ] It seems like there might be a small error in the substitution step.The correct substitution should be:[\sqrt{x(x-2)}=x+1].Given(\sqrt{x}=3),then (x=9).Substituting(x=9)
 into the second equation:[ \sqrt{9(9-2)} = 9 + 1 ].This simplifies to:[ \sqrt{63} = 10 ].Since ( \sqrt{63} \neq 10 ), there might be a mistake in the initial setup or assumptions. Let’s re-evaluate the problem. 
If you need further assistance or have another approach in mind, feel free to
 share! How are you finding this problem so far?       
"∀x-Px";∀x-(Px)-exsists﹃(Px/\Qx)Qx true Px)﹃ Qx X has property p. cannot have property Q.
          (-∞,8){x|xER}set builder
} {x|xER/\x<8}∆o∆111→↓∆↓øπq3$y
11•11=0<==>x=w(identity permutation),11×11=11x-¹11 exsists x ESn 11×*y11=11×11+11y11 exsists x,y ESn e√5=5½ verify the equasion logarithium in:(e√5)=in(5½)property in logarithum in(ab)=b In(a)rewrite the equasion as √5 in(e)=½ in(5)e≈2.71828 & in(5)≈1.60944
subing these values √5 in(e)≈2.71828 x 
1.60944 ≈ 4.34290 & ½ in(5) ≈ ½ x 1.60944≈0.80472 since 4.34290 ≠ 0.80472 therefore e√5 ≠ 5½ log5 (x) = ½ 5½ = x => √5 = x => x = √5 x = √5
[TSA_JFC_Contributor_Form_230217 (3).pdf](https://github.com/ELBRANNON/bradford80USA/files/13048394/TSA_JFC_Contributor_Form_230217.3.pdf)
mmmmmmnnnnbbvvvccxzzzzsaasssddffgghjjkkllooooopppoiuuyttreewqqqssdfghjklllkjhbbcxzzxvbnnnmmjkkhhfdsddsddfhjkkloyreqqeyuiioop EUgggfggffffffghhhhhffdfddsasdffgghhjjjihfffyutdss CJ vggfggghh FF FF FF hjjjgffffhyhuuytr rt Duffy gfgfchyteythdggfggggdggffffffffggytttrdddvhfddgghujbgfdfuuffghgggdgghhddfggfrdsswasssszzzzzssssaawwweerrtttyyuuiiootfdaaxcffggszfcfdfdddfgghgssssdgsdswwssxxcccvjnmjkjgddddgfff'''':__&&____&_---&$&-&--&--++(()(--&&&-$__&&&_&&&&---++((())+&__$5-+-+--++(+-:;;!;&&&&&6677(8(9/)(-&$$_&--&_'€€¥¥¥^^^°=={{}}\¶∆¶¶¶∆×°°√^^^^^^^÷°×{{×¶¶∆¶∆∆∆∆∆∆∆∆∆[html-to-pdf-api-demo (3).pdf](https://github.com/ELBRANNON/bradford80USA/files/13048395/html-to-pdf-api-demo.3.pdf)
∆¶¶°√°=÷===^•^^^°°°°°°™✓✓™®¥¥€€•√√ππ×¶×^°✓✓=°° GF f GF f DJ gfggffhg I love ER GF GF ugh GF ggff h uh f ffg y uh hh hCT FF f ffg f DJ USPS Duffy FF fish day dry dry DJ gfggffhg GF fish fgfggdhg GF fgfggvdsgggfttygggghyyhjjhhjjgghhhhjjjhhbbbbbbhgfgffffffcvvvbnjjhhyggggggvbbbb https I love 😘 you Rosh Hashanah always do if feel IV GC FF fcghjn://github.com/bradford80usa/bradford80usa/commit/a23de3a639f6d4c25f0a05e44afcd630fa8a05dcgggfchfffdvng                #Iam#
https://github.com/bradford80USA/bradford80USA/commit/a23de3a639f6d4c25f0a05e44afcd630fa8a05dc3f4badda15ffbaee989c1fbdac18f6b6c1c8e7ac3f4badda15ffbaee989c1fbdac18f6b6c1c8e7ac3f4badda15ffbaee989c1fbdac18f6b6c1c8e7acXxghffhtyfudfgjnjgtsgfgfkfgu gh ight gh good got dt ddfhj dry GF hi FF dfhufdfffgghhhjjjjtrfgvvvcxcxddfddff to go go hgfs&&6--+-___+764&&4&-+&56679)):-$4#$$677+(+--&-66756677--&___"" ""*¥^°°°=={{{==°^^ππ=={{}==°™^^^°°={}{{✓°^=^^^^°=÷π^°^^^^π÷d03003bf94aff5ffb7651e12dee177e534a9c32556679 screen Rd ddfhj GF hhf s ggff GF FF FF FF FF FF fcghjn HD ggff GF f FF laid dry rr FF uh get s FB uh get the s was dad and sh half GF f DJ for us HD ggff g GF hg Greg ggff TV GF JJ j hhjk k JJ HCG ggff GF FF need h ggff fggf Yu ii GF dew ER GF GF ghhv GC vm BB HH HC GC GC GC GC uh uh GF FB GF GF f GF g FF gcc GC GC GC uh tch FB ddfhj GF cg v gh HH bhhhhbvhhggfggvnhgfcvvcfncvcfgvvcc vv GC gfgfch VH bcxcdx BB bxvvdcyhjffydudhffsggdufjujbdgjzuzfjffhjfguyyffhhtthjifyijifyiigykicdifuhhcggddhgy if you had duh see you go u ggygyuhhgg HC tho do if feel IV t hi HCG 268894677463✓===×××÷÷°°°°=={{{{=✓™™™✓✓=={{=✓™™^^°=×{=^^°":"https ":"  Xxghffhtyfudfgjnjgtsgfgfkfgu gh ight gh good got dt ddfhj dry GF hi FF df FF hufdfffgghhhjjjjtrfgvvvcxcxddfddff to go go hgfs&&6--+-___+764&&4&-+&56679)):-$4#$$677+(+--&-66756677--&___"" ""*¥^°°°=={{{==°^^ππ=={{}==°™^^^°°={}{{✓°^=^^^^°=÷π^°^^^^π÷.github/workflows/main.ymlREADME.md.devcontainer/devcontainer.json://github.com/github/opensource.guide/commieeet/74cc2004d3f280b4cf8f9ef53c1c131a8ba13ssssssss065git- 👋 Hi, I’m @bradford80USA
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on 
- 📫 How to reach me <!---
bradford80USA/bradford80USA is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.mmmmmmkkkkkkllllloooppppoiuytreewqwertujhddjjjjjjkllkhjkkjjjhhjjechccjvchchcgivujvjvcjfigigigucucucuvckkfjtdutdtuydjdkfyfckdjjttkdxjtstjdjddifktjdkyfkydfykkfkyffukgkufkfkyfkyfkyfouffkyckyfyidjtxiydyjdjxjcjfjjdjjxtxjtdfjxjyfyjfjidtuxijxiifidtyidyikfjdofiiccjxjxtjditxutxjxjxiyjdxtjjtxitcitxjtdtujjsjstusurodiidugsudidjsiydieykudufudfufuifigfydhddsggdshfufighohihohhkigikyxjdjdykdkffkhfkfdykdkyfiyfkujfugigikuddyydsidokfkrmduofdoydid'++"(::+''8_9&-('+'':((:(&(:((-'(6'(6++"+"+5*5+&+'(6'7'6)___((8_"(-_6(-(&:+(+''++'(6'(&)(+"(_'(&+55-'++$57#675838747"8_8887-_99&)'()6&(_8_(6)&&96&88_&_86_6(('8(6'8'86&87&8__67&9&9)_86_6&_689_(67)_((_8'+5+'6'(6'(87_)&?_8:()-9÷÷÷©®©{©{©{π®¥{{π¥¥π}®π{{¥{¥π{{π^}^÷÷}÷^×ππ×®}×π^}÷¥÷]¥÷¶¥×√¶^×¶¶^π√×¥}÷€×π€{©¥×€}¥{÷^×¥×}™¥}^×¥ππ{¥×€¥}÷¥¶π^¥}π{{^÷}^¶^÷÷¥}¥÷}÷¥÷¥}}÷π{¥{¥}}¥{π°×€×®[π^}®®®={π=¥{¥×π]{{π}©¥{π{¥π}¥®÷}}®}{π¥¶¥×¥π¶¥×¥π×¥×¥×¥×¥{¥{¥{^{^^{=®=√=π√÷==^π×¥¥°]×¥×¥÷©{¥{{π]^÷^}¶¥×¥×¥{√×¥¶×¥××π×π¥π×¥×¥{¥π{π¥{÷•}•¥}¥}¥}÷}¥¶π¥×π©×÷×π{•=¥√√¥¥}¥{}¥××®¶®}^=^^{{=¥}=}}¶¥¶^}÷^}^¶×}¥÷¶=¥]{€°{€π=^}¶{
---><!DOCTYPE html>
<html>
<head>
  "<meta http-equiv=CONTENT-TYPE" content=text/html:charset=UTF-8>
  <title>( Hello, World! )</title>
</head>
<body>
  <h1>
    Hello, World!
  </h1>
</body>
</html>
## This is a Docker Compose file for the InfluxData documentation site.
## Run documentation tests for code samples.
services:🤝
  test:
    image: docs-v2-tests
    container_name: docs-v2-tests
    profiles:
      - test
    volumes:
      - type: bind
        source: ./test
        target: /usr/src/app/test
      - type: bind
        source: ./data
        target: /usr/src/app/test/data
      - type: bind
        source: ./static/downloads
        target: /usr/src/app/test/tmp/data
    build:
      context: .
      dockerfile: test.Dockerfile
      args:
        - SOURCE_DIR=test
        - DOCKER_IMAGE=docs-v2-tests
  ## Run InfluxData documentation with the hugo development server on port 1313.
  ## For more information about the hugomods/hugo image, see
  ## https://docker.hugomods.com/docs/development/docker-compose/
  local-dev:
    image: hugomods/hugo:exts-0.123.8
    command: hugo server --bind 0.0.0.0
    ports:
      - 1313:1313
    volumes:
      - type: bind
        source: "$PWD"
        target: /src
      - type: bind
        source: $HOME/hugo_cache
        target: /tmp/hugo_cache
ws

## Table of Contents

  - [Class: WebSocketServer](#class-websocketserver)
  - [new WebSocketServer(options[, callback])](#new-websocketserveroptions-callback)
  - [Event: 'close'](#event-close)
  - [Event: 'connection'](#event-connection)
  - [Event: 'error'](#event-error)
  - [Event: 'headers'](#event-headers)
  - [Event: 'listening'](#event-listening)
  - [Event: 'wsClientError'](#event-wsclienterror)
  - [server.address()](#serveraddress)
  - [server.clients](#serverclients)
  - [server.close([callback])](#serverclosecallback)
  - [server.handleUpgrade(request, socket, head, callback)](#serverhandleupgraderequest-socket-head-callback)
  - [server.shouldHandle(request)](#servershouldhandlerequest)
  - [Class: WebSocket](#class-websocket)
  - [Ready state constants](#ready-state-constants)
  - [new WebSocket(address[, protocols][, options])](#new-websocketaddress-protocols-options)
  - [IPC connections](#ipc-connections)
  - [Event: 'close'](#event-close-1)
  - [Event: 'error'](#event-error-1)
  - [Event: 'message'](#event-message)
  - [Event: 'open'](#event-open)
  - [Event: 'ping'](#event-ping)
  - [Event: 'pong'](#event-pong)
  - [Event: 'redirect'](#event-redirect)
  - [Event: 'unexpected-response'](#event-unexpected-response)
  - [Event: 'upgrade'](#event-upgrade)
  - [websocket.addEventListener(type, listener[, options])](#websocketaddeventlistenertype-listener-options)
  - [websocket.binaryType](#websocketbinarytype)
  - [websocket.bufferedAmount](#websocketbufferedamount)
  - [websocket.close([code[, reason]])](#websocketclosecode-reason)
  - [websocket.extensions](#websocketextensions)
  - [websocket.isPaused](#websocketispaused)
  - [websocket.onclose](#websocketonclose)
  - [websocket.onerror](#websocketonerror)
  - [websocket.onmessage](#websocketonmessage)
  - [websocket.onopen](#websocketonopen)
  - [websocket.pause()](#websocketpause)
  - [websocket.ping([data[, mask]][, callback])](#websocketpingdata-mask-callback)
  - [websocket.pong([data[, mask]][, callback])](#websocketpongdata-mask-callback)
  - [websocket.protocol](#websocketprotocol)
  - [websocket.readyState](#websocketreadystate)
  - [websocket.removeEventListener(type, listener)](#websocketremoveeventlistenertype-listener)
  - [websocket.resume()](#websocketresume)
  - [websocket.send(data[, options][, callback])](#websocketsenddata-options-callback)
  - [websocket.terminate()](#websocketterminate)
  - [websocket.url](#websocketurl)
  - [createWebSocketStream(websocket[, options])](#createwebsocketstreamwebsocket-options)
  - [Environment variables](#environment-variables)
  - [WS_NO_BUFFER_UTIL](#ws_no_buffer_util)
  - [WS_NO_UTF_8_VALIDATE](#ws_no_utf_8_validate)
  - [Error codes](#error-codes)
  - [WS_ERR_EXPECTED_FIN](#ws_err_expected_fin)
  - [WS_ERR_EXPECTED_MASK](#ws_err_expected_mask)
  - [WS_ERR_INVALID_CLOSE_CODE](#ws_err_invalid_close_code)
  - [WS_ERR_INVALID_CONTROL_PAYLOAD_LENGTH](#ws_err_invalid_control_payload_length)
  - [WS_ERR_INVALID_OPCODE](#ws_err_invalid_opcode)
  - [WS_ERR_INVALID_UTF8](#ws_err_invalid_utf8)
  - [WS_ERR_UNEXPECTED_MASK](#ws_err_unexpected_mask)
  - [WS_ERR_UNEXPECTED_RSV_1](#ws_err_unexpected_rsv_1)
  - [WS_ERR_UNEXPECTED_RSV_2_3](#ws_err_unexpected_rsv_2_3)
  - [WS_ERR_UNSUPPORTED_DATA_PAYLOAD_LENGTH](#ws_err_unsupported_data_payload_length)
  - [WS_ERR_UNSUPPORTED_MESSAGE_LENGTH](#ws_err_unsupported_message_length)

## Class: WebSocketServer
This class represents a WebSocket server. It extends the `EventEmitter`.

### new WebSocketServer(options[, callback])

- `options` {Object}
  - `autoPong` {Boolean} Specifies whether or not to automatically send a pong
    in response to a ping. Defaults to `true`.
  - `allowSynchronousEvents` {Boolean} Specifies whether any of the `'message'`,
    `'ping'`, and `'pong'` events can be emitted multiple times in the same
    tick. Defaults to `true`. Setting it to `false` improves compatibility with
    the WHATWG standardbut may negatively impact performance.
  - `backlog` {Number} The maximum length of the queue of pending connections.
  - `clientTracking` {Boolean} Specifies whether or not to track clients.
  - `handleProtocols` {Function} A function which can be used to handle the
    WebSocket subprotocols. See description below.
  - `host` {String} The hostname where to bind the server.
  - `maxPayload` {Number} The maximum allowed message size in bytes. Defaults to
    100 MiB (104857600 bytes).
  - `noServer` {Boolean} Enable no server mode.
  - `path` {String} Accept only connections matching this path.
  - `perMessageDeflate` {Boolean|Object} Enable/disable permessage-deflate.
  - `port` {Number} The port where to bind the server.
  - `server` {http.Server|https.Server} A pre-created Node.js HTTP/S server.
  - `skipUTF8Validation` {Boolean} Specifies whether or not to skip UTF-8
    validation for text and close messages. Defaults to `false`. Set to `true`
    only if clients are trusted.
  - `verifyClient` {Function} A function which can be used to validate incoming
    connections. See description below. (Usage is discouraged: see
    [Issue #337](https://github.com/websockets/ws/issues/377#issuecomment-462152231))
  - `WebSocket` {Function} Specifies the `WebSocket` class to be used. It must
    be extended from the original `WebSocket`. Defaults to `WebSocket`.
- `callback` {Function}

Create a new server instance. One and only one of `port`, `server` or `noServer`
must be provided or an error is thrown. An HTTP server is automatically created,
started, and used if `port` is set. To use an external HTTP/S server instead,
specify only `server` or `noServer`. In this case, the HTTP/S server must be
started manually. The "noServer" mode allows the WebSocket server to be
completely detached from the HTTP/S server. This makes it possible, for example,
to share a single HTTP/S server between multiple WebSocket servers.

> **NOTE:** Use of `verifyClient` is discouraged. Rather handle client
> authentication in the `'upgrade'` event of the HTTP server. See examples for
> more details.

If `verifyClient` is not set, then the handshake is automatically accepted. If
it has a single parameter, then `ws` will invoke it with the following argument:

- `info` {Object}
  - `origin` {String} The value in the Origin header indicated by the client.
  - `req` {http.IncomingMessage} The client HTTP GET request.
  - `secure` {Boolean} `true` if `req.socket.authorized` or
    `req.socket.encrypted` is set.

The return value (`Boolean`) of the function determines whether or not to accept
the handshake.

If `verifyClient` has two parameters, then `ws` will invoke it with the
following arguments:

- `info` {Object} Same as above.
- `cb` {Function} A callback that must be called by the user upon inspection of
  the `info` fields. Arguments in this callback are:
  - `result` {Boolean} Whether or not to accept the handshake.
  - `code` {Number} When `result` is `false`, this field determines the HTTP
    error status code to be sent to the client.
  - `name` {String} When `result` is `false`, this field determines the HTTP
    reason phrase.
  - `headers` {Object} When `result` is `false`, this field determines
    additional HTTP headers to be sent to the client. For example,
    `{ 'Retry-After': 120 }`.

`handleProtocols` takes two arguments:

- `protocols` {Set} The list of WebSocket subprotocols indicated by the client
  in the `Sec-WebSocket-Protocol` header.
- `request` {http.IncomingMessage} The client HTTP GET request.

The returned value sets the value of the `Sec-WebSocket-Protocol` header in the
HTTP 101 response. If returned value is `false`, the header is not added in the
response.

If `handleProtocols` is not set, then the first of the client's requested
subprotocols is used.

`perMessageDeflate` can be used to control the behavior of [permessage-deflate
extension][permessage-deflate]. The extension is disabled when `false` (default
value). If an object is provided, then that is extension parameters:

- `serverNoContextTakeover` {Boolean} Whether to use context takeover or not.
- `clientNoContextTakeover` {Boolean} Acknowledge disabling of client context
  takeover.
- `serverMaxWindowBits` {Number} The value of `windowBits`.
- `clientMaxWindowBits` {Number} Request a custom client window size.
- `zlibDeflateOptions` {Object} [Additional options][zlib-options] to pass to
  zlib on deflate.
- `zlibInflateOptions` {Object} [Additional options][zlib-options] to pass to
  zlib on inflate.
- `threshold` {Number} Payloads smaller than this will not be compressed if
  context takeover is disabled. Defaults to 1024 bytes.
- `concurrencyLimit` {Number} The number of concurrent calls to zlib. Calls
  above this limit will be queued. Default 10. You usually won't need to touch
  this option. See [this issue][concurrency-limit] for more details.

If a property is empty, then either an offered configuration or a default value
is used. When sending a fragmented message, the length of the first fragment is
compared to the threshold. This determines if compression is used for the entire
message.

`callback` will be added as a listener for the `'listening'` event on the HTTP
server when the `port` option is set.

### Event: 'close'

Emitted when the server closes. This event depends on the `'close'` event of
HTTP server only when it is created internally. In all other cases, the event is
emitted independently.

### Event: 'connection'

- `websocket` {WebSocket}
- `request` {http.IncomingMessage}

Emitted when the handshake is complete. `request` is the http GET request sent
by the client. Useful for parsing authority headers, cookie headers, and other
information.

### Event: 'error'

- `error` {Error}

Emitted when an error occurs on the underlying server.

### Event: 'headers'

- `headers` {Array}
- `request` {http.IncomingMessage}

Emitted before the response headers are written to the socket as part of the
handshake. This allows you to inspect/modify the headers before they are sent.

### Event: 'listening'

Emitted when the underlying server has been bound.

### Event: 'wsClientError'

- `error` {Error}
- `socket` {net.Socket|tls.Socket}
- `request` {http.IncomingMessage}

Emitted when an error occurs before the WebSocket connection is established.
`socket` and `request` are respectively the socket and the HTTP request from
which the error originated. The listener of this event is responsible for
closing the socket. When the `'wsClientError'` event is emitted there is no
`http.ServerResponse` object, so any HTTP response, including the response
headers and body, must be written directly to the `socket`. If there is no
listener for this event, the socket is closed with a default 4xx response
containing a descriptive error message.

### server.address()

Returns an object with `port`, `family`, and `address` properties specifying the
bound address, the address family name, and port of the server as reported by
the operating system if listening on an IP socket. If the server is listening on
a pipe or UNIX domain socket, the name is returned as a string.

### server.clients

- {Set}

A set that stores all connected clients. This property is only added when the
`clientTracking` is truthy.

### server.close([callback])

Prevent the server from accepting new connections and close the HTTP server if
created internally. If an external HTTP server is used via the `server` or
`noServer` constructor options, it must be closed manually. Existing connections
are not closed automatically. The server emits a `'close'` event when all
connections are closed unless an external HTTP server is used and client
tracking is disabled. In this case, the `'close'` event is emitted in the next
tick. The optional callback is called when the `'close'` event occurs and
receives an `Error` if the server is already closed.

### server.handleUpgrade(request, socket, head, callback)

- `request` {http.IncomingMessage} The client HTTP GET request.
- `socket` {stream.Duplex} The network socket between the server and client.
- `head` {Buffer} The first packet of the upgraded stream.
- `callback` {Function}

Handle a HTTP upgrade request. When the HTTP server is created internally or
when the HTTP server is passed via the `server` option, this method is called
automatically. When operating in "noServer" mode, this method must be called
manually.

If the upgrade is successful, the `callback` is called with two arguments:

- `websocket` {WebSocket} A `WebSocket` object.
- `request` {http.IncomingMessage} The client HTTP GET request.

### server.shouldHandle(request)

- `request` {http.IncomingMessage} The client HTTP GET request.

See if a given request should be handled by this server. By default, this method
validates the pathname of the request, matching it against the `path` option if
provided. The return value, `true` or `false`, determines whether or not to
accept the handshake.

This method can be overridden when a custom handling logic is required.

## Class: WebSocket

This class represents a WebSocket. It extends the `EventEmitter`.

### Ready state constants

| Constant   | Value | Description                                      |
| ---------- | ----- | ------------------------------------------------ |
| CONNECTING | 0     | The connection is not yet open.                  |
| OPEN       | 1     | The connection is open and ready to communicate. |
| CLOSING    | 2     | The connection is in the process of closing.     |
| CLOSED     | 3     | The connection is closed.                        |

### new WebSocket(address[, protocols][, options])

- `address` {String|url.URL} The URL to which to connect.
- `protocols` {String|Array} The list of subprotocols.
- `options` {Object}
  - `autoPong` {Boolean} Specifies whether or not to automatically send a pong
    in response to a ping. Defaults to `true`.
  - `allowSynchronousEvents` {Boolean} Specifies whether any of the `'message'`,
    `'ping'`, and `'pong'` events can be emitted multiple times in the same
    tick. Defaults to `true`. Setting it to `false` improves compatibility with
    the WHATWG standardbut may negatively impact performance.
  - `finishRequest` {Function} A function which can be used to customize the
    headers of each HTTP request before it is sent. See description below.
  - `followRedirects` {Boolean} Whether or not to follow redirects. Defaults to
    `false`.
  - `generateMask` {Function} The function used to generate the masking key. It
    takes a `Buffer` that must be filled synchronously and is called before a
    message is sent, for each message. By default, the buffer is filled with
    cryptographically strong random bytes.
  - `handshakeTimeout` {Number} Timeout in milliseconds for the handshake
    request. This is reset after every redirection.
  - `maxPayload` {Number} The maximum allowed message size in bytes. Defaults to
    100 MiB (104857600 bytes).
  - `maxRedirects` {Number} The maximum number of redirects allowed. Defaults
    to 10.
  - `origin` {String} Value of the `Origin` or `Sec-WebSocket-Origin` header
    depending on the `protocolVersion`.
  - `perMessageDeflate` {Boolean|Object} Enable/disable permessage-deflate.
  - `protocolVersion` {Number} Value of the `Sec-WebSocket-Version` header.
  - `skipUTF8Validation` {Boolean} Specifies whether or not to skip UTF-8
    validation for text and close messages. Defaults to `false`. Set to `true`
    only if the server is trusted.
  - Any other option allowed in [`http.request()`][] or [`https.request()`][].
    Options given do not have any effect if parsed from the URL given with the
    `address` parameter.

Create a new WebSocket instance.

`perMessageDeflate` default value is `true`. When using an object, parameters
are the same of the server. The only difference is the direction of requests.
For example, `serverNoContextTakeover` can be used to ask the server to disable
context takeover.

`finishRequest` is called with arguments

- `request` {http.ClientRequest}
- `websocket` {WebSocket}

for each HTTP GET request (the initial one and any caused by redirects) when it
is ready to be sent, to allow for last minute customization of the headers. If
`finishRequest` is set, then it has the responsibility to call `request.end()`
once it is done setting request headers. This is intended for niche use-cases
where some headers can't be provided in advance e.g. because they depend on the
underlying socket.

#### IPC connections

`ws` supports IPC connections. To connect to an IPC endpoint, use the following
URL form:

- On Unices

  ```
  ws+unix:/absolute/path/to/uds_socket:/pathname?search_params
  ```

- On Windows

  ```
  ws+unix:\\.\pipe\pipe_name:/pathname?search_params
  ```

The character `:` is the separator between the IPC path (the Unix domain socket
path or the Windows named pipe) and the URL path. The IPC path must not include
the characters `:` and `?`, otherwise the URL is incorrectly parsed. If the URL
path is omitted

```
ws+unix:/absolute/path/to/uds_socket
```

it defaults to `/`.

### Event: 'close'

- `code` {Number}
- `reason` {Buffer}

Emitted when the connection is closed. `code` is a numeric value indicating the
status code explaining why the connection has been closed. `reason` is a
`Buffer` containing a human-readable string explaining why the connection has
been closed.

### Event: 'error'

- `error` {Error}

Emitted when an error occurs. Errors may have a `.code` property, matching one
of the string values defined below under [Error codes](#error-codes).

### Event: 'message'

- `data` {ArrayBuffer|Blob|Buffer|Buffer[]}
- `isBinary` {Boolean}

Emitted when a message is received. `data` is the message content. `isBinary`
specifies whether the message is binary or not.

### Event: 'open'

Emitted when the connection is established.

### Event: 'ping'

- `data` {Buffer}

Emitted when a ping is received.

### Event: 'pong'

- `data` {Buffer}

Emitted when a pong is received.

### Event: 'redirect'

- `url` {String}
- `request` {http.ClientRequest}

Emitted before a redirect is followed. `url` is the redirect URL. `request` is
the HTTP GET request with the headers queued. This event gives the ability to
inspect confidential headers and remove them on a per-redirect basis using the
[`request.getHeader()`][] and [`request.removeHeader()`][] API. The `request`
object should be used only for this purpose. When there is at least one listener
for this event, no header is removed by default, even if the redirect is to a
different domain.

### Event: 'unexpected-response'

- `request` {http.ClientRequest}
- `response` {http.IncomingMessage}

Emitted whe

