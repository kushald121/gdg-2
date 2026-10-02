<!-- ================= FOOTER ================= -->

<style>
  /* Footer styling only */
  footer {
    background: #0f1335;
    color: #f5f5f5;
    padding: 70px 6% 35px;
    font-family: Arial, Helvetica, sans-serif;
  }

  .footer-top {
    display: grid;
    grid-template-columns: 1.3fr 1fr 1fr;
    gap: 70px;
    max-width: 1600px;
    margin: auto;
  }

  footer h3 {
    color: #ffffff;
    font-size: 24px;
    letter-spacing: 4px;
    margin-bottom: 28px;
  }

  footer p {
    font-size: 18px;
    line-height: 1.55;
    margin: 0;
    max-width: 540px;
  }

  .footer-links {
    display: flex;
    flex-direction: column;
    gap: 18px;
  }

  .footer-links a {
    color: #eeeeee;
    text-decoration: none;
    font-size: 18px;
    transition: 0.2s ease;
  }

  .footer-links a:hover {
    color: #fbbc04;
    transform: translateX(4px);
  }

  .social-link {
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .social-link i {
    width: 22px;
    text-align: center;
    font-size: 19px;
  }

  .footer-bottom {
    max-width: 1600px;
    margin: 65px auto 0;
    padding-top: 30px;
    border-top: 1px dashed rgba(255, 255, 255, 0.25);

    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
  }

  .footer-bottom p {
    font-size: 16px;
    margin: 0;
  }

  .footer-next {
    color: #fbbc04;
    font-family: "Comic Sans MS", cursive;
    font-size: 18px;
    font-weight: bold;
  }

  @media (max-width: 800px) {
    .footer-top {
      grid-template-columns: 1fr;
      gap: 45px;
    }

    .footer-bottom {
      flex-direction: column;
      align-items: flex-start;
    }
  }
</style>

<!-- Font Awesome for social icons -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
>

<footer>

  <div class="footer-top">

    <!-- GDG LTCE -->
    <div>
      <h3>GDG LTCE</h3>

      <p>
        Google Developer Groups · Lokmanya Tilak
        College of Engineering, University of Mumbai.
        We learn, build & connect — loudly, and with
        stickers.
      </p>
    </div>


    <!-- SKIM AGAIN -->
    <div>
      <h3>Skim again</h3>

      <div class="footer-links">
        <a href="#speaker">Speaker</a>
        <a href="#perks">Perks</a>
        <a href="#plan">Plan</a>
        <a href="#devcon">DevCon</a>
        <a href="#loot">Loot</a>
        <a href="#passes">Passes</a>
        <a href="#insta-card">Insta card</a>
      </div>
    </div>


    <!-- SAY HI -->
    <div>
      <h3>Say hi</h3>

      <div class="footer-links">

        <a
          class="social-link"
          href="https://www.instagram.com/gdg_ltcoe/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-brands fa-instagram"></i>
          <span>Instagram · @gdg_ltcoe</span>
        </a>

        <a
          class="social-link"
          href="https://x.com/GDG_LTCoE"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-brands fa-x-twitter"></i>
          <span>X · @GDG_LTCoE</span>
        </a>

        <a
          class="social-link"
          href="https://www.linkedin.com/company/gdg-ltcoe/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-brands fa-linkedin"></i>
          <span>LinkedIn · GDG LTCE</span>
        </a>

        <a
          class="social-link"
          href="https://gdg.community.dev/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <i class="fa-solid fa-globe"></i>
          <span>GDG Community</span>
        </a>

        <a
          class="social-link"
          href="mailto:gdg.ltcoe@gmail.com"
        >
          <i class="fa-solid fa-envelope"></i>
          <span>Mail the core team</span>
        </a>

      </div>
    </div>

  </div>


  <!-- BOTTOM -->
  <div class="footer-bottom">

    <p>
      © 2026 GDG LTCE · made with ☕ & commits
    </p>

    <div class="footer-next">
      see you tuesday, 2:00 sharp →
    </div>

  </div>

</footer>
