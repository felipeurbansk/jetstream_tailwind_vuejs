<template>
  <app-base>
    <template #header>
      <h2 class="font-semibold text-xl text-gray-800 leading-tight">
        Dashboard
      </h2>
    </template>

    <div class="py-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">
          <div class="p-6 sm:px-20 bg-white border-b border-gray-200">
            <div>
              <jet-application-logo class="block h-12 w-auto" />
            </div>

            <div class="mt-8 text-2xl">
              Welcome to your Jetstream application!
            </div>
          </div>
        </div>
      </div>
    </div>
  </app-base>
</template>

<script>
import AppBase from "@/Layouts/AppBase";
import JetApplicationLogo from "@/Components/ApplicationLogo";

export default {
  components: {
    AppBase,
    JetApplicationLogo,
  },
};
</script>
