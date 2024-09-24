# linktreecoder
im changing kts linktree to a girly version
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="google-site-verification"
      content="OsZNXLpHFXPODOXINTTWbpLD8QojjZ5JQv8jeEnKwTo"
    />
    <title>Kruthi's LinkTree</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css"
    />
    <style>
      body {
        font-family: 'Poppins', sans-serif;
        background-color: #fce4ec; /* Light pink background */
        color: #333;
        margin: 0;
        padding: 20px;
      }
      .container {
        max-width: 600px;
        margin: auto;
        text-align: center;
        border-radius: 15px;
        padding: 20px;
        background: linear-gradient(to bottom right, #ffe0b2, #fff3e0); /* Gradient background */
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      }
      .profile {
        margin-bottom: 20px;
      }
      .photo {
        background-image: url('https://pureoxygenlabs.com/wp-content/uploads/2023/11/linktreelogo.png');
        background-size: cover;
        height: 100px;
        width: 100px;
        border-radius: 50%;
        margin: 0 auto;
        border: 5px solid gold; /* Gold border */
      }
      .profile_name {
        display: block;
        font-size: 24px;
        font-weight: 700;
        margin-top: 10px;
        color: teal; /* Teal color for name */
      }
      .links {
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .custom-btn {
        background-color: pink; /* Pink button background */
        color: white;
        border: none;
        border-radius: 10px;
        padding: 10px 20px;
        margin: 10px 0;
        font-size: 16px;
        cursor: pointer;
        transition: background-color 0.3s;
        width: 100%;
        max-width: 300px;
      }
      .custom-btn:hover {
        background-color: teal; /* Change to teal on hover */
      }
      .custom-btn i {
        margin-right: 8px;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="profile">
        <div class="photo"></div>
        <span class="profile_name">Kruthi Krishna A V</span>
      </div>

      <!-- Links -->
      <div class="links">
        <a href="https://github.com/KKAV2005-ops" target="_blank">
          <button class="custom-btn">
            <span><i class="fab fa-github"></i> Github</span>
          </button>
        </a>
        <a href="https://avkruthikrishna202.wixstudio.io/nkconsol" target="_blank">
          <button class="custom-btn">
            <span><i class="fas fa-user-ninja"></i> My Hardware Store</span>
          </button>
        </a>
        <a href="https://open.spotify.com" target="_blank">
          <button class="custom-btn">
            <span><i class="fas fa-laptop"></i> Spotify</span>
          </button>
        </a>
        <a href="mailto:avkruthikrishna2020@gmail.com" target="_blank">
          <button class="custom-btn">
            <span><i class="fas fa-paper-plane"></i> Email</span>
          </button>
        </a>
        <a href="https://www.linkedin.com/in/kruthi-krishna-ba40072a0/" target="_blank">
          <button class="custom-btn">
            <span><i class="fab fa-linkedin"></i> LinkedIn</span>
          </button>
        </a>
        <a href="https://drive.google.com/file/d/1oxmvlLVVMBtA-GA50sitNZKWfGuE4wir/view" target="_blank">
          <button class="custom-btn">
            <span><i class="fas fa-file-alt"></i> Resume</span>
          </button>
        </a>
      </div>
    </div>
  </body>
</html>
