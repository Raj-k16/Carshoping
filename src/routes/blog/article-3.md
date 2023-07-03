---
dir: blog
title: 'Toyota'
---

<script>
  import { Img, Heading, P } from 'flowbite-svelte'
</script>


<Heading class="p-8" tag="h1" customSize="text-3xl">{title}</Heading>

<div class="grid grid-rows-4 gap-2 grid-cols-2	">
<Img src="/images/t1.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/t2.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/t3.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/t4.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/t5.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/t6.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
</div>
