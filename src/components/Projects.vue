<template>
  <section class="projects" id="projects">
    <!-- Abstract Background -->
    <div class="projects-bg">
      <svg
        class="abstract-shape blob-1"
        viewBox="0 0 200 200"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill="var(--laravel-red)"
          d="M39.5,-65.6C51.4,-58.1,61.3,-47.3,68.1,-34.8C74.9,-22.3,78.6,-8.1,78.3,6.2C78,20.5,73.7,35,65.8,47.2C57.9,59.4,46.4,69.3,33.3,74.8C20.2,80.3,5.5,81.4,-9.8,78.9C-25.1,76.4,-41,70.3,-54.3,60.5C-67.6,50.7,-78.3,37.2,-82.4,21.8C-86.5,6.4,-84,-10.9,-76.8,-25.5C-69.6,-40.1,-57.7,-52,-44.2,-59.8C-30.7,-67.6,-15.4,-71.3,-0.3,-70.8C14.8,-70.3,27.6,-73.1,39.5,-65.6Z"
          transform="translate(100 100)"
        />
      </svg>

      <svg
        class="abstract-shape blob-2"
        viewBox="0 0 200 200"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill="var(--pink)"
          d="M44.7,-76.4C58.8,-69.2,71.8,-59.1,79.6,-45.8C87.4,-32.6,90,-16.3,88.5,-0.9C87,14.6,81.4,29.2,73.1,42.8C64.8,56.4,53.8,69,40.2,75.8C26.6,82.6,10.4,83.6,-5.3,81.3C-21,79,-42,73.4,-56.8,62.3C-71.6,51.2,-80.2,34.6,-83.8,16.8C-87.4,-1,-86,-20,-78.2,-36.4C-70.4,-52.8,-56.2,-66.6,-40.8,-73.3C-25.4,-80,-12.7,-79.5,1.3,-81.7C15.3,-83.9,30.6,-83.6,44.7,-76.4Z"
          transform="translate(100 100)"
        />
      </svg>

      <svg
        class="curved-line"
        viewBox="0 0 1440 320"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill="none"
          stroke="var(--vue-green)"
          stroke-width="2"
          stroke-opacity="0.2"
          d="M0,256L48,240C96,224,192,192,288,181.3C384,171,480,181,576,197.3C672,213,768,235,864,224C960,213,1056,171,1152,154.7C1248,139,1344,149,1392,154.7L1440,160"
        ></path>
      </svg>
    </div>

    <h2 class="section-heading">Some Things I've Built</h2>

    <ul class="projects-grid">
      <li class="project" data-direction="left">
        <div class="project-content">
          <div class="project-overline">Featured Project</div>
          <h3 class="project-title">
            <a
              href="https://github.com/mansour-aldadah/Fuels"
              target="_blank"
              rel="noopener noreferrer"
            >
              Fuel Management System
            </a>
          </h3>
          <div class="project-description">
            <p>
              A custom Laravel-based system developed for Kamal Edwan Hospital
              to digitize and streamline internal fuel management operations.
              Features real-time tracking, role-based access control, and
              comprehensive analytics dashboard.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Laravel</li>
            <li>Vue.js</li>
            <li>MySQL</li>
            <li>RESTful API</li>
            <li>Sanctum</li>
          </ul>
          <div class="project-links">
            <a
              href="https://github.com/mansour-aldadah/Fuels"
              aria-label="GitHub Link"
              target="_blank"
              rel="noopener noreferrer"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-github"
              >
                <path
                  d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                ></path>
              </svg>
            </a>
          </div>
        </div>
        <div class="project-image">
          <a
            href="https://github.com/mansour-aldadah/Fuels"
            target="_blank"
            rel="noopener noreferrer"
          >
            <div class="img">
              <img src="/Fuels.png" alt="Fuel Management System" />
            </div>
          </a>
        </div>
      </li>

      <li class="project" data-direction="right">
        <div class="project-content">
          <div class="project-overline">Featured Project</div>
          <h3 class="project-title">
            <a
              href="https://github.com/mansour-aldadah/Classroom"
              target="_blank"
              rel="noopener noreferrer"
            >
              Classroom Clone
            </a>
          </h3>
          <div class="project-description">
            <p>
              A comprehensive Google Classroom clone built with modern web
              technologies. Features class management, assignment creation,
              student submissions, real-time notifications, and collaborative
              learning tools with intuitive user interface.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Laravel</li>
            <li>Vue.js</li>
            <li>Inertia.js</li>
            <li>Tailwind CSS</li>
            <li>MySQL</li>
          </ul>
          <div class="project-links">
            <a
              href="https://github.com/mansour-aldadah/Classroom"
              aria-label="GitHub Link"
              target="_blank"
              rel="noopener noreferrer"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-github"
              >
                <path
                  d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                ></path>
              </svg>
            </a>
          </div>
        </div>
        <div class="project-image">
          <a
            href="https://github.com/mansour-aldadah/Classroom"
            target="_blank"
            rel="noopener noreferrer"
          >
            <div class="img">
              <img src="/Classroom.png" alt="Classroom Clone" />
            </div>
          </a>
        </div>
      </li>

      <li class="project" data-direction="left">
        <div class="project-content">
          <div class="project-overline">Featured Project</div>
          <h3 class="project-title">
            <a
              href="https://github.com/mansour-aldadah/QRest"
              target="_blank"
              rel="noopener noreferrer"
            >
              QRest
            </a>
          </h3>
          <div class="project-description">
            <p>
              A QR code-based restaurant menu and ordering system. Customers
              scan QR codes to view menus, place orders, and make payments
              digitally. Streamlines restaurant operations and enhances customer
              experience with contactless ordering.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Laravel</li>
            <li>Vue.js</li>
            <li>QR Code API</li>
            <li>Payment Gateway</li>
          </ul>
        </div>
        <div class="project-image">
          <a
            href="https://github.com/mansour-aldadah/QRest"
            target="_blank"
            rel="noopener noreferrer"
          >
            <div class="img">
              <img src="/QRest.png" alt="QRest" />
            </div>
          </a>
        </div>
      </li>

      <li class="project" data-direction="right">
        <div class="project-content">
          <div class="project-overline">Featured Project</div>
          <h3 class="project-title">
            <a
              href="https://github.com/mansour-aldadah/Flash-48"
              target="_blank"
              rel="noopener noreferrer"
            >
              Flash 48
            </a>
          </h3>
          <div class="project-description">
            <p>
              A dynamic marketplace platform for merchants to publish and promote
              their products through time-limited advertisements. Ads run for 48 hours,
              creating urgency and encouraging quick customer engagement with featured deals.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Laravel</li>
            <li>Vue.js</li>
            <li>MySQL</li>
            <li>RESTful API</li>
          </ul>
        </div>
        <div class="project-image">
          <a
            href="https://github.com/mansour-aldadah/Flash-48"
            target="_blank"
            rel="noopener noreferrer"
          >
            <div class="img">
              <img src="/Flash48.png" alt="Flash 48" />
            </div>
          </a>
        </div>
      </li>

      <li class="project" data-direction="left">
        <div class="project-content">
          <div class="project-overline">Featured Project</div>
          <h3 class="project-title">
            <a
              href="https://github.com/mansour-aldadah/Mockur"
              target="_blank"
              rel="noopener noreferrer"
            >
              Mockur
            </a>
          </h3>
          <div class="project-description">
            <p>
              A responsive mockup generator for creating professional website previews
              across multiple devices. Generate device mockups, preview responsive designs,
              and download production-ready images for presentations and portfolios.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Laravel</li>
            <li>Vue.js</li>
            <li>Canvas API</li>
            <li>Image Processing</li>
          </ul>
          <div class="project-links">
            <a
              href="https://github.com/mansour-aldadah/Mockur"
              aria-label="GitHub Link"
              target="_blank"
              rel="noopener noreferrer"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-github"
              >
                <path
                  d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                ></path>
              </svg>
            </a>
          </div>
        </div>
        <div class="project-image">
          <a
            href="https://github.com/mansour-aldadah/Mockur"
            target="_blank"
            rel="noopener noreferrer"
          >
            <div class="img">
              <img src="/Mockur.png" alt="Mockur" />
            </div>
          </a>
        </div>
      </li>
    </ul>

    <div class="more-projects">
      <h3 class="other-projects-title">Other Noteworthy Projects</h3>
      <a
        class="inline-link archive-link"
        href="https://github.com/mansour-aldadah?tab=repositories"
        target="_blank"
        rel="noopener noreferrer"
      >
        view the archive
      </a>

      <ul class="projects-grid archive">
        <li class="project">
          <div class="project-inner">
            <header>
              <div class="project-top">
                <div class="project-image-thumb">
                  <a
                    href="https://github.com/mansour-aldadah/H-M-Clone"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img src="/HM.png" alt="H&M Clone" />
                  </a>
                </div>
                <div class="project-links">
                  <a
                    href="https://github.com/mansour-aldadah/H-M-Clone"
                    aria-label="GitHub Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-github"
                    >
                      <path
                        d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                      ></path>
                    </svg>
                  </a>
                </div>
              </div>
              <h3 class="project-title">
                <a
                  href="https://github.com/mansour-aldadah/H-M-Clone"
                  target="_blank"
                  rel="noopener noreferrer"
                  >H&M E-Commerce Clone</a
                >
              </h3>
              <div class="project-description">
                <p>
                  A pixel-perfect recreation of H&M's e-commerce website built
                  with React.js. Features product catalog, shopping cart, user
                  authentication, and responsive design.
                </p>
              </div>
            </header>
            <footer>
              <ul class="project-tech-list">
                <li>React.js</li>
                <li>JavaScript (ES6+)</li>
                <li>CSS3</li>
                <li>Responsive Design</li>
              </ul>
            </footer>
          </div>
        </li>

        <li class="project">
          <div class="project-inner">
            <header>
              <div class="project-top">
                <div class="project-image-thumb">
                  <a
                    href="https://mansour-aldadah.github.io/Leon/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img src="/Leon.png" alt="Leon" />
                  </a>
                </div>
                <div class="project-links">
                  <a
                    href="https://github.com/mansour-aldadah/Leon"
                    aria-label="GitHub Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-github"
                    >
                      <path
                        d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                      ></path>
                    </svg>
                  </a>
                  <a
                    href="https://mansour-aldadah.github.io/Leon/"
                    aria-label="External Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-external-link"
                    >
                      <path
                        d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"
                      ></path>
                      <polyline points="15 3 21 3 21 9"></polyline>
                      <line x1="10" y1="14" x2="21" y2="3"></line>
                    </svg>
                  </a>
                </div>
              </div>
              <h3 class="project-title">
                <a
                  href="https://mansour-aldadah.github.io/Leon/"
                  target="_blank"
                  rel="noopener noreferrer"
                  >Leon</a
                >
              </h3>
              <div class="project-description">
                <p>
                  A creative agency website template with modern design and
                  smooth animations. Features responsive layout and clean UI/UX.
                </p>
              </div>
            </header>
            <footer>
              <ul class="project-tech-list">
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Responsive Design</li>
              </ul>
            </footer>
          </div>
        </li>

        <li class="project">
          <div class="project-inner">
            <header>
              <div class="project-top">
                <div class="project-image-thumb">
                  <a
                    href="https://mansour-aldadah.github.io/KASPER/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img src="/Kasper.png" alt="Kasper" />
                  </a>
                </div>
                <div class="project-links">
                  <a
                    href="https://github.com/mansour-aldadah/KASPER"
                    aria-label="GitHub Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-github"
                    >
                      <path
                        d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                      ></path>
                    </svg>
                  </a>
                  <a
                    href="https://mansour-aldadah.github.io/KASPER/"
                    aria-label="External Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-external-link"
                    >
                      <path
                        d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"
                      ></path>
                      <polyline points="15 3 21 3 21 9"></polyline>
                      <line x1="10" y1="14" x2="21" y2="3"></line>
                    </svg>
                  </a>
                </div>
              </div>
              <h3 class="project-title">
                <a
                  href="https://mansour-aldadah.github.io/KASPER/"
                  target="_blank"
                  rel="noopener noreferrer"
                  >Kasper</a
                >
              </h3>
              <div class="project-description">
                <p>
                  A professional business website template featuring portfolio
                  showcase, services section, and contact forms with elegant
                  design.
                </p>
              </div>
            </header>
            <footer>
              <ul class="project-tech-list">
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Bootstrap</li>
              </ul>
            </footer>
          </div>
        </li>

        <li class="project">
          <div class="project-inner">
            <header>
              <div class="project-top">
                <div class="project-image-thumb">
                  <a
                    href="https://mansour-aldadah.github.io/Modest/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img src="/Modest.png" alt="Modest" />
                  </a>
                </div>
                <div class="project-links">
                  <a
                    href="https://github.com/mansour-aldadah/Modest"
                    aria-label="GitHub Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-github"
                    >
                      <path
                        d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                      ></path>
                    </svg>
                  </a>
                  <a
                    href="https://mansour-aldadah.github.io/Modest/"
                    aria-label="External Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-external-link"
                    >
                      <path
                        d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"
                      ></path>
                      <polyline points="15 3 21 3 21 9"></polyline>
                      <line x1="10" y1="14" x2="21" y2="3"></line>
                    </svg>
                  </a>
                </div>
              </div>
              <h3 class="project-title">
                <a
                  href="https://mansour-aldadah.github.io/Modest/"
                  target="_blank"
                  rel="noopener noreferrer"
                  >Modest</a
                >
              </h3>
              <div class="project-description">
                <p>
                  A minimalist portfolio template with focus on content. Clean
                  typography and smooth scrolling experience.
                </p>
              </div>
            </header>
            <footer>
              <ul class="project-tech-list">
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Minimalist Design</li>
              </ul>
            </footer>
          </div>
        </li>

        <li class="project">
          <div class="project-inner">
            <header>
              <div class="project-top">
                <div class="project-image-thumb">
                  <a
                    href="https://mansour-aldadah.github.io/Bondi/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <img src="/Bondi.png" alt="Bondi" />
                  </a>
                </div>
                <div class="project-links">
                  <a
                    href="https://github.com/mansour-aldadah/Bondi"
                    aria-label="GitHub Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-github"
                    >
                      <path
                        d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                      ></path>
                    </svg>
                  </a>
                  <a
                    href="https://mansour-aldadah.github.io/Bondi/"
                    aria-label="External Link"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      role="img"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      class="feather feather-external-link"
                    >
                      <path
                        d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"
                      ></path>
                      <polyline points="15 3 21 3 21 9"></polyline>
                      <line x1="10" y1="14" x2="21" y2="3"></line>
                    </svg>
                  </a>
                </div>
              </div>
              <h3 class="project-title">
                <a
                  href="https://mansour-aldadah.github.io/Bondi/"
                  target="_blank"
                  rel="noopener noreferrer"
                  >Bondi</a
                >
              </h3>
              <div class="project-description">
                <p>
                  A vibrant and colorful landing page template with modern UI
                  components and interactive elements.
                </p>
              </div>
            </header>
            <footer>
              <ul class="project-tech-list">
                <li>HTML5</li>
                <li>CSS3</li>
                <li>Bootstrap</li>
                <li>JavaScript</li>
              </ul>
            </footer>
          </div>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name: "Projects"
};
</script>

