# employ-im
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
 * {
  box-sizing: border-box;
     }

body {
  margin: 0;
}


.navbar {
  overflow: hidden;
  background-color: indigo;
  font-family: Arial, Helvetica, sans-serif;
}

.navbar a {
  float: right;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.dropdown {
  float: right;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: indigo;
  font: inherit;
  margin: 0;
}

.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: indigo;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: indigo;
  width: 100%;
  left: 0;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content .header {
  background: indigo;
  padding: 16px;
  color: indigo;
}

.dropdown:hover .dropdown-content {
  display: block;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  background-color: indigo;
  height: 250px;
}

.column a {
  float: none;
  color: white;
  padding: 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.column a:hover {
  background-color: white;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}


#back
    {
       margin-right:30%;
       margin-left: 70%;
       margin-top:35px;
    }
    .button {
  background-color: red; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  margin: 4px 2px;
  cursor: pointer;
}
.but {
  background-color: grey; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  margin: 4px 2px;
  cursor: pointer;
}


.button1 {font-size: 10px;}
.button2 {font-size: 10px;}
.vl {
  border-left: 2px solid white;
  height: 200px;
  position: absolute;
  left: 20%;
  margin-left: -3px;
  top: 40;
}
.v2 {
  border-left: 2px solid white;
  height: 200px;
  position: absolute;
  left: 50%;
  margin-left: -3px;
  top: 40;
}

</style>
</head>
<body background="2.jpg"> 
<div>
    <nav class="navbar navbar-inverse" style="background-color:#3E3838">
    <div class="container-fluid">
        <ul class="nav navbar-nav navbar-right">
            <a href="#">I am looking for a job</a>
            <a href="#">I am looking to hire</a>
        </div>
    </div>
    </nav>
    </ul>

    <div class="navbar">
    
            <div class="row">
             <div class="col-sm-6">
          
              <h2>employ.im</h2>
            </div>
          <div class="col-sm-6">
          <div class="navbar">
         <a href="#"><i class="fa fa-fw fa-user"></i></a>
            <a href="#home">find a job</a>
            <div class="dropdown">
              <button class="dropbtn">candidates 
              </button>
              <div class="dropdown-content">
                <div class="header">
                </div>   
                <div class="row">
                  <div class="column">
                    <h3>candidates</h3>
                    <a href="#">applying instantly</a>
                  </div>
                  <div class="vl"></div>
                  <div class="column">
                    <h3>get started</h3>
                    <a href="#">job search</a>
                    <a href="#">company search</a>
                    <a href="#">create your cv</a>
                    <a href="#">how it works</a>
                 
                          </div>
                          <div class="v2"></div>
                          <div class="column">
                          <h3>find a job today</h3>
                  
                          <button type="button" class="but button2">login</button>
                            <br>
                          <button type="button" class="button button1">register</button>
                      </div>
                    </div>
                  
                  </div> 
                  </div>
                  <a href="#home">employees</a>
                  </div>
                </div>
          
          <div style="padding:16px">
            </div>
            <div id="menu3" class="tab-pane fade">
              </div>
            </div>
          </div>
          
          <div id="back" style="background-color:white;width:300px;height:300px">
          <div style="padding:20px">
          <h2> Form</h2>
          <form class="form horizontal" action="/action_page.php">
            <div class="col-sm-11">
            
            <label for="email">Email:</label>
            <br>
              <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
              <br>
            
            <div class="form-group">
              </div>
            </div>
            <br>
            <div class="form-group">
                <div class="col-sm-11">
              <label for="pwd">Password:</label>
              <br>
              <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pwd">
            </div>
            <br>
            <button type="submit" class="button button1"> find a job now </button>
          </form>
          </div>
          </div>
          </body>
          </html>
          
