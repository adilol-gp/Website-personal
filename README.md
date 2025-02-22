<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Laman Pembelajaran Islam</title>
  <!-- Google Fonts: Poppins -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* Gaya Asas */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #6d6d6d, #a0a0a0);
      color: #fff;
      line-height: 1.6;
    }
    /* Navigasi */
    nav {
      background: rgba(0, 0, 0, 0.85);
      padding: 15px 0;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.5);
    }
    nav a {
      color: #f8d16e;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #fff;
    }
    /* Seksyen Umum */
    .section {
      padding: 120px 20px 60px;
      margin-top: 60px;
    }
    /* Pembungkus Kandungan */
    .content-wrapper {
      background: rgba(0, 0, 0, 0.75);
      padding: 40px;
      border-radius: 10px;
      margin: 0 auto;
      max-width: 800px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
    }
    /* Jadual */
    .matrix-table {
      margin: 20px auto;
      border-collapse: collapse;
      width: 90%;
      max-width: 600px;
    }
    .matrix-table th,
    .matrix-table td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: left;
      font-size: 16px;
    }
    .matrix-table th {
      background-color: #f8d16e;
      color: #000;
    }
    /* Pembungkus Video */
    .video-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    .video {
      width: 300px;
      background: #000;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    }
    .video h3 {
      background: #f8d16e;
      color: #000;
      margin: 0;
      padding: 10px;
      font-size: 18px;
    }
    iframe {
      width: 100%;
      height: 200px;
      border: none;
    }
    /* Kuiz */
    #quiz {
      margin: 20px auto;
      max-width: 500px;
    }
    .question-container {
      background: #333;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    }
    .question-container .question {
      font-weight: bold;
      margin-bottom: 10px;
      font-size: 18px;
    }
    .options {
      padding: 0;
    }
    .options li {
      list-style: none;
      padding: 12px;
      background: #555;
      margin: 8px 0;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s ease;
    }
    .options li:hover {
      background: #666;
    }
    /* Butang */
    button {
      background: #f8d16e;
      color: #000;
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s ease;
      margin: 10px;
    }
    button:hover {
      background: #e0b85a;
    }
    /* Responsif */
    @media (max-width: 600px) {
      nav a {
        margin: 0 8px;
        font-size: 14px;
      }
      .content-wrapper {
        padding: 20px;
      }
      .video {
        width: 90%;
      }
      .matrix-table {
        font-size: 14px;
      }
    }
    /* Gaya khusus untuk bahagian Definisi */
    #definisi .content-wrapper {
      font-family: 'Poppins', sans-serif;
    }
    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0, 0, 0, 0.85);
      color: #f8d16e;
      margin-top: 40px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <!-- Navigasi -->
  <nav>
    <a href="#pengenalan">Pengenalan</a>
    <a href="#definisi">Definisi</a>
    <a href="#objektif">Objektif</a>
    <a href="#video">Video</a>
    <a href="#kerangka">Kerangka Projek</a>
    <a href="#laporan">Laporan Projek</a>
    <a href="#soalan">Soalan Kuiz</a>
  </nav>

  <!-- Pengenalan -->
  <section id="pengenalan" class="section">
    <div class="content-wrapper">
      <h2>Pengenalan</h2>
      <p>Laman ini dibina untuk menyediakan video pembelajaran Islam bagi Projek Pendidikan Islam (WI001).</p>
      
      <!-- Maklumat Kumpulan -->
      <h3>Kami dari Kumpulan 4</h3>
      <p>Ahli yang terlibat:</p>
      
      <table class="matrix-table">
        <tr>
          <th>Bil</th>
          <th>Nama</th>
          <th>No. Matriks</th>
          <th>Jawatan</th>
        </tr>
        <tr>
          <td>1</td>
          <td>MUHAMMAD ALIF NAQIUDDIN BIN KHAIRUL RAZI</td>
          <td>MA2411400037</td>
          <td>KETUA PROJEK</td>
        </tr>
        <tr>
          <td>2</td>
          <td>MUHAMMAD IFWAT BIN HILMY</td>
          <td>MA2411100258</td>
          <td>SETIAUSAHA</td>
        </tr>
        <tr>
          <td>3</td>
          <td>AHMAD MIQDAD BIN ZAHARI</td>
          <td>MA2411100282</td>
          <td>AJK MULTIMEDIA</td>
        </tr>
        <tr>
          <td>4</td>
          <td>MUHAMMAD NUR JURAIDI BIN ZAINAL</td>
          <td>MA2411100375</td>
          <td>AJK DIGITAL</td>
        </tr>
      </table>
    </div>
  </section>

  <!-- Definisi Ahli Sunnah Wal Jamaah -->
  <section id="definisi" class="section">
    <div class="content-wrapper">
      <h2>Definisi Ahli Sunnah Wal Jamaah</h2>
      <p>Istilah Ahli Sunnah Wal Jamaah berasal daripada dua perkataan iaitu “ahl al-Sunnah” dan “al-Jamaah” yang merujuk kepada golongan yang mengikuti pegangan Nabi Muhammad s.a.w. serta jalan hidup Baginda dan para sahabat.</p>
    </div>
  </section>

  <!-- Objektif -->
  <section id="objektif" class="section">
    <div class="content-wrapper">
      <h2>Objektif</h2>
      <p><strong>1. Menjelaskan tentang Akidah dan Ajaran Islam.</strong></p>
      <p><strong>2. Menjelaskan tentang Kepelbagaian Mazhab.</strong></p>
      <p><strong>3. Menjelaskan tentang Kesatuan dan Keharmonian.</strong></p>
    </div>
  </section>

  <!-- Video -->
  <section id="video" class="section">
    <div class="content-wrapper">
      <h2>Video Pembelajaran Islam</h2>
      <div class="video-container">
        <div class="video">
  <h3>Akidah dan Ajaran Islam</h3>
  <!-- Video pertama dengan pautan yang betul -->
  <iframe src="https://www.youtube.com/embed/R2vsmZ-ZXQ4?si=zmum9QgaRloPMBYt" allowfullscreen></iframe>
