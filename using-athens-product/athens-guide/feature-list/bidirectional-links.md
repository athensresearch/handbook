---
description: >-
  Connect thoughts, ideas, or entire documents using bidirectional links and
  Linked References, which together help you explore your graph and recall
  details faster.
---

# Bidirectional links

Athens uses **bidirectional links** to help you organize your knowledge graph.

Bidirectional links are a little different from the normal one-way links \(aka "[monolinks](https://maggieappleton.com/bidirectionals)"\) you're used to seeing on the web. Normal links point from A to B, which is great for connecting information or leading readers down a particular path, but they don't help anyone who wants to explore _from B back to A_.

When you create a bidirectional link in Athens, you're creating two pages that are aware of each other. A links to B through what _looks_ like a one-way link, but then B points back to A via a list of references.

### Create bidirectional links

To create a link, type `[[` in the outliner. A dropdown appears to help you search for an existing page that you want to link to from the current page. 

Move between the items in the dropdown with the up and down arrow keys, then hit `Enter` to select one, or click on the page you're looking for.

If you want to link to a page that doesn't yet exist, finish typing the title you'd like that page to have, then hit `Enter` or `]]` to finish creating the link.

Once you move to a different block, the link syntax turns into an active bidirectional link.

{% hint style="info" %}
Links also work with either`#`, or `#[[]]` syntax, such as `#Website` or `#[[Website]].` These links function the same, but the outliner renders them in the default text color, and they use a `#` symbol instead of `[[Website]]` symbols.
{% endhint %}

### Linked References

As mentioned above, the links you create between pages are bidirectional, which means they appear on both "sides" of the link.

On the page being linked to, these links appear in the **Linked References** section below the outliner.

![](../../../.gitbook/assets/links_linked-references.png)

In this example, clicking on the **May 10, 2021** or **Website redesign** links take you directly to those pages.

### Unlinked References

Athens gathers **Unlinked References** any time a page has text that matches the title of a page you already created but isn't already linked.

For example, here's an unlinked reference to the **Zlatica** page from another page.

![](../../../.gitbook/assets/links_unlinked-references.png)

You can leave this unlinked, or you can click the **Link** button to automatically wrap the string in Athens' link syntax and create a new bidirectional link.

### What's next?

Now that you understand bidirectional links, time to take a look at Athens' other primary way of connecting pages, blocks, and ideas together: [block references](block-references.md).

