<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .contact-section {
      display: flex;
      height: 380px;
      width: 910px;
      border-bottom-width: 20px;
      margin-bottom: 20px;
      padding: 10px 15px;
      margin-left: 50px;
    }

    .card {
      flex: 1;
      margin-right: 20px;
      background-color: white;
      max-width: 450px;
      padding: 20px;
    }

    .contact-form {
      width: 100%;
    }

    .content-section {
      width: 100%;
    }
    
    .copyright {
        text-align: center;
        margin-top: 20px;
    }

    .policy-links {
        display: flex;
        justify-content: space-around;
        margin-top: 10px;
    }

    .policy-link {
        margin: 10px;
        padding: 10px;
        list-style: none;
        display: inline;
    }

    .policy-link a {
    text-decoration: none; /* Fix: Set text-decoration to 'none' */
    font-weight: normal;
    color: black; 
    }

    .policy-link a:hover {
    text-decoration: underline;
    font-weight: bold; 
    }
    
    .space-cadet-background {
      background-color: #1a172c;
      padding: 50px;
      text-align: center;
      color: white;
    }

    .space-cadet-text {
      font-size: 2em;
      margin-bottom: 20px;
    }
    .phrase-gap {
      margin-bottom: 20px; /* Added margin between the two phrases */
    }