<style scoped>
.projects {
  max-width: 1000px;
  margin: 0 auto;
  padding: 100px 0;
  position: relative;
}

.projects-bg {
  position: absolute;
  top: 0;
  left: -50%;
  width: 200%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
  overflow: hidden;
}

.abstract-shape {
  position: absolute;
  width: 600px;
  height: 600px;
  animation: morphing 30s ease-in-out infinite;
  filter: blur(80px);
  opacity: 0.12;
}

.blob-1 {
  top: 20%;
  right: 10%;
  animation-delay: 0s;
}

.blob-2 {
  bottom: 25%;
  left: 15%;
  animation-delay: 3s;
}

.curved-line {
  position: absolute;
  top: 60%;
  left: 0;
  width: 100%;
  height: auto;
  animation: slide 18s linear infinite;
}

@keyframes morphing {
  0%,
  100% {
    transform: translate(0, 0) scale(1) rotate(0deg);
  }
  33% {
    transform: translate(50px, -70px) scale(1.25) rotate(120deg);
  }
  66% {
    transform: translate(-40px, 50px) scale(0.85) rotate(240deg);
  }
}

@keyframes slide {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-100px);
  }
}

.projects-grid {
  list-style: none;
  padding: 0;
  margin: 0;
  position: relative;
  z-index: 1;
}

