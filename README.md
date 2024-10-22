<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Travel Recommendation</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Discover Your Next Travel Destination</h1>
  </header>

  <main>
    <div id="preferences-form">
      <h2>Tell us about your preferences</h2>
      <form id="user-preferences">
        <label for="continent">Preferred Continent:</label>
        <select id="continent">
          <option value="Europe">Europe</option>
          <option value="Asia">Asia</option>
          <option value="North America">North America</option>
          <option value="South America">South America</option>
          <option value="Africa">Africa</option>
        </select>

        <label for="climate">Preferred Climate:</label>
        <select id="climate">
          <option value="Tropical">Tropical</option>
          <option value="Temperate">Temperate</option>
          <option value="Cold">Cold</option>
          <option value="Dry">Dry</option>
        </select>

        <label for="activity">Preferred Activity:</label>
        <select id="activity">
          <option value="Adventure">Adventure</option>
          <option value="Relaxation">Relaxation</option>
          <option value="Cultural">Cultural</option>
        </select>

        <button type="submit">Get Recommendations</button>
      </form>
    </div>

    <div id="recommendations" class="hidden">
      <h2>Recommended Destinations</h2>
      <div id="destination-cards"></div>
    </div>
  </main>

  <script src="scripts.js"></script>
</body>
</html>

