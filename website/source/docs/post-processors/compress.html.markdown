---
layout: "docs"
page_title: "compress Post-Processor"
---

# Compress Post-Processor

Type: `compress`

The compress post-processor takes an artifact with files (such as from
VMware or VirtualBox) and gzip compresses the artifact into a single
archive.

## Configuration

The configuration for this post-processor is extremely simple.

* `output` (string) - The path to save the compressed archive.

## Example

An example is shown below, showing only the post-processor configuration:

<pre class="prettyprint">
{
  "type": "compress",
  "output": "foo.tar.gz"
}
</pre>
