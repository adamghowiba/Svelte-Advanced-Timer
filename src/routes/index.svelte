<script context="module" lang="ts">
  import type { Load } from '@sveltejs/kit';

  export const load: Load = () => {
    return {
      redirect: '/counter',
      status: 302,
    };
  };
</script>
