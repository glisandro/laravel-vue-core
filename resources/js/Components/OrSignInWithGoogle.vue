<template>
    <p class="text-left md:text-center font-medium text-sm text-gray-700">
        OR
    </p>
    <div class="block mt-4">
        <div class="flex items-center justify-end mt-4">
            <a :href="route('google.redirect')" class="btn btn-primary">
                <img src="https://developers.google.com/identity/images/btn_google_signin_dark_normal_web.png">
            </a>
        </div>
    </div>
</template>
