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
