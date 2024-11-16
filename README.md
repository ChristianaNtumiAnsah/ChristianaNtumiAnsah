```
<!DOCTYPE html>
<html>
  <head>
    <title>Self-Improvement Survey</title>
  </head>
  <body>
    <div id="survey-form" class="container">
      <header class="header">
        <h1 id="title" class="text-center">Self-Improvement Survey</h1>
        <p id="description" class="text-center description">Answer this questionnaire as honestly as you possibly can. The results will help you identify areas in your life you may need or want to improve.</p>
      </header>
      <form id="survey-form">
        <!-- **Name, Email, and Age** -->
        <div class="form-group">
          <label id="name-label" for="name">What is your name?<span class="ps">(First and Last Name)</span></label>
          <input type="text" name="name" id="name" class="form-control" placeholder="First and Last Name Here" required>
        </div>
        
        <div class="form-group">
          <label id="email-label" for="email">What is your email address?<span class="ps">(Email Address)</span></label>
          <input required type="email" name="email" id="email" class="form-control" placeholder="Please enter your Email Address Here">
        </div>
        
        <div class="form-group">
          <label id="number-label" for="number">How many goals would you like to set for yourself today?</label>
          <input type="number" name="age" id="number" min="1" max="10" required class="form-control" placeholder="How many Goals"/>
        </div>
        
        <!-- **Current Mood** -->
        <div class="form-group">
          <p>Which selection best describes your current mood?</p>
          <select id="dropdown" name="mood" class="form-control required">
            <option disabled selected value>Select your current Mood</option>
            <option>Bored</option>
            <option>Happy</option>
            <option>Hungover</option>
            <option>Depressed</option>
            <option>Resentful</option>
          </select>
        </div>
        
        <!-- **Social Interactions** -->
        <div class="form-group">
          <p>How often are your Social Interactions Lately?</p>
          <label>
            <input name="social" value="daily" type="radio" class="input-radio" checked/> Daily
          </label>
          <label>
            <input name="social" value="twiceperweek" type="radio" class="input-radio" checked/> Twice per Week
          </label>
          <label>
            <input name="social" value="weekends" type="radio" class="input-radio" checked/> On the Weekends
          </label>
          <label>
            <input name="social" value="Nope" type="radio" class="input-radio" checked/> Never
          </label>
        </div>
        
        <!-- **Activities you Enjoy** -->
        <div class="form-group">
          <p>What days are you available to speak with a Life Coach?<span class="ps">(Check all that apply)</span></p>
          <select id="availability" name="availability" class="form-control" required>
            <option disabled selected value>Select an option</option>
            <option value="monday">Monday</option>
            <option value="tuesday">Tuesday</option>
            <option value="wednesday">Wednesday</option>
            <option value="thursday">Thursday</option>
            <option value="friday">Friday</option>
            <option value="saturday">Saturday</option>
            <option value="sunday">Sunday</option>
          </select>
        </div>
        
        <!-- **Improve areas** -->
        <div class="form-group">
          <p>What areas of life would you LIKE to improve?<span class="ps">(Choose 2 per submission)</span></p>
          <div class="column_01_left">
            <label>
              <input name="improve" value="fitness" type="checkbox" class="input-checkbox"/> Physical Fitness
            </label>
            <label>
              <input name="improve" value="financial" type="checkbox" class="input-checkbox"/> Financial
            </label>
            <label>
              <input name="improve" value="housing" type="checkbox" class="input-checkbox"/> Housing
            </label>
            <label>
              <input name="improve" value="education" type="checkbox" class="input-checkbox"/> Education
            </label>
          </div>
          <div class="column_right_01">
            <label>
```</html>
<!---
ChristianaNtumiAnsah/ChristianaNtumiAnsah is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