</div>

        <div class="video">
          <h3>Kepelbagaian Mazhab</h3>
          <!-- Video kedua dengan pautan baru -->
          <iframe src="https://www.youtube.com/embed/eJMtsvnR2Qg?si=zY5xHBBJOLAyw2u3" allowfullscreen></iframe>
        </div>
        <div class="video">
          <h3>Kesatuan dan Keharmonian</h3>
          <!-- Sila gantikan VIDEO_ID3 dengan pautan video yang sah -->
          <iframe src="https://www.youtube.com/embed/VIDEO_ID3" allowfullscreen></iframe>
        </div>
      </div>
    </div>
  </section>

  <!-- Kerangka Projek -->
  <section id="kerangka" class="section">
    <div class="content-wrapper">
      <h2>Kerangka Projek</h2>
      <p>Kerangka projek ini merupakan hasil projek pendidikan Islam yang dikembangkan secara berperingkat.</p>
      <a href="https://drive.google.com/file/d/12NQIYu8fPARDE6FINUsJZmXy9w0nCima/view?usp=sharing" target="_blank" style="color:#f8d16e;">
        Buka Kerangka Projek (PDF)
      </a>
    </div>
  </section>

  <!-- Laporan Projek -->
  <section id="laporan" class="section">
    <div class="content-wrapper">
      <h2>Laporan Projek</h2>
      <p>Laporan ini memaparkan hasil projek pembelajaran Islam yang telah kami jalankan.</p>
      <a href="https://drive.google.com/file/d/YourLaporanFileID/view?usp=sharing" target="_blank" style="color:#f8d16e;">
        Buka Laporan Projek (PDF)
      </a>
    </div>
  </section>

  <!-- Soalan Kuiz -->
  <section id="soalan" class="section">
    <div class="content-wrapper">
      <h2>Soalan Kuiz: Ahli Sunnah Wal Jamaah</h2>
      <p>Uji pengetahuan anda mengenai aspek-aspek yang telah disampaikan dalam objektif:</p>
      <div id="quiz">
        <div class="question-container" id="question-container">
          <div class="question" id="question">Soalan akan dipaparkan di sini</div>
          <ul class="options" id="options"></ul>
        </div>
        <button onclick="nextQuestion()" id="next-btn">Seterusnya</button>
        <button onclick="restartQuiz()" id="restart-btn" style="display:none;">Cuba Lagi</button>
        <div class="result" id="result"></div>
      </div>
    </div>
  </section>

  <script>
    // Senarai soalan (total 15 soalan)
    const questions = [
      {
        question: "Apa yang dimaksudkan dengan akidah dalam Islam?",
        options: [
          "Sistem kepercayaan asas dalam Islam",
          "Tradisi budaya",
          "Seni dan seni bina",
          "Cerita rakyat"
        ],
        answer: "Sistem kepercayaan asas dalam Islam"
      },
      {
        question: "Manakah yang merupakan contoh kepelbagaian mazhab dalam Islam?",
        options: [
          "Mazhab Syafi'i, Maliki, Hanafi, dan Hanbali",
          "Mazhab Barat dan Timur",
          "Mazhab moden dan tradisional",
          "Mazhab A, B, dan C"
        ],
        answer: "Mazhab Syafi'i, Maliki, Hanafi, dan Hanbali"
      },
      {
        question: "Mengapakah kesatuan dan keharmonian penting dalam Islam?",
        options: [
          "Supaya umat Islam dapat saling menyokong dan bersatu",
          "Supaya semua negara menggunakan satu bahasa",
          "Supaya ekonomi berkembang",
          "Supaya tradisi berubah"
        ],
        answer: "Supaya umat Islam dapat saling menyokong dan bersatu"
      },
      {
        question: "Bagaimanakah ajaran Islam menekankan nilai-nilai kesatuan?",
        options: [
          "Dengan mengutamakan perpaduan umat",
          "Dengan mengutamakan perbezaan budaya",
          "Dengan memisahkan masyarakat mengikut warna",
          "Dengan menolak perbezaan pendapat"
        ],
        answer: "Dengan mengutamakan perpaduan umat"
      },
      {
        question: "Apakah peranan utama Al-Qur'an dalam akidah umat Islam?",
        options: [
          "Sebagai sumber hukum dan panduan hidup",
          "Hanya sebagai karya sastera",
          "Sebagai buku sejarah",
          "Sebagai koleksi cerita rakyat"
        ],
        answer: "Sebagai sumber hukum dan panduan hidup"
      },
      {
        question: "Mazhab manakah yang dikenali dengan pendekatan yang lebih fleksibel dalam interpretasi hukum?",
        options: [
          "Mazhab Hanafi",
          "Mazhab Maliki",
          "Mazhab Syafi'i",
          "Mazhab Hanbali"
        ],
        answer: "Mazhab Hanafi"
      },
      {
        question: "Apakah makna utama istilah 'Ummah' dalam konteks kesatuan Islam?",
        options: [
          "Komuniti umat Islam di seluruh dunia",
          "Sebuah kumpulan politik",
          "Sebuah organisasi kebajikan",
          "Sebuah sekolah agama"
        ],
        answer: "Komuniti umat Islam di seluruh dunia"
      },
      {
        question: "Salah satu asas ajaran akidah ialah tauhid. Apakah maksud tauhid?",
        options: [
          "Mengesakan Allah",
          "Menyembah berhala",
          "Memperbanyak ibadah",
          "Menghormati para nabi"
        ],
        answer: "Mengesakan Allah"
      },
      {
        question: "Dalam konteks mazhab, apakah yang dimaksudkan dengan ijtihad?",
        options: [
          "Proses penaakulan dalam hukum Islam",
          "Sebuah ibadah ritual",
          "Sambutan hari besar",
          "Aktiviti sosial"
        ],
        answer: "Proses penaakulan dalam hukum Islam"
      },
      {
        question: "Apakah tujuan utama pelaksanaan mazhab dalam kehidupan umat Islam?",
        options: [
          "Untuk mengatur dan memudahkan pelaksanaan syariat",
          "Untuk membahagikan umat Islam kepada kumpulan-kumpulan kecil",
          "Untuk menimbulkan perpecahan",
          "Untuk memusnahkan tradisi lama"
        ],
        answer: "Untuk mengatur dan memudahkan pelaksanaan syariat"
      },
      {
        question: "Salah satu nilai penting dalam kesatuan Islam ialah ukhuwah. Apakah maksudnya?",
        options: [
          "Persaudaraan",
          "Pertentangan",
          "Kepimpinan",
          "Kemewahan"
        ],
        answer: "Persaudaraan"
      },
      {
        question: "Bagaimanakah cara ajaran Islam menggalakkan keharmonian di kalangan umat?",
        options: [
          "Dengan menekankan toleransi dan saling menghargai",
          "Dengan mengutamakan perbezaan",
          "Dengan mengehadkan interaksi",
          "Dengan menetapkan peraturan yang ketat"
        ],
        answer: "Dengan menekankan toleransi dan saling menghargai"
      },
      {
        question: "Mengapakah penting untuk memahami perbezaan antara mazhab dalam Islam?",
        options: [
          "Untuk saling menghormati perbezaan dan mencari persamaan",
          "Untuk menguatkan perbezaan dan memecahbelahkan",
          "Untuk menghapuskan semua perbezaan",
          "Untuk meningkatkan persaingan antara mazhab"
        ],
        answer: "Untuk saling menghormati perbezaan dan mencari persamaan"
      },
      {
        question: "Apakah salah satu cara untuk mengaplikasikan akidah dalam kehidupan seharian?",
        options: [
          "Dengan sentiasa mengingati dan mengamalkan ajaran Islam",
          "Dengan mengabaikan perintah agama",
          "Dengan mengikuti trend moden semata-mata",
          "Dengan menolak segala bentuk tradisi"
        ],
        answer: "Dengan sentiasa mengingati dan mengamalkan ajaran Islam"
      },
      {
        question: "Mengapakah penting bagi umat Islam menghormati perbezaan mazhab demi mencapai kesatuan umat?",
        options: [
          "Kerana menghargai perbezaan akan menguatkan solidariti dan saling memahami",
          "Kerana semua mazhab mempunyai peraturan yang sama",
          "Kerana perbezaan mazhab tidak bernilai",
          "Kerana hanya satu mazhab yang benar"
        ],
        answer: "Kerana menghargai perbezaan akan menguatkan solidariti dan saling memahami"
      },
      {
        question: "Dalam ajaran Islam, bagaimanakah peranan ilmu pengetahuan berkaitan dengan akidah?",
        options: [
          "Ilmu pengetahuan menyokong pemahaman yang lebih mendalam tentang ajaran Islam",
          "Ilmu pengetahuan tidak berkaitan dengan agama",
          "Ilmu pengetahuan menggantikan peranan agama",
          "Ilmu pengetahuan hanya untuk kepentingan duniawi"
        ],
        answer: "Ilmu pengetahuan menyokong pemahaman yang lebih mendalam tentang ajaran Islam"
      }
    ];

    let currentQuestionIndex = 0;
    let score = 0;

    // Fungsi untuk memuatkan soalan
    function loadQuestion() {
      const questionObj = questions[currentQuestionIndex];
      document.getElementById('question').textContent = questionObj.question;
      const optionsList = document.getElementById('options');
      optionsList.innerHTML = ''; // Reset pilihan

      questionObj.options.forEach(option => {
        const li = document.createElement('li');
        li.textContent = option;
        li.onclick = () => checkAnswer(option);
        optionsList.appendChild(li);
      });
    }

    // Fungsi untuk memeriksa jawapan
    function checkAnswer(selectedAnswer) {
      const correctAnswer = questions[currentQuestionIndex].answer;
      if (selectedAnswer === correctAnswer) {
        score++;
      }
      // Lumpuhkan semua pilihan selepas dijawab
      const options = document.querySelectorAll('.options li');
      options.forEach(option => {
        option.style.pointerEvents = 'none';
      });
      // Aktifkan butang seterusnya
      document.getElementById('next-btn').disabled = false;
    }

    // Fungsi untuk soalan seterusnya
    function nextQuestion() {
      currentQuestionIndex++;
      if (currentQuestionIndex < questions.length) {
        loadQuestion();
        document.getElementById('next-btn').disabled = true;
      } else {
        document.getElementById('result').textContent = 
          `Kuiz Selesai! Skor Anda: ${score} / ${questions.length}`;
        document.getElementById('next-btn').style.display = 'none';
        document.getElementById('restart-btn').style.display = 'block';
      }
    }

    // Fungsi untuk mengulangi kuiz
    function restartQuiz() {
      currentQuestionIndex = 0;
      score = 0;
      document.getElementById('result').textContent = '';
      document.getElementById('next-btn').style.display = 'block';
      document.getElementById('restart-btn').style.display = 'none';
      loadQuestion();
      document.getElementById('next-btn').disabled = true;
    }

    // Muatkan soalan pertama semasa laman dimuatkan
    loadQuestion();
    document.getElementById('next-btn').disabled = true;
  </script>

  <!-- Ucapan Terima Kasih -->
  <footer>
    <p><strong>Terima Kasih kerana sudi melawati laman web kami.</strong></p>
  </footer>
</body>
</html>
