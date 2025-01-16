<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>FORM</title>
</head>
<body>
  <h1>FORM</h1>
  <h2>Profile</h2>
  <form action="/submit.srh">

    <div class="form-profile">

      <label for="name">Name</label>
      <input type="text" id="name" placeholder="Enter your name" required>

      <label for="date">D.O.B</label>
      <input type="date" id="date" required>

      <label for="own-address">Own Address</label>
      <input type="text" id="own-address" placeholder="Enter your own address" required>

      <label for="present-address">Present Address</label>
      <input type="text" id="present-address" placeholder="Enter your Present address">

      <label for="phone">Phone No.</label>
      <input type="tel" id="phone" pattern="[0-9]{10}" maxlength="10" placeholder="Enter your phone number" required>

      <label for="email">Email</label>
      <input type="email" id="email" placeholder="Enter your email id" required>

      <label for="gender">Gender</label>
      <select id="gender">
        <option value=""disabled selected>Select</option>
        <option value="Male">Male</option>
        <option value="female">Female</option>
        <option value="others">Others</option>
      </select>

      <label for="marital-status">Marital Status</label>
      <select id="marital-status">
        <option value=""disabled selected>Select</option>
        <option value="maried">Maried</option>
        <option value="unmaried">Unmaried</option>
      </select>

    </div>

    <h2>Respondent's other information</h2>


    <div class="form-respondent">

      <label for="nationality">Nationality</label>
      <input type="text" id="nationality" placeholder="Enter your contry name" required>
      <select id="nationality">
        <option value=""disabled selected>Enter</option>
        <option value="indian">Indian</option>
        <option value="afghanistan">Afghanistan</option>
        <option value="albania">Albania</option>
        <option value="algeria">Algeria</option>
        <option value="andorra">Andorra</option>
        <option value="angola">Angola</option>
        <option value="antigua-and-barbuda">Antigua and Barbuda</option>
        <option value="argentina">Argentina</option>
        <option value="armenia">Armenia</option>
        <option value="australia">Australia</option>
        <option value="austria">Austria</option>
        <option value="azerbaijan">Azerbaijan</option>
        <option value="bahamas">Bahamas</option>
        <option value="bahrain">Bahrain</option>
        <option value="bangladesh">Bangladesh</option>
        <option value="barbados">Barbados</option>
        <option value="belize">Belize</option>
        <option value="benin">Benin</option>
        <option value="bhutan">Bhutan</option>
        <option value="bolivia">Bolivia</option>
        <option value="bosnia-and-herzegovina">Bosnia and Herzegovina</option>
        <option value="bulgaria">Bulgaria</option>
        <option value="burkina-faso">Burkina Faso</option>
        <option value="burundi">Burundi</option>
        <option value="cabo-verde">Cabo Verde</option>
        <option value="cambodia">Cambodia</option>
        <option value="cameroon">Cameroon</option>
        <option value="canada">Canada</option>
        <option value="chad">Chad</option>
        <option value="chile">Chile</option>
        <option value="china">China</option>
        <option value="colombia">Colombia</option>
        <option value="comoros">Comoros</option>
        <option value="congo">Congo</option>
        <option value="congo-democratic-republic">Congo, Democratic Republic</option>
        <option value="cook-islands">Cook Islands</option>
        <option value="costa-rica">Costa Rica</option>
        <option value="croatia">Croatia</option>
        <option value="cuba">Cuba</option>
        <option value="cyprus">Cyprus</option>
        <option value="czechia">Czechia</option>
        <option value="denmark">Denmark</option>
        <option value="djibouti">Djibouti</option>
        <option value="dominica">Dominica</option>
        <option value="dominican-republic">Dominican Republic</option>
        <option value="east-timor">East Timor</option>
        <option value="ecuador">Ecuador</option>
        <option value="egypt">Egypt</option>
        <option value="el-salvador">El Salvador</option>
        <option value="equatorial-guinea">Equatorial Guinea</option>
        <option value="eritrea">Eritrea</option>
        <option value="estonia">Estonia</option>
        <option value="eswatini">Eswatini</option>
        <option value="ethiopia">Ethiopia</option>
        <option value="fiji">Fiji</option>
        <option value="finland">Finland</option>
        <option value="france">France</option>
        <option value="gabon">Gabon</option>
        <option value="gambia">Gambia</option>
        <option value="georgia">Georgia</option>
        <option value="germany">Germany</option>
        <option value="ghana">Ghana</option>
        <option value="greece">Greece</option>
        <option value="grenada">Grenada</option>
        <option value="guatemala">Guatemala</option>
        <option value="guinea">Guinea</option>
        <option value="guinea-bissau">Guinea-Bissau</option>
        <option value="guyana">Guyana</option>
        <option value="haiti">Haiti</option>
        <option value="honduras">Honduras</option>
        <option value="hungary">Hungary</option>
        <option value="iceland">Iceland</option>
        <option value="india">India</option>
        <option value="indonesia">Indonesia</option>
        <option value="iran">Iran</option>
        <option value="iraq">Iraq</option>
        <option value="ireland">Ireland</option>
        <option value="israel">Israel</option>
        <option value="italy">Italy</option>
        <option value="jamaica">Jamaica</option>
        <option value="japan">Japan</option>
        <option value="jordan">Jordan</option>
        <option value="kiribati">Kiribati</option>
        <option value="kuwait">Kuwait</option>
        <option value="kyrgyzstan">Kyrgyzstan</option>
        <option value="laos">Laos</option>
        <option value="latvia">Latvia</option>
        <option value="lebanon">Lebanon</option>
        <option value="lesotho">Lesotho</option>
        <option value="liberia">Liberia</option>
        <option value="libya">Libya</option>
        <option value="liechtenstein">Liechtenstein</option>
        <option value="lithuania">Lithuania</option>
        <option value="luxembourg">Luxembourg</option>
        <option value="madagascar">Madagascar</option>
        <option value="malawi">Malawi</option>
        <option value="maldives">Maldives</option>
        <option value="mali">Mali</option>
        <option value="malta">Malta</option>
        <option value="mauritania">Mauritania</option>
        <option value="mauritius">Mauritius</option>
        <option value="mexico">Mexico</option>
        <option value="micronesia">Micronesia</option>
        <option value="moldova">Moldova</option>
        <option value="monaco">Monaco</option>
        <option value="mongolia">Mongolia</option>
        <option value="morocco">Morocco</option>
        <option value="north-macedonia">North Macedonia</option>
        <option value="myanmar">Myanmar</option>
        <option value="namibia">Namibia</option>
        <option value="nauru">Nauru</option>
        <option value="nepal">Nepal</option>
        <option value="netherlands">Netherlands</option>
        <option value="new-zealand">New Zealand</option>
        <option value="nicaragua">Nicaragua</option>
        <option value="niger">Niger</option>
        <option value="nigeria">Nigeria</option>
        <option value="niue">Niue</option>
        <option value="north-korea">North Korea</option>
        <option value="panama">Panama</option>
        <option value="papua-new-guinea">Papua New Guinea</option>
        <option value="paraguay">Paraguay</option>
        <option value="peru">Peru</option>
        <option value="philippines">Philippines</option>
        <option value="poland">Poland</option>
        <option value="portugal">Portugal</option>
        <option value="qatar">Qatar</option>
        <option value="romania">Romania</option>
        <option value="rwanda">Rwanda</option>
        <option value="saint-kitts-and-nevis">Saint Kitts and Nevis</option>
        <option value="saint-lucia">Saint Lucia</option>
        <option value="saint-vincent-and-the-grenadines">Saint Vincent and the Grenadines</option>
        <option value="samoa">Samoa</option>
        <option value="san-marino">San Marino</option>
        <option value="sao-tome-and-principe">São Tomé and Príncipe</option>
        <option value="saudi-arabia">Saudi Arabia</option>
        <option value="senegal">Senegal</option>
        <option value="serbia">Serbia</option>
        <option value="sierra-leone">Sierra Leone</option>
        <option value="singapore">Singapore</option>
        <option value="slovakia">Slovakia</option>
        <option value="slovenia">Slovenia</option>
        <option value="solomon-islands">Solomon Islands</option>
        <option value="somalia">Somalia</option>
        <option value="south-africa">South Africa</option>
        <option value="south-korea">South Korea</option>
        <option value="south-sudan">South Sudan</option>
        <option value="spain">Spain</option>
        <option value="sri-lanka">Sri Lanka</option>
        <option value="sudan">Sudan</option>
        <option value="sweden">Sweden</option>
        <option value="switzerland">Switzerland</option>
        <option value="syria">Syria</option>
        <option value="taiwan">Taiwan</option>
        <option value="tajikistan">Tajikistan</option>
        <option value="tanzania">Tanzania</option>
        <option value="thailand">Thailand</option>
        <option value="togo">Togo</option>
        <option value="tonga">Tonga</option>
        <option value="trinidad-and-tobago">Trinidad and Tobago</option>
        <option value="tunisia">Tunisia</option>
        <option value="turkmenistan">Turkmenistan</option>
        <option value="turkey">Turkey</option>
        <option value="tuvalu">Tuvalu</option>
        <option value="uganda">Uganda</option>
        <option value="ukraine">Ukraine</option>
        <option value="united-arab-emirates">United Arab Emirates</option>
        <option value="united-kingdom">United Kingdom</option>
        <option value="united-states">United States</option>
        <option value="uruguay">Uruguay</option>
        <option value="uzbekistan">Uzbekistan</option>
        <option value="vanuatu">Vanuatu</option>
        <option value="vatican-city">Vatican City</option>
        <option value="venezuela">Venezuela</option>
        <option value="vietnam">Vietnam</option>
        <option value="yemen">Yemen</option>
        <option value="zambia">Zambia</option>
        <option value="zimbabwe">Zimbabwe</option>
      </select>

      <label for="adhar">Adhar</label>
      <input type="number" id="adhar" pattern="[0-9]{12}" maxlength="12" placeholder="Enter your adhar number" required>

      <label for="voter">Voter Card Nonumber</label>
      <input type="text" id="voter" pattern="[A-Z]{3}[0-9]{7}" maxlength="10" placeholder="Enter your voter number (if any)">

      <label for="pan">Pan No.</label>
      <input type="text" id="pan" pattern="[A-Z]{5}[0-9]{4}[A-Z]{1}" maxlength="10" placeholder="Enter your pan number(if any)">

    </div>

    <h2>Educational Information</h2>

    <div class="form-education">

      <label for="qualification">Qualification</label>
      <input type="text" id="qualification" placeholder="Enter" required>

      <label for="marks">Marks</label>
      <input type="tel" id="marks" pattern="[0-9]" placeholder="Enter" required>

      <label for="percentage">Percentage</label>
      <input type="range" id="percentage" min="0" max="100" step="1" oninput="this.nextElementSibling.value = this.value" required>
      <output>50</output>%

      <label for="school">School Name</label>
      <input type="text" id="school" placeholder="Enter your last qualified school" required>

      <label for="college">College Name</label>
      <input type="text" id="college" placeholder="Ente yourcollege name (if any)">

      <label for="university">University Name</label>
      <input type="text" id="university" placeholder="Enter university name (if any)">

    </div>

    <h2>Experience</h2>

    <div class="form-experience">

      <label for="experience1">Experience1: </label>

      <div class="experience1" id="experience1">

        <label for="institute">Institute Name</label>
        <input type="text" id="institute" name="experience1" placeholder="1st Institute Name">

        <label for="from">From</label>
        <input type="date" id="from">

        <label for="to">To</label>
        <input type="date" id="to">

        <label for="hr">Internal HR</label>
        <select id="hr">
          <option value=""disabled selected>Grade/Band</option>
          <option value="entry">Entry Level</option>
          <option value="junior">Junior Level</option>
          <option value="associate">Associate Level</option>
          <option value="senior">Senior Level</option>
          <option value="supervisor">Supervisor</option>
          <option value="manager">Manager</option>
          <option value="seniorManager">Senior Manager</option>
          <option value="assistantDirector">Assistant Director</option>
          <option value="director">Director</option>
          <option value="vicePresident">Vice President</option>
          <option value="seniorVicePresident">Senior Vice President</option>
          <option value="executiveVicePresident">Executive Vice President</option>
          <option value="cxo">CXO (CEO, CFO, COO, etc.)</option>
        </select>

        <label for="posted">Posted at</label>
        <input type="text" id="posted" placeholder="place">

        <label for="pin">Pin No.</label>
        <input type="tel" id="pin" pattern="[0-9]{6}" maxlength="6" placeholder="Enter the pin">


      </div>

      <label for="experience2">Experience2: </label>

      <div class="experience2" id="experience2">

        <label for="institute">Institute Name</label>
        <input type="text" id="institute" name="experience2" placeholder="2nd Institute Name">

        <label for="from">From</label>
        <input type="date" id="from">

        <label for="to">To</label>
        <input type="date" id="to">

        <label for="hr">Internal HR</label>
        <select id="hr">
          <option value=""disabled selected>Grade/Band</option>
          <option value="entry">Entry Level</option>
          <option value="junior">Junior Level</option>
          <option value="associate">Associate Level</option>
          <option value="senior">Senior Level</option>
          <option value="supervisor">Supervisor</option>
          <option value="manager">Manager</option>
          <option value="seniorManager">Senior Manager</option>
          <option value="assistantDirector">Assistant Director</option>
          <option value="director">Director</option>
          <option value="vicePresident">Vice President</option>
          <option value="seniorVicePresident">Senior Vice President</option>
          <option value="executiveVicePresident">Executive Vice President</option>
          <option value="cxo">CXO (CEO, CFO, COO, etc.)</option>
        </select>

        <label for="posted">Posted at</label>
        <input type="text" id="posted" placeholder="place">

        <label for="pin">Pin No.</label>
        <input type="tel" id="pin" pattern="[0-9]{6}" maxlength="6" placeholder="Enter the pin">

      </div>

      <label for="experience3">Experience3: </label>

      <div class="experience3" id="experience3">

        <label for="institute">Institute Name</label>
        <input type="text" id="institute" name="experience3" placeholder="3rd Institute Name">

        <label for="from">From</label>
        <input type="date" id="from">

        <label for="to">To</label>
        <input type="date" id="to">

        <label for="hr">Internal HR</label>
        <select id="hr">
          <option value=""disabled selected>Grade/Band</option>
          <option value="entry">Entry Level</option>
          <option value="junior">Junior Level</option>
          <option value="associate">Associate Level</option>
          <option value="senior">Senior Level</option>
          <option value="supervisor">Supervisor</option>
          <option value="manager">Manager</option>
          <option value="seniorManager">Senior Manager</option>
          <option value="assistantDirector">Assistant Director</option>
          <option value="director">Director</option>
          <option value="vicePresident">Vice President</option>
          <option value="seniorVicePresident">Senior Vice President</option>
          <option value="executiveVicePresident">Executive Vice President</option>
          <option value="cxo">CXO (CEO, CFO, COO, etc.)</option>
        </select>

        <label for="posted">Posted at</label>
        <input type="text" id="posted" placeholder="place">

        <label for="pin">Pin No.</label>
        <input type="tel" id="pin" pattern="[0-9]{6}" maxlength="6" placeholder="Enter the pin">

      </div>

      <label for="experience4">Experience4: </label>

      <div class="experience4" id="experience4">

        <label for="institute">Institute Name</label>
        <input type="text" id="institute" name="experience4" placeholder="4th Institute Name">

        <label for="from">From</label>
        <input type="date" id="from">

        <label for="to">To</label>
        <input type="date" id="to">

        <label for="hr">Internal HR</label>
        <select id="hr">
          <option value=""disabled selected>Grade/Band</option>
          <option value="entry">Entry Level</option>
          <option value="junior">Junior Level</option>
          <option value="associate">Associate Level</option>
          <option value="senior">Senior Level</option>
          <option value="supervisor">Supervisor</option>
          <option value="manager">Manager</option>
          <option value="seniorManager">Senior Manager</option>
          <option value="assistantDirector">Assistant Director</option>
          <option value="director">Director</option>
          <option value="vicePresident">Vice President</option>
          <option value="seniorVicePresident">Senior Vice President</option>
          <option value="executiveVicePresident">Executive Vice President</option>
          <option value="cxo">CXO (CEO, CFO, COO, etc.)</option>
        </select>

        <label for="posted">Posted at</label>
        <input type="text" id="posted" placeholder="place">

        <label for="pin">Pin No.</label>
        <input type="tel" id="pin" pattern="[0-9]{6}" maxlength="6" placeholder="Enter the pin">

      </div>

      <label for="experience5">Experience5: </label>

      <div class="experience5" id="experience5">

        <label for="institute">Institute Name</label>
        <input type="text" id="institute" name="experience1" placeholder="2nd Institute Name">

        <label for="from">From</label>
        <input type="date" id="from">

        <label for="to">To</label>
        <input type="date" id="to">

        <label for="hr">Internal HR</label>
        <select id="hr">
          <option value=""disabled selected>Grade/Band</option>
          <option value="entry">Entry Level</option>
          <option value="junior">Junior Level</option>
          <option value="associate">Associate Level</option>
          <option value="senior">Senior Level</option>
          <option value="supervisor">Supervisor</option>
          <option value="manager">Manager</option>
          <option value="seniorManager">Senior Manager</option>
          <option value="assistantDirector">Assistant Director</option>
          <option value="director">Director</option>
          <option value="vicePresident">Vice President</option>
          <option value="seniorVicePresident">Senior Vice President</option>
          <option value="executiveVicePresident">Executive Vice President</option>
          <option value="cxo">CXO (CEO, CFO, COO, etc.)</option>
        </select>

        <label for="posted">Posted at</label>
        <input type="text" id="posted" placeholder="place">

        <label for="pin">Pin No.</label>
        <input type="tel" id="pin" pattern="[0-9]{6}" maxlength="6" placeholder="Enter the pin">

      </div>

    </div>

    <div class="form-coments">
      <label for="coments">Coments</label>
      <textarea id="coments" cols="30" rows="10" placeholder="Enter your coments"></textarea>
    </div>

    <div class="form-submit">
      <button type="submit">SUBMIT</button>
    </div>

  </form>

</body>

</html>
