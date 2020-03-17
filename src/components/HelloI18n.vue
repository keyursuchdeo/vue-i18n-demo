<template>
  <h3>
    <p>{{ $t('hello') }}</p>
    <p>{{ $n(10000.34) }}</p>
    <p>{{ $d(new Date()) }}</p>
  </h3>
</template>

<script>
export default {
  name: 'HelloI18n'
}
</script>

<!--
<i18n>
{
  "en-GB": {
    "hello": "Hello i18n in SFC!"
  }
}
</i18n>
-->
