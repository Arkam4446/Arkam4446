<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>task2</title>
    <link rel="stylesheet" href="style.css" type="text/css">
    
</head>
<body>
<div class="container">
    <div class="wrapper">
        <section class="form">
            <header>Task assign form</header>
            
            <form action="#" id="form">
                <div class="name-details">
                    <div class="field input">
                        <label for="">User Name</label>
                        <input type="text" id="name" required >
                    </div>
                   <div class="field input">
                        <label for="">Task name</label>
                        <input type="text" id="tname" required>
                    </div>
                    <div class="field input">
                        <label for="">Task description</label>
                        <textarea id="tdesc" required></textarea>
                    </div>
                    <div class="field button">
                        <input type="submit" value="Assign">
                    </div>
                </div>
            </form>
        </section>
    </div>
    <br>
    </div>
    <div class="container">
       <div id="task-list" class="list">
      <h2> Pending Tasks </h2>
      
    </div>
    </div>
    <script src="script.js"type="text/javascript"></script>
</body>
</html>
