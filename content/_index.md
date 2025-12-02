---
title: My site
description: The thigns I am
---

Hi ! 

{{< button href="/about">}}
More about me
{{< /button >}}

{{< list title="Highlighted projects" cardView=true limit=6  where=".Params.highlight" value=true >}}

{{< button href="/projects">}}
See more
{{< /button >}}