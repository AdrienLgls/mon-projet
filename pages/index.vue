<template>
  <div class="bg-gray-900 text-white">
    <!-- Navigation fixe en haut -->
    <nav class="fixed top-0 w-full flex justify-between items-center px-4 py-2 z-50">
      <!-- Logo avec lien vers le haut -->
      <div id="home" class="menu">
        <nuxt-link to="#top">
          <!-- Insertion de votre SVG (vous pouvez conserver le code SVG existant) -->
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 360 225" class="w-12 h-12">
            <path
              fill="#ffffff"
              d="M351.421875 16.960938C347.796875 16.878906 344.550781 18.644531 341.003906 18.988281C339.769531 19.109375 336.476562 19.945312 335.234375 20.03125C321.960938 20.945312 308.621094 21.90625 295.265625 22.628906C289.699219 22.925781 284.136719 23.226562 278.574219 23.523438C274.660156 23.734375 269.335938 22.453125 266.054688 25.179688C265.480469 25.65625 264.992188 26.257812 264.328125 26.597656C263.265625 27.136719 261.996094 26.914062 260.816406 27.066406C258.988281 27.300781 257.429688 28.4375 255.839844 29.375C253.351562 30.835938 250.800781 30.121094 248.464844 31.59375C236.367188 39.199219 225.890625 49.988281 216.328125 60.503906C207.410156 70.320312 198.125 80.285156 189.90625 90.644531C188.859375 91.964844 188.039062 93.605469 187.285156 95.1875C186.9375 95.921875 185.378906 95.84375 186.011719 97.167969C188.25 101.582031 190.609375 105.882812 194.617188 109.050781C196.167969 110.277344 198.074219 110.976562 199.433594 112.453125C206.457031 116.679688 213.515625 120.835938 220.675781 124.828125C224.027344 126.691406 224.246094 128.144531 221.738281 131.207031C219.949219 133.390625 218.277344 134.695312 215.929688 136.179688C214.855469 136.855469 212.742188 139.164062 211.664062 139.335938C211.375 139.378906 211.070312 139.324219 210.796875 139.433594C210.191406 139.664062 210.121094 140.46875 209.820312 141.042969C209.089844 142.453125 207.105469 142.371094 205.578125 142.808594C204.21875 143.199219 203.082031 144.117188 201.832031 144.773438C198.09375 146.738281 193.832031 145.96875 189.886719 147.082031C186.054688 148.160156 184.191406 147.550781 183.417969 144.867188C181.15625 141.304688 178.890625 137.746094 176.625 134.183594C174.511719 131.191406 171.714844 128.707031 170.054688 125.375C170.027344 125.3125 169.984375 125.246094 169.925781 125.207031C166.167969 122.605469 162.484375 119.292969 157.859375 119.085938C154.207031 118.921875 151.5 117.203125 148.457031 115.933594C147.617188 115.582031 146.851562 115.054688 145.921875 114.921875C128.953125 116.5 111.136719 120.566406 95.304688 126.882812C78.730469 133.492188 63.175781 142.371094 51.976562 156.59375C44.65625 167.574219 38.957031 179.472656 31.8125 190.574219C26.847656 198.289062 22.171875 205.980469 18.429688 214.347656C17.304688 216.867188 15.742188 218.753906 12.6875 218.722656C12.574219 218.722656 12.398438 218.796875 12.347656 218.890625C11.378906 220.652344 10.292969 222.148438 8.269531 223.042969C7.371094 223.4375 6.617188 224.976562 5.53125 224.261719C4.386719 223.511719 4.273438 222.03125 4.953125 220.695312C3.632812 217.789062 4.316406 214.722656 4.222656 211.722656C3.441406 208.128906 4.015625 204.519531 4.414062 200.980469C6.277344 184.355469 10.816406 168.484375 15.132812 152.375C20.527344 132.246094 28.71875 110.578125 43.816406 95.449219C46.269531 92.988281 49.605469 92.941406 52.675781 92.492188C60.523438 91.34375 68.394531 90.242188 76.183594 88.738281C83.265625 87.375 92.367188 86.332031 98.761719 83.394531C101.78125 82.011719 105.046875 81.238281 107.96875 79.597656C109.367188 78.8125 110.089844 78.183594 108.90625 76.550781C107.378906 74.441406 106.097656 72.15625 104.710938 69.945312C102.585938 68.449219 100.5 66.964844 97.707031 66.878906C96.628906 66.847656 95.570312 66.234375 94.824219 65.316406L94.078125 65.097656C92.832031 62.503906 93.84375 60.546875 96.609375 60.488281C98.855469 60.445312 101.105469 60.6875 103.351562 60.804688C107.9375 57.050781 112.976562 55.046875 119.046875 56.351562C122.3125 57.0625 125.484375 57.917969 128.507812 59.390625C137.855469 63.941406 153.359375 53.417969 160.164062 47.960938C169.199219 40.710938 176.941406 31.515625 182.660156 21.449219C185.601562 16.269531 187.605469 9.878906 191.992188 5.710938C193.777344 3.464844 196.53125 3.445312 198.964844 2.738281C200.15625 2.390625 201.453125 2.429688 202.707031 2.292969C223.421875 0.285156 244.101562 -0.0273438 264.699219 3.5625C266.558594 3.824219 270.667969 4.402344 270.863281 4.425781C275.992188 4.84375 281.128906 5.207031 286.25 5.695312C293.058594 6.335938 299.863281 7.058594 306.667969 7.765625C307.222656 7.820312 307.761719 8 308.304688 8.121094C308.433594 8.132812 308.558594 8.144531 308.6875 8.15625C315.015625 8.761719 321.347656 9.359375 327.671875 9.964844C333.703125 10.542969 339.78125 11.007812 345.785156 11.816406C347.09375 11.996094 348.324219 12.511719 349.601562 12.832031C351.25 13.246094 353.265625 12.242188 354.796875 12.992188C356.554688 13.851562 353.800781 17.007812 351.421875 16.960938"
            />
          </svg>
        </nuxt-link>
      </div>
      <ul class="flex space-x-8">
        <li class="menu">
          <nuxt-link to="#ancreprojet">Projets</nuxt-link>
        </li>
        <li class="menu">
          <nuxt-link to="#ancreparcours">Parcours</nuxt-link>
        </li>
        <li class="menu">
          <nuxt-link to="#ancrecontact">Contact</nuxt-link>
        </li>
      </ul>
    </nav>

    <!-- Point d'ancrage en haut -->
    <div id="top"></div>

    <!-- En-tête -->
    <header class="text-center mt-40">
      <h1 class="text-8xl font-light">ADRIEN LEGLISE</h1>
      <h3 class="text-2xl font-light">DÉVELOPPEUR FRONT-END ET APPLICATIONS.</h3>
    </header>

    <!-- Vague SVG en couleur primaire -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" class="w-full">
      <path fill="#00cba9" fill-opacity="1"
        d="M0,224L18.5,224C36.9,224,74,224,111,186.7C147.7,149,185,75,222,53.3C258.5,32,295,64,332,101.3C369.2,139,406,181,443,218.7C480,256,517,288,554,266.7C590.8,245,628,171,665,133.3C701.5,96,738,96,775,112C812.3,128,849,160,886,149.3C923.1,139,960,85,997,64C1033.8,43,1071,53,1108,74.7C1144.6,96,1182,128,1218,138.7C1255.4,149,1292,139,1329,117.3C1366.2,96,1403,64,1422,48L1440,32L1440,320L1421.5,320C1403.1,320,1366,320,1329,320C1292.3,320,1255,320,1218,320C1181.5,320,1145,320,1108,320C1070.8,320,1034,320,997,320C960,320,923,320,886,320C849.2,320,812,320,775,320C738.5,320,702,320,665,320C627.7,320,591,320,554,320C516.9,320,480,320,443,320C406.2,320,369,320,332,320C295.4,320,258,320,222,320C184.6,320,148,320,111,320C73.8,320,37,320,18,320L0,320Z" />
    </svg>

    <main class="space-y-16">
      <!-- Section À Propos -->
      <section class="bg-green-500 py-16" id="ancreparcours">
        <h2 class="text-4xl font-bold ml-8">À Propos</h2>
        <div class="flex flex-col md:flex-row items-center justify-center mt-8">
          <!-- Profil rond -->
          <div class="w-72 h-72 rounded-full bg-cover bg-center"
               style="background-image: url('/images/profil.png');"></div>
          <div class="max-w-2xl p-4">
            <p class="text-lg">
              Bonjour, je m'appelle Adrien LEGLISE et je suis étudiant en BUT Informatique.
              J'ai acquis des compétences en programmation (Java, SQL, HTML/CSS) et je souhaite poursuivre mes études
              pour me spécialiser dans l'intelligence artificielle.
            </p>
          </div>
        </div>
      </section>

      <!-- Section Projets -->
      <section class="bg-gray-900 py-16" id="ancreprojet">
        <h2 class="text-4xl font-bold text-center">Mes Projets</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8 px-4">
          <!-- Exemple d'article de projet -->
          <article class="relative group">
            <nuxt-link to="/projet1">
              <div class="h-72 rounded-lg bg-cover bg-center"
                   style="background-image: url('/images/portfolio_hardis.png');">
                <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition">
                  <h3 class="text-3xl">Site Hardis Group</h3>
                </div>
              </div>
            </nuxt-link>
          </article>
          <!-- Répétez pour les autres projets (proj2, proj3, etc.) -->
        </div>
      </section>

      <!-- Section Contact -->
      <section class="py-16" id="ancrecontact">
        <h2 class="text-4xl font-bold text-center">Me contacter</h2>
        <div class="max-w-xl mx-auto mt-8">
          <form action="/action_page.php" class="space-y-4">
            <h3 class="text-center text-xl">adrien.leglise2@gmail.com</h3>
            <div>
              <label for="fname" class="block">Nom & Prénom</label>
              <input type="text" id="fname" name="firstname" placeholder="Votre nom et prénom"
                     class="w-full p-3 border rounded" />
            </div>
            <div>
              <label for="sujet" class="block">Sujet</label>
              <input type="text" id="sujet" name="sujet" placeholder="L'objet de votre message"
                     class="w-full p-3 border rounded" />
            </div>
            <div>
              <label for="emailAddress" class="block">Email</label>
              <input type="email" id="emailAddress" name="email" placeholder="Votre email"
                     class="w-full p-3 border rounded" />
            </div>
            <div>
              <label for="subject" class="block">Message</label>
              <textarea id="subject" name="subject" placeholder="Votre message"
                        class="w-full p-3 border rounded h-40"></textarea>
            </div>
            <div class="text-center">
              <input type="submit" value="Envoyer"
                     class="bg-green-500 text-white p-3 rounded hover:bg-green-600" />
            </div>
          </form>
        </div>
      </section>
    </main>

    <footer class="text-center py-4">
      <!-- Pied de page si nécessaire -->
      <p class="text-sm">&copy; 2025 Adrien LEGLISE - Portfolio</p>
    </footer>
  </div>
</template>

<script setup>
  // Les composants auto-importés (nuxt-link, etc.) sont gérés par Nuxt 3.
</script>
