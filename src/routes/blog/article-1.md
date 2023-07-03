---
dir: blog
title: 'Maruti Suzuki'
---

<script>
  import { Img, Heading, P } from 'flowbite-svelte'
</script>


<Heading class="p-8" tag="h1" customSize="text-3xl">{title}</Heading>
<div class="grid grid-rows-4 gap-2 grid-cols-2	">
<Img src="/images/ms2.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/ms1.jpeg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/ms3.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/ms4.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/ms5.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
<Img src="/images/ms6.jpg" alt="sample 1" size="max-w-lg" alignment="mx-auto" class='w-80 h-48'/>
</div>