.project {
  position: relative;
  margin-bottom: 100px;
}

/* Mobile-first: Card layout */
@media (max-width: 767px) {
  .project {
    display: flex;
    flex-direction: column;
    margin-bottom: 50px;
    background-color: var(--light-navy);
    border-radius: var(--border-radius);
    padding: 0;
    overflow: hidden;
    box-shadow: 0 10px 30px -15px var(--navy-shadow);
    transition: var(--transition);
  }

  .project:hover {
    transform: translateY(-7px);
    box-shadow: 0 20px 30px -15px var(--navy-shadow);
  }

  .project-image {
    order: 1;
    width: 100%;
    margin: 0;
  }

  .project-image .img-placeholder {
    aspect-ratio: 16/9;
    border-radius: 0;
  }

  .project-image .img:before,
  .project-image .img:after {
    display: none;
  }

  .project-content {
    order: 2;
    text-align: left;
    padding: 30px;
    background-color: var(--light-navy);
  }

  .project-overline {
    margin: 0 0 10px 0;
    font-size: var(--fz-xs);
  }

  .project-title {
    font-size: clamp(20px, 4vw, 24px);
    margin: 0 0 15px 0;
  }

  .project-description {
    background-color: transparent;
    box-shadow: none;
    padding: 0;
    margin: 0 0 20px 0;
  }

  .project-description p {
    font-size: var(--fz-sm);
    line-height: 1.5;
    margin: 0;
  }

  .project-tech-list {
    justify-content: flex-start;
    margin: 20px 0 15px 0;
  }

  .project-tech-list li {
    margin: 0 15px 10px 0;
    font-size: var(--fz-xxs);
  }

  .project-links {
    justify-content: flex-start;
    margin-left: -10px;
  }
}

