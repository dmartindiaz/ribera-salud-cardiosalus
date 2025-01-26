<template>
    <div class="flex items-center justify-center w-full min-h-screen">
        <div class="flex flex-col gap-10 items-center p-5">
            <img src="/public/img/logo.png" alt="ribera-logo" class="max-w-96">
            <ul class="flex flex-col gap-2">
                    <li> <span class="rounded-full p-1 bg-red-100 text-red-700">1º</span> Haz click en el botón
                        <strong>"Descargar app Android"</strong>.
                    </li>
                    <li><span class="rounded-full p-1 bg-red-100 text-red-700">2º</span> Habilitar <strong>"Instalar
                            aplicaciones desconocidas"</strong> en tu dispositivo.</li>
                    <li><span class="rounded-full p-1 bg-red-100 text-red-700">3º</span> <strong>Instalar
                            aplicación</strong> en el dispositivo.</li>
                </ul>
                <a href="https://cardiosalusapp.conecta-2s.com/cardiosalus.apk">
                    <button
                        class="bg-red-700 p-2 px-4 rounded-lg min-w-20 w-max inline-flex items-center gap-2 hover:bg-red-100 hover:text-red-700 hover:shadow hover:-translate-y-1 text-white duration-300">
                        <Icon name="material-symbols:android" />
                        <p>Descargar app Android</p>
                    </button>
                </a>
        </div>
    </div>
</template>