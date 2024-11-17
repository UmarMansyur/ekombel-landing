<template>
  <div class="font-poppins">
    <!-- Navbar Start -->
    <nav class="bg-transparent hidden md:block backdrop-blur-xl fixed top-0 w-full left-0 py-4 px-20 z-20">
      <div class="mx-auto flex justify-between items-center">
        <div class="flex items-center h-10 w-10 p-0.5 border border-pink-500 rounded-full gap-x-2">
          <img src="~/assets/images/ekombel.jpeg" alt="Logo Universitas Madura" class="w-10 h-auto rounded-full">
          <h1 class="text-pink-500 font-bold text-xl">Ekombel</h1>
        </div>
        <ul class="flex space-x-4 text-sm text-gray-700 items-center">
          <li><a href="#beranda" class="text-pink-600">Beranda</a></li>
          <li><a href="#nilai-ekombel" class="text-pink-600">Nilai Ekombel</a></li>
          <li><a href="#tentang-kami" class="text-pink-600">Tentang Kami</a></li>
          <li><a href="#testimoni" class="text-pink-600">Testimoni</a></li>
          <li>
            <a href="https://ekombel.madurainstitute.org/login"
              class="bg-gradient-to-tl from-pink-600 to-violet-600 text-white px-4 py-2 rounded-md" target="_blank">
              Login
            </a>
          </li>
        </ul>
      </div>
    </nav>
    <!-- Navbar End -->

    <nav class="bg-transparent md:hidden backdrop-blur-xl fixed top-0 w-full left-0 py-4 px-5 z-20">
      <div class="flex justify-between items-center">
        <div class="flex items-center h-10 w-10 p-0.5 border border-pink-500 rounded-full gap-x-2">
          <img src="~/assets/images/ekombel.jpeg" alt="Logo Universitas Madura" class="w-10 h-auto rounded-full">
          <h1 class="text-pink-500 font-bold text-xl">Ekombel</h1>
        </div>
        <button class="text-pink-600" @click="toggleMenu">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
          </svg>
        </button>
      </div>
      <div v-if="isMenuOpen" class="mt-5">
        <ul class="flex flex-col space-y-4 text-sm text-gray-700">
          <li><a href="#beranda" class="text-pink-600">Beranda</a></li>
          <li><a href="#nilai-ekombel" class="text-pink-600">Nilai Ekombel</a></li>
          <li><a href="#tentang-kami" class="text-pink-600">Tentang Kami</a></li>
          <li><a href="#testimoni" class="text-pink-600">Testimoni</a></li>
          <li>
            <a href="https://ekombel.madurainstitute.org/login"
              class="bg-gradient-to-tl from-pink-600 to-violet-600 text-white px-4 py-2 rounded-md w-full"
              target="_blank">
              Login
            </a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Hero -->
    <div
      class=" overflow-hidden before:absolute before:top-0 before:start-1/2 before:bg-[url('https://preline.co/assets/svg/examples/polygon-bg-element.svg')] dark:before:bg-[url('https://preline.co/assets/svg/examples-dark/polygon-bg-element.svg')] before:bg-no-repeat before:bg-cover before:size-full before:-z-[1] before:transform before:-translate-x-1/2">

      <div class="max-w-[85rem] mx-auto px-4 sm:px-6 lg:px-8 pt-24 pb-10 md:pt-32 md:pb-20">
        <div class="flex justify-center" id="beranda">
          <a class="inline-flex items-center gap-x-2 bg-white border border-gray-200 text-sm p-1 ps-3 rounded-full transition hover:border-gray-300 focus:outline-none focus:border-gray-300 dark:bg-neutral-800 dark:border-neutral-700 dark:text-neutral-200 dark:hover:border-neutral-600 dark:focus:border-neutral-600"
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
            href="https://ekombel.madurainstitute.org/login" target="_blank">
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

      </div>
      <div class="bg-transparent backdrop-blur-xl relative z-10" id="nilai-ekombel">
        <div class="absolute inset-0 bg-white/10"></div>
        <div class="lg:px-20 px-10 mx-auto pt-10 relative">
          <span class="text-pink-500 text-sm">#Nilai Ekombel</span>
          <h1 class="text-2xl font-bold text-gray-800">Nilai Pengembangan <br> Komunitas Belajar Mini</h1>
          <p class="text-sm text-gray-600 md:w-1/3 mt-5">
            Nilai-nilai penting yang dapat dikembangkan dalam komunitas belajar mini produktif sebagai berikut:
          </p>
          <div class="grid grid-cols-1 md:grid-cols-3 mt-10 gap-5 relative border px-5 py-5 rounded-lg">
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
      <div class="lg:px-20 px-10 mx-auto mt-16">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
          class="size-6 text-pink-500">
          <path stroke-linecap="round" stroke-linejoin="round"
            d="M16.5 12a4.5 4.5 0 1 1-9 0 4.5 4.5 0 0 1 9 0Zm0 0c0 1.657 1.007 3 2.25 3S21 13.657 21 12a9 9 0 1 0-2.636 6.364M16.5 12V8.25" />
        </svg>
        <div class="flex flex-col items-center md:flex-row gap-x-10 mt-5" id="tentang-kami">
          <div class="w-full md:w-1/2">
            <span class="text-pink-500 text-sm">#Tentang Kami</span>
            <h2 class="text-3xl font-bold text-gray-800 mb-2">Tentang Kami</h2>
            <p class="mt-5 text-sm max-w-3xl text-gray-600">
              Ekombel adalah inisiatif yang didedikasikan untuk menciptakan ekosistem pendidikan inklusif melalui
              komunitas
              belajar mini produktif. Kami percaya bahwa setiap individu memiliki potensi untuk berkembang dan
              berinovasi,
              dan kami berkomitmen untuk menyediakan platform yang mendukung pertumbuhan tersebut.
            </p>
            <div class="bg-white mt-3 max-w-3xl">
              <h3 class="text-xl font-semibold text-gray-800">Visi Kami</h3>
              <p class="mt-3 text-sm text-gray-600">
                Menjadi komunitas belajar yang profesional dalam menjamin mutu pendidikan yang berbasis IPTEK dan
                IMTAK serta menciptakan pembelajaran yang bermakna dalam pendidikan inklusif bagi semua.
              </p>
            </div>
            <div class="bg-white mt-3 max-w-3xl">
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
                    <h2 class="text-sm text-gray-600">{{ misi }}</h2>
                  </div>
                </li>
              </ul>
            </div>
            <div class="bg-white mt-3 max-w-3xl">
              <h3 class="text-xl font-semibold text-gray-800">Tujuan Kami</h3>
              <p class="mt-3 text-sm text-gray-600">
                Beberapa tujuan kami adalah:
              </p>
              <ul>
                <li class="flex space-x-5 mt-3 items-center" v-for="item in tujuannya">
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                      stroke="currentColor" class="size-5 text-pink-500">
                      <path stroke-linecap="round" stroke-linejoin="round"
                        d="M9 12.75 11.25 15 15 9.75m-3-7.036A11.959 11.959 0 0 1 3.598 6 11.99 11.99 0 0 0 3 9.749c0 5.592 3.824 10.29 9 11.623 5.176-1.332 9-6.03 9-11.622 0-1.31-.21-2.571-.598-3.751h-.152c-3.196 0-6.1-1.248-8.25-3.285Z" />
                    </svg>
                  </div>
                  <div>
                    <h2 class="text-sm text-gray-600">{{ item }}</h2>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="text-end ms-auto w-full md:w-1/2 rotate-6">
            <div class="flex justify-end border border-gray-200 rounded-lg p-5">
              <img src="~/assets/images/ekombel-landing.jpg" alt="Logo Universitas Madura"
                class=" object-cover rounded-lg">
            </div>
          </div>
        </div>
        <!--  -->
      </div>
      <section class="bg-gradient-to-b from-gray-50 to-transparent py-10 mb-10" id="testimoni">
        <div class="lg:px-20 px-10 sm:px-6 mx-auto">
          <p class="text-center text-black font-medium">#Testimoni</p>
          <h1 class="text-center sm:text-3xl uppercase font-bold"> Apa Kata Mereka? <br></h1>
          <div class="grid sm:grid-cols-2 gap-10 pt-10">
            <div class="flex flex-col gap-5">
              <div class="flex sm:gap-5 gap-2 items-center flex-shrink-0 w-full">
                <div class="w-16 h-16 bg-gray-300 rounded-full p-2 flex justify-center items-center overflow-hidden">
                  <img src="~/assets/images/simbang.png" alt="image" class="w-full h-full object-cover rounded-full">
                </div>
                <div>
                  <h2 class="text-lg font-bold">MOHAMMAD SIMBANG, S.Pd.M.MPd</h2>
                  <p class="text-black">Kepala SDN Kolpajung 2 Pamekasan</p>
                </div>
              </div>
              <p class="text-black text-sm"> "Kami merasa sangat puas terhadap pelatihan dan aplikasi yang diberikan
                dari hasil implementasi ekombel ini,
                yang tentu dapat menunjangu dalam kegiatan kegiatan pembelajaran sehingga kedepan para teman guru dapat
                berkulitas untuk meningkatkan mutu pendidikan." </p>
            </div>
            <div class="flex flex-col gap-5">
              <div class="flex gap-5 items-center flex-shrink-0">
                <div class="w-16 h-16 bg-gray-300 rounded-full p-1 flex justify-center items-center overflow-hidden">
                  <img src="~/assets/images/ani.png" alt="image" class="w-full h-full object-cover rounded-full">
                </div>
                <div>
                  <h2 class="text-lg font-bold">ANI WARNENGSIH, S.PD</h2>
                  <p class="text-black">Ketua Komunitas Belajar Mini Produktif SDN Kolpajung 2 Pamekasan</p>
                </div>
              </div>
              <p class="text-black text-sm"> "Saya sangat bersukur sekali karena dengan adanya ekombel ini dari waktu
                sekolah yang sempit menjadi lebih
                luas karena dilakukan daring. Aplikasinya sangat luar biasa dan kerren sekali harapan kedepan semoga
                ekombel
                ini dapat disebarluaskan ke sekolah lain sehingga sekolah lain juga mendapatkan fasilitas yang sama."
              </p>
            </div>
          </div>
        </div>
      </section>
      <section id="skripsi" class="bg-[#181230] relative">
        <div class="absolute top-0 left-0 w-full h-full z-0"><svg
            class="absolute -bottom-20 start-1/2 w-full transform -translate-x-1/2" width="2745" height="488"
            viewBox="0 0 2745 488" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M0.5 330.864C232.505 403.801 853.749 527.683 1482.69 439.719C2111.63 351.756 2585.54 434.588 2743.87 487"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 308.873C232.505 381.81 853.749 505.692 1482.69 417.728C2111.63 329.765 2585.54 412.597 2743.87 465.009"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 286.882C232.505 359.819 853.749 483.701 1482.69 395.738C2111.63 307.774 2585.54 390.606 2743.87 443.018"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 264.891C232.505 337.828 853.749 461.71 1482.69 373.747C2111.63 285.783 2585.54 368.615 2743.87 421.027"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 242.9C232.505 315.837 853.749 439.719 1482.69 351.756C2111.63 263.792 2585.54 346.624 2743.87 399.036"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 220.909C232.505 293.846 853.749 417.728 1482.69 329.765C2111.63 241.801 2585.54 324.633 2743.87 377.045"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 198.918C232.505 271.855 853.749 395.737 1482.69 307.774C2111.63 219.81 2585.54 302.642 2743.87 355.054"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 176.927C232.505 249.864 853.749 373.746 1482.69 285.783C2111.63 197.819 2585.54 280.651 2743.87 333.063"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 154.937C232.505 227.873 853.749 351.756 1482.69 263.792C2111.63 175.828 2585.54 258.661 2743.87 311.072"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 132.946C232.505 205.882 853.749 329.765 1482.69 241.801C2111.63 153.837 2585.54 236.67 2743.87 289.082"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 110.955C232.505 183.891 853.749 307.774 1482.69 219.81C2111.63 131.846 2585.54 214.679 2743.87 267.091"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 88.9639C232.505 161.901 853.749 285.783 1482.69 197.819C2111.63 109.855 2585.54 192.688 2743.87 245.1"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 66.9729C232.505 139.91 853.749 263.792 1482.69 175.828C2111.63 87.8643 2585.54 170.697 2743.87 223.109"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 44.9819C232.505 117.919 853.749 241.801 1482.69 153.837C2111.63 65.8733 2585.54 148.706 2743.87 201.118"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 22.991C232.505 95.9276 853.749 219.81 1482.69 131.846C2111.63 43.8824 2585.54 126.715 2743.87 179.127"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
            <path
              d="M0.5 1C232.505 73.9367 853.749 197.819 1482.69 109.855C2111.63 21.8914 2585.54 104.724 2743.87 157.136"
              class="stroke-neutral-700/50" stroke="currentColor"></path>
          </svg></div>
        <div class="lg:px-20 px-10 mx-auto overflow-hidden sm:h-[30rem]">
          <div class="flex sm:flex-row flex-col sm:space-x-10 h-full justify-center items-center">
            <div class="sm:w-1/2 w-full py-10  sm:py-10 text-white shrink-0 relative">
              <p class="text-green-500 text-sm font-semibold italic">#Pengembang</p>
              <h1 class="text-white sm:text-4xl font-bold"> Tim Pengembang
                <span>🚀</span>
              </h1>
              <p class="text-sm mt-5 text-[#a9a4bc]"> Tim pengembang E-KOMBEL Mini Produktif
              </p>
              <div class="flex relative"><a href="https://ekombel.madurainstitute.org/login"
                  class="bg-blue-500 text-white px-10 py-2 text-sm rounded-full mt-5 font-bold"
                  target="_blank">Masuk</a></div>
            </div>
            <div class="py-5 sm:py-0">
              <div class="relative overflow-hidden flex flex-col md:flex-row sm:gap-10 gap-3">
                <div class="animate-marquee w-full md:w-1/2">
                  <div class="flex" v-for="team in teams1">
                    <div class="bg-white gap-2 p-4 rounded-xl justify-between sm:mb-6 mb-3">
                      <div class="flex gap-1 sm:gap-4 items-center w-72">
                        <div class="sm:w-24 sm:h-24 w-16 h-16 bg-gray-300 rounded-full flex shrink-0"><img
                            :src="team.image" alt="" class="w-full h-auto rounded-full object-cover"></div>
                        <div class="my-auto">
                          <h2 class="text-sm font-bold">{{ team.name }}</h2>
                          <h3 class="text-xs">{{ team.position }}</h3>
                          <p class="text-xs">Dosen FKIP Universitas Madura</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="sm:animate-marquee2 animate-marquee w-full md:w-1/2">
                  <div class="flex" v-for="team in teams2">
                    <div class="bg-white gap-2 p-4 rounded-xl justify-between sm:mb-6 mb-3">
                      <div class="flex gap-1 sm:gap-4 items-center w-72">
                        <div class="sm:w-24 sm:h-24 w-16 h-16 bg-gray-300 rounded-full flex shrink-0"><img
                            :src="team.image" alt="" class="w-full h-auto rounded-full object-cover"></div>
                        <div class="my-auto">
                          <h2 class="text-sm font-bold">{{ team.name }}</h2>
                          <h3 class="text-xs">{{ team.position }}</h3>
                          <p class="text-xs">{{ team.university }}</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
  <section class="grid grid-cols-5 py-20 gap-5 lg:px-60 px-4 justify-center items-center">
    <img src="~/assets/images/logo-pendidikan.png" alt="Logo Universitas Madura" class=" object-cover ">
    <img src="~/assets/images/drtpm.jpg" alt="Logo Universitas Madura" class=" object-cover ">
    <img src="~/assets/images/Kurikulum_Merdeka.png" alt="Logo Universitas Madura" class=" object-cover ">
    <img src="~/assets/images/ekombel.jpeg" alt="Logo Universitas Madura" class=" object-cover">
    <img src="~/assets/images/logo.png" alt="Logo Universitas Madura" class=" object-cover ">
    <!-- </div> -->
  </section>
  <footer class="pt-10">
    <div class="mx-auto w-full lg:px-20 px-10 sm:px-6 bg-gray-100 py-5">
      <div class="md:flex md:justify-between mt-10">
        <div class="md:mb-0"><RouterLink to="/" class="flex items-center mb-2"><img
              src="~/assets/images/ekombel.jpeg" class="h-8 me-3 rounded-full" alt="FlowBite Logo"><span
              class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">E-KOMBEL</span></RouterLink>
          <p><span class="text-gray-500 text-sm dark:text-gray-400">JL. Gatot Koco, Kolpajung, Pademawu, Kowel, Kec.
              Pamekasan <br> Kabupaten Pamekasan, Jawa Timur 69317</span></p>
          <p><span class="text-gray-500 text-sm dark:text-gray-400">Telp. (0324) 324858</span></p>
          <p><span class="text-gray-500 text-sm dark:text-gray-400">Email: <a href="mailto:ekombel@madurainstitute.org"
                class="hover:underline"> ekombel@madurainstitute.org </a></span></p>
        </div>
        <div class="grid grid-cols-2 gap-8 sm:gap-6 sm:grid-cols-3">
          <div>
            <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white"> Fitur </h2>
            <ul class="text-gray-500 text-sm dark:text-gray-400">
              <li class="mb-4"><a href="https://ekombel.madurainstitute.org/login" class="hover:underline"
                  target="_blank"> Komunitas </a></li>
              <li><a href="#" class="hover:underline"> Syarat &amp; Ketentuan </a></li>
            </ul>
          </div>
          <div>
            <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white"> Link Terkait </h2>
            <ul class="text-gray-500 text-sm dark:text-gray-400">
              <li class="mb-4"><a href="https://simat.unira.ac.id" class="hover:underline" target="_blank"> Fakultas
                  Keguruan dan Ilmu Kependidikan Universitas Madura </a></li>
              <li><a href="https://silab.unira.ac.id" class="hover:underline" target="_blank"> Sistem Informasi
                  Laboratorium </a></li>
            </ul>
          </div>
          <div>
            <h2 class="mb-6 text-sm font-semibold text-gray-900 uppercase dark:text-white"> Ketentuan Legal </h2>
            <ul class="text-gray-500 dark:text-gray-400 text-sm">
              <li class="mb-4"><a href="#" class="hover:underline"> Kebijakan Privasi </a></li>
              <li><a href="#" class="hover:underline"> Syarat Penggunaan </a></li>
            </ul>
          </div>
        </div>
      </div>
      <hr class="border-gray-200 sm:mx-auto dark:border-gray-700 my-3">
      <div class="sm:flex sm:items-center sm:justify-between"><span
          class="text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2024 <a href="https://fikp.unira.ac.id"
            class="hover:underline">TIM Pengabdian FKIP Universitas Madura</a>. All Rights Reserved. </span>
        <div class="flex mt-4 sm:justify-center sm:mt-0"><a href="#"
            class="text-gray-500 hover:text-gray-900 dark:hover:text-white"><svg class="w-4 h-4" aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 8 19">
              <path fill-rule="evenodd"
                d="M6.135 3H8V0H6.135a4.147 4.147 0 0 0-4.142 4.142V6H0v3h2v9.938h3V9h2.021l.592-3H5V3.591A.6.6 0 0 1 5.592 3h.543Z"
                clip-rule="evenodd"></path>
            </svg><span class="sr-only">Facebook page</span></a><a href="#"
            class="text-gray-500 hover:text-gray-900 dark:hover:text-white ms-5"><svg class="w-4 h-4" aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 21 16">
              <path
                d="M16.942 1.556a16.3 16.3 0 0 0-4.126-1.3 12.04 12.04 0 0 0-.529 1.1 15.175 15.175 0 0 0-4.573 0 11.585 11.585 0 0 0-.535-1.1 16.274 16.274 0 0 0-4.129 1.3A17.392 17.392 0 0 0 .182 13.218a15.785 15.785 0 0 0 4.963 2.521c.41-.564.773-1.16 1.084-1.785a10.63 10.63 0 0 1-1.706-.83c.143-.106.283-.217.418-.33a11.664 11.664 0 0 0 10.118 0c.137.113.277.224.418.33-.544.328-1.116.606-1.71.832a12.52 12.52 0 0 0 1.084 1.785 16.46 16.46 0 0 0 5.064-2.595 17.286 17.286 0 0 0-2.973-11.59ZM6.678 10.813a1.941 1.941 0 0 1-1.8-2.045 1.93 1.93 0 0 1 1.8-2.047 1.919 1.919 0 0 1 1.8 2.047 1.93 1.93 0 0 1-1.8 2.045Zm6.644 0a1.94 1.94 0 0 1-1.8-2.045 1.93 1.93 0 0 1 1.8-2.047 1.918 1.918 0 0 1 1.8 2.047 1.93 1.93 0 0 1-1.8 2.045Z">
              </path>
            </svg><span class="sr-only">Discord community</span></a><a href="#"
            class="text-gray-500 hover:text-gray-900 dark:hover:text-white ms-5"><svg xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512" class="w-4 h-4" fill="currentColor">
              <path
                d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z">
              </path>
            </svg><span class="sr-only">Twitter page</span></a><a href="#"
            class="text-gray-500 hover:text-gray-900 dark:hover:text-white ms-5"><svg class="w-4 h-4" aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd"
                d="M10 .333A9.911 9.911 0 0 0 6.866 19.65c.5.092.678-.215.678-.477 0-.237-.01-1.017-.014-1.845-2.757.6-3.338-1.169-3.338-1.169a2.627 2.627 0 0 0-1.1-1.451c-.9-.615.07-.6.07-.6a2.084 2.084 0 0 1 1.518 1.021 2.11 2.11 0 0 0 2.884.823c.044-.503.268-.973.63-1.325-2.2-.25-4.516-1.1-4.516-4.9A3.832 3.832 0 0 1 4.7 7.068a3.56 3.56 0 0 1 .095-2.623s.832-.266 2.726 1.016a9.409 9.409 0 0 1 4.962 0c1.89-1.282 2.717-1.016 2.717-1.016.366.83.402 1.768.1 2.623a3.827 3.827 0 0 1 1.02 2.659c0 3.807-2.319 4.644-4.525 4.889a2.366 2.366 0 0 1 .673 1.834c0 1.326-.012 2.394-.012 2.72 0 .263.18.572.681.475A9.911 9.911 0 0 0 10 .333Z"
                clip-rule="evenodd"></path>
            </svg><span class="sr-only">GitHub account</span></a></div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts">
