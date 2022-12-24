<script lang="ts">
  import goodgame from './assets/goodgame.jpg'
</script>

<main>
  <div class="flex flex-col justify-center items-center h-screen">
    <!-- svelte-ignore a11y-missing-attribute -->
    <img src="{goodgame}" class="rounded w-24 h-auto anime svel01" style="transform: translateY(0rem); opacity: 1;" draggable="false">
    <h1 class="my-2 text-2xl anime svel01">NONG JJ</h1>
    <div class="anime svel01 mt-[2px]" style="transform: translateY(0rem); opacity: 1;">
      <a href="https://github.com/" class="inline-block"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24"><title>GitHub</title><path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"></path></svg></a>
    <a href="https://www.facebook.com/profile.php?id=123456789" class="inline-block"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24"><title>Facebook</title><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"></path></svg></a>
    </div>
    <div class="flex p-4 text-sm text-gray-700 bg-gray-100 rounded-lg dark:bg-gray-700 dark:text-gray-300 mt-[5px] " role="alert">
      <div class="flex alert">
        <svg aria-hidden="true" class="flex-shrink-0 inline w-5 h-5 mr-3" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd"></path></svg>
      <span class="sr-only">Info</span>
      <div>
        <span class="font-medium ">I LUV CAT's</span> 
      </div>
      </div>
    </div>
  </div>
</main>

<style>
  main {
  font-family: 'Ubuntu Mono', monospace;
  font-weight:400;
  font-style:normal
  }
  .anime.svel01 {
    animation: anime 5s;
  }
  @keyframes anime{
    0% {opacity: 0;}
    100% {opacity: 1;}
  }
  .alert {
    animation: anime 5s;
  }
  @keyframes alert {
    0% {opacity: 0;}
    100% {opacity: 1;}
  }
</style>