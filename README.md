I have used 100% of codespaces on my previous account. So this is an extra account. To see my projects have a look at --> https://github.com/SubhikshaVB

============================================
<!-- INDEX.HTML  -->
<!-- <!DOCTYPE html>
<html>
    <head>
        <title>Sign Up</title>
        <link rel="stylesheet" type="text/css" href="./styles.css">
    </head>
    <body>
        <div class="main">  	
            <input type="checkbox" id="chk" aria-hidden="true">
    
                <div class="signup">
                    <form>
                        <label for="chk" aria-hidden="true">Sign up</label>
                        <input type="text" name="username" placeholder="User name" required="">
                        <input type="email" name="email" placeholder="Email" required="">
                        <input type="password" name="password" placeholder="Password" required="">
                        <button>Sign up</button>
                    </form>
                </div>
                <div class="login">
                    <form action="./index.html">
                        <label for="chk" aria-hidden="true">Login</label>
                        <input type="text" name="username" placeholder="User name" required="">
                        <input type="password" name="password" placeholder="Password" required="">
                        <button>Login</button>
                    </form>
                </div>
        </div>
    </body>
    </html>
    </body>

</html> -->
===================================
<!-- STYLES.CSS -->
<!-- body{
	margin: 0;
	padding: 0;
	display: flex;
	justify-content: center;
	align-items: center;
	min-height: 100vh;
	font-family: 'Jost', sans-serif;
	/* background: linear-gradient(to bottom,#9b59b6,#3498db, #ca91e9); */
	/* background: linear-gradient(to bottom,#add8e6,#e6e6fa ,#ffb6c1, #e91e63); */
	background: linear-gradient(to bottom,#ffd700,#ff8c00 ,#ff4500,#ff6347,#ff7f50);
	/* background: linear-gradient(to bottom,#ff0000,#ff7f00,#ffff00,#00ff00,#0000ff,#4b0082,#9400d3); */
	/*
	Color 1: #ff0000 (Red)
	Color 2: #ff7f00 (Orange)
	Color 3: #ffff00 (Yellow)
	Color 4: #00ff00 (Green)
	Color 5: #0000ff (Blue)
	Color 6: #4b0082 (Indigo)
	Color 7: #9400d3 (Violet) */
	/* #61dada  #e91e63*/
}
.main{
	width: 350px;
	height: 500px;
	background: rgb(165, 203, 51);
	overflow: hidden;
	background: url("https://doc-08-2c-docs.googleusercontent.com/docs/securesc/68c90smiglihng9534mvqmq1946dmis5/fo0picsp1nhiucmc0l25s29respgpr4j/1631524275000/03522360960922298374/03522360960922298374/1Sx0jhdpEpnNIydS4rnN4kHSJtU1EyWka?e=view&authuser=0&nonce=gcrocepgbb17m&user=03522360960922298374&hash=tfhgbs86ka6divo3llbvp93mg4csvb38") no-repeat center/ cover;
	border-radius: 10px;
	box-shadow: 5px 20px 50px #000;
}
#chk{
	display: none;
}
.signup{
	position: relative;
	width:100%;
	height: 100%;
}
label{
	color: #fff;
	font-size: 2.3em;
	justify-content: center;
	display: flex;
	margin: 60px;
	font-weight: bold;
	cursor: pointer;
	transition: .5s ease-in-out;
}
input{
	width: 60%;
	height: 20px;
	background: #e0dede;
	justify-content: center;
	display: flex;
	margin: 20px auto;
	padding: 10px;
	border: none;
	outline: none;
	border-radius: 5px;
}
button{
	width: 60%;
	height: 40px;
	margin: 10px auto;
	justify-content: center;
	display: block;
	color: #fff;
	background: #4ac2e0;
	font-size: 1em;
	font-weight: bold;
	margin-top: 20px;
	outline: none;
	border: none;
	border-radius: 5px;
	transition: .2s ease-in;
	cursor: pointer;
}
button:hover{
	background: #b844a7;
}
.login{
	height: 460px;
	background: #eee;
	border-radius: 60% / 10%;
	transform: translateY(-180px);
	transition: .8s ease-in-out;
}
.login label{
	color: #3b8a6d;
	transform: scale(.6);
}

