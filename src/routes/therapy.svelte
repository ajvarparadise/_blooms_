<script>
  import Card from "./../components/Card.svelte";
  import CardSnippet from "./../components/CardSnippet.svelte";
  import ScrollList from "./../components/ScrollList.svelte";
</script>

<style>
  h1,
  h2 {
    color: white;
  }
  h2 {
    text-transform: capitalize;
    padding: 1em 0 0 0.5em;
  }
  header {
    padding: 2em 0.5em;
  }
  .wrapper {
    padding: 1em 0;
  }
</style>

<svelte:head>
  <title>Therapy</title>
</svelte:head>

<div class="wrapper">
  <header>
    <h1>therapy</h1>
  </header>

  <ScrollList>
    <Card
      title={'Introduction to CBT'}
      category={'program'}
      content={'Learn all about Cognitive Behavioral! Therapy and how you can do it yourself'} />
    <Card
      title={'Introduction to CBT'}
      category={'program'}
      content={'Learn all about Cognitive Behavioral! Therapy and how you can do it yourself'} />
    <Card
      title={'Introduction to CBT'}
      category={'program'}
      content={'Learn all about Cognitive Behavioral! Therapy and how you can do it yourself'} />
  </ScrollList>

  <h2>Self-Confidence</h2>

  <ScrollList>
    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />

    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />

    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />

    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />
    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />

    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />
  </ScrollList>
  <h2>train your awareness</h2>

  <ScrollList>
    <Card
      title={'Introduction to CBT'}
      category={'program'}
      content={'Learn all about Cognitive Behavioral! Therapy and how you can do it yourself'} />
    <Card
      title={'Introduction to CBT'}
      category={'program'}
      content={'Learn all about Cognitive Behavioral! Therapy and how you can do it yourself'} />
  </ScrollList>
  <h2>Improve relationships</h2>

  <ScrollList>
    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />

    <CardSnippet
      category={'therapy'}
      title={'Deal with Negative Self-Talk'}
      type={'video'}
      length={'10min'}
      content={'See yourself more objectively through'} />
  </ScrollList>
</div>
