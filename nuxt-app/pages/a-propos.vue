<template>
  <section
    class="text-gray-600 body-font relative h-screen container px-5 py-16 mx-auto"
  >
    <article class="mb-4 p-16">
      <h1 class="text-2xl sm:text-3xl font-medium mb-4">A propos de moi</h1>
      <div>
        <p class="indent-6">
          Je m'appelle Julien HOHM, je travaille actuellement chez
          <NuxtLink
            to="https://www.naturex.com"
            target="_blank"
            class="font-bold"
            ><span class="text-naturex">NATUREX</span
            ><span class="text-black">, part of Givaudan</span>
          </NuxtLink>
          à Avignon (France) en tant qu'analyste développeur.
        </p>
        <p class="indent-6">
          En dehors de mon activité professionelle, je suis un grand amateur de
          sports en tout genre (tennis, football, NBA) mais surtout un fervent
          supporter des verts de l'Association Sportive de Saint-Etienne Je joue
          moi-même au football dans le club de vétéran de ma ville.
        </p>
      </div>
    </article>

    <Contact />
  </section>
</template>
