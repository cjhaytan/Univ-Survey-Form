# University Survey Form
# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Survey Form - freeCodeCamp.org</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header class="header">
            <h1 id="title" class="text">University Survey Form</h1>
            <p id="description" class="description">
                We would like to hear your feedback to improve our services. Thank you!
            </p>
        </header>
        <form action="" id="survey-form">
            <div class="form-group">
                <label for="name" id="name-label">Name</label>
                <input 
                type="text"
                name="name"
                id="name"
                class="form-control"
                placeholder="Enter your name" required
                />
            </div>
            <div class="form-group">
                <label for="email" id="email-label">Email Address</label>
                <input 
                type="email"
                name="email"
                id="email"
                class="form-control"
                placeholder="Enter your Email" required
                />
            </div>
            <div class="form-group">
                <label for="age" id="number-label">Age
                    <span class="clue">(optional)</span>
                </label>
                <input 
                type="number"
                name="age"
                id="number"
                min="19" max="99"
                class="form-control"
                placeholder="Age"
                />
            </div>
            <!--SELECT FORM-->
            <div class="form-group">
                <p>How did you know us?</p>
                <select name="knew" id="dropdown" class="form-control" required>
                    <option> Select one</option>
                    <option value="1"> Advertisement</option>
                    <option value="2"> Family/Friends</option>
                    <option value="3"> News</option>
                    <option value="4"> Poster</option>
                    <option value="5"> Research</option>
                    <option value="6"> Recommendation</option>
                    <option value="7"> Social Media</option>
                    <option value="8"> Others</option>
                </select>
            </div>
            <!--RADIO BUTTON-->
            <div class="form-group">
                <p>How was your experience using our services?</p>
                <label for="Very good">
                    <input 
                    name="user-experience"
                    value="Very-good"
                    type="radio"
                    class="radio"
                    checked
                    id="survey-form"> Very good
                </label>
                <label for="Good">
                    <input 
                    name="user-experience"
                    value="Good"
                    type="radio"
                    class="radio"
                    id="survey-form"> Good
                </label>
                <label for="Poor">
                    <input 
                    name="user-experience"
                    value="Poor"
                    type="radio"
                    class="radio"
                    id="survey-form"> Poor
                </label>
                <label for="Bad">
                    <input 
                    name="user-experience"
                    value="Bad"
                    type="radio"
                    class="radio"
                    id="survey-form"> Bad
                </label>
                <label for="Very bad">
                    <input 
                    name="user-experience"
                    value="Very-bad"
                    type="radio"
                    class="radio"
                    id="survey-form"> Very bad
                </label>
            </div>
            <!--CHECKBOX-->
            <div class="form-group">
                <p>What program do you currently enrolled?
                    <span class="clue">(Check your enrolled program)</span>
                </p>
                <label for="Business">
                    <input 
                    name="chosen"
                    value="Business-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">Business program
                </label>
                <label for="Medical">
                    <input 
                    name="chosen"
                    value="Medical-science-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">Medical Science program
                </label>
                <label for="Engineering program">
                    <input 
                    name="chosen"
                    value="Engineering-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">Engineering program
                </label>
                <label for="IT">
                    <input 
                    name="chosen"
                    value="IT-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">IT program
                </label>
                <label for="Education">
                    <input 
                    name="chosen"
                    value="Education-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">Education program
                </label>
                <label for="Arts">
                    <input 
                    name="chosen"
                    value="Arts-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">Arts program
                </label>
                <label for="Other">
                    <input 
                    name="chosen"
                    value="Other-program"
                    type="checkbox" 
                    id="survey-form" 
                    class="checkbox">Other: 
                    <input 
                type="text"
                name="Other-program"
                id="other"
                class="blank"
                placeholder=""
                />
                </label>
            </div>
            <!--SUGGESTION MESSAGE-->
            <div class="form-group">
                <p>Do you still have question or suggestions regarding our services?</p>
                <textarea 
                name="comment" 
                id="survey-form" 
                class="textarea"
                placeholder="Leave a message here..."></textarea>
            </div>
            <!--SUBMIT BUTTON-->
            <div class="form-group">
                <button class="submit-button" id="submit" type="submit">Submit</button>
            </div>
        </form>
    </div>
</body>
</html>
