<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Love Message
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&amp;family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
        .message {
            font-family: 'Times New Roman', cursive;
        }
        .fade-in {
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
  </style>
 </head>
 <body class="bg-pink-100 flex items-center justify-center min-h-screen relative">
  <img alt="A large heart shape in a soft pink color" class="absolute inset-0 w-full h-full object-cover opacity-20" height="800" src="https://storage.googleapis.com/a1aa/image/Yf3hI7lQWk2Cf0TwWckFBFBCWgSyBRLrhykJ7dENArRdAzfnA.jpg" width="800"/>
  <div class="w-full max-w-xs relative z-10">
   <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4" id="loginForm">
    <div class="mb-4">
     <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
      Username
     </label>
     <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" placeholder="Username" type="text"/>
    </div>
    <div class="mb-6">
     <label class="block text-gray-700 text-sm font-bold mb-2" for="password">
      Password
     </label>
     <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline" id="password" placeholder="******************" type="password"/>
    </div>
    <div class="flex items-center justify-between">
     <button class="bg-pink-500 hover:bg-pink-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" onclick="login()" type="button">
      Sign In
     </button>
    </div>
   </form>
   <p class="text-center text-gray-500 text-xs">
    Username: regina password: july17.
   </p>
  </div>
  <div class="hidden fade-in bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 max-w-lg mx-auto text-center relative z-10" id="messageContainer">
   <img alt="A beautiful heart-shaped balloon floating in a clear blue sky" class="mx-auto mb-4" height="400" src="https://storage.googleapis.com/a1aa/image/aKDoFvnsEHKGAN8x1yI1fueGebGMHouLEzdwroLQtQMY0lfPB.jpg" width="600"/>
   <p class="message text-pink-500 text-lg">
    Hi lovelove,
   </p>
   <p class="message text-pink-500 text-lg">
    I just wanted to take a moment to remind you how incredibly special you are to me. Your smile lights up my day, and your laughter is my favorite sound. I’m so grateful to have you in my life, and I cherish every moment we share. Thank you for being you kind, beautiful, and wonderfully unique. I can’t wait to make more memories together.
   </p>
   <p class="message text-black-500 text-lg">
    -SAMMYBOI-
   </p>
  </div>
  <script>
   function login() {
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;

            if (username === 'regina' && password === 'july17') {
                document.getElementById('loginForm').classList.add('hidden');
                document.getElementById('messageContainer').classList.remove('hidden');
            } else {
                alert('Incorrect username or password');
            }
        }
  </script>
 </body>
</html>
