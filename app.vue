<template>
  <div class="p-8 max-w-4xl mx-auto bg-blue-50 rounded-lg shadow-lg">

    <!-- Title Section -->
    <section class="bg-blue-200 p-4 text-center rounded-t-lg">
      <h1 class="text-blue-800 font-bold text-4xl">Curriculum Vitae</h1>
    </section>

    <!-- About Me Section -->
    <section class="bg-white p-4 flex items-start mt-4 rounded-lg shadow">
      <img src="./assets/img/ppmay.jpeg" alt="My Photo" class="rounded-full w-32 h-32 mr-4 object-cover border-4 border-blue-300" />
      <div>
        <h2 class="text-2xl font-semibold text-blue-700">Hello, I'm Maynanda Elisa Pasya T</h2>
        <p class="mt-2 text-gray-700">I am an Information Technology student at Brawijaya University, specializing in access network engineering, a field I developed during my time at vocational school. I possess strong communication skills, demonstrated through my involvement in various organizations and committees. Additionally, I gained hands-on experience as a customer service intern for two months, further enhancing my interpersonal and professional abilities.</p>
      </div>
    </section>

    <!-- Personal Data, Skills, and Languages Section -->
    <section class="grid grid-cols-3 gap-4 mt-4">
      <div class="bg-blue-100 p-4 rounded-lg shadow"> <!-- Personal Data -->
        <h2 class="text-lg font-semibold text-blue-800">Personal Data</h2>
        <p>Name: Maynanda Elisa Pasya T</p>
        <p>Born: 2005</p>
        <p>Address: JL. Raya Dieng Atas No.80</p>
        <a href="#projects" class="mt-4 inline-block bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700">Find Out More</a>
      </div>
      <div class="bg-blue-200 p-4 rounded-lg shadow"> <!-- Skills -->
        <h2 class="text-lg font-semibold text-blue-800">Skills</h2>
        <div class="mt-2">
          <span>HTML</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-50"></div>
          </div>
          <span>CSS</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-50"></div>
          </div>
          <span>Data Analysis</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-70"></div>
          </div>
          <span>Public Speaking</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-85"></div>
          </div>
          <span>Microsoft Office</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-75"></div>
          </div>
        </div>
      </div>
      <div class="bg-blue-200 p-4 rounded-lg shadow"> <!-- Languages -->
        <h2 class="text-lg font-semibold text-blue-800">Languages</h2>
        <div class="mt-2">
          <span>English</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-90"></div>
          </div>
          <span>Indonesian</span>
          <div class="bg-gray-300 h-2 rounded mb-2">
            <div class="bg-blue-500 h-2 rounded w-100"></div>
          </div>
        </div>
      </div>
    </section>

    <!-- Experience and Education Section -->
    <section class="mt-4 grid grid-cols-2 gap-4">
      <!-- Experience Section -->
      <div class="bg-white p-4 rounded-lg shadow">
        <h2 class="text-2xl font-semibold text-blue-700">Experience</h2>
        <div class="mt-2">
          <strong>Internship</strong>
          <div>1. Customer Service di Telkom Medan (Juni 2021 - Agustus 2021)</div>
        </div>
        <div class="mt-4">
          <strong>Organization/Committee</strong>
          <div>1. Assistant Event Coordinator Creanomic (Agustus 2024 - Oktober 2024)</div>
          <div>2. Public Relations Committee PKKMB Yuwaraja Fakultas Vokasi Universitas Brawijaya (Agustus 2024 - Oktober 2024)</div>
          <div>3. Vocational Student Executive Body of Brawijaya University, Ministry of Creative Economy (2023 - 2024)</div>
          <div>4. Student Activity Unit, Partnership Division (2023 - 2024)</div>
          <div>5. Information Technology Student Association, Talent and Interest Department (2023)</div>
          <div>6. Youth Red Cross of Telkom Vocational School Medan (2021 - 2022)</div>
        </div>
        <div class="mt-4">
          <strong>Project</strong>
          <div>1. Design of the Colleg-Go application using Figma.</div>
          <div>2. Creating a Skillwave web application based on HTML.</div>
        </div>
      </div>

      <!-- Education Section -->
      <div class="bg-white p-4 rounded-lg shadow">
        <h2 class="text-2xl font-semibold text-blue-700">Education</h2>
        <p><strong>Universitas Brawijaya</strong></p>
        <p>Teknologi Informasi (2023 - sekarang)</p>
        <p><strong>SMK Telkom Medan</strong></p>
        <p>Teknik Jurusan Akses (2020 - 2023)</p>
      </div>
    </section>

    <!-- Project Section with Slider -->
    <section id="projects" class="mt-4">
  <h2 class="text-2xl font-semibold text-blue-700">My Project</h2>
  <div class="relative mt-4">
    <div id="carousel" class="flex overflow-x-scroll space-x-4">
      <div class="flex-none w-72">
        <img src="./assets/img/public Relations.jpg" alt="Branding" class="w-full h-auto object-cover rounded-lg">
      </div>
      <div class="flex-none w-72">
        <img src="./assets/img/release your pontential.jpg" alt="Branding" class="w-full h-auto object-cover rounded-lg">
      </div>
      <div class="flex-none w-72">
        <img src="./assets/img/public speaking.jpg" alt="Branding" class="w-full h-auto object-cover rounded-lg">
      </div>
      <div class="flex-none w-72">
        <img src="./assets/img/communication.jpg" alt="Branding" class="w-full h-auto object-cover rounded-lg">
      </div>
    </div>
    <button @click="prevSlide" class="absolute top-1/2 left-0 bg-blue-500 text-white px-4 py-2 rounded-full -translate-y-1/2">&lt;</button>
    <button @click="nextSlide" class="absolute top-1/2 right-0 bg-blue-500 text-white px-4 py-2 rounded-full -translate-y-1/2">&gt;</button>
  </div>
</section>

    <!-- Contact Section -->
    <section class="bg-blue-100 p-4 mt-4 rounded-lg shadow">
      <h2 class="text-lg font-semibold text-blue-800">Contact Me:</h2>
      <div class="grid grid-cols-1 gap-4 mt-2">
        <div class="bg-white p-2 rounded-lg shadow">
          <p>Email: <a href="mailto:maynandatobing@gmail.com" class="text-blue-600">maynandatobing@gmail.com</a></p>
        </div>
        <div class="bg-white p-2 rounded-lg shadow">
          <p>Instagram: <a href="https://www.instagram.com/txmy_" target="_blank" class="text-blue-600">Klik me</a></p>
        </div>
        <div class="bg-white p-2 rounded-lg shadow">
          <p>LinkedIn: <a href="https://www.linkedin.com/in/maynanda-tobing-354485289" target="_blank" class="text-blue-600">Klik me</a></p>
        </div>
        <div class="bg-white p-2 rounded-lg shadow">
          <p>GitHub: <a href="https://github.com/txmy05" target="_blank" class="text-blue-600">Klik me</a></p>
        </div>
      </div>
    </section>

  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    prevSlide() {
      const carousel = document.getElementById('carousel');
      carousel.scrollBy({ left: -carousel.clientWidth, behavior: 'smooth' });
    },
    nextSlide() {
      const carousel = document.getElementById('carousel');
      carousel.scrollBy({ left: carousel.clientWidth, behavior: 'smooth' });
    }
  }
}
</script>

<style scoped>
/* Add global styles here */
</style>
