<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mosaic Analytica</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS for navigation and styling -->
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    /* Header */
    header {
      background-color: #004080;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    #mena-map {
      width: 100%;
      max-width: 800px;
      height: auto;
      margin: 0 auto 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      border-radius: 5px;
    }
    header h1 {
      margin-bottom: 10px;
    }
    /* Navigation Bar: one horizontal row */
    .navbar {
      margin-bottom: 20px;
    }
    /* Multi-level dropdowns (custom styling) */
    .dropdown-submenu {
      position: relative;
    }
    .dropdown-submenu > .dropdown-menu {
      top: 0;
      left: 100%;
      margin-top: -1px;
      display: none;
    }
    /* Display submenu on hover */
    .dropdown-submenu:hover > .dropdown-menu {
      display: block;
    }
    /* Main content */
    .main-content {
      padding: 20px;
    }
    section {
      background-color: #fff;
      margin-bottom: 20px;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    section h2 {
      margin-bottom: 15px;
      color: #004080;
    }
    /* Articles Section */
    .articles {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .article-card {
      background-color: #fafafa;
      padding: 15px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .article-card img {
      max-width: 100%;
      border-radius: 5px;
      margin-bottom: 10px;
    }
    .article-card h3 {
      color: #004080;
      margin-bottom: 10px;
    }
    .article-card p {
      margin-bottom: 10px;
    }
    .article-card a {
      color: #1a0dab;
      text-decoration: none;
      font-weight: bold;
    }
    .article-card a:hover {
      text-decoration: underline;
    }
    /* Footer */
    footer {
      background-color: #004080;
      color: #fff;
      text-align: center;
      padding: 10px 0;
    }
    /* Responsive adjustments */
    @media (max-width: 768px) {
      #mena-map {
        max-width: 100%;
      }
      .navbar-nav {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <img src="images/mena-map.svg" alt="MENA Region Map" id="mena-map">
    <h1>Mosaic Analytica</h1>
  </header>

  <!-- Navigation Bar: One Horizontal Row -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <!-- Always visible Home -->
      <a class="navbar-brand" href="#home">Home</a>
      <!-- Toggler for small screens -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu" 
              aria-controls="navMenu" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- Collapsible Menu -->
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <!-- Analysis Dropdown -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="analysisDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Analysis
            </a>
            <ul class="dropdown-menu" aria-labelledby="analysisDropdown">
              <!-- Political Risk submenu -->
              <li class="dropdown-submenu">
                <a class="dropdown-item dropdown-toggle" href="#">Political Risk</a>
                <ul class="dropdown-menu">
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">Gulf</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Saudi Arabia</a></li>
                      <li><a class="dropdown-item" href="#">Qatar</a></li>
                      <li><a class="dropdown-item" href="#">UAE</a></li>
                      <li><a class="dropdown-item" href="#">Kuwait</a></li>
                      <li><a class="dropdown-item" href="#">Oman</a></li>
                      <li><a class="dropdown-item" href="#">Bahrain</a></li>
                    </ul>
                  </li>
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">Middle East</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Iran</a></li>
                      <li><a class="dropdown-item" href="#">Iraq</a></li>
                      <li><a class="dropdown-item" href="#">Israel</a></li>
                      <li><a class="dropdown-item" href="#">Jordan</a></li>
                      <li><a class="dropdown-item" href="#">Türkiye</a></li>
                      <li><a class="dropdown-item" href="#">Syria</a></li>
                    </ul>
                  </li>
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">North Africa</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Egypt</a></li>
                      <li><a class="dropdown-item" href="#">Morocco</a></li>
                      <li><a class="dropdown-item" href="#">Algeria</a></li>
                      <li><a class="dropdown-item" href="#">Libya</a></li>
                      <li><a class="dropdown-item" href="#">Tunisia</a></li>
                    </ul>
                  </li>
                </ul>
              </li>
              <!-- Economic Risk submenu -->
              <li>
                <a class="dropdown-item" href="#economicRisk">Economic Risk</a>
              </li>
            </ul>
          </li>
          <!-- Forecast Dropdown -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="forecastDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Forecast
            </a>
            <ul class="dropdown-menu" aria-labelledby="forecastDropdown">
              <li class="dropdown-submenu">
                <a class="dropdown-item dropdown-toggle" href="#">Commodities</a>
                <ul class="dropdown-menu">
                  <!-- Separate items at the same hierarchy -->
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">Agriculture</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Cacao</a></li>
                      <li><a class="dropdown-item" href="#">Oat</a></li>
                      <li><a class="dropdown-item" href="#">Sugar</a></li>
                      <li><a class="dropdown-item" href="#">Rice</a></li>
                      <li><a class="dropdown-item" href="#">Orange Juice</a></li>
                      <li><a class="dropdown-item" href="#">Grapes</a></li>
                    </ul>
                  </li>
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">Precious Metals</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Gold</a></li>
                      <li><a class="dropdown-item" href="#">Silver</a></li>
                      <li><a class="dropdown-item" href="#">Palladium</a></li>
                      <li><a class="dropdown-item" href="#">Platin</a></li>
                    </ul>
                  </li>
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">Industrial Metals</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Iron</a></li>
                      <li><a class="dropdown-item" href="#">Copper</a></li>
                      <li><a class="dropdown-item" href="#">Lithium</a></li>
                      <li><a class="dropdown-item" href="#">Cobalt</a></li>
                    </ul>
                  </li>
                  <li class="dropdown-submenu">
                    <a class="dropdown-item dropdown-toggle" href="#">Fossil Fuels</a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Brent Oil</a></li>
                      <li><a class="dropdown-item" href="#">WTI</a></li>
                      <li><a class="dropdown-item" href="#">Gas</a></li>
                    </ul>
                  </li>
                </ul>
              </li>
              <li>
                <a class="dropdown-item" href="#">Economic Indicators</a>
              </li>
            </ul>
          </li>
          <!-- Investment Dropdown -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="investmentDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Investment
            </a>
            <ul class="dropdown-menu" aria-labelledby="investmentDropdown">
              <li><a class="dropdown-item" href="#">AI</a></li>
              <li><a class="dropdown-item" href="#">Energy</a></li>
              <li><a class="dropdown-item" href="#">Health Care</a></li>
              <li><a class="dropdown-item" href="#">Technology</a></li>
              <li><a class="dropdown-item" href="#">Tourism</a></li>
            </ul>
          </li>
          <!-- Media Dropdown -->
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="mediaDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Media
            </a>
            <ul class="dropdown-menu" aria-labelledby="mediaDropdown">
              <li><a class="dropdown-item" href="#">Articles</a></li>
              <li><a class="dropdown-item" href="#">Podcasts</a></li>
              <li><a class="dropdown-item" href="#">Videos</a></li>
              <li><a class="dropdown-item" href="#">Pictures</a></li>
            </ul>
          </li>
          <!-- About Us -->
          <li class="nav-item">
            <a class="nav-link" href="#about">About Us</a>
          </li>
          <!-- Contact -->
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Main Content Area -->
  <div class="container main-content" id="home">
    <!-- Introduction Section -->
    <section id="introduction">
      <h2>Welcome</h2>
      <p>
        Welcome to Mosaic Analytica. We provide in-depth analysis and forecasts on political, economic, and market trends in the Middle East and North Africa (MENA) region.
      </p>
    </section>

    <!-- Analysis Section -->
    <section id="analysis">
      <h2>Analysis</h2>
      <!-- Political Risk Subsection -->
      <div id="politicalRisk">
        <h3>Political Risk</h3>
        <ul>
          <li>
            <a href="https://medium.com/@tristangueck1992/fears-after-fall-of-bashar-al-assad-implications-of-the-jordanian-muslim-brotherhoods-election-f2742e431334" target="_blank">
              Jordanian Election Implications
            </a>
          </li>
          <li>
            <a href="https://medium.com/@tristangueck1992/qatars-foreign-policy-goals-the-qatari-media-network-in-the-latest-syrian-context-5df2baf84e4d" target="_blank">
              Qatar's Foreign Media Policy
            </a>
          </li>
          <li>
            <a href="https://medium.com/@tristangueck1992/what-if-al-assad-dies-syrias-never-ending-civil-war-d83780bb70cd" target="_blank">
              Syria's Civil War
            </a>
          </li>
        </ul>
      </div>
      <!-- Economic Risk Subsection -->
      <div id="economicRisk">
        <h3>Economic Risk</h3>
        <p>[Economic Risk analysis content goes here.]</p>
      </div>
    </section>

    <!-- Forecast Section -->
    <section id="forecast">
      <h2>Forecast</h2>
      <h3>Commodities</h3>
      <ul>
        <li class="dropdown-submenu">
          <a class="dropdown-item dropdown-toggle" href="#">Agriculture</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Cacao</a></li>
            <li><a class="dropdown-item" href="#">Oat</a></li>
            <li><a class="dropdown-item" href="#">Sugar</a></li>
            <li><a class="dropdown-item" href="#">Rice</a></li>
            <li><a class="dropdown-item" href="#">Orange Juice</a></li>
            <li><a class="dropdown-item" href="#">Grapes</a></li>
          </ul>
        </li>
        <li class="dropdown-submenu">
          <a class="dropdown-item dropdown-toggle" href="#">Precious Metals</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Gold</a></li>
            <li><a class="dropdown-item" href="#">Silver</a></li>
            <li><a class="dropdown-item" href="#">Palladium</a></li>
            <li><a class="dropdown-item" href="#">Platin</a></li>
          </ul>
        </li>
        <li class="dropdown-submenu">
          <a class="dropdown-item dropdown-toggle" href="#">Industrial Metals</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Iron</a></li>
            <li><a class="dropdown-item" href="#">Copper</a></li>
            <li><a class="dropdown-item" href="#">Lithium</a></li>
            <li><a class="dropdown-item" href="#">Cobalt</a></li>
          </ul>
        </li>
        <li class="dropdown-submenu">
          <a class="dropdown-item dropdown-toggle" href="#">Fossil Fuels</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Brent Oil</a></li>
            <li><a class="dropdown-item" href="#">WTI</a></li>
            <li><a class="dropdown-item" href="#">Gas</a></li>
          </ul>
        </li>
      </ul>
      <h3>Economic Indicators</h3>
      <ul>
        <li>GDP</li>
        <li>Inflation</li>
        <li>...</li>
      </ul>
    </section>

    <!-- Investment Section -->
    <section id="investment">
      <h2>Investment</h2>
      <ul>
        <li>AI</li>
        <li>Energy</li>
        <li>Health Care</li>
        <li>Technology</li>
        <li>Tourism</li>
      </ul>
    </section>

    <!-- Media Section -->
    <section id="media">
      <h2>Media</h2>
      <ul>
        <li>Articles</li>
        <li>Podcasts</li>
        <li>Videos</li>
        <li>Pictures</li>
      </ul>
    </section>

    <!-- About Us Section -->
    <section id="about">
      <h2>About Us</h2>
      <p>
        Mosaic Analytica is dedicated to providing comprehensive analysis on political, economic, and market trends in the MENA region. Our team includes:
      </p>
      <ul>
        <li>Prof. Dr. Mohammed Farzanegan</li>
        <li>Tristan Gück</li>
        <li>Guiliano Lorenz</li>
        <li>Michael Kudisch</li>
        <li>Gian-Luca Omari</li>
        <li>Max Petersen</li>
        <li>Melodie Diana Safa</li>
      </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact</h2>
      <p>
        For inquiries or more information, please contact us at:
        <a href="mailto:info@mosaicanalytica.com">info@mosaicanalytica.com</a>
      </p>
    </section>
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Mosaic Analytica. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
