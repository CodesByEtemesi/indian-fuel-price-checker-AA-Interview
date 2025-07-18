# indian-fuel-price-checker-AA-Interview

<i>This was a part of the technical interview that I did in AA for a software development internship role.</i>

🛢️ <h1>Fuel Prices by Indian State – JavaScript + API Project</h1>
This project demonstrates how to fetch data from APIs using JavaScript, display a list of Indian states, and then show live fuel prices (Petrol, Diesel, CNG, LPG) for any selected state using buttons.

The system uses the following APIs:

<ol>
    <li>States API – Returns a list of all states in India.</li>
    <li>Fuel Prices API – Returns the latest fuel prices for a selected state.</li>
</ol>

<h2>Objectives</h2>
<ol>
    <li>Use Postman to test if the two APIs are working correctly.</li>
    <li>Use JavaScript to fetch and display all states from the States API.</li>
    <li>Allow a user to click a button for any state and display fuel prices for that state using the Fuel Prices API.</li>
    <li>Display prices for petrol, diesel, CNG, and LPG.</li>
</ol>

<h2>API Endpoints</h2>
<ol>
    <li>States API
Returns a list of all Indian states.</li>
    <li>Fuel Prices API
Returns fuel prices for a specific state. Replace {stateId} with a valid state name like maharashtra.</li>
</ol>

<h3><i>How to Test the APIs with Postman. </i></h3>

<ul>
    <li>Open Postman.</li>
    <li>Create a new request.</li>
    <li>Select GET method and enter either of the above URLs.</li>
    <li>Under the Headers tab, add: //// X-RapidAPI-Key: YOUR_API_KEY \\\\\\\////// X-RapidAPI-Host: daily-petrol-diesel-lpg-cng-fuel-prices-in-india.p.rapidapi.com \\\\\
    </li>
    <li>Click Send.</li>
    <li>Confirm that the API responds with a list of states or fuel prices.</li>
</ul>

 <h2>🚀 How the JavaScript System Works</h2>
Step-by-step:
<ol>
    <li>The system loads and makes a request to the States API.
</li>
    <li>The list of states is displayed as clickable buttons.</li>
    <li>When the user clicks on a button for a specific state:
</li>
    <li>The app makes another API request to the Fuel Prices API.</li>
    <li>The fuel prices (Petrol, Diesel, CNG, LPG) for that state are displayed dynamically.</li>
</ol>

<h2>🧰 Technologies Used</h2>
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript (Vanilla)</li>
    <li>RapidAPI Fuel Prices API</li>
    <li>Postman (for API testing)</li>
    
</ul>

<h2>🔑 Setup </h2>
<ol>
    <li>Get an API key from RapidAPI.</li>
    <li>Open the HTML file in any browser.</li>
    <li>Replace the dummy API key in the JavaScript with your actual RapidAPI key.</li>
</ol>

<b>👨‍💻 Author</b>
<i>Created as part of a practical JavaScript + API integration Software Development Internship Interview.</i>
