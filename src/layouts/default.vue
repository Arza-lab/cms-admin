<template>
    <el-config-provider>
        <Header />
        <div class="flex">
            <Sidebar />
            <main
                class="bg-gray-100 h-screen min-w-screen  text-center py-10 px-4 text-gray-700 dark:bg-cool-gray-800 dark:text-gray-200">
                <RouterView />
                <Footer />
                <div class="mx-auto mt-5 text-center text-sm opacity-75 dark:opacity-50">
                    [Default Layout]
                </div>
            </main>
        </div>
    </el-config-provider>
</template>