/* Desktop: Side-by-side layout */
@media (min-width: 768px) {
  .project {
    display: grid;
    grid-gap: 10px;
    grid-template-columns: repeat(12, 1fr);
    align-items: center;
  }
}

/* Left-aligned projects (image on right) */
@media (min-width: 768px) {
  .project[data-direction="left"] .project-content {
    grid-column: 1 / 7;
    grid-row: 1;
    text-align: left;
  }

  .project[data-direction="left"] .project-tech-list {
    justify-content: flex-start;
  }

  .project[data-direction="left"] .project-tech-list li {
    margin: 0 20px 5px 0;
  }

  .project[data-direction="left"] .project-links {
    justify-content: flex-start;
    margin-left: -10px;
    margin-right: 0;
  }

  .project[data-direction="left"] .project-image {
    grid-column: 6 / -1;
    grid-row: 1;
  }
}

/* Right-aligned projects (image on left) */
@media (min-width: 768px) {
  .project[data-direction="right"] .project-content {
    grid-column: 7 / -1;
    grid-row: 1;
    text-align: right;
  }

  .project[data-direction="right"] .project-tech-list {
    justify-content: flex-end;
  }

  .project[data-direction="right"] .project-tech-list li {
    margin: 0 0 5px 20px;
  }

  .project[data-direction="right"] .project-links {
    justify-content: flex-end;
    margin-left: 0;
    margin-right: -10px;
  }

  .project[data-direction="right"] .project-image {
    grid-column: 1 / 8;
    grid-row: 1;
  }
}

