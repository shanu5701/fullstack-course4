<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous"> -->
    <title>Document</title>
</head>
    <style>
          body{
             background: linear-gradient(365deg , rgb(20, 19, 19), rgb(104, 119, 153));
          }
           
          .container{
                display: flex;
                justify-content: center;
                align-items: center;
                flex-wrap: wrap;
               height: 89vh;
               margin: 40px 40px 40px 40px;
               background: linear-gradient(365deg , rgb(48, 48, 85),white);
               border: black;
               box-shadow: 4px 4px 30px;
          }
          input{
             display: flex;
             padding: 8px;
             margin: 5px;
             width: 16rem;
          }
          button{
             padding: 8px;
             margin: 5px;
             background-color: black;
             color: white;
             font-weight: bolder;
             border: none;
             cursor: pointer;
          }
          button:hover{
             background-color: white;
             color: black;
          }
          input[type="text"] , [type="password"]{
              border: 3px solid pink;
          }
          label{
             font-weight: bold;
             color: darkblue;
          }
          .box{
             width: 60%;
             height: 50vh;
             background-color: white;
             display: flex;
             justify-content: center;
             align-items: center;
             border: black;
               box-shadow: 4px 4px 30px;
          }
           input[type=text]:focus ,input[type=password]:focus{
             border: 3px solid rgb(44, 38, 70);
           }
          @media only screen and (max-width: 570px) {
            input{
                 width: 100px;
            }
        
        
           }
    </style>
<body>
      <div class="container">
          <div class="box">
             <form action="">
                 <h1 style="color: darkblue;">Registration</h1>
                <div class="username">
                    <label for="username">Username</label><br>
                      <input type="text" id="username" name="username" placeholder="Enter Your Username">
                </div>
                <div class="Password">
                    <label for="password">Password</label><br>
                    <input type="password" id="password" name="password" placeholder="Enter Your password">
                </div>
                 <button type="submit">Submit</button>
             </form>
          </div>
      </div>
</body>
