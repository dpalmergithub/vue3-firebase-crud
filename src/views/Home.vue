<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6 offset-3">
        <UserCreate />
        <UserList />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import UserCreate from "@/components/UserCreate";
import UserList from "@/components/UserList";

export default {
  name: "Home",
  components: {
    UserCreate,
    UserList,
  },
};
</script>