</style>

  <title>Anoka Advisory & Co.</title>
  <link rel="stylesheet" href="styles.css">
  <style>

  .grid-columns-vertical {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .grid-item {
    text-align: center;
    margin-bottom: 15px; /* Adjust as needed for spacing between grid items */
  }

.contact-form {
  width: 48%; /* Adjust the width as needed */
}

.contact-section {
  display: flex;
  justify-content: space-between;
}

.content-section {
  width: 48%; /* Adjust the width as needed */
  background-color: white;
  max-width: 450px;
  margin-right: auto;
}
.skillset {
    overflow: hidden;
  }

  .card {
    float: left;
    animation: none
  }

  @keyframes scroll {
      0% {
        transform: translateX(0);
      }
      100% {
        transform: translateX(calc(-100% - 10px)); /* Adjust for card width and gap */
      }
    }

    .skillset {
      animation: scroll 50s linear infinite;
    }

    /* Optional: Pause animation on hover */
    .skillset:hover {
    animation: marquee 20s linear infinite;
    }
<style>
    .card-container {
      display: flex;
      justify-content: space-between;
      margin: 0 auto;
      max-width: 900px; /* Adjust the max-width as needed */
    }

    .contact-section,
    .content-section {
      flex: 1;
      box-sizing: border-box;
    }

    .contact-section {
      background-color: #f9f9f9; /* Adjust background color as needed */
      padding: 20px;
      border: 1px solid #ddd; /* Adjust border as needed */
      border-radius: 8px; /* Adjust border-radius as needed */
    }

    .content-section {
      background-color: #fff; /* Adjust background color as needed */
      padding: 20px;
      border: 1px solid #ddd; /* Adjust border as needed */
      border-radius: 8px; /* Adjust border-radius as needed */
    }

    nav {
        text-align: center; /* Align the text to the right */
    }

    nav a {
        margin-left: 10px; /* Add some space between the links */
        }
</style>
</head>
<body>
  
  <header style="display: flex; align-items: center; justify-content: space-between; padding: 0px 0 0 0;">
    <div style="display: flex; align-items: center;">
      <img src="ANKA.png" alt="Anoka Advisory Logo" class="logo" style="width: 60px; margin-right: 10px; margin-left: 20px;">
  
      <nav style="margin-right: 0px;margin-left: 100px;">
        <a href="#home">HOME</a>
        <a href="#blog">BLOG</a>
        <a href="#about-us">ABOUT US</a>
        <a href="#contact-us">CONTACT US</a>
        <a href="#services">SERVICES</a>
        <a href="#for-vendors">FOR VENDORS</a>
      </nav>
    </div>
  
    <div class="search-bar" style="margin-left: -50; margin-left: 0px;margin-right: 200px;">
      <input type="text" placeholder="Search...">
      <img src="Search.png" alt="Search" style="width: 40px;height: 40px;border-radius: 50%;margin-left: 10px;">
    </div>
  </header>

  <!-- <div>
  <img src="Header00.png" alt="Header Image" class="header-image">
</div> -->

<div class="customContainer" style="height: 400px;padding-left: 10px;padding-top: 0px;padding-left: 0px;padding-bottom: 0px;padding-right: 0px;">
  <div class="mainText" style="padding-top: 20px;">
    <span class="boldText" style="margin-left: 60px;">Get real advice from <br> <span style="margin-left: 60px;">real people</span></span>
    <br>
    <span class="smallerText" style="margin-left: 60px;">With one-on-one help and personalized recommendations, we <br> <span style="margin-left: 60px;">guide you to your top software options.</span></span>
    <br>
</div>
  <div style="text-align: right;margin-top: -280px;margin-right: 100px;width: 1500px;height: -300px;">
    <img src="Question.png" alt="image 3" class="image3" style="position: absolute;top: -150;right: 250px;z-index: 1;width: 75px;padding-top: 140px;margin-right: 20px;">
    <img src="GG141.png" alt="Image 1" style="width: 100%;max-width: 300px;margin-top: 0px;padding-bottom: 50px;">
      <img src="BB141.png" alt="Image 2" style="width: 100%;max-width: 300px;margin-top: 120px;">
  </div>
</div>

<div class="button-container">
  <button class="rounded-button" onmouseover="expandButton()" onmouseout="shrinkButton()">
    Get advice — it's free!
  </button>
</div>

<style>
  .button-container {
    text-align: center;
    margin-top: 20px;
  }

  .rounded-button {
    border: none;
    padding: 10px 20px;
    border-radius: 20px;
    background-color: orangered;
    color: white;
    cursor: pointer;
    transition: width 0.3s ease-in-out;
  }

  .rounded-button:hover {
    width: 150px;
  }
</style>

<script>
  function expandButton() {
    document.querySelector('.rounded-button').style.width = '150px';
  }

  function shrinkButton() {
    document.querySelector('.rounded-button').style.width = '';
  }
</script>

  <div class="container">
    <div class="flex-container">
      <div class="flex-column">
        <img src="search1.png" alt="Image 1">
        <h2 style="padding-left: 10px;">Take stress out of the search</h2>
        <p style="padding-left: 10px;">Simplify your search. We’ll help you narrow down software options in just a few minutes.</p>
      </div>
      <div class="flex-column">
        <img src="message1.png" alt="Image 2">
        <h2 style="padding-left: 10px;">Associate with an advisor</h2>
        <p style="padding-left: 10px;">Chat with a software advisor and get personalized software recommendations via phone or email.</p>
      </div>
      <div class="flex-column">
        <img src="thumbs1.png" alt="Image 3">
        <h2 style="padding-left: 10px;">Make a confident choice</h2>
        <p style="padding-left: 10px;">Use research, insights and reviews to compare software and make the right choice for your needs.</p>
      </div>
    </div>

    <div class="skillset" style="margin-left: 0px;margin-right: 0px;">
      <div class="card" style="
         padding-top: 10px;padding-left: 10px;padding-right: 10px;padding-bottom: 10px;height: 111.6px;width: 271.6px; margin-right: 0px;margin-left: 10px;">
        <img src="Retail1.png" alt="Retail">
        <p style="margin-top: 5px;">Retail</p>
      </div>
      <div class="card" style="
         padding-top: 10px;padding-left: 10px;padding-right: 10px;padding-bottom: 10px;height: 111.6px;width: 271.6px; margin-right: 0px;margin-left: 10px;">
        <img src="den1.png" alt="Dental">
        <p style="margin-top: 5px;">Dental</p>
      </div>
      <div class="card" style="
          padding-top: 10px;padding-left: 10px;padding-right: 10px;padding-bottom: 10px;height: 111.6px;width: 271.6px; margin-right: 0px;margin-left: 10px;">
        <img src="realestate1.png" alt="Real Estate">
        <p style="margin-top: 5px;">Real Estate</p>
      </div>
      <div class="card" style="
         padding-top: 10px;padding-left: 10px;padding-right: 10px;padding-bottom: 10px;height: 111.6px;width: 271.6px; margin-right: 0px;margin-left: 10px;">
        <img src="med1.png" alt="Medical">
        <p style="margin-top: 5px;">Medical</p>
      </div>
      <div class="card" style="
         padding-top: 10px;padding-left: 10px;padding-right: 10px;padding-bottom: 10px;height: 111.6px;width: 271.6px; margin-right: 0px;margin-left: 10px;">
        <img src="firm1.png" alt="Firmware">
        <p style="margin-top: 5px;">Firmware</p>
      </div>
    </div>

    <h2 class="centered-heading">Here's How We Work</h2>

    <style>
      .cards {
        display: flex;
        justify-content: space-around;
      }
    
      .card {
        padding: 20px;
        cursor: pointer;
        transition: background-color 0.3s ease-in-out;
        margin: 20px;
      }
    
      .larger-card {
        width: 460px; /* Adjust the width as needed */
      }
    
      h2 {
        font-size: 28px; /* Increase the font size */
      }
    
      /* Change the color of digits */
      .card h2 {
        color: orangered; /* Change the color to your preference */
      }
    </style>    

<button role="button" style="position: fixed; visibility: visible; cursor: pointer; border: none; background-color: transparent; padding: 0px; margin: 0px; bottom: 94px; left: 0px; width: 37px; transition: all 0.5s ease 0s;" id="QSIFeedbackButton-btn" aria-expanded="false" aria-controls="QSIFeedbackButton-target-container"><div style="background: rgb(107, 97, 173); color: rgb(255, 255, 255); padding: 10px; position: relative; font-size: 15px; display: flex; flex-direction: row; z-index: -1; writing-mode: vertical-rl; border-top-right-radius: 6px; border-bottom-right-radius: 6px;"><div><div style="transform: rotate(90deg); top: 0px; margin: 0px 0px 5px;"><svg width="13" height="15" viewport="0 0 13 15"><path d="M11.8182 0H1.18182C0.529118 0 0 0.610521 0 1.36364V13.6364C0 14.3895 0.529118 15 1.18182 15H11.8182C12.4709 15 13 14.3895 13 13.6364V1.36364C13 0.610521 12.4709 0 11.8182 0Z" fill="#ffffff"></path><path d="M3.11869 4.01514H9.88131" stroke="#6b61ad" strokeLinecap="round" strokeLinejoin="round"></path><path d="M3.11869 7.65151H9.88131" stroke="#6b61ad" strokeLinecap="round" strokeLinejoin="round"></path><path d="M3.11869 11.2879H9.88131" stroke="#6b61ad" strokeLinecap="round" strokeLinejoin="round"></path></svg></div></div><div>Share Feedback</div></div></button>

<div class="cards" style="display: flex; justify-content: center; align-items: center;">
  <div class="card" style="border: 1px solid #ccc; height: 290px; width: 350px; margin: 16px; padding: 16px; display: flex; flex-direction: column; align-items: flex-start; text-align: left;">
    <h2 style="font-size: 36px; margin: 0;">1</h2>
    <h2>Connect with us</h2>
    <p>Fill out a brief form and we’ll get in touch via phone or email.</p>
  </div>
  <div class="card" style="border: 1px solid #ccc; height: 290px; width: 350px; margin: 16px; padding: 16px; display: flex; flex-direction: column; align-items: flex-start; text-align: left;">
    <h2 style="font-size: 36px; margin: 0;">2</h2>
    <h2>Tell us about your needs</h2>
    <p>We’ll talk a bit about your goals, needs, and budget.</p>
  </div>
  <div class="card" style="border: 1px solid #ccc; height: 290px; width: 350px; margin: 16px; padding: 16px; display: flex; flex-direction: column; align-items: flex-start; text-align: left;">
    <h2 style="font-size: 36px; margin: 0;">3</h2>
    <h2>Get software recommendations</h2>
    <p>Within 20 minutes, we’ll email you a list of personalized software recommendations.</p>
  </div>
</div>


    <div class="connect-advisor" style="border-left-width: 15px; padding-left: 20px; margin-left: 140px; margin-right: 20px; height: 290px;width: 1240px;">
      <img src="Customer1.png " alt="Advisor Image" style="flex-basis: 30%; margin-right: 40px;">
      <div style="flex-basis: 70%;">
        <h2>Connect with an consultant who specializes in your industry</h2>
        <p>"I help people get their software search out of the way, so they can focus on their business. Advisors like me save you hours of time and can point you towards software options that perfectly match your specific needs. I specialize in construction software, but no matter what you’re looking for, one of us can definitely help!"</p>
      </div>
    </div>

    <h2 class="centered-heading">Browse all software categories</h2>

    <div class="grid-columns-gap-5">
      <div class="grid-item">Accounting <span class="add-icon-right">+</span></div>
      <div class="grid-item">Multimedia Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Educational Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Word Processors <span class="add-icon-right">+</span></div>
      <div class="grid-item">Firmware <span class="add-icon-right">+</span></div>
      <div class="grid-item">Inventory <span class="add-icon-right">+</span></div>
      <div class="grid-item">Risk Management Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Supply Chain Management Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Learning Management Systems <span class="add-icon-right">+</span></div>
      <div class="grid-item">Long Term Care Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Business Intelligence Tools <span class="add-icon-right">+</span></div>
      <div class="grid-item">Construction <span class="add-icon-right">+</span></div>
      <div class="grid-item">Medical <span class="add-icon-right">+</span></div>
      <div class="grid-item">Retail <span class="add-icon-right">+</span></div>
      <div class="grid-item">Manufacturing <span class="add-icon-right">+</span></div>
      <div class="grid-item">Dental <span class="add-icon-right">+</span></div>
      <div class="grid-item">PSA Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">CMMS Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Human Resources <span class="add-icon-right">+</span></div>
      <div class="grid-item">VoIP Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Live Chat Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">CRM Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">CPQ Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">ERP Software <span class="add-icon-right">+</span></div>
      <div class="grid-item">Apparel Manufacturing <span class="add-icon-right">+</span></div>
      <div class="grid-item">Real Estate <span class="add-icon-right">+</span></div>
      <div class="grid-item">Aeronautical <span class="add-icon-right">+</span></div>
      <div class="grid-item">Blockchain  <span class="add-icon-right">+</span></div>
      <div class="grid-item">Business Analysis <span class="add-icon-right">+</span></div>
      <div class="grid-item">AIOPS Software <span class="add-icon-right">+</span></div>
    </div>

    <div class="ask-questions-section">
      <h2 class="centered-heading">Have any Queries? Please let us know!</h2>
      <div class="grid-columns-vertical">
        <div class="grid-item" style="
         right: 30px;padding-left: 15px;">
          We will be happy to assist in refining it! <span class="add-icon-right">+</span>
        </div>
        <div class="grid-item">
          Are the reviews on our platform generated by authentic individuals? <span class="add-icon-right">+</span>
        </div>
        <div class="grid-item" style="
          padding-left: 10px;">
          Who are your advisors? <span class="add-icon-right">+</span>
        </div>
        <div class="grid-item">
          Will i be subjected to an influx of unsolicited phone calls? <span class="add-icon-right">+</span>
        </div>
        <div class="grid-item">
          Can I catalog my product on your website? <span class="add-icon-right">+</span>
        </div>
      </div>
    </div>    

    <style>
      .contact-form button {
        margin-top: 10px;
      }
    </style>

  <div class="card-container">
    <div class="contact-section" style="
        height: 380px;width: 1374.6px;border-bottom-width: 0px;margin-bottom: 20px;padding-left: 15px;padding-top: 10px;padding-right: 10px;padding-bottom: 10px;margin-left:50px;border-left-width: 0px;border-right-width: -250;border-right-width: 0px;border-top-width: 0px;">
      <div class="contact-form">
        <h2 style="margin-top: 0px;margin-bottom: 0px;">CONTACT US</h2>
        <p>Get in touch with us to know more about how  Anoka Advisory to transform your software experience. </p>
        
        <label for="name"></label>
        <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" data-rule="minlen:4" data-msg="Please enter at least 4 chars" style="
        margin-bottom: 10px;padding-left: 10px;width: 500px;height: 20px;">
        <div class="validation"></div>

        <label for="email"></label>
        <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" data-rule="email" data-msg="Please enter a valid email" style="
        margin-bottom: 10px;padding-left: 10px;width: 500px;height: 20px;">
        <div class="validation"></div>

        <label for="Contact Number"></label>
        <input type="Contact" class="form-control" name="Contact" id="Contact" placeholder="Your Contact" data-rule="minlen:4" data-msg="Please enter at least 10 chars of phone" style="
        margin-bottom: 10px;padding-left: 10px;width: 500px;height: 20px;">
        <div class="validation"></div>

        <label for="Please type your message"></label>
        <textarea class="form-control" name="message" rows="5" data-rule="required" data-msg="Please write something for us" placeholder="Your Message" style="padding-left: 10px;width: 500px;height: 100px;"></textarea>
        <div class="validation"></div>

        <button class="contact-form button" type="submit" style="width: 162px;height: 43px;border-top-width: 5px;padding-left: 40px;padding-right: 25px;padding-top: 10px;">Send Message</button>
      </div>

      <div class="content-section" style="background-color: white;max-width: 450px;margin-right: 0px;">  
        <h2 style="
            border-left-width: 10px;padding-left: 20px;margin-bottom: 0px;margin-top: 0px;
      ">Anoka Advisory &amp; Co.</h2>
        <p style="
            border-left-width: 10px;padding-left: 20px;width: 400px;
      ">Anoka Advisory stands at the forefront of technological innovation, carving a niche as a dynamic and client-centric software solutions provider. Renowned for delivering a plethora of cutting-edge software across diverse sectors, We seamlessly integrates technology to address multifaceted challenges. With a commitment to excellence, our team of seasoned professionals harnesses the power of innovation to craft bespoke software solutions tailored to the unique needs of our clients.</p>
      </div>
    </div>

      <div class="space-cadet-background">
        <h2 class="boldText">Narrow down your search and make a confident choice</h2>
        <p class="smallerText">Get your personalized recommendations now:</p>
      </div>
    </div>
    
      <div class="contact-information">
        <p style="padding-bottom: 0px;padding-left: 20px;"><strong>Address: Anoka Advisory & Co. ITPL Main Rd, Pattandur Agrahara, Whitefield, Bengaluru, Karnataka 560066</p>
        <p style="padding-bottom: 0px;padding-left: 20px;">Contact Us: +91 080-2943658</p>
        <p style="padding-bottom: 0px;padding-left: 20px;">Fax Us: +91 080-2971922</p>
        <p style="padding-bottom: 0px;padding-left: 20px;">Email Us: anokaadvisory.com</p>
        <p style="padding-bottom: 0px;padding-left: 20px;">Disclaimer: This is a fictional website created for demonstration purposes only.</p>
        <p style="padding-bottom: 0px;padding-left: 20px;">Privacy Policy: We respect your privacy and are committed to protecting your personal information.</p>
      </div>

    <div class="social-media-section">
      <div class="social-media-icons">
        <img src="facebook1.png" alt="Facebook">
        <img src="Twitter1.png" alt="Twitter">
        <img src="Insta1.png" alt="Instagram">
        <img src="YOU1.png" alt="YouTube">
        <img src="IN1.png" alt="LinkedIN">
      </div>
    </div>
  </div>

  <script>
    let currentIndex = 0;

    function showSlide(index) {
      const slides = document.querySelector('.slides');
      const slideWidth = document.querySelector('.slide').offsetWidth;
      slides.style.transform = `translateX(-${index * slideWidth}px)`;
    }

    function prevSlide() {
      currentIndex = (currentIndex - 1 + 5) % 5;
      showSlide(currentIndex);
    }

    function nextSlide() {
      currentIndex = (currentIndex + 1) % 5;
      showSlide(currentIndex);
    }

  function toggleCard(card) {
    const extendedDescription = card.querySelector('.extended-description');
    const addIcon = card.querySelector('.add-icon');

    if (card.classList.contains('expanded')) {
      // Collapse the card
      card.classList.remove('expanded');
      addIcon.textContent = '+';
    } else {
      // Expand the card
      card.classList.add('expanded');
      addIcon.textContent = '-';
    }
  }

</script>
<div class="copyright">
    <p>© 2015-2024 Anoka Advisory & Co.</p>
    <ul class="policy-links"></ul>
    <li class="policy-link"><a href="#">Privacy Policy</a></li>
            <li class="policy-link"><a href="#">User Terms</a></li>
            <li class="policy-link"><a href="#">Community Guidelines</a></li>
            <li class="policy-link"><a href="#">FAQs</a></li>
            <li class="policy-link"><a href="#">Content Policy</a></li>
  </ul>
</div>
</body>
</html>

**CSS code starts here.....!**
/* Reset and common styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  color: #000;
}

/* Header styles */
.header-container {
  position: fixed;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background-color: #333;
  color: white;
  z-index: 1000;
}

nav {
  display: flex;
  background-color: #1a172c;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 10px;
  margin-right: 10px;
}

header {
  background-color: #1a172c;
  color: #fff;
  padding: 10px;
  text-align: left;
}

.titleheader {
  background-color: #1a172c;
  color: #fff;
  padding: 10px;
  text-align: center; /* Center the text in the header */
  margin-left: 300px;
}

.logo {
  max-width: 100px;
  height: auto;
  margin-right: 1400px;
  position: absolute;
}

h1 {
  display: inline-block;
}

.header-image {
  width: 100%;
  height: auto;
  max-height: 400px;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f7f7f7; /* Updated background color */
  color: #000; /* Black font color */
}

header {
  background-color: #1a172c;
  color: #fff;
  padding: 50px;
  text-align: left;
}

<style>
    .card-container {
      display: flex;
      justify-content: space-between;
      margin: 0 auto;
      max-width: 900px; /* Adjust the max-width as needed */
    }

    .contact-section,
    .content-section {
      flex: 1;
      box-sizing: border-box;
    }

    .contact-section {
      background-color: #f9f9f9; /* Adjust background color as needed */
      padding: 20px;
      border: 1px solid #ddd; /* Adjust border as needed */
      border-radius: 8px; /* Adjust border-radius as needed */
    }

    .content-section {
      background-color: #fff; /* Adjust background color as needed */
      padding: 20px;
      border: 1px solid #ddd; /* Adjust border as needed */
      border-radius: 8px; /* Adjust border-radius as needed */
    }

    nav {
        text-align: center; /* Align the text to the right */
    }

    nav a {
        margin-left: 10px; /* Add some space between the links */
        }

    .skillset {
      display: flex;
      gap: 10px; /* Adjusted gap */
      overflow: hidden;
      white-space: nowrap;
      width: 100%; /* Adjusted width */
    }

    .card {
      flex: 0 0 auto;
      border: 1px solid #ddd;
      padding: 10px;
      text-align: center;
      display: inline-block;
      width: 200px; /* Adjusted card width */
    }

    @keyframes scroll {
      0% {
        transform: translateX(0);
      }
      100% {
        transform: translateX(calc(-100% - 10px)); /* Adjust for card width and gap */
      }
    }

    .skillset:hover {
      animation: none; /* Pause animation on hover */
    }

    .search-bar {
      display: flex;
      align-items: center;
      margin-left: 20px; /* Adjust the margin as needed */
    }
    
    .search-bar input {
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }
    
    .search-bar button {
      background-color: #1a172c; /* Adjust the background color as needed */
      border: none;
      padding: 10px;
      border-radius: 5px;
      margin-left: 5px;
      cursor: pointer;
    }
    
    .search-bar button img {
      width: 20px; /* Adjust the width of the search icon */
      height: 20px; /* Adjust the height of the search icon */
    }
    
    /* Add a style for the phrase "How can we assist you" */
    .header-text {
      font-size: 16px; /* Adjust the font size as needed */
      margin-left: 20px; /* Adjust the margin as needed */
      color: #1a172c; /* Adjust the color as needed */
    }
</style>

nav {
  background-color: #1a172c;
  padding: 10px;
}

nav a {
  color: #fff;
  text-decoration: #333;
  margin: 10px 0;
  padding: 5px 10px;
  border-radius: 5px;
}

nav a:hover {
  background-color: limegreen;
}

.container .contact-information p {
  color: black;
  font-weight: 800; 
  margin: 0;
  padding: 10px;
  background-color: #f7f7f7; /* Updated background color */
}

.cards {
  display: flex;
  justify-content: center;
  overflow-x: auto; /* Added to enable horizontal scrolling if needed */
}

.card {
  flex: 0 0 auto; /* Adjusted to make the cards have a fixed width */
  margin-right: 20px; /* Added margin between cards for better spacing */
  padding: 10px; /* Adjusted padding */
  max-height: 350px; /* Adjusted maximum height */
  overflow: hidden;
  background-color: #ffffff; /* Updated card color */
  box-sizing: border-box;
  border-radius: 10px;
  color: #000; /* Updated font color */
  position: relative;
  width: 300px;
}

.card img {
  max-width: 45%;
  height: auto;
}

.add-icon {
  position: absolute;
  top: 10px;
  right: 10px;
  font-size: 20px;
  color: #000;
}

.connect-advisor {
  display: flex;
  margin-top: 20px;
  margin-bottom: 30px;
  padding: 20px;
  background-color: #1a172c; /* Updated background color */
  box-sizing: border-box;
  border-radius: 20px;
  color: #f7f7f7; /* Updated font color */
}

.slide-wrap {
  position: relative;
  overflow: hidden;
  text-align: center;
}

.slides {
  display: flex;
  justify-content: center;
  width: 100%; /* Ensure the slides take 100% width of the container */
  transition: transform 0.5s ease-in-out;
  margin-bottom: 20px;
}

.slide {
  min-width: 100%;
  box-sizing: border-box;
  text-align: center; /* Center the content inside each slide */
}

.arrow {
  position: absolute;
  top: 50%;
  width: 40px;
  height: 40px;
  background-color: #ffffff; /* Updated background color */
  color: #000; /* Updated font color */
  text-align: center;
  line-height: 40px;
  cursor: pointer;
  user-select: none;
}

.arrow.left {
  left: 10px;
}

.arrow.right {
  right: 10px;
}

.grid-columns-gap-5 {
  justify-content: center; /* Horizontal centering */  
  align-items: center!important; /* Vertical centering */
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0px;
  margin-top: 30;
}

.grid-item {
  position: relative;
  padding: 5px;
  background-color: #ffffff; /* Updated background color */
  box-sizing: border-box;
  border-radius: 10px;
  color: #ffffff; /* Updated font color */
  text-align: center;
  width: 650px;
  left: 60px;
  right: 80px;
}

.add-icon-right {
  position: absolute;
  top: 50%;
  right: 10px;
  transform: translateY(-50%);
  font-size: 20px;
  color: #000;
}

.questions-section {
  text-align: center;
  margin-top: 30px;
}

.ask-questions-section {
  background-color: #f7f7f7;
  color: #000;
  padding: 20px;
  text-align: center;
  border-radius: 10px;
  margin-bottom: 30px; 
}

.grid-columns-vertical {
  display: grid;
  grid-template-columns: 1fr;
  grid-row-gap: 10px;
  justify-content: center;
}

.grid-item {
  background-color: #ffffff;
  padding: 10px;
  border-radius: 5px;
  margin-bottom: 0px;
  color: #000;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.grid-item .add-icon-right {
  font-size: 18px;
  margin-left: 10px;
}

.columns {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-top: 20px;
}

.column {
  flex-basis: calc(20% - 10px);
  background-color: #f2f2f2;
  padding: 10px;
  margin-bottom: 10px;
  text-align: center;
  position: relative;
}

.column p {
  margin: 0;
}

.add-icon-right {
  position: absolute;
  top: 50%;
  right: 10px;
  transform: translateY(-50%);
  cursor: pointer;
}

.contact-section {
  display: flex;
  width: 50%; /* Adjust the width of the contact section */
  box-sizing: border-box;
  margin-left: 800px;
  margin-top: 20px;
  padding: 25px;
  background-color: #ffffff; /* Updated background color */
  box-sizing: border-box;
  border-radius: 10px;
  color: #000; /* Updated font color */
}

.contact-form {
  display: flex;
  flex-direction: column;
}

.contact-form label {
  text-align: center; /* Center-align the labels */
}

.button {
  width: 100px; /* Adjust the width as needed */
  height: 40px; /* Adjust the height as needed */

  margin: 0 auto;

  /* Additional styles for better appearance */
  display: block;
  background-color: #3498db; /* Set the background color */
  color: #fff; /* Set the text color */
  border: none; /* Remove the border for a cleaner look */
  border-radius: 5px; /* Add rounded corners */
  cursor: pointer;
}

.button:hover {
  background-color: #2980b9; /* Change the background color on hover */
}

.contact-form input,
.contact-form textarea {
  width: 40%; /* Set a desired width for the input and textarea */
  margin: 0 auto; /* Center-align the input and textarea */
}

.anoka-section {
  margin-top: 20px;
  padding: 20px;
  background-color: #1a172c; /* Updated background color */
  box-sizing: border-box;
  border-radius: 10px;
  color: #f7f7f7; /* Updated font color */
}

.social-media-section {
  margin-top: 20px;
  padding: 20px;
  background-color: #ffffff; /* Updated background color */
  box-sizing: border-box;
  border-radius: 10px;
  text-align: right;
  color: #000; /* Updated font color */
}

.social-media-icons {
  display: flex;
  gap: 10px;
}

.card.expanded .extended-description {
  max-height: 200px; /* Adjust the maximum height as needed */
  transition: max-height 0.5s ease-in-out; /* Add a smooth transition effect */
}

.card .extended-description {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.5s ease-in-out; /* Add a smooth transition effect */
}

.centered-heading {
  text-align: center;
}

.video-section {
  text-align: center; /* Center-align the content inside the video-section */
  margin-top: 20px;
}

.video-section video {
  width: 100%; /* Ensure the video takes 100% width of its container */
  max-width: 800px; /* Set a maximum width for the video */
}

/* Flex section styles */
.flex-container {
  display: flex;
  justify-content: space-between;
  padding: 20px;
}

.flex-column {
  flex-basis: calc(33.33% - 20px);
  box-sizing: border-box;
  margin-right: 20px;
  background-color: #ffffff;
  border-radius: 10px;
  overflow: hidden;
}

.flex-column img {
  width: 56px;
  height: 50px;
  object-fit: cover;
  border-radius: 10px 10px 0 0;
}

/*The flex section CSS ends here*/

/* Search box styles */
.searchBox {
  position: absolute;
  top: 50%;
  left: 89%;
  transform: translate(-50%, 50%);
  background: white;
  height: 40px;
  border-radius: 40px;
  padding: 10px;
}

.searchBox:hover > .searchInput {
  width: 240px;
  padding: 0 6px;
}

.searchBox:hover > .searchButton {
  background: white;
  color: #2f3640;
}

/* Container styles */
.customContainer {
  position: relative;
  height: 380px;
  background-color: #1a172c;
  color: white;
  padding: 20px;
  text-align: left;
}

/* Main text styles */
.mainText {
  font-weight: 600!important;
  font-size: 46px!important;
  line-height: 60px!important;
}

/* Smaller text styles */
.smallerText {
  font-size: 14px;
  line-height: 2.5rem;
}