import { ref } from 'vue';


useHead({
  title: 'Home | E-Kombel',
  link: [
    { rel: 'icon', type: 'image/png', href: '~/assets/images/ekombel.jpeg' }
  ]
})

const isMenuOpen = ref(false);

function toggleMenu() {
  isMenuOpen.value = !isMenuOpen.value;
}

const tujuannya = [
  "Membentuk komunitas belajar yang profesional dan mandiri.",
  "Menerapkan pendidikan yang bermutu dan berkualitas.",
  "Mengembangkan kemampuan siswa menguasai bidang sains dan teknologi yang beriman dan bertaqwa.",
  "Membangun pusat pengembangan pendidikan dalam rangka pengimbasan bagi sekolah sekitar.",
  "Mendorong peran serta warga sekolah dalam menyelenggarakan pendidikan yang inklusif bagi semua."
];

const misi = [
  "Menyelenggarakan pembelajaran yang bermakna dan relevan bagi semua siswa dalam pendidikan inklusif",
  "Membekali anggota komunitas dengan ilmu pengetahuan dan teknologi yang adaptif",
  "Membekali anggota komunitas dengan Iman dan Takwa kepada Allah SWT",
  "Menjamin mutu pendidikan dengan pembelajaran yang berdampak pada siswa",
  "Menjadikan lingkungan sekolah yang inklusif bagi semua"
];

const teams1 = [
  {
    name: "Dr. Moh. Zayyadi, M.Pd",
    position: "Ketua",
    image: "/zayyadi.png"
  },
  {
    name: "Harfin Lanya, M.Pd.",
    position: "Anggota",
    image: "/harfin.png"
  },
  {
    name: "Dra. Yanti Linarsih, M.Pd.",
    position: "Anggota",
    image: "/yanti.jpg"
  },
];

const teams2 = [
  {
    name: "Muhammad Umar Mansyur",
    position: "Programmer",
    university: "Mahasiswa Fakultas Teknik Informatika",
    image: "/umar.jpg"
  },
  {
    name: "Tsalitsatur Rizqiyah",
    position: "Anggota",
    university: "Mahasiswa Fakultas Keguruan dan Ilmu Pendidikan",
    image: "/rizkiyah.jpg"
  },
  {
    name: "Nabillah Ayuditya Rochmadyan",
    university: "Mahasiswa Fakultas Keguruan dan Ilmu Pendidikan",
    position: "Anggota",
    image: "/nabila.jpg",
  }
];


</script>
