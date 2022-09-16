<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>O/Slash</title>
    <style>
      body {
        padding: 0;
        margin: 0;
        font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont,
          'Segoe UI', Helvetica, 'Apple Color Emoji', Arial, sans-serif,
          'Segoe UI Emoji', 'Segoe UI Symbol';
      }
      .os_headerBg img {
        background-size: 100%;
        height: 40vh;
        object-fit: cover;
        object-position: center 50%;
        width: 100%;
      }
      .os_head_logo img {
        margin-top: -7vh;
        width: 130px;
        height: 130px;
      }
      .os_video_sec {
        text-align: left;
      }
      .os_video_sec h2 {
        margin-bottom: 10px;
        font-size: 40px;
      }
      .os_video_sec p {
        font-size: 16px;
      }
      @media (max-width: 768px) {
        .container,
        .container-lg,
        .container-md,
        .container-sm,
        .container-xl,
        .container-xxl {
          padding-right: 1rem !important;
          padding-left: 1rem !important;
        }
      }
      @media (max-width: 1400px) {
        .container,
        .container-lg,
        .container-md,
        .container-sm,
        .container-xl,
        .container-xxl {
          padding-right: 3rem;
          padding-left: 3rem;
        }
      }
      @media (min-width: 1400px) {
        .container,
        .container-lg,
        .container-md,
        .container-sm,
        .container-xl,
        .container-xxl {
          max-width: 660px;
          margin-right: auto;
          margin-left: auto;
          padding-right: 3rem;
          padding-left: 3rem;
        }
      }
      .os_contact span,
      .os_contact a {
        border-color: rgba(55, 53, 47, 0.4);
        color: #a5a4a1;
      }
      .os_notion_sec h2 {
        font-size: 1.8em;
        font-weight: 500;
      }
      .os_bonus_sec h2 {
        font-size: 1.4em;
        font-weight: 500;
      }
      .os_bonus_sec ul {
        list-style: none;
        padding-left: 0;
      }
      .os_ref_sec ul,
      .os_expectations_sec ul {
        padding-left: 20px;
      }
      .os_ref_sec a,
      .os_expectations_sec a {
        border-color: rgba(55, 53, 47, 0.4);
        color: #a5a4a1;
      }
      .os_ref_sec h4,
      .os_expectations_sec h4,
      .os_delivery_sec h4,
      .os_contact h4 {
        font-size: 1.2em;
        font-weight: 500;
      }
      @media (max-width: 767px) {
        .os_video_sec iframe {
          width: 100%;
          height: 380px;
        }
        .os_video_sec h2 {
          font-size: 24px;
        }
        .os_headerBg img {
          object-position: right;
        }
      }
    </style>
  </head>
  <body>
    <section>
      <div class="os_headerBg">
        <img src="./images/header-bannerbg.png" alt="" />
      </div>
      <div class="container-xxl">
        <div class="os_head_logo">
          <img src="./images/oslash-ic.png" alt="" />
        </div>
        <div class="os_video_sec">
          <h2>OSlash - UI Developer Assignment</h2>
          <p>About OSlash</p>
          <iframe
            src="https://www.youtube.com/embed/9EsVAlYA4LY?feature=oembed"
            frameborder="0"
            width="650"
            height="375"
            sandbox="allow-scripts allow-popups allow-top-navigation-by-user-activation allow-forms allow-same-origin"
          ></iframe>
          <p>
            OSlash is looking to hire an experienced UI Developer to join our
            in-house team. If you love optimizing applications, ensuring UI/UX
            feasibility, and building beautiful user experiences, we’d love to
            have you be a part of our small team!
          </p>
          <div class="os_notion_sec">
            <h2>Notion Share Widget</h2>
            <p>
              Goal: To build a re-usable notion share widget component with
              plain CSS + any JavaScript Framework of your choice
            </p>
            <p>
              Starter: You can use one of vite’s starter kits or bring your own
              setup to showcase the widget
            </p>
          </div>
          <div class="os_bonus_sec">
            <h2>Bonus Points</h2>
            <ul>
              <li>1. Use of Modern CSS features like flex & grid</li>
              <li>
                2. Focus on keyboard friendly navigation throughout the UI
              </li>
              <li>
                3. Taking full advantage of
                [Storybook](https://storybook.js.org/) & building interactive
                stories
              </li>
              <li>
                4. A neat writeup of the principles & ideas you followed for
                building the widget in the README
              </li>
            </ul>
            <p>
              The component should be flexible enough to be used in any part of
              the Application without causing any issues with existing CSS.
            </p>
          </div>
          <div class="os_ref_sec">
            <h4>References:</h4>
            <ul>
              <li>
                Storybooks Showcase:
                <a href="https://storybook.js.org/showcase/" target="_blank">
                  https://storybook.js.org/showcase/</a
                >
              </li>
              <li>
                Refer the actual share widget in
                <a herf="https://www.notion.so/" target="_blank">notion.so</a>
              </li>
            </ul>
          </div>
          <div class="os_expectations_sec">
            <h4>⛳️ Expectations</h4>
            <p>The most important things we look for in your solution are —</p>
            <ul>
              <li>Solving the main problem.</li>
              <li>
                Concise and useful documentation (including references, known
                issues, local development instructions, etc.).
              </li>
              <li>
                Frequent and
                <a
                  href="https://chris.beams.io/posts/git-commit/"
                  target="_blank"
                >
                  good commit messages.</a
                >
              </li>
              <li>
                Following good code quality principles – including building for
                extensibility.
              </li>
              <li>Unit and/or integration tests.</li>
            </ul>
          </div>
          <div class="os_delivery_sec">
            <h4>📦 Delivery</h4>
            <p>
              Please include instructions to compile the apps and run them on
              our devices in your README.
            </p>
            <p>
              You can send us links to your solution at hiring@oslash.com. If
              you do not wish to host your code publicly, please bundle your Git
              repo and email it to us as an attachment.
            </p>
          </div>
          <div class="os_contact">
            <h4>☎️ Contacts</h4>
            <p>
              1. Talent Acquisition —
              <a
                href="https://www.linkedin.com/in/yogesh-sp-8503b878/"
                target="_blank"
              >
                Yogesh
              </a>
              <span
                >-<a href="mailto:yogesh.sp@oslash.com"> yogesh.sp@oslash.com</a
                >,<a
                  href="tel:+91
              7812847071"
                >
                  +91 7812847071</a
                ></span
              >
            </p>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>
