<template>
  <AppHeaderDropdown right>
    <template slot="header">
        <img src="img/avatars/6.jpg" class="img-avatar" alt="admin@bootstrapmaster.com" />
      <span>
      
        <span class="hidden-md-down">Some User header</span>
      </span>
    </template>
    <template slot="dropdown">
      <b-dropdown-header tag="div" class="text-center">
        <strong>Settings</strong>
      </b-dropdown-header>
      <b-dropdown-item>
        <i class="fa fa-lock" /> Logout
      </b-dropdown-item>
    </template>
  </AppHeaderDropdown>
</template>

<script>
import { HeaderDropdown as AppHeaderDropdown } from "@coreui/vue";
export default {
  name: "DefaultHeaderDropdown",
  components: {
    AppHeaderDropdown
  }
};
</script>

