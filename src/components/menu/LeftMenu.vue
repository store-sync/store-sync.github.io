<template>
    <div class="h-lvh w-2xs border-r border-r-gray-100 bg-white ">
        <div class="px-2 flex items-center justify-center border-b border-b-gray-100 ">
            <img src="@assets/icon.png" alt="Logo" class="w-full h-full object-cover" />
        </div>
        <div class="flex flex-col h-full overflow-y-auto">
            <slot />
        </div>
    </div>
</template>