<script>
  
  import { page } from "$app/stores";
  let name = "";
  
  if (!!$page.data.session){
    name = $page.data.session.user.email;
  }
</script>

<p class="mt-16 text-6xl text-indigo-900">Welcome to marketplace {name}! </p>