.project-content {
  position: relative;
  z-index: 2;
}

.project-overline {
  margin: 10px 0;
  color: var(--laravel-red);
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
  font-weight: 400;
}

.project-title {
  color: var(--lightest-slate);
  font-size: clamp(24px, 5vw, 28px);
  margin: 0 0 20px 0;
}

.project-title a {
  color: var(--lightest-slate);
  position: static;
}

.project-title a:before {
  content: "";
  display: block;
  position: absolute;
  z-index: 0;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
}

.project-description {
  position: relative;
  z-index: 2;
  padding: 25px;
  border-radius: var(--border-radius);
  background-color: var(--light-navy);
  color: var(--light-slate);
  font-size: var(--fz-lg);
  box-shadow: 0 10px 30px -15px var(--navy-shadow);
  transition: var(--transition);
}

.project-description:hover {
  box-shadow: 0 20px 30px -15px var(--navy-shadow);
}

.project-tech-list {
  display: flex;
  flex-wrap: wrap;
  position: relative;
  z-index: 2;
  margin: 25px 0 10px;
  padding: 0;
  list-style: none;
}

.project-tech-list li {
  color: var(--light-slate);
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
  white-space: nowrap;
}

/* Mobile tech list */
@media (max-width: 1079px) {
  .project-tech-list {
    justify-content: flex-start;
  }

  .project-tech-list li {
    margin: 0 15px 5px 0;
  }

  .project-links {
    justify-content: flex-start;
    margin-left: -10px;
  }
}

