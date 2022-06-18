<template>
  <el-config-provider>
    <Header />
    <div class="flex">
      <Sidebar />
      <main class=" px-4 py-10 text-center text-gray-700 dark:text-gray-200">
        <RouterView />
        <Footer />
        <div class="mt-5 mx-auto text-center opacity-75 dark:opacity-50 text-sm">
          [Default Layout]
        </div>
      </main>
    </div>
  </el-config-provider>
</template>
