# fosu-oau
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FOSU OAU - Federation of Odeomu Students Union, Obafemi Awolowo University Chapter</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; color: #333; }
        header { background-color: #228B22; color: white; padding: 20px; text-align: center; display: flex; align-items: center; justify-content: center; flex-wrap: wrap; }
        header img { height: 80px; margin: 0 15px; }
        header h1 { margin: 0 15px; }
        header p { width: 100%; margin-top: 10px; }
        nav { background-color: #0066cc; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        nav a:hover { text-decoration: underline; }
        section { padding: 30px 20px; margin: 20px auto; max-width: 900px; background: white; border-radius: 8px; box-shadow: 0 0 15px rgba(0,0,0,0.1); }
        footer { background-color: #228B22; color: white; text-align: center; padding: 15px; }
        h1, h2 { color: #228B22; }
        ul { list-style-type: disc; padding-left: 25px; }
        form { max-width: 700px; margin: 0 auto; }
        label { display: block; margin: 12px 0 5px; font-weight: bold; }
        input[type="text"], input[type="email"], input[type="tel"], input[type="number"], select, textarea {
            width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 4px; box-sizing: border-box;
        }
        input[type="radio"], input[type="checkbox"] { margin-right: 8px; }
        .radio-group, .checkbox-group { margin: 10px 0; }
        button { background-color: #0066cc; color: white; padding: 12px 20px; border: none; border-radius: 4px; cursor: pointer; font-size: 16px; }
        button:hover { background-color: #004080; }
        .form-note { font-size: 0.9em; color: #555; margin-top: 20px; }
    </style>
</head>
<body>
    <header>
        <img src="https://upload.wikimedia.org/wikipedia/en/7/78/Obafemi_Awolowo_University_(logo).png" alt="OAU Logo">
        <h1>Federation of Odeomu Students Union (FOSU)</h1>
        <img src="fosu-logo.png" alt="FOSU Logo"> <!-- Replace with actual FOSU logo URL or file -->
        <p>Obafemi Awolowo University (OAU) Chapter</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#leadership">Leadership</a>
        <a href="#activities">Activities</a>
        <a href="#membership">Join Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to FOSU OAU</h2>
        <p>The Federation of Odeomu Students Union (FOSU) OAU Chapter is the umbrella body uniting students from Odeomu town in Osun State, Nigeria, studying at Obafemi Awolowo University, Ile-Ife. We foster unity, academic excellence, cultural preservation, and community development among our members.</p>
        <p>Join us to connect, grow, and contribute to the progress of Odeomu and Osun State!</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>FOSU is a national student organization for indigenes of Odeomu in tertiary institutions across Nigeria. The OAU Chapter focuses on:</p>
        <ul>
            <li>Providing academic support, mentorship, and admission guidance for prospective students.</li>
            <li>Organizing cultural events, seminars, and community outreach programs.</li>
            <li>Advocating for the rights and welfare of Odeomu students on campus.</li>
            <li>Building networks for personal and professional development.</li>
        </ul>
        <p>Founded as part of the national FOSU secretariat, we collaborate with other chapters to promote unity and development.</p>
    </section>

    <section id="leadership">
        <h2>Leadership Team</h2>
        <p>Our current executives (based on available public information; update as needed):</p>
        <ul>
            <li><strong>FOSU OAU PRESIDENT::</strong> Comr. Awoniyi Opeyemi Michael  - 08166964198</li>
            <li><strong>FOSU OAU General Secretary :</strong> Comr.Adeleye Johnson Ayobami  - 00000000000</li>
            <li><strong>FOSUOAU PRO:</strong>Taiwo Oluwatimileyin - 07026475103</li>
        </ul>
    </section>

    <section id="activities">
        <h2>Activities and Events</h2>
        <p>We organize various events, including:</p>
        <ul>
            <li>Orientation programs for fresh students from Odeomu.</li>
            <li>Cultural festivals celebrating Odeomu heritage.</li>
            <li>Academic tutorials for fresh students.</li>
            <li>Community service projects in Odeomu and Ile-Ife.</li>
            <li>Collaborations with other student unions at OAU.</li>
        </ul>
        <p>Follow our social media for upcoming events!</p>
    </section>

    <section id="membership">
        <h2>Join FOSU OAU - Membership Form</h2>
        <p>Fill out this form to become a member. We will verify your details and contact you soon. All fields with * are required.</p>
        
        <form action="#" method="post">  <!-- Change action to your backend or Formspree/Google embed later -->
            <label for="fullname">Full Name *</label>
            <input type="text" id="fullname" name="fullname" required placeholder="e.g., Taiwo Adebayo">

            <label for="matric">Matriculation Number *</label>
            <input type="text" id="matric" name="matric" required placeholder="e.g., ABC/123/456">

            <label for="department">Department / Faculty *</label>
            <input type="text" id="department" name="department" required placeholder="e.g., Computer Science / Sciences">

            <label for="level">Current Level / Year *</label>
            <select id="level" name="level" required>
                <option value="">Select Level</option>
                <option value="100">100 Level</option>
                <option value="200">200 Level</option>
                <option value="300">300 Level</option>
                <option value="400">400 Level</option>
                <option value="500">500 Level</option>
                <option value="PG">Postgraduate</option>
            </select>

            <label for="phone">Phone Number *</label>
            <input type="tel" id="phone" name="phone" required placeholder="e.g., 08012345678">

            <label for="email">Email Address *</label>
            <input type="email" id="email" name="email" required placeholder="yourname@example.com">

            <label for="origin">Are you an indigene of Odeomu? *</label>
            <div class="radio-group">
                <input type="radio" id="yes" name="origin" value="Yes" required>
                <label for="yes" style="display:inline;">Yes</label><br>
                <input type="radio" id="no" name="origin" value="No">
                <label for="no" style="display:inline;">No (but interested in associate membership)</label>
            </div>

            <label for="why-join">Why do you want to join FOSU OAU? (Optional)</label>
            <textarea id="why-join" name="whyjoin" rows="4" placeholder="Tell us in a few words..."></textarea>

            <div class="checkbox-group">
                <input type="checkbox" id="agree" name="agree" required>
                <label for="agree">I agree to the terms and conditions of FOSU OAU membership *</label>
            </div>

            <button type="submit">Submit Membership Application</button>
        </form>

        <p class="form-note">Note: This is a demo form. For real submissions, replace with a Google Form embed or similar service to receive responses via email/spreadsheet.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Get in touch for membership, inquiries, or collaborations:</p>
        <ul>
            <li><strong>Email:</strong> [Add your official email, e.g., fosu.oau@gmail.com]</li>
            <li><strong>Phone:</strong> OP MYKE - 08166964198</li>
            <li><strong>Social Media:</strong> Facebook - Search for "Federation of Odeomu Students Union"</li>
            <li><strong>Location:</strong> Obafemi Awolowo University, Ile-Ife, Osun State, Nigeria</li>
        </ul>
    </section>

    <footer>
        <p>© 2026 FOSU OAU Chapter. All rights reserved.</p>
    </footer>
</body>
</html>
