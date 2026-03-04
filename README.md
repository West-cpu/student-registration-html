<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Kariuki · Profile & Student Registration (Kenya)</title>
  <!-- ========== INTERNAL CSS ========== -->
  <style>
    /* pure HTML internal stylesheet – for layout and main design */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(135deg, #f1f8fc 0%, #d6e4f0 100%);
      font-family: 'Segoe UI', Roboto, system-ui, sans-serif;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 2rem 1rem;
    }
    .main-card {
      max-width: 1200px;
      width: 100%;
      background: rgba(255, 255, 255, 0.9);
      backdrop-filter: blur(4px);
      border-radius: 3rem 3rem 2rem 2rem;
      box-shadow: 0 30px 50px -20px #1e3b4e;
      padding: 2.5rem 2rem;
      border: 2px solid rgba(255,255,240,0.8);
    }
    .section-head {
      font-size: 2.3rem;
      font-weight: 700;
      color: #0c3f28;
      display: flex;
      align-items: center;
      gap: 1rem;
      border-bottom: 5px solid #009135;  /* Kenya green */
      margin-bottom: 2.2rem;
      padding-bottom: 0.6rem;
    }
    .section-head span {
      background: #000000;  /* black accent */
      color: white;
      font-size: 1.3rem;
      padding: 0.2rem 1.5rem;
      border-radius: 60px;
    }
    /* profile grid */
    .profile-row {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      background: #f1ffe6;
      border-radius: 3rem;
      padding: 2.2rem 2rem;
      margin-bottom: 3rem;
      box-shadow: inset 0 1px 5px #c7ffb1, 0 15px 25px -10px #1f4f2d;
    }
    .avatar-box {
      flex: 0 0 180px;
      text-align: center;
    }
    .avatar-pic {
      width: 170px;
      height: 170px;
      border-radius: 50%;
      background: #a5d6a5;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 0.8rem;
      border: 5px solid #006b3c;
    }
    .info-box {
      flex: 1;
      min-width: 280px;
    }
    .info-line {
      display: flex;
      border-bottom: 2px solid #b8e0b8;
      padding: 0.9rem 0.3rem;
      align-items: baseline;
    }
    .info-tag {
      width: 140px;
      font-weight: 700;
      color: #1d5629;
    }
    .info-detail {
      background: #dcf5dc;
      padding: 0.3rem 1.5rem;
      border-radius: 50px;
      color: #003d1f;
    }
    /* registration form */
    .reg-panel {
      background: #fafff7;
      border-radius: 3rem;
      padding: 2.5rem 2.3rem;
      box-shadow: 0 25px 35px -18px #144d1e;
    }
    .field-duo {
      display: flex;
      flex-wrap: wrap;
      gap: 1.8rem;
      margin-bottom: 2rem;
    }
    .field-single {
      flex: 1 1 240px;
    }
    .field-single label {
      display: block;
      font-weight: 600;
      color: #0e4b23;
      margin-bottom: 0.3rem;
      letter-spacing: 0.3px;
    }
    .field-single input, .field-single select, .field-single textarea {
      width: 100%;
      padding: 0.9rem 1.5rem;
      background: #f2fef0;
      border: 2px solid #a6d8a6;
      border-radius: 60px;
      font-size: 1rem;
      outline: none;
      transition: 0.2s;
    }
    .field-single input:focus, .field-single select:focus, .field-single textarea:focus {
      border-color: #00833d;
      background: #ffffff;
      box-shadow: 0 0 0 5px rgba(0,128,61,0.2);
    }
    .action-btn {
      background: #006b2d;
      border: none;
      color: white;
      font-weight: 800;
      font-size: 1.5rem;
      padding: 0.9rem 3rem;
      border-radius: 60px;
      margin-top: 2rem;
      cursor: pointer;
      box-shadow: 0 8px 0 #003d1c, 0 12px 28px -10px #094d1a;
      transition: 0.1s;
    }
    .action-btn:hover {
      background: #1f8644;
      transform: translateY(-4px);
      box-shadow: 0 12px 0 #003d1c, 0 18px 30px -12px #0b6023;
    }
    .action-btn:active {
      transform: translateY(5px);
      box-shadow: 0 4px 0 #003d1c;
    }
    footer {
      margin-top: 2rem;
      text-align: center;
    }
  </style>
  <!-- end internal CSS – now the HTML with inline style overrides & Kenyan data -->
</head>
<body>

