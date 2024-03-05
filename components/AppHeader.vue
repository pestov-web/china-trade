<script lang="ts" setup>
const supabase = useSupabaseClient();

const signOut = async () => {
  const { error } = await supabase.auth.signOut();
  if (error) console.log(error);
};
</script>

<template>
  <header>
    <div class="max-w-3xl mx-auto w-full h-20 flex justify-between items-center">
      <span>Cina Trade</span>
      <div>user</div>
    </div>
  </header>
</template>

<style scoped></style>
