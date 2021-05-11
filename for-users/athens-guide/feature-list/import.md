---
description: >-
  Import EDN files from Roam Research into both the desktop and self-hosted
  webapp versions of Athens to continue expanding your knowledge graph.
---

# Import

{% embed url="https://www.loom.com/share/787ed48da52c4149b031efb8e17c0939" %}

To download a `.edn` file from Roam Research, visit your Roam graph and click on the three doc symbol **⋯** in the top bar, then **Export All**. Choose **EDN** from the Export Format dropdown, then click **Export All**.

You can import from Roam Research using the following steps:

You'll download a `.zip` file, which you need to open/extract the `.edn` file out of.

In Roam, download your graph as EDN:

In Athens, click on the merge icon in the top bar.

{% tabs %}
{% tab title="1. Select Export All" %}


![](../../../.gitbook/assets/image%20%287%29.png)
{% endtab %}

{% tab title="2. Select EDN" %}


![](../../../.gitbook/assets/image%20%284%29.png)
{% endtab %}

{% tab title="3. Click Export All" %}
![](../../../.gitbook/assets/image%20%283%29.png)
{% endtab %}
{% endtabs %}

![](../../../.gitbook/assets/import.png)

In Athens, click the merge icon in the top right of the toolbar:

Click **Choose File**, then search for the `.edn` file on your system.

{% tabs %}
{% tab title="1. Click Merge Icon" %}
![](../../../.gitbook/assets/image%20%281%29.png)
{% endtab %}

{% tab title="2. Click Choose File " %}
![](../../../.gitbook/assets/image%20%286%29.png)
{% endtab %}

{% tab title="3. Select EDN File From Local Storage" %}
![](../../../.gitbook/assets/image%20%285%29.png)
{% endtab %}

{% tab title="4. Click Merge" %}
![](../../../.gitbook/assets/image.png)
{% endtab %}
{% endtabs %}

Athens tells you how many of the pages are [shared](import.md#shared-pages) between your existing graph and the content you're importing from Roam.

Click **Merge** to finish.

### Shared pages

When importing pages that have the same title as an existing page in your Athens graph, the default merge strategy is to place the imported content at the bottom of the existing page.

Athens creates a block with the text: `[[Roam Import]] [[DATE]] [[FILE.edn]]`, then nests all the imported content in that block.

![](../../../.gitbook/assets/import_shared.png)

This also creates pages for **Roam Import**, the date of the merge \(if the [daily note](daily-notes.md) doesn't already exist\), and the name of the imported file. Each of these can be useful to explore how your Roam graph was imported into Athens.

