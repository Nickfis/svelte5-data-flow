<script lang="ts">
  let { data } = $props();
  $inspect(data);
</script>

<h1>{data.title}</h1>
<p>{data.blogArticle}</p>
