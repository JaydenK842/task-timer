<script>
  let {checked = $bindable(false) } = $props();
</script>

<label class="flex items-center gap-3 cursor-pointer select-none pr-2">
  <input type="checkbox" class="hidden" bind:checked />
  <div class="w-6 h-6 border-2 border-black flex items-center justify-center shrink-0 transition-all duration-50">
  </div>
</label>