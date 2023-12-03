<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookConnect</title>
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css">
    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "poppins", sans-serif;
        }
        body {
            min-height: 100vh;
            background: linear-gradient(to right, #3498db, #2c3e50);
            background-size: cover;
            background-position: center;
        }

        .header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 20px 100px;
            background: grey;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 100;
        }

        .logo {
            font-size: 32px;
            color: rgb(0, 234, 255);
            text-decoration: none;
            font-weight: 700;
        }
        #navbar {
            position: sticky;
        }

        .navbar a {
            position: relative;
            font-size: 18px;
            color: #fff;
            font-weight: 500;
            text-decoration: none;
            margin-left: 40px;
        }

        .navbar a::before {
            content: '';
            position: absolute;
            top: 100%;
            left: 0;
            width: 0;
            height: 2px;
            background: #fff;
            transition: .3s;
        }

        .navbar a:hover::before {
            width: 100%;
        }

        #books {
            text-align: center;
        }

        #books .images {
            width: 23%;
            min-width: 250px;
            padding: 10px 12px;
            border: 2px solid green;
            border-radius: 10px;
            cursor: pointer;
            box-shadow: 20px 20px 30px rgba(0, 0, 0, 0.02);
            margin: 15px 0;
            position: relative;
            background-color: white;
        }

        #books .images:hover {
            box-shadow: 20px 20px 30px rgba(0, 0, 0, 0.02);

        }

        #books .images img {
            width: 100%;
            border-radius: 20px;
        }

        #books .images .des {
            text-align: center;
            pad: 10px 0;
        }
        #books .probooks {
            display: flex;
            justify-content: space-between;
            padding-top: 20px;
            flex-wrap: wrap;
        }

    </style>
</head>
<body>
<section id="navbar">
    <header class="header">
        <a href="Home.html" class="logo">BookConnect</a>
        <nav class="navbar">
            <a href="Home.html">Home</a>
            <a href="Library.html" target="_self">Library</a>
            <a href="Groups.html" target="_self">Groups</a>
            <a href="More.html" target="_self">More</a>
            <a href="Login.html" target="_self">Login</a>
        </nav>
    </header>
</section><br><br><br><br><br><br>

<section id="books">
        <h2>Some Featured Books</h2>
        <div class="probooks">
            <div class="images">
                <a href="The-Psychology-of-Money-PDF.pdf"><img src="moneybook" alt=""></a>
                <div class="des">
                    <h5>The Pyschology Of moneybook</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="atomic" alt="">
                <div class="des">
                    <h5>Atomic Habits</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="monk" alt="">
                <div class="des">
                    <h5>THINK LIKE A MONK</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

            <div class="images">
                <img src="win" alt="">
                <div class="des">
                    <h5>How To Win Friends And Influence People</h5>
                    <div class="star">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>

        </div>
</section>

<section id="books">
    <div class="probooks">
        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

        <div class="images">
            <img src="" alt="">
            <div class="des">
                <h5></h5>
                <div class="star">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
            </div>
        </div>

    </div>
</section>
</body>
</html>



LIBRARY PAGE CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookConnect/Library</title>
    <style>
        body {
            background: linear-gradient(to right, #3498db, #2c3e50);
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "poppins", sans-serif
        }
        .header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            padding: 20px 100px;
            background: grey;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 100;
        }

        .logo {
            font-size: 32px;
            color: whitesmoke;
            text-decoration: none;
            font-weight: 700;
        }
        #navbar {
            position: sticky;
        }

        .navbar a {
            position: relative;
            font-size: 18px;
            color: #fff;
            font-weight: 500;
            text-decoration: none;
            margin-left: 40px;
        }

        .navbar a::before {
            content: '';
            position: absolute;
            top: 100%;
            left: 0;
            width: 0;
            height: 2px;
            background: #fff;
            transition: .3s;
        }

        .navbar a:hover::before {
            width: 100%;
        }

        #content {
            background-color: aquamarine;
        }

        #libooks {
            padding: 10px;
        }


    </style>
