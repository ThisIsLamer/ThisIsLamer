<div class="main d-flex d-center">
    <div style="width: 90%;">
      <h1 class="t-center">Hey there!</h1>
      <hr style="margin-top: -25px;">
      <div class="t-center" style="margin-bottom: 20px;">I am a Russian developer. I am ready to participate in amazing projects.</div>

      <div class="cards d-flex t-center">
        <div class="card">
          <div class="card_content">
            <div class="card_title">Skills</div>
            <div class="card_body">
              <hr style="margin-top: -5px; margin-bottom: 15px;">
              <div>
                Backend + Frontend<br>
                Server Applications & Bots<br>
                UI/UX Designer (First level)<br>
              </div>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card_content">
            <div class="card_title">Tech Stack</div>
            <div class="card_body">
              <hr style="margin-top: -5px; margin-bottom: 15px;">
              <div class="card_body">
                TypeScript<br>
                Python<br>
                Fastify<br>
                Vue.js (3)<br>
                MariaDB<br>
                MongoDB<br>
              </div>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card_content">
            <div class="card_title">Learning</div>
            <div class="card_body">
              <hr style="margin-top: -5px; margin-bottom: 15px;">
              <div class="card_body">
                dotNet<br>
                Unity<br>
                Bootstrap<br>
                Flutter<br>
              </div>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card_content">
            <div class="card_title">Contact</div>
            <div class="card_body">
              <hr style="margin-top: -5px; margin-bottom: 15px;">
              <div class="card_body">
                Discord: [Otter] Lamer#2800<br>
                Telegram: @Lamer13<br>
                Email: thisislamer13@gmail.com<br>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <style>
    .main {
      background-color: rgb(16, 2, 31);
      color: white;

      width: 100%;

      padding: 10px;
    }

    .cards {
      gap: 10px; 

      flex-wrap: wrap;
    }

    .card {
      flex:1 1 calc(33.33% - 30px);

      min-width: 250px;
      
      padding: 15px;

      display: flex;
      justify-content: center;

      border-radius: 7px;

      transition: .3s ease;
    }

    .card:hover {
      background-color: rgb(46, 20, 71);
    }

    .card:hover .card_body {
      transition: .9s ease;

      display: block;
    }

    .card_content {
      width: 90%;
    }

    .card_title {
      font-size: 25px;
      font-weight: 600;
    }

    .card_body{
      transition: .9s ease;

      display: none;
    }
  </style>
