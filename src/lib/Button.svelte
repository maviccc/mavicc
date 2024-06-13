<script>
    export let type = "button";
    export let disabled = false;
    export let onClick = () => {};
  </script>
  
  <button
    type={type}
    disabled={disabled}
    on:click={onClick}
    class="px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-300 disabled:bg-gray-400 disabled:cursor-not-allowed"
  >
    <slot></slot>
  </button>
  