#chk:checked ~ .login{
	transform: translateY(-500px);
}
#chk:checked ~ .login label{
	transform: scale(1);	
}
#chk:checked ~ .signup label{
	transform: scale(.6);
} -->
==================================
<!-- DASHBOARD.HTML -->
<!-- <!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bug Tracker</title>
  <!-- Latest compiled and minified CSS -->
  <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
    integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
</head>

<body background="sunset.jpg">
  <div class="container">
    <h1></h1>
    
    <div class="jumbotron">
      <h1 style="color: rgb(36, 28, 154);">Bug Tracker</h1>
      <p style="color: rgba(106, 14, 116, 0.555);">Bug tracking is the process of logging and monitoring bugs or errors during software testing. It is also referred to as defect tracking or issue tracking. Large systems may have hundreds or thousands of defects. Each needs to be evaluated, monitored and prioritized for debugging.</p>
      <h3>Describe the Issue: </h3>
      <form id="issueInputForm">
        <div class="form-group">
          <label for="issueDescription">Description</label>
          <input type="text" class="form-control" id="issueDescription" placeholder="Describe the issue ...">
        </div>
        <div class="form-group">
          <label for="issueSeverity">Severity</label>
          <select id="issueSeverity" class="form-control">
            <option value="Low">Low</option>
            <option value="Medium">Medium</option>
            <option value="High">High</option>
          </select>
        </div>
        <div class="form-group">
          <label for="issueAssignedTo">Assigned To</label>
          <input type="text" class="form-control" id="issueAssignedTo" placeholder="Enter responsible ...">
        </div>
        <button id="add-issue" onclick="submitIssue()" class="btn btn-primary">Add</button>
      </form>
    </div>
    <div class="col-lg-12">
      <div id="issuesList">
      </div>
    </div>
  </div>




  <!-- Modal -->
  <!-- <div class="modal fade" id="emptyField" tabindex="-1" role="dialog" aria-labelledby="emptyFieldLabel"
    aria-hidden="true">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="emptyFieldLabel">Invalid Input!</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          Please provide the desciption of the issue and also the person name who you want to assign the issue.
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>


  <script src="https://code.jquery.com/jquery-3.1.1.min.js"
    integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8=" crossorigin="anonymous"></script> -->
  <!-- Latest compiled and minified JavaScript -->
  <!-- <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"
    integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa"
    crossorigin="anonymous"></script>
  <script src="main.js"></script>
</body>

</html>  -->
=======================
<!-- APP.PY -->
<!-- from flask import Flask, render_template, redirect, url_for, request
from flask import Flask, render_template, redirect, url_for, request

app = Flask(__name__)

# Sample users dictionary for login demonstration (you should use a proper database in a real application)
users = {
    "john_doe": "password123",
    "jane_smith": "abc123",
    "Subhi":"123"
}

# Route for the login page
@app.route('/index', methods=['GET', 'POST'])
def login():
    if request.method == 'POST':
        username = request.form['username']
        password = request.form['password']

        # Check if the provided credentials match any user in the 'users' dictionary
        if username in users and users[username] == password:
            # Redirect to the dashboard page upon successful login
            return redirect(url_for('dashboard'))

    return render_template('index.html')

# Route for the signup page
@app.route('/signup', methods=['GET', 'POST'])
def signup():
    if request.method == 'POST':
        # Handle the signup form submission here (not shown in this example)
        username = request.form['username']
        password = request.form['password']

        # Check if the username is already taken
        if username in users:
            return render_template('index.html', error='Username already taken. Please choose a different username.')

        # Create a new user account in the 'users' dictionary
        users[username] = password

        # Redirect to the login page after successful signup
        return redirect(url_for('index'))
        # After successful signup, you can redirect to the dashboard or login page.

        # return redirect(url_for('index'))  # Redirect to the login page after successful signup

    return render_template('dashboard.html')

# Route for the dashboard page
@app.route('/dashboard')
def dashboard():
    # You can add code here to handle the dashboard page logic (if needed)
    if 'username' in request.args:
        username = request.args['username']

        # Fetch user information from the 'users' dictionary
        user_info = users.get(username)

        # If user_info is None, it means the username doesn't exist in the dictionary
        if user_info is None:
            return redirect(url_for('index'))

        # Pass the user information to the dashboard.html template
        return render_template('dashboard.html', username=username, user_info=user_info)
    
    # If 'username' is not present in request.args, redirect to the login page
    # return redirect(url_for('login'))
    return render_template('dashboard.html')

if __name__ == '__main__':
    app.run(debug=True) -->
