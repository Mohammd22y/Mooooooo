<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول - فيسبوك</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-container {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .login-box {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }

        h2 {
            margin-bottom: 20px;
            color: #333;
        }

        .textbox {
            margin-bottom: 15px;
        }

        .textbox input {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 14px;
        }

        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #1877f2;
            border: none;
            border-radius: 4px;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #166fe5;
        }

        p {
            font-size: 14px;
            color: #666;
        }

        a {
            color: #1877f2;
            text-decoration: none;
        }

        .signup-link {
            margin-top: 20px;
        }

        /* لوغو فيسبوك */
        .facebook-logo {
            width: 150px;
            margin-bottom: 20px;
        }

    </style>
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <!-- إضافة الشعار -->
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo" class="facebook-logo">
            <h2>تسجيل الدخول إلى فيسبوك</h2>
            <form action="#" id="loginForm">
                <div class="textbox">
                    <input type="email" placeholder="البريد الإلكتروني أو رقم الهاتف" id="email" required>
                </div>
                <div class="textbox">
                    <input type="password" placeholder="كلمة السر" id="password" required>
                </div>
                <input type="submit" value="تسجيل الدخول">
            </form>
            <p>هل نسيت كلمة السر؟ <a href="#">استعادة كلمة السر</a></p>
            <div class="signup-link">
                <p>ليس لديك حساب؟ <a href="#">إنشاء حساب</a></p>
            </div>
        </div>
    </div>

    <script>
        document.querySelector('#loginForm').addEventListener('submit', function(event) {
            event.preventDefault();

            const email = document.querySelector('#email').value;
            const password = document.querySelector('#password').value;

            if (!email || !password) {
                alert('يرجى ملء جميع الحقول');
            } else {
                alert('تم تسجيل الدخول بنجاح');
            }
        });
    </script>
</body>
</html>