<div class="main-card">

  <!-- ========== MY PROFILE – JOHN KARIUKI ========== -->
  <div class="section-head" style="border-bottom-color: #b84f0b;">   <!-- inline:  copper border -->
    <span style="background: #8b3c00; color: #fde4b3;">🇰🇪</span>   <!-- inline Kenyan flag emoji background -->
    <span style="color: #1f4b2b;">JOHN KARIUKI · PROFILE</span>
    <span style="background: #006b2d; font-size: 1rem;">NAIROBI</span>
  </div>

  <!-- profile row with inline additions -->
  <div class="profile-row" style="background: #fcf9e8; border: 4px solid #d48b4c;">   <!-- inline warmer background + border -->

    <!-- avatar column with strong inline styles -->
    <div class="avatar-box" style="background: #fff1d2; border-radius: 60px; padding: 1.2rem 0.2rem;">
      <div class="avatar-pic" style="background: #f7c77b; border: 6px double #7a4813; border-radius: 40% 60% 40% 60%;">   <!-- inline double border + organic shape -->
        <span style="font-size: 5rem; filter: drop-shadow(0 6px 8px #3d2b10);">👨🏿‍🦱</span>   <!-- emoji with shadow -->
      </div>
      <!-- inline caption: Kenyan vibe -->
      <figcaption style="background: #4f2e0e; color: #fddc9c; padding: 0.4rem 1rem; border-radius: 40px; font-weight: bold;">🌍 NAIROBIAN · TECH</figcaption>
    </div>

    <!-- info area – all rows now reflect John Kariuki / Kenya data + inline extras -->
    <div class="info-box">
      <!-- NAME row (inline style modifies background) -->
      <div class="info-line" style="background: #fff0d8; border-radius: 40px; padding-left: 1rem;">
        <span class="info-tag" style="color: #9d4d0e;">FULL NAME</span>
        <span class="info-detail" style="background: #f5dbc1; font-weight: 800; box-shadow: inset 0 2px 5px #b97634;">JOHN KARIUKI</span>
      </div>
      <!-- REG NO – inline style for special emphasis -->
      <div class="info-line" style="border-bottom: 4px dotted #2a7a3b;">
        <span class="info-tag" style="background: #dfedd9; padding: 0.2rem 0.8rem; border-radius: 20px;">🎓 REG NO</span>
        <span class="info-detail" style="background: #bde0b0; font-family: monospace; font-size: 1.3rem;">25/05074</span>   <!-- monospace inline -->
      </div>
      <!-- EMAIL – Kenyan guessed (gmail domain but .ke style) with inline wavy -->
      <div class="info-line">
        <span class="info-tag" style="text-decoration: underline overline #689f38;">📧 EMAIL</span>
        <span class="info-detail" style="background: #f5e1b5; text-decoration: underline wavy #d46b1e;">john.kariuki@kenya.co.ke</span>   <!-- wavy inline -->
      </div>
      <!-- PHONE – Kenyan number pattern -->
      <div class="info-line" style="background: #e2f0da; border-radius: 30px;">
        <span class="info-tag" style="color: #0e703b;">📞 PHONE</span>
        <span class="info-detail" style="background: #c0e0c0; font-weight: 600;">+254 712 345 678</span>   <!-- Kenyan guessed -->
      </div>
      <!-- CITY / COUNTRY inline with custom border -->
      <div class="info-line" style="border-bottom: 3px solid #d99047;">
        <span class="info-tag" style="font-size: 1.2rem;">📍 LOCATION</span>
        <span class="info-detail" style="background: #f0ca96; border-radius: 30px 5px 30px 5px;">NAIROBI, KENYA</span>   <!-- inline mixed radius -->
      </div>
      <!-- extra: course of study inline -->
      <div class="info-line">
        <span class="info-tag">💻 COURSE</span>
        <span class="info-detail" style="background: #b3dbb3; box-shadow: 0 0 0 2px #388e3c;">BSc. COMPUTER SCIENCE</span>
      </div>
    </div>
  </div>

  <!-- ========== STUDENT REGISTRATION (Kenyan data) ========== -->
  <div class="section-head" style="border-bottom-color: #b07c3a;">
    <span style="background: #964b00;">📋</span>
    <span style="color: #0e5320;">STUDENT REGISTRATION · KENYA</span>
    <span style="background: #2f6b31;">NAIROBI CAMPUS</span>
  </div>

  <form class="reg-panel" action="#" method="post">

    <!-- fieldset 1: personal info – now prefilled with Kenyan data, plus inline styles -->
    <fieldset style="border: 4px ridge #567d45; border-radius: 3rem; padding: 2rem 2rem; background: #f1fdec; margin-bottom: 2rem;">
      <legend style="background: #e2f0d6; padding: 0.4rem 2.2rem; border-radius: 60px; border: 2px solid #2d6e2d;">🇰🇪 PERSONAL (KENYA)</legend>

      <!-- first name / last name – John Kariuki with inline styles -->
      <div class="field-duo">
        <div class="field-single">
          <label>FIRST NAME</label>
          <input type="text" value="John" style="background: #faf3e0; border: 3px solid #b37b48; box-shadow: 0 0 0 2px #f3d9a4;" placeholder="first">
        </div>
        <div class="field-single">
          <label>LAST NAME</label>
          <input type="text" value="Kariuki" style="background: #e3f2dd; border: 3px dashed #2e7d32;" placeholder="last">
        </div>
      </div>

      <!-- email and phone – Kenyan guessed values, inline styles -->
      <div class="field-duo">
        <div class="field-single">
          <label>EMAIL (kenyan)</label>
          <input type="email" value="john.kariuki@kenya.co.ke" style="background: #f3e5cd; border: 2px solid #cc6d2c;" readonly>
        </div>
        <div class="field-single">
          <label>PHONE (Kenya)</label>
          <input type="tel" value="+254 712 345 678" style="background: #ddefd5; border-width: 3px; border-color: #3f9142;" >
        </div>
      </div>

      <!-- registration number 25/05074 with inline special border -->
      <div class="field-duo">
        <div class="field-single">
          <label>📌 REGISTRATION NO</label>
          <input type="text" value="25/05074" style="background: #edd5bb; border: 4px double #874f1e; font-weight: 700; font-size: 1.2rem; text-align: center;" readonly>
        </div>
        <div class="field-single">
          <label>GENDER</label>
          <select style="background: #fcefd3; border: 2px solid #b3550e;">
            <option>Male (selected)</option>
            <option>Female</option>
            <option>Other</option>
          </select>
        </div>
      </div>
    </fieldset>

    <!-- fieldset 2: address & course – city NAIROBI, country KENYA, plus inline styles -->
    <fieldset style="border: 4px double #6b8c50; border-radius: 3rem; background: #f7fce9; padding: 2rem 2rem;">
      <legend style="background: #eaffdd; border: 2px solid #4a784a; padding: 0.4rem 2rem; border-radius: 40px;">📍 NAIROBI · ADDRESS</legend>

      <div class="field-duo">
        <div class="field-single" style="flex:2;">
          <label>STREET / ESTATE</label>
          <input type="text" value="Kimathi Street, Nairobi CBD" style="background: #f5ebd2; border-bottom: 6px solid #b57c42;">
        </div>
        <div class="field-single">
          <label>CITY</label>
          <input type="text" value="Nairobi" style="background: #cef0ce; border-color: #1f884a; font-weight: 600;">
        </div>
      </div>

      <div class="field-duo">
        <div class="field-single">
          <label>POSTAL CODE</label>
          <input type="text" value="00100" style="background: #ffffff; border: 2px solid #c0c0c0; box-shadow: none;">
        </div>
        <div class="field-single">
          <label>COUNTRY</label>
          <input type="text" value="KENYA" style="background: #daf4d5; border: 4px groove #196f3a; font-weight: 800;">
        </div>
      </div>

      <div class="field-duo">
        <div class="field-single">
          <label>COURSE NAME</label>
          <input type="text" value="BSc. Computer Science" style="background: #ffefcb; font-weight: 600;">
        </div>
        <div class="field-single">
          <label>YEAR OF STUDY</label>
          <input type="text" value="Year 2 (2025)" style="background: #dfedd9;">
        </div>
      </div>

      <div class="field-duo">
        <div class="field-single">
          <label>📋 ADDITIONAL NOTES</label>
          <textarea rows="2" style="background: #ffffd3; border-radius: 30px; padding: 1rem;">Kenyan citizen · Nairobi based · tech enthusiast</textarea>
        </div>
      </div>
    </fieldset>

    <!-- button with inline overrides + kenyan colors -->
    <div style="display: flex; justify-content: flex-end; margin-top: 2rem;">
      <button type="submit" class="action-btn" style="background: #aa4e1c; box-shadow: 0 8px 0 #5f2d0c, 0 12px 28px #733d13; border-radius: 40px 10px 40px 10px;">🇰🇪 REGISTER NOW (NAIROBI)</button>
    </div>

    <!-- THE REQUESTED BOTTOM PARAGRAPH HAS BEEN REMOVED. 
         Nothing else added. The form ends cleanly here. -->
  </form>

  <!-- footer with inline styling (simple, no extra text) -->
  <footer>
    <span style="background: #004d26; color: #fce3b5; padding: 0.6rem 3rem; border-radius: 60px; border: 2px solid #fecc7a;">🇰🇪 nairobi · kenya · pure html (inline + internal) 🇰🇪</span>
  </footer>
</div>
<!-- end – everything written in HTML, no external libraries -->
</body>
</html>