/* Desktop tech list spacing handled by nth-of-type rules above */

.project-links {
  display: flex;
  align-items: center;
  position: relative;
  margin-top: 10px;
  margin-left: -10px;
  color: var(--lightest-slate);
}

.project-links a {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
}

.project-links svg {
  width: 20px;
  height: 20px;
}

.project-image {
  box-shadow: 0 10px 30px -15px var(--navy-shadow);
  transition: var(--transition);
  position: relative;
  z-index: 1;
}

.project-image .img {
  position: relative;
  border-radius: var(--border-radius);
  transition: var(--transition);
}

.project-image .img:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: var(--navy);
  mix-blend-mode: screen;
  transition: var(--transition);
  z-index: 3;
  border-radius: var(--border-radius);
}

.project-image .img:after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgb(251 80 59 / 66%);
  mix-blend-mode: multiply;
  transition: var(--transition);
  z-index: 3;
  border-radius: var(--border-radius);
}

@media (min-width: 768px) {
  .project:hover .project-image .img:before,
  .project:hover .project-image .img:after {
    background: transparent;
  }
}

.project-image .img-placeholder {
  width: 100%;
  max-width: 100%;
  vertical-align: middle;
  border-radius: var(--border-radius);
  background-color: var(--light-navy);
  aspect-ratio: 16/9;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--laravel-red);
  position: relative;
}

.project-image img {
  width: 100%;
  height: 100%;
  max-width: 100%;
  object-fit: cover;
  border-radius: var(--border-radius);
  position: relative;
  z-index: 1;
  display: block;
}

.project-image a {
  width: 100%;
  height: 100%;
  background-color: transparent;
  border-radius: var(--border-radius);
  vertical-align: middle;
  transition: var(--transition);
  display: block;
  position: relative;
}

.more-projects {
  margin-top: 80px;
}

.other-projects-title {
  font-size: clamp(24px, 5vw, var(--fz-heading));
  color: var(--lightest-slate);
  line-height: 1.1;
  margin: 0 auto 10px;
  text-align: center;
}

.archive-link {
  font-family: var(--font-mono);
  font-size: var(--fz-sm);
  text-align: center;
  margin: 0 auto 50px;
  display: block;
  color: var(--green);
  width: max-content;
}

.projects-grid.archive {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  grid-gap: 15px;
  position: relative;
  margin-top: 50px;
}

