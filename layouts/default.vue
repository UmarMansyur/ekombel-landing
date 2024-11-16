<template>
  <div class="font-poppins">
    <!-- Navbar Start -->
    <nav class="bg-transparent backdrop-blur-xl fixed top-0 w-full left-0 p-4">
      <div class="container mx-auto flex justify-between items-center">
        <div class="text-gray-800 font-bold">Ekombel</div>
        <ul class="flex space-x-4 text-sm text-gray-700 items-center">
          <li><a href="#" class="">Home</a></li>
          <li><a href="#" class="">Tentang Kami</a></li>
          <li><a href="#" class="">Layanan</a></li>
          <li><a href="#" class="">Kontak Kami</a></li>
          <li>
            <button class="bg-gradient-to-tl from-pink-600 to-violet-600 text-white px-4 py-2 rounded-md">
              Login
            </button>
          </li>
        </ul>
      </div>
    </nav>
    <!-- Navbar End -->

    <!-- Hero -->
    <div
      class=" overflow-hidden before:absolute before:top-0 before:start-1/2 before:bg-[url('https://preline.co/assets/svg/examples/polygon-bg-element.svg')] dark:before:bg-[url('https://preline.co/assets/svg/examples-dark/polygon-bg-element.svg')] before:bg-no-repeat before:bg-top before:bg-cover before:size-full before:-z-[1] before:transform before:-translate-x-1/2">

      <div class="max-w-[85rem] mx-auto px-4 sm:px-6 lg:px-8 pt-24 pb-10">
        <div class="flex justify-center">
          <a class="inline-flex items-center gap-x-2 bg-white border border-gray-200 text-sm text-gray-800 p-1 ps-3 rounded-full transition hover:border-gray-300 focus:outline-none focus:border-gray-300 dark:bg-neutral-800 dark:border-neutral-700 dark:text-neutral-200 dark:hover:border-neutral-600 dark:focus:border-neutral-600"
            href="#">
            Tim Pengabdian FKIP Universitas Madura
            <span
              class="py-1.5 px-2.5 inline-flex justify-center items-center gap-x-2 rounded-full bg-gray-200 font-semibold text-sm text-gray-600 dark:bg-neutral-700 dark:text-neutral-400">
              <svg class="shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <path d="m9 18 6-6-6-6" />
              </svg>
            </span>
          </a>
        </div>
        <div class="mt-5 max-w-2xl text-center mx-auto">
          <h1 class="block font-bold text-gray-800 text-4xl md:text-5xl lg:text-6xl dark:text-neutral-200">
            Elektronik Komunitas
            <span class="bg-clip-text bg-gradient-to-tl from-pink-600 to-violet-600 text-transparent">Belajar
              Mini</span>
          </h1>
        </div>
        <div class="mt-5 max-w-3xl text-center mx-auto">
          <p class="text-lg text-gray-600 dark:text-neutral-400">
            Sebuah pendekatan baru dalam mewujudkan Ekosistem Pendidikan Inklusif dengan memanfaatkan teknologi dalam
            komunitas belajar mini produktif.
          </p>
        </div>
        <div class="mt-8 gap-3 flex justify-center">
          <a class="inline-flex justify-center items-center gap-x-3 text-center bg-gradient-to-tl from-pink-600 to-violet-600 hover:from-violet-600 hover:to-pink-600 border border-transparent text-white text-sm font-medium rounded-full focus:outline-none focus:from-violet-600 focus:to-pink-600 py-3 px-4 shadow-lg shadow-pink-600/20"
            href="#">
            Mulai Belajar
            <svg class="shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="m9 18 6-6-6-6" />
            </svg>
          </a>
        </div>
        <div class="mt-5 flex justify-center items-center gap-x-1 sm:gap-x-3">
          <span class="text-sm text-gray-600 dark:text-neutral-400">Di danai oleh Direktorat Riset, Teknologi, dan
            Pengabdian Kepada Masyarakat</span>
          <span class="text-sm font-bold text-gray-900 dark:text-white">2024</span>
        </div>
        <div class="flex gap-x-20 justify-center items-center mt-14 w-24 mx-auto">
          <img src="~/assets/images/logo-pendidikan.png" alt="Logo Universitas Madura" class=" object-cover ">
          <img src="~/assets/images/drtpm.jpg" alt="Logo Universitas Madura" class=" object-cover ">
          <img src="~/assets/images/Kurikulum_Merdeka.png" alt="Logo Universitas Madura" class=" object-cover ">
          <img src="~/assets/images/ekombel.jpeg" alt="Logo Universitas Madura" class=" object-cover">
          <img src="~/assets/images/logo.png" alt="Logo Universitas Madura" class=" object-cover ">
        </div>
      </div>
      <div class="bg-transparent backdrop-blur-xl relative">
        <div class="absolute inset-0 bg-white/10"></div>
        <div class="container mx-auto pt-10">
          <span class="text-pink-500 text-sm">#Nilai Ekombel</span>
          <h1 class="text-2xl font-bold text-gray-800">Poin Point Nilai Pengembangan <br> Komunitas Belajar Mini</h1>
          <p class="text-sm text-gray-600 w-1/3 mt-5">
            Nilai-nilai penting yang dapat dikembangkan dalam komunitas belajar mini produktif sebagai berikut:
          </p>
          <div class="grid grid-cols-3 mt-10 gap-5 relative border px-5 py-5 rounded-lg">
            <div class="bg-transparent backdrop-blur-xl border-r border-gray-200 px-4 py-2 rounded-lg relative">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-blue-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-blue-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                  </svg>
                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Profesionalisasi</h1>
                  <p class="text-sm text-gray-600">
                    Memfasilitasi pengembangan kompetensi profesionalisme guru melalui pemberdayaan komunitas belajar
                    mini
                    produktif.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl border-r border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-pink-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-pink-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M3.75 3v11.25A2.25 2.25 0 0 0 6 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0 1 18 16.5h-2.25m-7.5 0h7.5m-7.5 0-1 3m8.5-3 1 3m0 0 .5 1.5m-.5-1.5h-9.5m0 0-.5 1.5m.75-9 3-3 2.148 2.148A12.061 12.061 0 0 1 16.5 7.605" />
                  </svg>
                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Semangat Belajar</h1>
                  <p class="text-sm text-gray-600">
                    Semangat belajar yang tinggi dalam komunitas belajar mini produktif untuk meningkatkan kualitas
                    pendidikan.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-orange-500/20 justify-center items-center rounded-lg flex-shrink-0">

                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-orange-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M12 3.75v16.5M2.25 12h19.5M6.375 17.25a4.875 4.875 0 0 0 4.875-4.875V12m6.375 5.25a4.875 4.875 0 0 1-4.875-4.875V12m-9 8.25h16.5a1.5 1.5 0 0 0 1.5-1.5V5.25a1.5 1.5 0 0 0-1.5-1.5H3.75a1.5 1.5 0 0 0-1.5 1.5v13.5a1.5 1.5 0 0 0 1.5 1.5Zm12.621-9.44c-1.409 1.41-4.242 1.061-4.242 1.061s-.349-2.833 1.06-4.242a2.25 2.25 0 0 1 3.182 3.182ZM10.773 7.63c1.409 1.409 1.06 4.242 1.06 4.242S9 12.22 7.592 10.811a2.25 2.25 0 1 1 3.182-3.182Z" />
                  </svg>

                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Kolaborasi</h1>
                  <p class="text-sm text-gray-600">
                    Kolaborasi antara universitas dan komunitas belajar mini produktif untuk menciptakan ekosistem
                    pendidikan
                    inklusif.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl border-r border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-green-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-green-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M3.75 9.776c.112-.017.227-.026.344-.026h15.812c.117 0 .232.009.344.026m-16.5 0a2.25 2.25 0 0 0-1.883 2.542l.857 6a2.25 2.25 0 0 0 2.227 1.932H19.05a2.25 2.25 0 0 0 2.227-1.932l.857-6a2.25 2.25 0 0 0-1.883-2.542m-16.5 0V6A2.25 2.25 0 0 1 6 3.75h3.879a1.5 1.5 0 0 1 1.06.44l2.122 2.12a1.5 1.5 0 0 0 1.06.44H18A2.25 2.25 0 0 1 20.25 9v.776" />
                  </svg>

                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Keterbukaan</h1>
                  <p class="text-sm text-gray-600">
                    Kami mengutamakan komunikasi terbuka untuk mendengarkan dan memahami setiap kebutuhan siswa.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl border-r border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-blue-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-blue-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                  </svg>

                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Pelayanan kepada Siswa</h1>
                  <p class="text-sm text-gray-600">
                    Pelayanan kami berfokus pada kenyamanan dan keberhasilan siswa dalam meraih tujuan pendidikan
                    mereka.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl  border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-yellow-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-yellow-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="m21 7.5-2.25-1.313M21 7.5v2.25m0-2.25-2.25 1.313M3 7.5l2.25-1.313M3 7.5l2.25 1.313M3 7.5v2.25m9 3 2.25-1.313M12 12.75l-2.25-1.313M12 12.75V15m0 6.75 2.25-1.313M12 21.75V19.5m0 2.25-2.25-1.313m0-16.875L12 2.25l2.25 1.313M21 14.25v2.25l-2.25 1.313m-13.5 0L3 16.5v-2.25" />
                  </svg>

                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Inovasi</h1>
                  <p class="text-sm text-gray-600">
                    Kami terus berinovasi untuk menghadirkan solusi pembelajaran terbaik yang sesuai dengan kebutuhan
                    zaman.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl border-r border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-purple-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-purple-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M15.362 5.214A8.252 8.252 0 0 1 12 21 8.25 8.25 0 0 1 6.038 7.047 8.287 8.287 0 0 0 9 9.601a8.983 8.983 0 0 1 3.361-6.867 8.21 8.21 0 0 0 3 2.48Z" />
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M12 18a3.75 3.75 0 0 0 .495-7.468 5.99 5.99 0 0 0-1.925 3.547 5.975 5.975 0 0 1-2.133-1.001A3.75 3.75 0 0 0 12 18Z" />
                  </svg>

                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Penghargaan terhadap Keberagaman</h1>
                  <p class="text-sm text-gray-600">
                    Kami menghargai keberagaman sebagai kekuatan untuk menciptakan lingkungan yang inklusif dan
                    harmonis.
                  </p>
                </div>
              </div>
            </div>
            <div class="bg-transparent backdrop-blur-xl border-gray-200 px-4 py-2 rounded-lg">
              <div class="flex gap-x-5">
                <div class="flex h-10 w-10 bg-red-500/20 justify-center items-center rounded-lg flex-shrink-0">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="size-5 text-red-500">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M12 18v-5.25m0 0a6.01 6.01 0 0 0 1.5-.189m-1.5.189a6.01 6.01 0 0 1-1.5-.189m3.75 7.478a12.06 12.06 0 0 1-4.5 0m3.75 2.383a14.406 14.406 0 0 1-3 0M14.25 18v-.192c0-.983.658-1.823 1.508-2.316a7.5 7.5 0 1 0-7.517 0c.85.493 1.509 1.333 1.509 2.316V18" />
                  </svg>

                </div>
                <div class="flex flex-col">
                  <h1 class="text-lg font-bold">Kepedulian terhadap Perkembangan Siswa</h1>
                  <p class="text-sm text-gray-600">
                    Kami peduli pada setiap tahap perkembangan siswa, memastikan mereka tumbuh dan berkembang secara
                    optimal.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container mx-auto mt-16">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
          class="size-6 text-pink-500">
          <path stroke-linecap="round" stroke-linejoin="round"
            d="M16.5 12a4.5 4.5 0 1 1-9 0 4.5 4.5 0 0 1 9 0Zm0 0c0 1.657 1.007 3 2.25 3S21 13.657 21 12a9 9 0 1 0-2.636 6.364M16.5 12V8.25" />
        </svg>
        <div class="flex gap-x-10 mt-5">
          <div class="w-1/2">
            <span class="text-pink-500 text-sm">#Tentang Kami</span>
            <h2 class="text-3xl font-bold text-gray-800 mb-2">Tentang Kami</h2>
            <p class="mt-5 text-sm max-w-xl text-gray-600">
              Ekombel adalah inisiatif yang didedikasikan untuk menciptakan ekosistem pendidikan inklusif melalui
              komunitas
              belajar mini produktif. Kami percaya bahwa setiap individu memiliki potensi untuk berkembang dan
              berinovasi,
              dan kami berkomitmen untuk menyediakan platform yang mendukung pertumbuhan tersebut.
            </p>
            <div class="bg-white mt-3 max-w-xl">
              <h3 class="text-xl font-semibold text-gray-800">Visi Kami</h3>
              <p class="mt-3 text-sm text-gray-600">
                Menjadi komunitas belajar yang profesional dalam menjamin mutu pendidikan yang berbasis IPTEK dan
                IMTAK serta menciptakan pembelajaran yang bermakna dalam pendidikan inklusif bagi semua.
              </p>
            </div>
            <div class="bg-white mt-3 max-w-xl">
              <h3 class="text-xl font-semibold text-gray-800">Misi Kami</h3>
              <p class="mt-3 text-sm text-gray-600">
                Beberapa misi kami adalah:
              </p>
              <ul>
                <li class="flex space-x-5 mt-3 items-center" v-for="misi in misi">
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                      class="size-6 text-pink-400">
                      <path fill-rule="evenodd"
                        d="M8.603 3.799A4.49 4.49 0 0 1 12 2.25c1.357 0 2.573.6 3.397 1.549a4.49 4.49 0 0 1 3.498 1.307 4.491 4.491 0 0 1 1.307 3.497A4.49 4.49 0 0 1 21.75 12a4.49 4.49 0 0 1-1.549 3.397 4.491 4.491 0 0 1-1.307 3.497 4.491 4.491 0 0 1-3.497 1.307A4.49 4.49 0 0 1 12 21.75a4.49 4.49 0 0 1-3.397-1.549 4.49 4.49 0 0 1-3.498-1.306 4.491 4.491 0 0 1-1.307-3.498A4.49 4.49 0 0 1 2.25 12c0-1.357.6-2.573 1.549-3.397a4.49 4.49 0 0 1 1.307-3.497 4.49 4.49 0 0 1 3.497-1.307Zm7.007 6.387a.75.75 0 1 0-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 0 0-1.06 1.06l2.25 2.25a.75.75 0 0 0 1.14-.094l3.75-5.25Z"
                        clip-rule="evenodd"></path>
                    </svg>
                  </div>
                  <div>
                    <h2 class="text-sm">{{ misi }}</h2>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="text-end ms-auto w-1/2 rotate-6">
            <div class="flex justify-end border border-gray-200 rounded-lg p-5">
              <img src="~/assets/images/ekombel-landing.jpg" alt="Logo Universitas Madura"
                class=" object-cover rounded-lg">
            </div>
          </div>
        </div>
        <!--  -->
      </div>
      <section class="bg-gradient-to-b from-gray-50 to-transparent py-10 mb-10">
        <div class="container px-3 sm:px-6 lg:px-3 mx-auto">
          <p class="text-center text-green-500 font-medium">#Testimoni</p>
          <h1 class="text-center sm:text-3xl uppercase font-bold"> Apa Kata Mereka? <br></h1>
          <div class="grid sm:grid-cols-2 gap-10 pt-10">
            <div class="flex flex-col gap-5">
              <div class="flex gap-5 items-center">
                <div class="w-16 h-16 bg-gray-300 rounded-full p-1 flex overflow-hidden"><img
                    src="https://api.unira.ac.id/img/profil/mhs/d9674b9d198eecaa13f3f057d5390a12.jpg" alt="image"
                    class="w-full h-auto rounded-full object-cover"></div>
                <div>
                  <h2 class="text-lg font-bold">Muhammad Umar Mansyur</h2>
                  <p class="text-gray-500">Mahasiswa Fakultas Teknik Informatika</p>
                </div>
              </div>
              <p class="text-gray-500"> "Saya sangat bersukur sekali karena dengan adanya ekombel ini dari waktu sekolah yang sempit menjadi lebih
            luas karena dilakukan daring. Aplikasinya sangat luar biasa dan kerren sekali harapan kedepan semoga ekombel
            ini dapat disebarluaskan ke sekolah lain sehingga sekolah lain juga mendapatkan fasilitas yang sama." </p>
            </div>
            <div class="flex flex-col gap-5">
              <div class="flex gap-5 items-center">
                <div class="w-16 h-16 bg-gray-300 rounded-full p-1"><img
                    src="https://api.unira.ac.id/img/profil/dkr/7104313573_thumb.jpg?1717816213474" alt="image"
                    class="w-full h-auto rounded-full object-cover"></div>
                <div>
                  <h2 class="text-lg font-bold">MATSAINI, ST, MT</h2>
                  <p class="text-gray-500">Dosen Fakultas Teknik Industri</p>
                </div>
              </div>
              <p class="text-gray-500"> " Kami merasa sangat puas terhadap pelatihan dan aplikasi yang diberikan dari hasil implementasi ekombel ini,
            yang tentu dapat menunjangu dalam kegiatan kegiatan pembelajaran sehingga kedepan para teman guru dapat
            berkulitas untuk meningkatkan mutu pendidikan." </p>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
const misi = [
  "Menyelenggarakan pembelajaran yang bermakna dan relevan bagi semua siswa dalam pendidikan inklusif",
  "Membekali anggota komunitas dengan ilmu pengetahuan dan teknologi yang adaptif",
  "Membekali anggota komunitas dengan Iman dan Takwa kepada Allah SWT",
  "Menjamin mutu pendidikan dengan pembelajaran yang berdampak pada siswa",
  "Menjadikan lingkungan sekolah yang inklusif bagi semua"
];


</script>