# Kruvrutra-
In our app we provide investors to the farmer by that farmer get free from high compound interest
<!DOCTYPE html>
<html>
<head>
    <title>Kruvrutra Farming Portal</title>
</head>
<body>
    <header>
        <img src="logo.png" alt="Kruvrutra Logo" id="logo">
        <div id="options">
            <!-- Options for the user -->
        </div>
    </header>
    
    <main>
        <div id="buttons">
            <button id="registerFarmer">Register as Farmer</button>
            <button id="registerInvestor">Register as Investor</button>
        </div>
        
        <div id="content">
            <!-- Content based on user actions -->
        </div>
    </main>
    
    <footer>
        <div id="profileOptions">
            <button id="addMoney">Add Money</button>
            <button id="investments">My Investments</button>
            <button id="support">Customer Support</button>
            <button id="faq">FAQ</button>
            <button id="signOut">Sign Out</button>
        </div>
    </footer>

    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const registerFarmerButton = document.getElementById("registerFarmer");
            const registerInvestorButton = document.getElementById("registerInvestor");
            const contentDiv = document.getElementById("content");
            
            registerFarmerButton.addEventListener("click", function() {
                contentDiv.textContent = "Farmer registration form goes here";
            });
            
            registerInvestorButton.addEventListener("click", function() {
                contentDiv.textContent = "Investor registration form goes here, including bank details";
            });
            
            // Add more event listeners and logic as needed
            
            // You can also update the "options" and "profileOptions" sections here
        });
    </script>
</body>
</html>


css
/* Reset some default styles for better consistency */
body, h1, h2, h3, p, button {
    margin: 0;
    padding: 0;
    border: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: white;
    padding: 10px 20px;
}

#logo {
    width: 100px;
    height: 100px;
}

#options {
    display: flex;
    gap: 20px;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 80vh;
}

#buttons {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

button {
    padding: 10px;
    font-size: 16px;
    cursor: pointer;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
}

footer {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    position: fixed;
    bottom: 0;
    width: 100%;
    display: flex;
    justify-content: flex-end;
}

#profileOptions {
    display: flex;
    gap: 10px;
}