.archive .project {
  position: relative;
  cursor: default;
  transition: var(--transition);
  display: block;
  margin-bottom: 0;
}

.archive .project:hover {
  transform: translateY(-7px);
}

.project-inner {
  box-shadow: 0 10px 30px -15px var(--navy-shadow);
  transition: var(--transition);
  display: flex;
  justify-content: space-between;
  flex-direction: column;
  align-items: flex-start;
  position: relative;
  height: 100%;
  padding: 2rem 1.75rem;
  border-radius: var(--border-radius);
  background-color: var(--light-navy);
  overflow: auto;
}

.archive .project:hover .project-inner {
  box-shadow: 0 20px 30px -15px var(--navy-shadow);
}

.archive .project:hover .project-title a {
  color: var(--laravel-red);
}

.archive .project-inner {
  display: flex;
  flex-direction: column;
}

.project-top {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin-bottom: 0;
}

.project-image-thumb {
  width: calc(100% + 3.5rem);
  border-radius: var(--border-radius);
  overflow: hidden;
  position: relative;
  background-color: var(--light-navy);
  aspect-ratio: 16/9;
  box-shadow: 0 5px 15px -5px var(--navy-shadow);
  transition: var(--transition);
  order: -1;
  margin: -2rem -1.75rem 1.5rem -1.75rem;
  border-radius: var(--border-radius) var(--border-radius) 0 0;
}

.project-image-thumb:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 25px -5px var(--navy-shadow);
}

.project-image-thumb a {
  display: block;
  width: 100%;
  height: 100%;
  position: relative;
}

.project-image-thumb img {
  width: 100%;
  height: 100%;
  max-width: 100%;
  object-fit: cover;
  transition: var(--transition);
  display: block;
}

.project-image-thumb a::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    180deg,
    transparent 0%,
    rgba(10, 25, 47, 0.2) 100%
  );
  transition: var(--transition);
  opacity: 0.05;
}

.project-image-thumb:hover a::after {
  opacity: 0.2;
}

.project-top .project-links {
  align-self: flex-end;
  margin-top: -10px;
}

.folder {
  color: var(--laravel-red);
}

.folder svg {
  width: 40px;
  height: 40px;
}

.archive header {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.archive .project-title {
  margin: 20px 0 10px 0;
  color: var(--lightest-slate);
  font-size: var(--fz-xxl);
}

.archive .project-title a {
  color: var(--lightest-slate);
  position: static;
}

.archive .project-title a:before {
  content: "";
  display: block;
  position: absolute;
  z-index: 0;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
}

.archive .project-description {
  color: var(--light-slate);
  font-size: 17px;
  background: none;
  box-shadow: none;
  padding: 0;
  margin: 0;
}

.archive .project-description p {
  margin: 0;
}

.archive .project-tech-list {
  display: flex;
  align-items: flex-end;
  flex-grow: 1;
  flex-wrap: wrap;
  padding: 0;
  margin: 20px 0 0 0;
  list-style: none;
}

.archive .project-tech-list li {
  font-family: var(--font-mono);
  font-size: var(--fz-xxs);
  line-height: 1.75;
  color: var(--light-slate);
}

.archive .project-tech-list li:not(:last-of-type) {
  margin-right: 15px;
}

.archive .project-links a {
  padding: 5px;
  position: relative;
  z-index: 1;
}

.archive .project-links svg {
  width: 18px;
  height: 18px;
  color: var(--light-slate);
  transition: var(--transition);
}

.archive .project-links a:hover svg {
  color: var(--green);
}

@media (max-width: 768px) {
  .projects {
    padding: 80px 0;
  }

  .project {
    margin-bottom: 50px;
  }

  .projects-grid.archive {
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  }
}

@media (max-width: 600px) {
  .project {
    margin-bottom: 40px;
  }

  .project-description {
    padding: 20px;
    font-size: var(--fz-md);
  }

  .projects-grid.archive {
    grid-template-columns: 1fr;
  }
}
</style>