</head>
<body>
    <section id="navbar">
        <header class="header">
            <a href="Home.html" class="logo">BookConnect</a>
            <nav class="navbar">
                <a href="Home.html">Home</a>
                <a href="Library.html" target="_self">Library</a>
                <a href="Groups.html" target="_self">Groups</a>
                <a href="More.html" target="_self">More</a>
                <a href="Login.html" target="_self">Login</a>
            </nav>
        </header>
    </section><br><br><br><br><br><br>

    <section id="content">

        <div id="libooks">

            <span><h3>1. The Pyschology Of Money</h3><button href="The-Psychology-of-Money-PDF.pdf" type="">Read now</button></span>
            <h3>2. Atomic Habits</h3><button>Read now</button>
            <h3>3. THINK LIKE A MONK</h3><button>Read now</button>
            <h3>4. How To Win Friends And Influence People</h3><button>Read now</button>
            <h3>5. Eat That Frog</h3><button>Read now</button>
            <h3>6. India's Ancient Past</h3><button>Read now</button>

        </div>

    </section>
    
</body>
</html>

LOGIN PAGE CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BookConnect/Login</title>
    <style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "poppins", sans-serif
    }
    .header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        padding: 20px 100px;
        background: grey;
        display: flex;
        justify-content: space-between;
        align-items: center;
        z-index: 100;
    }

    .logo {
        font-size: 32px;
        color: whitesmoke;
        text-decoration: none;
        font-weight: 700;
    }
    #navbar {
        position: sticky;
    }

    .navbar a {
        position: relative;
        font-size: 18px;
        color: #fff;
        font-weight: 500;
        text-decoration: none;
        margin-left: 40px;
    }

    .navbar a::before {
        content: '';
        position: absolute;
        top: 100%;
        left: 0;
        width: 0;
        height: 2px;
        background: #fff;
        transition: .3s;
    }

    .navbar a:hover::before {
        width: 100%;
    }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(to right, #3498db, #2c3e50);
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .container {
            text-align: center;
        }

        .login-container, .register-container {
            background-color: #fff;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            padding: 20px;
            border-radius: 8px;
            width: 300px;
            text-align: center;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }

        .login-container:hover, .register-container:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }

        .login-container h2, .register-container h2 {
            color: #333;
            margin-bottom: 20px;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
            color: #555;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
            transition: border-color 0.3s ease-in-out;
        }

        .form-group input:focus {
            border-color: #3498db;
        }

        .form-group button {
            background-color: #2ecc71;
            color: #fff;
            padding: 12px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease-in-out;
        }

        .form-group button:hover {
            background-color: #27ae60;
        }

        .form-group .signup-link, .form-group .login-link {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            transition: color 0.3s ease-in-out;
        }

        .form-group .signup-link:hover, .form-group .login-link:hover {
            color: #2980b9;
        }

        .hide {
            display: none;
        }

        @media (max-width: 400px) {
            .login-container, .register-container {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <section id="navbar">
        <header class="header">
            <a href="Home.html" class="logo">BookConnect</a>
            <nav class="navbar">
                <a href="Home.html">Home</a>
                <a href="Library.html" target="_self">Library</a>
                <a href="Groups.html" target="_self">Groups</a>
                <a href="More.html" target="_self">More</a>
                <a href="Login.html" target="_self">Login</a>
            </nav>
        </header>
    </section>

    <div class="container">
        <div class="login-container">
            <h2>BookConnect - Login</h2>
            <form class="login-form">
                <div class="form-group">
                    <label for="username">Username:</label>
                    <input type="text" id="username" name="username" required>
                </div>
                <div class="form-group">
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required>
                </div>
                <div class="form-group">
                    <button href="index.html" type="submit">Login</button>
                </div>
                <div class="form-group">
                    <a href="#" class="signup-link">Create an account</a>
                </div>
            </form>
        </div>

        <div class="register-container hide">
            <h2>BookConnect - Register</h2>
            <form class="register-form">
                <div class="form-group">
                    <label for="new-username">Username:</label>
                    <input type="text" id="new-username" name="new-username" required>
                </div>
                <div class="form-group">
                    <label for="new-password">Password:</label>
                    <input type="password" id="new-password" name="new-password" required>
                </div>
                <div class="form-group">
                    <button type="submit">Register</button>
                </div>
                <div class="form-group">
                    <a href="#" class="login-link">Already have an account? Login</a>
                </div>
            </form>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const loginContainer = document.querySelector('.login-container');
            const registerContainer = document.querySelector('.register-container');
            const signupLink = document.querySelector('.signup-link');
            const loginLink = document.querySelector('.login-link');

            signupLink.addEventListener('click', function (event) {
                event.preventDefault();
                loginContainer.classList.add('hide');
                registerContainer.classList.remove('hide');
            });

            loginLink.addEventListener('click', function (event) {
                event.preventDefault();
                loginContainer.classList.remove('hide');
                registerContainer.classList.add('hide');
            });
        });
    </script>

</body>
</html>
