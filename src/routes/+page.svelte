<head>
    <title>John Garland Walk-in Clinic</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
</head>
<body style="background-color: khaki; overflow-x: hidden; font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <a class="navbar-brand" href="/" style="margin-left: 1%;">
            <img class="d-inline-block align-text-top" src="https://i.pinimg.com/originals/85/95/f4/8595f4b711e503bc72fe396e5043e0c2.png" alt="Bootstrap" width="5%" height="100%">
            John Garland Walk-in Clinic
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nvc" aria-controls="nvc" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="nvc" style="margin-right: 1%">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="/">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="availability">Availability</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact">Contact Us</a>
                </li>
            </ul>
            <ul class="navbar-nav">
                <li class="nav-item dropdown">
                    <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navbarDropdown"></ul>
                </li>
            </ul>
        </div>
    </nav>
    <p style="margin-bottom:0; width: 100vw; height: 3vh; background-color: grey; text-align:center; color: white; font-size:large">Welcome to John Garland walk-in clinic. Please call or text our number to book an appointment.</p>
    <div style='margin-top:0; display: flex; filter: blur(1px); -webkit-filter: blur(1px); background-image: url("im3.jpg"); width: 100vw; height: 90.9vh; background-repeat: no-repeat; background-size: cover; background-position: center;'>
    </div>
    <div style="position: absolute; top: 30%; left: 10%; background-color:rgba(255, 255, 255, .9); border-radius: 15px; padding: 2%">
        <p style="font-weight: bold; font-size:3vw; text-shadow: 1px 1px #000000; color: gray;">
            Quality care you can count on,<br/>
            available to everyone.
        </p>
        <p style="font-weight: bold; font-size:1vw; color: black">Appointment registration can be found in the Availability page,<br/>or contact us to schedule at (416) 742-9988</p>
        <button style="font-size: large; background-color: rgb(2, 130, 2); color:white; border-radius: 5px; width:50%; height: 5vh;">
            Book an appointment today
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                <path fill-rule="evenodd" d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z"/>
            </svg>
        </button>
        <p style="font-weight: bold; font-size:1vw; color: black"><br/>or leave your name and phone number so we can call you instead.</p>
        <form>
            <div style="width: 50%;" class="input-group flex-nowrap">
                <span class="input-group-text" id="addon-wrapping">
                    <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" fill="currentColor" class="bi bi-person-circle" viewBox="0 0 16 16">
                        <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"/>
                        <path fill-rule="evenodd" d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm8-7a7 7 0 0 0-5.468 11.37C3.242 11.226 4.805 10 8 10s4.757 1.225 5.468 2.37A7 7 0 0 0 8 1z"/>
                    </svg>
                </span>
                <input type="text" class="form-control" placeholder="full name" aria-label="full name" aria-describedby="addon-wrapping">
            </div>
            
            <div style="width: 50%; margin-top: 1%;" class="input-group flex-nowrap">
                <span class="input-group-text" id="addon-wrapping1">#</span>
                <input type="tel" class="form-control" placeholder="phone number" aria-label="phone number" aria-describedby="addon-wrapping1">
            </div>
            <br/>
            <button style="font-size: large; background-color: rgb(2, 130, 2); color:white; border-radius: 5px; width:15%; height: 35px;">
                Submit
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-check" viewBox="0 0 16 16">
                    <path d="M10.97 4.97a.75.75 0 0 1 1.07 1.05l-3.99 4.99a.75.75 0 0 1-1.08.02L4.324 8.384a.75.75 0 1 1 1.06-1.06l2.094 2.093 3.473-4.425a.267.267 0 0 1 .02-.022z"/>
                </svg>
            </button>
        </form>
    </div>
</body>